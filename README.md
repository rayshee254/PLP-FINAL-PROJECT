

## 🎤 AI Lecture & Meeting Assistant

Tired of manually transcribing hours of lectures or meetings? This **AI Audio Processor** is your intelligent assistant, designed to transform spoken content into actionable text. Leverage the power of **OpenAI's Whisper** for near-perfect transcription and **Hugging Face's state-of-the-art models** for intelligent summarization. Perfect for students capturing key lecture points or professionals distilling meeting takeaways.

---

## 📦 Tech Stack & Installation

The app is built on a powerful and modern Python stack. Get started in seconds.

**Core Dependencies:**
- **[Gradio](https://www.gradio.app/)**: For building the sleek, shareable web interface.
- **[OpenAI Whisper](https://github.com/openai/whisper)**: The industry-leading model for robust speech-to-text.
- **[Transformers](https://huggingface.co/docs/transformers)**: By Hugging Face, to access the summarization pipeline.
- **[ReportLab](https://www.reportlab.com/)**: For generating clean, downloadable PDF reports.

**Quick Install:**
```bash
# Install everything with one command
pip install gradio openai-whisper transformers reportlab
```

---

## 🚀 Launch Your Personal AI Assistant

### 🖥️ Local Development (For Full Control)
Ideal for developers who want to tinker and customize.

1.  **Get the Code:**
    ```bash
    git clone https://github.com/rayesh24/FJP-FINAL-PROJECT.git
    cd FJP-FINAL-PROJECT
    ```

2.  **Install & Run:**
    ```bash
    pip install -r requirements.txt  # Installs all dependencies
    python app.py                   # Launches your local server
    ```
    Your browser will open automatically, and you'll get a public URL to share with others!

### ☁️ One-Click Google Colab (Zero Setup)
Perfect for a quick test or if you don't want to install anything.
1.  **Open the Notebook:**
    > 🔗 **[Open in Colab](https://colab.research.google.com/github/rayesh24/FJP-FINAL-PROJECT/blob/main/your_notebook.ipynb)** (Click the link or the Colab icon on GitHub)

2.  **Runtime -> Run All**: Sit back as Colab handles the installation and launches the app.
3.  A public Gradio link will appear at the bottom of the notebook—click it to start processing!

---

## 🎧 See It In Action: Test Drive

Not convinced? Try it immediately with our provided sample audio from a TED Talk. See the magic happen before uploading your own files.

> 🎧 **[Sample Audio File](https://www.learnoutloud.com/audiobooks/TheLongTail.mp3)**

---

### 🎯 How to Use: 3 Steps to Insight

The interface is designed for simplicity and power.

1.  **INPUT:** Drag & drop your lecture `.mp3`/`.wav` file **or** use the built-in recorder for live sessions.
2.  **PROCESS:** Select the audio language and hit the **"🚀 Process Audio"** button. Watch the AI work its magic.
3.  **OUTPUT:**
    - **Read** the flawless transcript and bullet-point summary directly in the app.
    - **Download** a professional PDF report with one click (**"📥 Download PDF"**) for your notes or archives.

---

### ✨ Enhanced Features

- **Automatic Transcription:** Powered by OpenAI's Whisper for high accuracy, even with technical terminology.
- **AI-Powered Summarization:** Uses a fine-tuned model (e.g., DistilBART) to generate concise, bullet-point summaries from long lectures.
- **Live Recording:** Built-in functionality to record audio directly within the app.
- **PDF Export:** Download a neatly formatted PDF containing both the full transcript and the summary for offline use.
- **Web Interface:** A user-friendly Gradio app that can be shared via a public URL for easy access from any device.

---

### ⚡ Under the Hood: How It Works

This isn't just a simple script; it's a robust pipeline:
1.  **Transcription Engine:** Whisper converts your audio to text with impressive accuracy, handling various accents and background noise.
2.  **Summarization Model:** We use `sshleifer/distilbart-cnn-12-6`, a fast and efficient model fine-tuned for abstractive summarization, to distill the key points from long-form text.
3.  **PDF Generation:** The ReportLab engine dynamically creates a well-structured PDF, ensuring your results are portable and presentation-ready.

---

### 🛠️ Pro Tips & Troubleshooting

-   **`No module named...` Error?** Double-check your installation. Run `pip install` commands again.
-   **Running on a CPU?** The app will automatically detect it. For the summarization step, it will use the CPU if a GPU is unavailable—no changes needed.
-   **File Format Issues?** Stick to common formats: `.mp3`, `.wav`, `.m4a`, and `.flac` are all supported.
-   **For Long Lectures:** The summarization model has a maximum input length. The app intelligently handles longer transcripts by processing the most relevant segments.

---

### 📜 License

This project is proudly open-source under the **MIT License**. Feel free to use it, learn from it, and build upon it for your own projects!

**Built with passion for the developer community.**
