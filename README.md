# 🧪 Materials & AI Utility Scripts

> Ready-to-run code · Materials data pipeline · AI-assisted tools · Knowledge base management

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

---

## ✨ Overview

The companion utility scripts for xuanhan's AI workstation. Every script is a standalone, directly runnable Python tool. No framework dependency — copy and use.

---

## 📦 Script Inventory

### Materials Data
| Script | Purpose |
|--------|---------|
| `data/mat_pipeline.py` | Materials data pipeline (MLflow experiment tracking integrated) |
| `data/mat_features.py` | Materials feature engineering (descriptor computation, feature selection) |

### AI Assistance
| Script | Purpose |
|--------|---------|
| `ai/review_code.py` | Code review (Codex + MiMo Pro API) |
| `ai/gen_doc.py` | Automated documentation generation |

### Knowledge Base
| Script | Purpose |
|--------|---------|
| `kb/kb_update.py` | Batch KB updates |
| `kb/kb_validate.py` | KB format validation |

### Zotero
| Script | Purpose |
|--------|---------|
| `zotero/zotero_batch.py` | Zotero batch import |
| `zotero/paper_to_kb.py` | Paper → KB conversion (Stirling PDF integration) |

### System
| Script | Purpose |
|--------|---------|
| `system/health_check.py` | System health check (VRAM / disk / service status) |
| `system/gpu_monitor.py` | Real-time VRAM monitoring |

---

## 🚀 Usage

```bash
# Install dependencies
pip install pymatgen scikit-learn mlflow requests

# Run any script
python data/mat_pipeline.py
python system/health_check.py
```

---

## 🤝 Contributing

PRs welcome for new utility scripts!

---

## 📄 License

MIT — see [LICENSE](LICENSE)
