# Padhayi.ai
The AI takes audio recording of your class, summarizes(using NLTK) the content and gives you a few questions to test your understanding. Wrote an algorithm which slices the audio into smaller chunks and uses Google speech recognition API to convert speech to text and summarizes the transcript. The AI internally uses pre-trained models from HuggingFace Transformers to generate questions from the audio transcript.

```bash
streamlit run app.py
```
