![Nathan Benincase](https://capsule-render.vercel.app/api?type=rect&color=0:09090b,100:881337&height=130&text=Nathan%20Benincase&fontSize=44&fontColor=ffffff)

I build developer tools, ship projects people can use, and fix bugs in open-source software. I published **SiteMed**, a Chrome extension that explains broken webpages in plain English, and contributed fixes to **NVIDIA’s kvpress and garak**.

[Chrome Web Store](https://chromewebstore.google.com/detail/sitemed/knhjhefdfnlaoidhmmdkhmflabkccljc) · [Merged pull requests](https://github.com/search?q=author%3ANathanBenDev+is%3Apr+is%3Amerged&type=pullrequests)
<!-- Add your Portfolio and LinkedIn links to the line above. -->

## Open-source contributions

[![NVIDIA kvpress](https://img.shields.io/badge/NVIDIA-kvpress-881337?style=for-the-badge&logo=nvidia&logoColor=white)](https://github.com/NVIDIA/kvpress/pull/302)
[![NVIDIA garak](https://img.shields.io/badge/NVIDIA-garak-881337?style=for-the-badge&logo=nvidia&logoColor=white)](https://github.com/NVIDIA/garak/pull/2142)

- **kvpress** — Fixed a generation crash caused by uneven cache lengths across model layers. Added tests for batched and token-by-token decoding.
- **garak** — Fixed broken Markdown link templates and added regression tests for the corrected output.

## Selected projects

| Project | What I built | Explore |
| --- | --- | --- |
| **SiteMed** | A TypeScript Chrome extension that detects failed requests, JavaScript errors, and broken images, then explains what happened and what to try next. | [Install](https://chromewebstore.google.com/detail/sitemed/knhjhefdfnlaoidhmmdkhmflabkccljc) · [Site source](https://github.com/NathanBenDev/SiteMed-Site) |
| **Escape Circuit** | A first-person Godot game where the fly’s escape behavior is influenced by circuits derived from fruit-fly neural data. | [Source](https://github.com/NathanBenDev/EscapeCircuit) |
| **Grounded Search** | A local search engine that ranks passages from PDFs and other documents and points back to the original sources. | [Source](https://github.com/NathanBenDev/RAG-Pipeline) |

<!-- To show gameplay here, upload assets/escape-circuit.gif and uncomment the line below. -->
<!-- ![Escape Circuit gameplay](assets/escape-circuit.gif) -->

## Technical skills

| Area | Skills and examples |
| --- | --- |
| **Web development** | **TypeScript, JavaScript, Chrome Extension APIs** — built and published SiteMed, which detects failed requests, JavaScript errors, and broken page assets. |
| **Python & data** | **Python, SQL, SQLite** — built a local document search engine and queried iPhone backup databases to locate notes and voice memos. |
| **Debugging & testing** | **pytest, regression testing, HTTP debugging** — reproduced bugs and added tests for fixes merged into NVIDIA’s kvpress and garak. |
| **Development tools** | **Git, GitHub, Ubuntu Linux, Godot** — contributed upstream fixes, managed an Ubuntu server, and built a playable 3D game. |
| **Code review** | **Rust and C++** — reviewed code and evaluated correctness in AI coding tasks. |

## How I work

I like tracking down why something broke, reproducing it in a small test, and leaving behind a fix someone else can verify. SiteMed applies that same idea to the browser by showing people what went wrong in terms they can act on.
