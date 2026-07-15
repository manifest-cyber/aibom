# Examples Directory

## Contents
This directory contains several examples of AI-BOMs in CycloneDX format. 

- `Qwen2.5-7B-Instruct`: A popular text generation ML model listed on [HuggingFace](https://huggingface.co/Qwen/Qwen2.5-7B-Instruct).

- `Llama-3.2-1B-Instruct`: A popular text generation ML model listed on [HuggingFace](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct).

- `FLUX.1-dev`: A popular text-to-image ML model listed on [HuggingFace](https://huggingface.co/black-forest-labs/FLUX.1-dev).

## Custom Fields 
In the provided examples, we have included some custom properties relative to the standard fields in CycloneDX's [example](https://github.com/CycloneDX/specification/blob/master/tools/src/test/resources/1.5/valid-machine-learning-1.5.json) on their Github. These custom properties include important information, such as the model's stated category, base model, parent model, and dependent libraries, which are often included on Hugging Face and other similar repositories. We have also included custom properties for information that we didn't feel the existing format handles well, such as distinguishing between a model's intended use, out of scope usage, and malicious use. 

We are working with the CycloneDX community to add those fields and make these improvements to a future specification of their format, and look forward to doing the same with the SPDX community as well. 
