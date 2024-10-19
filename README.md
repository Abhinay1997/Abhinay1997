### Currently working on:

| Idea                                               | Status                                                                                     | References/Papers                                                 | 
|----------------------------------------------------|------------------------------------------------------------------------------------------------------|---------------------------------------------------------|
| FIFO CogVideoX                                     | In Progress                                                                                |   https://jjihwan.github.io/projects/FIFO-Diffusion |
|Comparision of different cfg like methods| In Progress                                   |  Smoothed Energy Guidance, Guidance embedding, CFG and CFG++| 
| Flux Image Inversion using RNRI                    | Blocked. Understanding of prior for flow matching too low. Dropped as well due to RF Inversion.                                  |   https://barakmam.github.io/rnri.github.io/| 
|Invertible MMDiT Transformer with Diff Attention | Planned. The idea is that the flow predicted by transformer is conditioned on both t_n and t_n-1 to allow for perfect inversion in theory | https://arxiv.org/pdf/2406.08929 https://arxiv.org/pdf/2410.05258
| CogVideoX Attention Scaling                        | Paused. Need to recheck for higher res                                                     |   https://arxiv.org/abs/2306.08645| 
| RB Modulation for FLUX                             | Dropped. RF Inversion makes this redundant                           |   https://rb-inversion.github.io/| 
| CogVideoX distillation using FineVideo and PeRFlow | Planned. Needs compute grant. May be scrapped once BFLs video model is out.                |   https://arxiv.org/abs/2405.07510| 
| Underwater Image Colorization as an Inverse Problem| Planned. Needs better underestanding of inverse problems                                   |   https://github.com/LituRout/PSLD| 
| Flux generation steering using SAE for CLIP        | Planned. Need better understanding of SAEs & apply them to T5 as well |   https://www.lesswrong.com/posts/Quqekpvx8BGMMcaem/interpreting-and-steering-features-in-images| 
| LoRA (move to MoRA ?) ControlNet layer        | Planned. Compute ∆W for Flux dev & its controlnet layer. Decompose to LoRA and see decomposition error. If its low enough, LoRA should be enough |   [ChatGPT conversation](https://chatgpt.com/share/66f12970-6608-800f-a24e-20c4d2766c4a)| 
| MoRA finetuning Flux              | I have a hypothesis: MoRA might give better samples than LoRA for Flux. I'll try it out sometime next week maybe. TLDR: 1. Full finetuning > LoRA for personalization. 2. Full finetuning > MoRA > DoRA > LoRA. 3. MoRA should converge fast like LoRA but give better quality/diversity like finetuning. There should be no free lunch though. Hmm | 1. [MoRA: High-rank PEFT Approach](https://linkedin.com/pulse/mora-high-rank-peft-approach-fine-tuning-himank-jain-ewe3f/) 2. [Full Finetuning of Flux](https://dev.to/furkangozukara/full-fine-tuning-of-flux-yields-way-better-results-than-lora-training-as-expected-overfitting-and-bleeding-reduced-a-lot-3g6g) 3. [GitHub: MoRA](https://github.com/kongds/MoRA) |
| Transformer layers as Painters for DiTs            | Complete. Results published [here](https://huggingface.co/blog/NagaSaiAbhinay/transformer-layers-as-painters-dit)|   https://arxiv.org/abs/2407.09298| 

Checkout my notes/blog here: [abhinay1997.github.io](https://abhinay1997.github.io)
