

## 🎤 AI Audio Processor

This project uses OpenAI's Whisper for high-accuracy speech-to-text and Hugging Face Transformers (like DistilBART) for summarization.
It is perfectly suited for students and professionals to record lectures, meetings, or any audio, and instantly receive a full transcript and a concise AI-generated summary.

---

## 📦 Required Libraries

Before running the app, install the following Python packages:

```bash
pip install gradio openai-whisper transformers reportlab
```

If you're using Google Colab, just run the first cell in the notebook to install everything automatically.

---

## 🚀 How to Run

You can run this project in **two ways**: locally on your machine or directly in **Google Colab**.

### 🖥️ Option 1: Run Locally

1. **Clone this repository**:
   ```bash
   git clone https://github.com/rayesh24/FJP-FINAL-PROJECT.git
   ```

2. **Navigate into the project folder**:
   ```bash
   cd FJP-FINAL-PROJECT
   ```

3. **Install dependencies**:
   ```bash
   pip install gradio openai-whisper transformers reportlab
   ```

4. **Run the app**:
   ```bash
   python app.py
   ```

5. The app will launch in your browser with a **public Gradio URL**.

---

### ☁️ Option 2: Run in Google Colab

1. Open the Colab notebook directly from GitHub:
   > 🔗 [Open in Colab: Just click the colab icon on the ipynb file]

2. Click **“Connect”** and then **“Run All”** to execute the notebook.

3. Upload your audio file when prompted and follow the interface to process and download results.

---

## 🎧 Sample Audio File

Use this sample audio to test the app:

> 🔗 [Sample Audio File – TED Talk](https://file-examples.com/wp-content/uploads/2017/11/file_example_MP3_700KB.mp3)

---

### 🎧 How to Use

1. **Upload an audio file** or record using your microphone.
2. **Select the language** of the audio.
3. Click **🚀 Process Audio** to transcribe and summarize.
4. Review the **Transcript** and **Bullet-Point Summary**.
5. Click **📥 Download PDF** to save the results.

---

### ✨ Enhanced Features

- **Automatic Transcription:** Powered by OpenAI's Whisper for high accuracy, even with technical terminology.
- **AI-Powered Summarization:** Uses a fine-tuned model (e.g., DistilBART) to generate concise, bullet-point summaries from long lectures.
- **Live Recording:** Built-in functionality to record audio directly within the app.
- **PDF Export:** Download a neatly formatted PDF containing both the full transcript and the summary for offline use.
- **Web Interface:** A user-friendly Gradio app that can be shared via a public URL for easy access from any device.

---

### 🛠 Troubleshooting

- **ModuleNotFoundError**: Make sure all required packages are installed.
- **CUDA errors**: If you're not using a GPU, change `device=0` to `device=-1` in the `pipeline()` call.
- **Audio not uploading**: Ensure the file format is supported (`.mp3`, `.wav`, `.m4a`, etc.).

---

### 📜 License

This project is open-source and free to use under the MIT License.

---

