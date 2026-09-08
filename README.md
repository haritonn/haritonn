# Hi, I'm Hariton!

**Aspiring ML Engineer | NLP, RAG & Information Retrieval | Python / PyTorch**

I'm a fourth-year student at Saratov State University, pursuing a bachelor's degree in Fundamental Computer Science and Information Technology.

I work on machine learning projects involving text, speech, and images. My experience includes a speech recognition system developed during a university internship, a local RAG assistant for PDF documents, and a search engine for biomedical publications.

I'm interested in the full process of building ML applications: preparing data, experimenting with models, evaluating results, and making the solution usable through an application. Alongside my projects, I teach machine learning at a student community and develop tools in Rust.

**Open to ML Engineering and Data Science internships / junior opportunities, including remote roles.** Based in Saratov, Russia. ![Check my resume (RU/EN)](https://github.com/haritonn/resume).

## Selected projects

### [Speech recognition for dialogues and catalog terms](https://github.com/haritonn/asr_practice)

A university internship project for transcribing Russian-language conversations, identifying speakers, and recognizing domain-specific catalog terms.

- Combined Faster-Whisper transcription, Silero VAD, and pyannote speaker diarization.
- Implemented catalog term recognition with a NeMo CTC context graph without fine-tuning the main ASR model.
- Linked transcripts and detected terms to speakers; evaluated transcription, diarization, and terminology recognition using WER, CER, DER, and F1.

**Built with:** Python, Faster-Whisper, Silero VAD, pyannote, NVIDIA NeMo.

### [Local RAG assistant for PDF documents](https://github.com/haritonn/pdf_rag)

A locally running assistant that answers questions about uploaded PDF documents and displays the retrieved evidence alongside its answers.

- Built a document retrieval and answer generation pipeline.
- Added interface controls for the LLM, embedding model, vector database, and number of retrieved sources.
- Exposed source documents and retrieved passages in Streamlit so users can inspect the evidence behind an answer.

**Built with:** Python, LLMs, text embeddings, Qdrant, Streamlit.

### [Biomedical publication search](https://github.com/haritonn/fitness_se)

A search engine for Europe PMC publications on training, recovery, and sports nutrition.

- Implemented BM25 lexical retrieval, semantic retrieval with MedCPT and FAISS, and hybrid retrieval using Reciprocal Rank Fusion.
- Added offline ranking evaluation and a local LLM-assisted relevance-labeling pipeline.
- Built a Streamlit interface for searching and exploring publications.

**Built with:** Python, BM25, MedCPT, FAISS, Ollama, Streamlit.

### [Image caption generator](https://github.com/haritonn/caption_gen)

An image-captioning pipeline trained on Flickr8k to generate English descriptions of images.

- Implemented a ResNet-50 encoder and an LSTM decoder with soft attention in PyTorch.
- Used scheduled sampling, label smoothing, attention regularization, gradient clipping, and early stopping during training.
- Added deterministic dataset splits, checkpointing, optional ClearML tracking, and evaluation with BLEU and METEOR.

**Built with:** Python, PyTorch, ResNet, LSTM, attention, ClearML.

### [cargo-smi — NVIDIA GPU monitoring in the terminal](https://github.com/haritonn/cargo-smi)

A Rust terminal dashboard for monitoring NVIDIA GPUs and host-system resources in one place.

- Integrated NVML to display GPU utilization, temperature, VRAM usage, and GPU-consuming processes.
- Added multi-GPU navigation, configurable refresh, and utilization history.

- Included CPU, RAM, swap, and process monitoring in the same interface.

**Built with:** Rust, NVML, Ratatui, Crossterm, Sysinfo.

## Research & coursework

### [Text-embedding geometry and HDBSCAN clustering](https://github.com/haritonn/coursework3)

Investigated how embedding models and feature-space transformations affect news-event clustering. Compared embedding families, dimensionality reduction methods, and HDBSCAN configurations to study their effect on clustering quality.

### [Generative computer vision for virtual try-on](https://github.com/haritonn/coursework2)

Compared diffusion models, GANs, and large multimodal model approaches for virtual clothing try-on. Evaluated visual quality and inference time on a custom dataset.

## Preferred languages

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/) [![SQL](https://img.shields.io/badge/SQL-3776AB?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

## Current stack

[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-9C27B0?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FF3E74?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/)
[![ClearML](https://img.shields.io/badge/ClearML-2393D1?style=for-the-badge&logo=clearml&logoColor=white)](https://clear.ml/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FE6F24?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com/)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](https://latex-project.org/)
[![Typst](https://img.shields.io/badge/Typst-0D7933?style=for-the-badge&logo=typst&logoColor=white)](https://typst.app/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)

My academic background includes linear algebra, calculus, probability, and statistics, alongside classical machine learning and deep learning.

## Teaching & community

I'm one of the leading lecturers at the machine learning club within [Development Students Clubs (DSC)](https://dsc.alivetech.org/), a student-led community at my university.

We cover classical machine learning with an emphasis on supervised learning. I enjoy connecting the underlying concepts to code and helping students understand how the methods work.

Some of my recorded lectures and club materials:

- [My NumPy lecture](https://youtu.be/5dgYgDVg4v0)
- [My Pandas lecture](https://youtu.be/ejz3DEaZGjw)
- [Machine Learning Club playlist](https://youtube.com/playlist?list=PLIz9eWHArYfhrL4Viaz2vEthyffHz8ZFM)

## Currently exploring

- **NLP & LLMs:** text representations and applications such as summarization and question answering.
- **RAG & information retrieval:** retrieval quality, ranking evaluation, and grounding answers in source documents.
- **ML engineering:** reproducible experiments, efficient inference, and integrating models into applications.

## Contact me

I'm happy to discuss internship and junior opportunities, ML projects, or collaboration.

**Location:** Saratov, Russia · Open to remote work  
**Languages:** Russian — native; English — B2

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=fff)](https://t.me/hariton_p)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=maildotru&logoColor=fff)](mailto:pitsikhariton@yandex.ru)


