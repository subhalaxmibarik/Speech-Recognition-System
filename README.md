# Speech Recognition System

A speech recognition project built using **NVIDIA NeMo Speech** for working with automatic speech recognition (ASR) models. The project explores speech-to-text processing using pretrained deep learning models and provides a foundation for experimenting with modern speech AI.

## 🚀 Features

- 🎙️ Automatic Speech Recognition (ASR)
- 🔊 Speech-to-text processing
- 🤖 Deep learning-based speech models
- 🧠 Support for pretrained NVIDIA NeMo models
- 🐍 Python-based implementation
- ⚡ GPU acceleration using CUDA
- 📊 Suitable for experimenting with speech recognition and audio processing

## 🛠️ Technologies Used

- **Python**
- **PyTorch**
- **NVIDIA NeMo Speech**
- **CUDA**
- **Automatic Speech Recognition (ASR)**
- **Deep Learning**

## 📂 Project Structure

```text
Speech-Recognition-System/
│
├── examples/          # Speech recognition examples
├── nemo/              # Core NeMo modules
├── scripts/            # Utility and execution scripts
├── tests/              # Testing files
├── docs/               # Documentation
├── README.md
└── LICENSE
```

## ⚙️ Requirements

The project is based on NVIDIA NeMo Speech and requires:

- Python 3.12+
- PyTorch 2.7+
- NVIDIA GPU + CUDA for training
- CUDA-compatible environment for GPU acceleration

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/subhalaxmibarik/Speech-Recognition-System.git
cd Speech-Recognition-System
```

Create and activate a Python environment, then install the required dependencies.

For the NeMo Speech environment, the recommended installation method is:

```bash
uv sync --extra all --extra cu13
```

For a custom PyTorch/CUDA setup:

```bash
pip install 'nemo-toolkit[asr,tts]'
```

## ▶️ Usage

After setting up the environment, speech recognition examples can be executed from the `examples/` directory.

Example:

```bash
python examples/asr/transcribe_speech.py
```

Refer to the individual example files for model-specific configuration and input requirements.

## 🧠 About the Project

This project focuses on understanding and working with **Automatic Speech Recognition**, where spoken audio is converted into written text.

The underlying NeMo Speech framework supports speech technologies including:

- Automatic Speech Recognition
- Text-to-Speech
- Speech Language Models
- Speech processing and model experimentation

## 📌 Learning Outcomes

Through this project, I explored:

- Speech-to-text systems
- Deep learning for audio processing
- Working with pretrained AI models
- PyTorch-based model workflows
- GPU/CUDA-based AI environments
- Running and experimenting with ASR models

## 📸 Demo

Add screenshots, sample input/output, or a short demo video here.

Example:

```text
Audio Input → Speech Recognition Model → Transcribed Text
```

## 🔮 Future Improvements

- Add a simple web interface for uploading audio
- Support real-time speech transcription
- Add multilingual speech recognition
- Improve inference speed
- Add confidence scores for transcriptions
- Deploy the system as a web application

## 📄 License

This project is based on NVIDIA NeMo Speech, which is licensed under the **Apache License 2.0**.

For more information, refer to the project's `LICENSE` file.

## 👩‍💻 Author

**Subhalaxmi Barik**

B.Tech – Industrial Design  
NIT Rourkela

GitHub: [subhalaxmibarik](https://github.com/subhalaxmibarik)
