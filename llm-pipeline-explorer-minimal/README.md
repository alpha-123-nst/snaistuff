# LLM Pipeline Explorer – Minimal UI

This is a lightweight, clean version of the original **LLM Pipeline Explorer** demo. It retains all functionality (tokenizer, vocabulary slider, 3‑D Plotly embedding) but uses a minimal CSS style for a distraction‑free experience.

## How to run
```bash
cd ~/Desktop/abc/llm-pipeline-explorer-minimal
open index.html   # on macOS
# or serve with any static server, e.g.:
python -m http.server 8000
```

The page works offline; the only external dependency is Plotly loaded from the CDN.
