# AI-Powered ATS Resume Scorer — Downloads

*Next-gen AI résumé intelligence.* Advanced AI scores and rewrites your résumé to beat the bots — AI semantic matching understands how your résumé fits the job, then AI rewrites it to win. 100% private: the AI runs on your machine and your résumé never leaves it.

## Download

Grab the latest build from the [*Releases*](../../releases/latest) page:

| OS | File |
|----|------|
| *macOS* | ATS-Resume-Scorer-macos.zip |
| *Windows* | ATS-Resume-Scorer-windows.exe |

## First run

*Recommended — install [Ollama](https://ollama.com):* the scorer uses a small embedding model via Ollama for the most accurate semantic score. It's lightweight (runs on almost any machine) and downloads the model automatically. Without Ollama the app still works, but scores use a simpler offline method and will vary.

*Rewriting needs no setup:* after scoring you get a ready-to-paste *ChatGPT prompt. *(Rewriting inside the app with a local chat model is a separate, optional feature — off by default, for advanced users with a capable machine.)

*macOS* — the app is unsigned, so the first launch needs:
1. Download ATS-Resume-Scorer-macos.
2. In Terminal: chmod +x ~/Downloads/ATS-Resume-Scorer-macos
3. Right-click the file → *Open* → *Open* (bypasses Gatekeeper once).
4. It starts a local server and opens your browser.

*Windows* — double-click ATS-Resume-Scorer-windows.exe. If SmartScreen appears: *More info → Run anyway*.

## Activation

You'll need an *Access Key* (sent to you by the owner). Paste it on the activation screen on first launch — it's tied to that one machine.

---

Source code is maintained privately. This repository only hosts the downloadable builds.
