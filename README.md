This repository contains basics of pipelines, Codemodels and Many more...

# CodeModels
I have added codes on how to use code models, for 1 code generation. These will be updated from time to time as well.
These are 10+ different models (Notes: 350M, 2B and 16B of codegen count as different). For these I have made functions of these so we can directly call ai model from <a href="https://docs.python.org/3/">.py</a> file. For example
```bash
from ai-model import ai-model-function
```
We just need to give prompt as arguments and we are done. <br>

Points to Note:
<ol>
1. We need to see whether to use "cpu"(CPU)or "cuda"(GPU) for various models.<br>
2. Some models code are long and a little scary(I felt so), but thats how these codes are run from their docs, although I have cleaned the bad ones quite a lot.<br>
3. These functions outputs need to properly taken out based on what FORMAT of output they give. Some models like InCoder, StableLM have a different type of output style compared to CodeGen.<br>
</ol>
You can visit of various models in order to know more about them. 
<ol>
1. <a href="https://github.com/nlpxucan/WizardLM/blob/main/WizardCoder/src/inference_wizardcoder.py"> Wizard Coder</a>  PS: this has some issues because of which I couldn't run properly in lab machine.<br>
2. <a href="https://github.com/Stability-AI/StableLM"> StableLM-7B</a><br>
3. <a href="https://github.com/bigcode-project/starcoder"> StarCoder  </a><br>
4. <a href="https://huggingface.co/bigcode/santacoder"> SantaCoder HuggingFace</a> OR <a href="https://github.com/bigcode-project/Megatron-LM"> SantaCoder GitHub </a><br>
5. <a href="https://github.com/salesforce/CodeGen"> CodeGen SalesForce</a> # OurFav<br>
6. <a href="https://huggingface.co/ise-uiuc/Magicoder-S-DS-6.7B"> Magicoder-S-DS-6.7B HuggingFace</a> or their <a href=https://github.com/ise-uiuc/magicoder/> GitHub </a><br>
</ol><br>
Many of them have playgrounds like <a href="https://huggingface.co/spaces/ise-uiuc/Magicoder-S-DS-6.7B"> Magicoder</a>. It is pretty amazing and if it is not usable in our system ( which will figure It out), we can for the time being, use this in place. PRETTY amazing reviews for this one!<br>
