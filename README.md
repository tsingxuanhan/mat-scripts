# 🧪 材料数据脚本集 | Materials & AI Utility Scripts

> 能直接跑的代码 · 材料数据Pipeline · AI辅助工具 · 知识库管理

[![Python](https://img.shields.io/badge/Python-3.10+-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()

## ✨ 概述

这是铉瀚AI工作站配套的工具脚本集。每个脚本都是独立的、可直接运行的Python工具。不依赖框架，copy即用。

## 📦 脚本清单

### 材料数据
| 脚本 | 用途 |
|------|------|
| `data/mat_pipeline.py` | 材料数据Pipeline（集成MLflow实验追踪） |
| `data/mat_features.py` | 材料特征工程（描述符计算、特征选择） |

### AI辅助
| 脚本 | 用途 |
|------|------|
| `ai/review_code.py` | 代码审查（Codex+MiMo Pro API） |
| `ai/gen_doc.py` | 文档自动生成 |

### 知识库
| 脚本 | 用途 |
|------|------|
| `kb/kb_update.py` | KB批量更新 |
| `kb/kb_validate.py` | KB格式校验 |

### Zotero
| 脚本 | 用途 |
|------|------|
| `zotero/zotero_batch.py` | Zotero批量导入 |
| `zotero/paper_to_kb.py` | 论文→KB（集成Stirling PDF） |

### 系统
| 脚本 | 用途 |
|------|------|
| `system/health_check.py` | 系统巡检（显存/磁盘/服务状态） |
| `system/gpu_monitor.py` | 实时显存监控 |

## 🚀 使用

```bash
# 安装依赖
pip install pymatgen scikit-learn mlflow requests

# 运行任意脚本
python data/mat_pipeline.py
python system/health_check.py
```

## 🤝 贡献

欢迎提交PR添加新的实用脚本！

## 📄 License

MIT — 详见 [LICENSE](LICENSE)
