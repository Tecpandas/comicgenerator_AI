# 🎨 AI-Powered Comic Generator

Turn your creative stories into stunning comic strips using AI-powered image generation, natural language captioning, and voice narration — all within a beautiful Streamlit interface.

![App Screenshot](https://via.placeholder.com/800x400.png?text=Comic+Generator+Preview)

## 🚀 Features

- ✍️ **Text-to-Comic**: Enter your story line-by-line or sentence-by-sentence.
- 🧠 **AI-Powered Captioning**: Automatically generates comic-style captions for each scene using a language model.
- 🖼️ **Image Generation**: Visualize scenes in multiple styles like *Cartoon*, *Anime*, or *Marvel Comic* using Stable Diffusion.
- 🎙️ **Voice Narration**: Converts captions to voice using Google Text-to-Speech (gTTS).
- 📄 **Comic Page Compilation**: Combines individual panels into comic pages.
- ⬇️ **Downloadable Pages**: Save and download final comic pages as high-resolution PNGs.

---

## 💻 Tech Stack

| Tool        | Purpose                                     |
|-------------|---------------------------------------------|
| `Streamlit` | Interactive Web UI                          |
| `Transformers` | Caption generation using `flan-t5-small` |
| `Diffusers` | Stable Diffusion-based image synthesis      |
| `Pillow`    | Image editing and panel layout              |
| `gTTS`      | Text-to-Speech narration                    |
| `PyTorch`   | Model acceleration on GPU                   |

---

## 📦 Installation

### 1. Set Up Environment

Install required packages:

```bash
pip install streamlit diffusers transformers accelerate pillow gTTS
2. (Optional) Enable GPU in Google Colab

    Go to Runtime > Change runtime type > Set Hardware Accelerator to GPU.

    Save changes.

3. Clone and Run

streamlit run app.py

To expose on the web using localtunnel (in Colab or locally):

npx localtunnel --port 8501

🖼️ Usage Instructions

    Launch the app.

    Enter your story — one scene per line or sentence.

    Choose a visual style (Default / Comic / Cartoon / Anime).

    Click "Generate Comic".

    View, listen to, and download your AI-generated comic pages.
