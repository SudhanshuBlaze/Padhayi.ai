# Padhayi.ai

The AI takes audio recording of your class, summarizes(using NLTK) the content and gives you a few questions to test your understanding.

## Description

Wrote an algorithm which slices the audio into smaller chunks and uses Google speech recognition API to convert speech to text and summarizes the transcript. The AI internally uses pre-trained models from HuggingFace Transformers to generate questions from the audio transcript.

## Getting Started


```bash
git clone https://github.com/SudhanshuBlaze/Padhayi.ai.git
```

### Installing Dependencies


- cd to the Padhayi.ai directory on your local computer
- run the below commands to install all the required dependencies

```bash
pip install -r requirements.txt
git clone https://github.com/amontgomerie/question_generator
python -m pip install -e question_generator
```

### Run the application

```bash
streamlit run app.py
```

#

> Do not forget to ⭐ this repo
