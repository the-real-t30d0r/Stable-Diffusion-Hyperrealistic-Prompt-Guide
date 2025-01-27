## Stable Diffusion Hyperrealistic Prompt Guide (Quick Generation)

This guide outlines the optimal settings and techniques for generating hyperrealistic portraits using Stable Diffusion. I tested it with a RTX 4060 Ti (8GB VRAM) .
![](https://raw.githubusercontent.com/the-real-t30d0r/Stable-Diffusion-Hyperrealistic-Prompt-Guide/refs/heads/main/results.png)


**Model:**

* **Recommended Model:** [https://civitai.com/models/3811?modelVersionId=4224](https://civitai.com/models/3811?modelVersionId=4224) 
    * This model offers a great balance of performance and generation time, resulting in high-quality, realistic portraits.

**Negative Prompt:**

The following negative prompt helps to avoid common artifacts and ensure high image quality:

((censored)), ((Asian)), (bad anatomy), bad hands, three hands, three legs, bad arms, missing legs, missing arms, poorly drawn face, bad face, fused face, cloned face, worst face, three crus, extra crus, fused crus, worst feet, three feet, fused feet, fused thigh, three thighs, fused thigh, extra thigh, worst thigh, missing fingers, extra fingers, ugly fingers, long fingers, horn, extra eyes, huge eyes, amputation, disconnected limbs, cartoon, cg, 3d, unreal, animate bad anatomy, bad hands, three hands, three legs, bad arms, missing legs, missing arms, poorly drawn face, bad face, fused face, cloned face, worst face, three crus, extra crus, fused crus, worst feet, three feet, fused feet, fused thigh, three thighs, fused thigh, extra thigh, worst thigh, missing fingers, extra fingers, ugly fingers, long fingers, horn, extra eyes, huge eyes, amputation, disconnected limbs, cartoon, cg, 3d, unreal, animate, Asian, ((malformed feet)), ((malformed foot)), ((deformed iris), deformed pupils)


**Generation Settings:**

* **Sampling Method:** DPM++ 2M
* **Schedule Type:** Karras
* **Sampling Steps:** 25
* **Width:** 640
* **Height:** 896
* **CFG Scale:** 7
* **Seed:** -1

**Prompt Examples:**
Use the following base prompt to achieve my results:

(8k, RAW photo, highest quality), hyperrealistic, Photo of INSERT PROMP HERE, highly detailed, cinematic, film grain, action-themed

You can use other prompts if you dont like it. Check this website out [https://prompthero.com/](https://prompthero.com/)

**NSFW Content:**

For NSFW content generation:

* Keep all other settings identical.
* Reduce sampling steps to 20.




