# Summer24nlp

## Part 1: data preprocessing
- Data preprocessing - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/NLP_Preprocessing.ipynb) [🌐](./NLP_Preprocessing.html)  
  ### Performs several preprocessing operations using [NLTK](https://www.nltk.org/) -
  - Stopword removal
  - Stemminng, lemmatization
  - Parts of speech tagging
  - Named entity recognition
  
  ### Implements different embedding techniques -
  - one hot encoding
  - bag-of-word
  - TF-IDF
  - word2vec
  - GloVe
  - BERT

## Part 2: Chatbot based on US president speeches
### Code
  - bigram model from scratch on Joe Biden dataset <sup>[*](#f1)</sup> - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/biden_bigram.ipynb) [🌐](./biden_bigram.html)
  - gpt from scratch on Joe Biden dataset <sup>[*](#f1)</sup> - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/biden_GPT.ipynb) [🌐](./biden_GPT.html)
  - gpt-2 finetuning on Joe Biden dataset - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/biden_gpt2.ipynb) [🌐](./biden_gpt2.html)
  - gpt-2 finetuning on all president dataset - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/presidents_gpt2.ipynb) [🌐](./presidents_gpt2.html)
  - gpt-2 all president (inference only) - [📓](https://github.com/47wolhaiksong/summer24nlp/blob/main/presidents_gpt2_inference.ipynb) [🌐](./presidents_gpt2_inference.ipynb.html)

### Development
- model hosting - [🌐](https://huggingface.co/spaces/adarksky/summer24-fine-tuning)
- final web deployment - [🌐](https://presidentgpt2.web.app/)

# Acknowledgements
<a name="f1">*</a> : heavily referenced from [Andrej Karpathy](https://youtu.be/kCc8FmEb1nY?si=rFriklQNCBkr231P)  
<a href="https://colab.research.google.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/archive/d/d0/20221103151253%21Google_Colaboratory_SVG_Logo.svg" alt="colab" width="65" height="40"></a> 
<a href="https://www.jetbrains.com/datalore/"><img src="https://blog.jetbrains.com/wp-content/uploads/2020/07/Datalore.svg" alt="datalore"></a> 
<a href="https://huggingface.co/"><img src="https://avatars.githubusercontent.com/u/25720743?s=200&v=4" alt="hugging face" width="40" height="40"> </a>
