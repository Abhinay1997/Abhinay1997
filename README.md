Hello 👋! 

I'm Abhinay, currently a Software Developer based out of India. I work on low latency data serving over Python API's at my job and in my free time I love exploring State-of-The-Art research in NLP and Computer Vision.

I'm a regular contributor to [huggingface/diffusers](https://github.com/huggingface/diffusers) and so far I've added:

1. [Checkpoint Merger Pipeline](https://github.com/huggingface/diffusers/blob/main/examples/community/README.md#checkpoint-merger-pipeline): A community pipeline for merging diffusion model checkpoints that can be loaded by the DiffusionPipeline class.
2. [UnCLIPTextInterpolationPipeline](https://github.com/huggingface/diffusers/blob/main/examples/community/README.md#unclip-text-interpolation-pipeline): A community pipeline to interpolate between the CLIP text embeddings of two text prompts and generate images from the intermediate embeddings.
3. [UnCLIPImageInterpolationPipeline](https://github.com/huggingface/diffusers/blob/main/examples/community/README.md#unclip-image-interpolation-pipeline): Following up on the above, a pipeline to interpolate between the CLIP image embeddings of two input image prompts and generate images from the intermediate embeddings.

Pending for final review and merge:
1. Tune-A-Video Pipeline: A one shot conditioned text-to-video pipeline that was proposed by [Jay Zhangjie Wu et al](https://tuneavideo.github.io/). Ported the model to huggingface with the [PR](https://github.com/huggingface/diffusers/pull/2455) pending merge approval.

The following works are in draft:
1. UniControlNet Pipeline: A unified controlnet pipeline that leverages a Mixture-of-Experts architecture and modulated zero conv layers to adapt controlnet conditioning using the same controlnet weights. Proposed by [Can Qin et al](https://canqin001.github.io/UniControl-Page/)

Feel free to reach out to me!
