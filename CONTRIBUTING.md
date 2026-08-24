# Contributing to CBT Toolkit

Thanks for your interest in improving these free CBT and mental health tools!

## Ways to Contribute

### Report a Bug
Use the [Bug Report template](../../issues/new?template=bug_report.md).

### Suggest a Feature
Use the [Feature Request template](../../issues/new?template=feature_request.md).

### Add a New CBT Tool
1. Create a single HTML file in seo/ or root
2. Use vanilla JavaScript only (no frameworks, no build step)
3. Store data in localStorage (no backend, no signup)
4. Follow the existing pattern: keyword-pattern matching for detection, structured output
5. Add a link to the tool in seo/cbt-toolkit-hub.html
6. Submit a PR

### Improve Existing Tools
- Fix bugs in distortion detection patterns
- Add new cognitive distortions to the classifier
- Improve the UI/UX of any tool
- Add translations

## Design Principles

- **No signup, no backend, no tracking** — privacy-first
- **Vanilla JavaScript** — no dependencies, no build step
- **localStorage** — data stays on the user's device
- **Evidence-based** — CBT techniques from established research

## Questions?

Open a [Discussion](../../discussions) — we have a community Q&A section.