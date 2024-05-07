# imageCPP_aka_llamaCPP
Repo of the code from the Medium article About Visual Languages and Llama.CPP

Tested Llama-cpp-python for Visual Languages with the following models:
- llava-phi2
- moondream2
- llava-phi3-mini


Main Repository is the amazing [llama-cpp-python](https://github.com/abetlen/llama-cpp-python)<br>

python bindings for [llama.cpp GG project](https://github.com/ggerganov/llama.cpp)

--


### Install dependencies
```
python -m venv venv
venv\Scripts\activate
pip install streamlit==1.26.0
pip install llama-cpp-python==0.2.68
pip install easygui
```

### Download the CLIP model and the VL weights
#### llava-phi-2-GGUF
from [kejcao/llava-phi-2-GGUF](https://huggingface.co/kejcao/llava-phi-2-GGUF/tree/main)

#### Moondream2
- mmproj from [vikhyatk/moondream2](https://huggingface.co/vikhyatk/moondream2/tree/main)  because it has only fp16 quantization
- weights from [sroecker/moondream2-GGUF](https://huggingface.co/sroecker/moondream2-GGUF)

#### LLaVA-Phi-3-mini-4k-instruct-GGUF
weights and mmproj from[dragonSwing/LLaVA-Phi-3-mini-4k-instruct-GGUF](https://huggingface.co/dragonSwing/LLaVA-Phi-3-mini-4k-instruct-GGUF/tree/main)

---


No graphic interface is provided,<br>
but we use easygui do choose the image file

---

Read more in the official paper

[LLaVA-Phi: Efficient Multi-Modal Assistant with Small Language Model](https://arxiv.org/pdf/2401.02330)

LlamaCPP Chat Format types here

https://github.com/abetlen/llama-cpp-python/blob/main/llama_cpp/llama_chat_format.py

