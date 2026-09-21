# Copilot Chat design mock

Live: https://adityavanna.github.io/copilot-designs/

Keep `index.html`, `support.js`, and `assets/` in the same folder. Opening the HTML file by itself (Downloads, email, Slack) shows raw `{{ placeholders }}`.

## Run locally

```bash
git clone https://github.com/AdityaVanna/copilot-designs.git
cd copilot-designs
python -m http.server 8000
```

On Windows, if `python` is missing:

```bash
py -3 -m http.server 8000
```

Then open http://localhost:8000/

Stop the server with Ctrl+C.
