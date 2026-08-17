# Raunaq David Nath

**AI/ML Engineer** — computer vision, model efficiency, and AI systems that run end to end rather than stopping at a notebook.

<!-- TODO: replace with your real details, or delete the line entirely.
     e.g. B.Tech in <branch> at <college>, graduating <year>. -->

---

## Featured Work

### LUMEN — Metadata catalog with automated lineage and AI enrichment

A lightweight catalog for SQL warehouses that builds its own documentation. It parses SQL views with `sqlglot` to construct a dependency graph at **table and column level**, then uses Gemini 2.0 Flash to generate a plain-English description, business glossary term, and owner team for every asset — so the catalog documents itself instead of waiting on humans who never get to it.

Search runs over vector embeddings (`text-embedding-004`), and the catalog is reachable two ways: a Streamlit UI for browsing, and an **MCP server** so an AI agent can query the lineage graph conversationally.

`sqlglot` · `networkx` · `pyvis` · SQLite · Gemini 2.0 Flash · Streamlit · FastMCP

---

### UAV Vehicle Detection — YOLOv5 on aerial imagery

Built during a **DRDO-DEAL internship**. Detects buses, cars, and trucks from drone footage, where the top-down perspective breaks most of the assumptions baked into ground-level detectors.

| Metric | Score |
|---|---|
| mAP@0.5 | **0.854** |
| mAP@0.5:0.95 | 0.472 |
| Precision | 0.861 |
| Recall | 0.789 |

YOLOv5s (~7.0M params), COCO-pretrained then fine-tuned for 100 epochs on 3,795 annotated aerial images. The augmentation policy was rebuilt for overhead views — ±15° rotation, 50% vertical flip, 0.6 scale, 0.1 mixup — rather than inheriting defaults tuned for street-level photography.

Cars were the strongest class at 0.905 mAP@0.5; trucks were hardest, since from directly overhead a truck and a bus are close to the same rectangle.

---

### Self-Pruning Neural Networks — learned sparsity during training

A network that decides which of its own connections to delete. A custom `PrunableLinear` layer attaches a learnable gate to every weight, squashed through a sigmoid so pruning is *soft* — connections fade toward zero across training instead of being cut by a hard threshold after the fact. Training optimises cross-entropy plus a sparsity term, with a lambda controlling where the accuracy/efficiency trade-off lands.

Developed across three iterations: a baseline MLP, the gated self-pruning MLP, and a final CNN feature extractor feeding a prunable classifier — keeping spatial feature learning while the classifier compresses itself.

PyTorch

---

### Role_Radar — self-hosted job monitoring

Polls Ashby, Greenhouse, and Lever career APIs on a timer, filters new postings for relevance through a **local** Ollama model, and pushes alerts to desktop and phone via ntfy.sh. No API keys, no accounts, no third-party service in the loop.

Designed to **fail open**: if the model is unavailable, postings are surfaced rather than silently dropped — a missed notification is a worse failure than a noisy one.

Python · Ollama · MIT licensed

---

## Currently

Contributing to [Kestra](https://github.com/kestra-io/kestra), an open-source workflow orchestration platform.

<!-- TODO: update this line as things change. Keep it current or delete it —
     a stale "currently" line is worse than none. -->

---

## GitHub

<p align="left">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=RaunaqDavidNath&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RaunaqDavidNath&layout=compact&hide_border=true&langs_count=6" alt="Top languages" />
</p>
