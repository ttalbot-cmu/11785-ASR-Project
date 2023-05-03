# 11785-ASR-Project

**Overview**

**accent_identification:** Initial attempt at creating an accent identification network using a custom network with a CNN + Transformer.

**Accent Embeddings:** Secondary attempt at creating an accent idenitifcation network with a pretrained model. 


**deepspeech_baseline:** Evaluation of the deepspeech pretrained ASR on the GMU Speech Accent Archive. Average WER and WIL results plots included. Reference for deepspeech (https://github.com/mozilla/DeepSpeech). 

**finetune:** Contains the notebooks used for finetuning Whisper ASR with Mozilla Common Voice 13.0. The first notebook, huggingface_whisper.ipynb is based on the blog post by Sanchit Gandhi (https://huggingface.co/blog/fine-tune-whisper). The second notebook, whisper2.ipynb uses a custom dataset and dataloader class to load common voice into an iterative dataset.  

**wav2vec_baseline:** Evaluation of the wav2vec pretained ASR from Meta AI. Reference for wav2vec2.0 (https://ai.facebook.com/blog/wav2vec-20-learning-the-structure-of-speech-from-raw-audio/). 

**whisper_baseline:** Evaluation of the whisper pretrained ASR on the GMU Speech Accent Archive. Average WER and WIL result plots included. Reference for Whisper ASR (https://openai.com/research/whisper).

**data_visualization:** Contains notebooks for plotting the relative performance of our baseline models and the results of finetuning Whisper ASR.
