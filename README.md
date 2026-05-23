# Bhargav Portfolio POC

Agentic dark portfolio proof-of-concept for Bhargav Kacharla.

Open locally:

```bash
open index.html
```

Test the RAG chatbot locally:

```bash
cp config.example.js config.js
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

For GitHub Pages deployment, set repository variable `PORTFOLIO_RAG_API_URL` to the deployed RAG API origin, for example:

```text
https://your-rag-api.up.railway.app
```

The deployment workflow writes `config.js` from that variable, and the frontend calls `/agent/ask`.

Design direction:
- Adam Boudjemaa-inspired agentic portfolio
- Dark cyber/AI background with particles, grid, glow, noise
- Split hero with terminal profile and live agent status
- Services cards for audit agents, protocol engineering, and security review
- Agentic systems proof section
