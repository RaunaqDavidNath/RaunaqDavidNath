<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Raunaq%20David%20Nath&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20/%20ML%20Engineer&descAlignY=55&descSize=20" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=7B61FF&center=true&vCenter=true&width=650&lines=Computer+Vision+%7C+Model+Efficiency+%7C+AI+Systems;Aerial+detection+at+0.854+mAP;Networks+that+prune+themselves;Catalogs+that+write+their+own+docs" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=RaunaqDavidNath&style=for-the-badge&color=7B61FF&label=PROFILE+VIEWS" alt="Profile views" />

</div>

<img width="100%" src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" />

## 🧠 About

> I build AI systems that run **end to end** — not notebooks that stop at a plot.
> Computer vision on aerial imagery, neural networks that compress themselves during training,
> and data infrastructure that documents itself using LLMs.

<img width="100%" src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" />

## ⚡ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

**Deep Learning & Vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white)

**AI & LLM**

![Gemini](https://img.shields.io/badge/Gemini_2.0_Flash-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Embeddings](https://img.shields.io/badge/Vector_Embeddings-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

**Data & Tooling**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-2C5BB4?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

<img width="100%" src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" />

## 🚀 Featured Projects

### 🔦 LUMEN — *Metadata catalog that documents itself*

<p>
<img src="https://img.shields.io/badge/sqlglot-4B8BBE?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/NetworkX-2C5BB4?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini_2.0_Flash-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/FastMCP-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
</p>

A lightweight catalog for SQL warehouses that **writes its own documentation**. It parses SQL views with `sqlglot` to build a dependency graph down to **column level**, then has Gemini 2.0 Flash generate a plain-English description, business glossary term, and owner team for every asset — so the catalog stays documented instead of waiting on humans who never get around to it.

Semantic search runs over vector embeddings, and the catalog is reachable two ways: a **Streamlit UI** for browsing, and an **MCP server** so an AI agent can query the lineage graph in plain language.

```
SQL schema ──▶ SQLite ──▶ lineage parse ──▶ AI enrichment ──┬──▶ Streamlit UI
                                                            └──▶ MCP server ──▶ AI agent
```

---

### 🛸 UAV Vehicle Detection — *YOLOv5 on drone imagery*

<p>
<img src="https://img.shields.io/badge/DRDO--DEAL_Internship-1F6FEB?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/YOLOv5s-00FFFF?style=flat-square&logo=yolo&logoColor=black" />
<img src="https://img.shields.io/badge/Tesla_T4-76B900?style=flat-square&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logo=roboflow&logoColor=white" />
</p>

Detects buses, cars, and trucks from drone footage, where the top-down perspective breaks most assumptions baked into ground-level detectors.

<div align="center">

![mAP@0.5](https://img.shields.io/badge/mAP@0.5-0.854-brightgreen?style=for-the-badge)
![mAP@0.5:0.95](https://img.shields.io/badge/mAP@0.5:0.95-0.472-green?style=for-the-badge)
![Precision](https://img.shields.io/badge/Precision-0.861-blue?style=for-the-badge)
![Recall](https://img.shields.io/badge/Recall-0.789-blueviolet?style=for-the-badge)

</div>

YOLOv5s (~7.0M params), COCO-pretrained then fine-tuned for **100 epochs** on **3,795** annotated aerial images. The augmentation policy was rebuilt for overhead views — ±15° rotation, 50% vertical flip, 0.6 scale, 0.1 mixup — rather than inheriting defaults tuned for street-level photography.

Cars scored highest at **0.905** mAP@0.5. Trucks were hardest: from directly overhead, a truck and a bus are close to the same rectangle.

---

### ✂️ Self-Pruning Neural Networks — *learned sparsity during training*

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Model_Compression-FF6F00?style=flat-square&logoColor=white" />
</p>

A network that decides which of its **own connections to delete**. A custom `PrunableLinear` layer attaches a learnable gate to every weight, squashed through a sigmoid so pruning is *soft* — connections fade toward zero across training instead of being cut by a hard threshold afterwards. The loss combines cross-entropy with a sparsity term, and a single lambda controls where the accuracy-versus-efficiency trade-off lands.

Built across three iterations:

| Stage | Architecture | What it added |
|:--|:--|:--|
| 1 | Baseline MLP | Reference accuracy |
| 2 | Self-pruning MLP | Learnable sigmoid gates |
| 3 | CNN + prunable classifier | Spatial features *and* self-compression |

---

### 📡 Role_Radar — *self-hosted job monitoring*

<p>
<img src="https://img.shields.io/badge/Python_3.9+-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/ntfy.sh-317F6F?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" />
</p>

Polls **Ashby, Greenhouse, and Lever** career APIs on a timer, filters new postings for relevance through a **locally-run** Ollama model, and pushes alerts to desktop and phone. No API keys, no accounts, no third-party service in the loop.

Designed to **fail open** — if the model is unavailable, postings get surfaced rather than silently dropped. A noisy notification beats a missed one.

<img width="100%" src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" />

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=RaunaqDavidNath&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight&title_color=7B61FF&icon_color=7B61FF" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RaunaqDavidNath&layout=compact&hide_border=true&langs_count=8&theme=tokyonight&title_color=7B61FF" alt="Top languages" />

<br/><br/>

<img height="165" src="https://streak-stats.demolab.com?user=RaunaqDavidNath&hide_border=true&theme=tokyonight&ring=7B61FF&fire=7B61FF&currStreakLabel=7B61FF" alt="Streak stats" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=RaunaqDavidNath&theme=tokyo-night&hide_border=true&line=7B61FF&point=ffffff&area=true" alt="Activity graph" />

<br/>

<img width="95%" src="https://github-profile-trophy.vercel.app/?username=RaunaqDavidNath&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" />
