# 🎨 AI POSTER GENERATOR
 <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXg1NDZwaW4zcm1vc29sMmptNm94M3dyazNjOHVhZTVzaG5uNDhyYSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/12r4pHjvAOv48o/giphy.gif" width="500" align="centre"></h2>

Transform your images with simple text prompts powered by Streamlit and Pillow.

Checkout our APP : https://penpotversion1-u9mwwdvgztkkyowfbhgjrc.streamlit.app/

## Features
- **Drag‑and‑drop upload** – just drop a JPG/PNG into the browser.
- **Prompt‑driven transformations** – type “make it bright and sunny” and watch the magic.
- **Example prompt buttons** – click to auto‑fill creative ideas.
- **Before/After comparison** – see your edits side‑by‑side.
- **One‑click download** – save the transformed PNG instantly.
- **Beautiful UI** – custom CSS, gradient buttons, and smooth progress animation.

## Tech Stack
- [Streamlit](https://streamlit.io/) — lightning‑fast Python web apps.
- [Pillow](https://python-pillow.org/) — image processing library.

## Quick Start
```bash
# 1. Clone
git clone https://github.com/your‑handle/ai-image-editor.git
cd ai-image-editor

# 2. (Recommended) Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch 🖥️
streamlit run app.py
```

Open the provided URL in your browser and start editing!

## Project Structure
```
├── app.py               # Streamlit application
├── requirements.txt
├── README.md
├── CONTRIBUTING.md
└── CHANGELOG.md
```

## Roadmap
- Replace mock filters with diffusion‑based generative editing (e.g., Stable Diffusion).
- Add masking & selective edits.
- History / undo stack.
- Dark mode toggle.

## Contributing
Pull requests are welcome! See **CONTRIBUTING.md** for details.

## License
GNU 3.0
