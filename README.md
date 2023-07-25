# TheBloke/FreeWilly2-GPTQ Cog model

This is an implementation of the [TheBloke/FreeWilly2-GPTQ](https://huggingface.co/TheBloke/FreeWilly2-GPTQ) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="Tell me about AI"
