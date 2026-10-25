# LogicCoach

LogicCoach is a web app that teaches programming logic. Enter a problem and it explains the idea step by step, draws a flowchart, and gives a 10-question easy quiz with hints. If you keep failing, it reveals the full code (Python, C or C++, your choice), explains your weak points and suggests how to improve.

## Run
1. Install [Ollama](https://ollama.com) and pull a model: `ollama pull gemma4:e2b`
2. Start it allowing the browser: `OLLAMA_ORIGINS="*" ollama serve`
3. Open `index.html` (or serve the folder: `python3 -m http.server 8000`).

## Stack
Plain HTML/CSS/JavaScript, Mermaid (flowcharts), Ollama.
Templates or starter kits used: none.

## Models and AI
- Open-weight model: Google Gemma (gemma4:e2b), run locally through Ollama. It generates explanations, flowcharts, quiz questions, hints, code and learning advice. The deployed page on GitHub Pages is only the interface, so the model is shown running locally during the live defense.
- Proprietary models in the product: none.
- AI coding assistant: Claude was used to generate the initial code during the competition period.

## Licence
MIT