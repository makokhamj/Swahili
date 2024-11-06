# Swahili
This repository has an implementation of a Swahili language model that fills/completes part of a sentence given the neighboring words provided, for example:
input_text = "Wakati [MASK] leo." 
It may suggest:
- wakati, leo.
- wakati : leo.
- wakati ya leo.
- wakati wa leo.
- wakati na leo.
You will need to download the LLaMa3.2 1B model from: https://huggingface.co/meta-llama/Llama-3.2-1B
The rest of the steps are noted in the notebook.
NOTE:
I initially installed several models: #!pip install keras==2.15.0
#!pip install tensorboard==2.15.0
#!pip install ml-dtypes==0.2.0
#!pip install transformers datasets torch sentencepiece
#!pip install tensorflow
#!pip install accelerate>=0.26.0

But during during Configuring Arguments, I ran into issues, so had to uninstall some of them: #!pip uninstall tensorflow tensorflow-macos keras -y. Make sure to remove comment character if you need to uninstall

