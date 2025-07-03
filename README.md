# 🧠 Minor LLM Projects

Welcome to the **Minor LLM Projects** repository — a growing collection of hands-on, experimental projects using Large Language Models (LLMs), audio models, and related AI tooling. This is a personal space to prototype, test, and build small yet powerful ideas using cutting-edge open-source models.

---

## 📌 Projects

### 1. 📝 Minutes of Meeting (MoM) Generator

**Description:**  
This project converts raw **meeting audio recordings** (e.g., `.wav`, `.mp3`) into **human-readable transcriptions**, which can later be summarized into Minutes of Meeting using an LLM.

**Tech Stack:**
- Hugging Face `pipeline()` for **automatic speech recognition (ASR)**
- Model used: [`openai/whisper-base`](https://huggingface.co/openai/whisper-base)
- Google Colab + Google Drive integration
- Summarization using `LLaMA` or similar models

**How to Run:**
1. Mount Google Drive in Colab
2. Upload meeting audio to `/MyDrive/Meetings/`
3. Run the transcription notebook
4. View full transcript with optional timestamps

📁 Notebook: [`MoM_Generator.ipynb`](./MoM_Generator.ipynb)

---

## 🛠️ What's Coming Next?

This repo will soon include:
- 📊 Dataset generators using LLMs
- 🤖 Custom chatbot prototypes
- 🗂️ Retrieval-Augmented Generation (RAG) tools
- 🎤 Speaker diarization & structured audio analytics

Stay tuned as this becomes a mini–LLM playground.

---

## 📚 Requirements

- Python 3.8+
- `transformers`, `torchaudio`, `librosa`, `google.colab` (for Colab setup)
- Optional GPU for faster Whisper inference

---

## 📩 Contributions & Ideas

This is a personal sandbox for learning and experimentation, but feel free to fork or suggest ideas!

---

## 🧑‍💻 Author

**Santhosh Raaj**  
Building cool stuff with LLMs, real estate tech, and more.

[GitHub Profile →](https://github.com/SanthoshRaaj-KR)

---

## ⭐️ If You Like It...

Star 🌟 the repo to follow future updates and experiments.
