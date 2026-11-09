<div align="center">

# 你好，我是 Yaqiong 👋

**翻译 / 语言学背景 → LLM Evaluation · Language AI**

文科生的语言学直觉 × 工程落地能力：做评测工具、语料工程和本地优先的 Web 应用

<sub>Translation & linguistics background, building toward LLM Evaluation / Language AI — evaluation tooling, corpus engineering, and local-first web apps.</sub>

<br/>

![LLM Evaluation](https://img.shields.io/badge/LLM-Evaluation-6E56CF?style=flat-square) ![Corpus Engineering](https://img.shields.io/badge/Corpus-Engineering-0E8A6B?style=flat-square) ![Translation Tech](https://img.shields.io/badge/Translation-Tech-D97706?style=flat-square) ![Local First](https://img.shields.io/badge/Local--First-Web_Apps-2563EB?style=flat-square)

</div>

---

### 🧭 我在做什么

- 🧪 **评测**：LLM-as-a-Judge、量规设计、评分一致性（κ）与人工复评流程
- 📚 **语料**：多版本平行语料库、句对齐、术语抽取与译者风格计量
- 🛠️ **工程**：Python / FastAPI 后端 + 零依赖纯前端工具，数据默认不出本机

---

### 🧪 LLM 评测工具链

<table>
<tr>
<td width="50%" valign="top">

**[PaperLens](https://github.com/tanyaqiongcode/paperlens)** &nbsp;![stars](https://img.shields.io/github/stars/tanyaqiongcode/paperlens?style=social)

本地部署的论文查重 + AIGC 检测 + 联网核查 + 降重改写一站式平台，完全离线内核。

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

</td>
<td width="50%" valign="top">

**[paper-grader](https://github.com/tanyaqiongcode/paper-grader)**

中文学术论文 LLM 辅助批量批改：可插拔量规、逐维度评分、置信度 + 人工复评标记，Excel 成绩汇总。

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LLM](https://img.shields.io/badge/LLM--as--a--Judge-6E56CF?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Bilingual-Term-Extract](https://github.com/tanyaqiongcode/Bilingual-Term-Extract)**

平行文本双语术语提取：统计召回 + LLM 精筛，TBX / CSV 导出，兼容 Trados MultiTerm 与 memoQ。

![Agent Skill](https://img.shields.io/badge/Agent-Skill-6E56CF?style=flat-square) ![TBX](https://img.shields.io/badge/TBX-CSV-555?style=flat-square)

</td>
<td width="50%" valign="top">

**[nlp-learning-site](https://github.com/tanyaqiongcode/nlp-learning-site)** · [在线访问 ↗](https://tanyaqiongcode.github.io/nlp-learning-site/)

面向文科生的 NLP 学习站：κ 一致性、LLM-as-a-Judge 等在线实验 + 每日前沿动态，零依赖双击即用。

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</td>
</tr>
</table>

### 🔤 翻译工程

<table>
<tr>
<td width="50%" valign="top">

**[Mini-CAT](https://github.com/tanyaqiongcode/mini-cat)** · [在线访问 ↗](https://tanyaqiongcode.github.io/mini-cat/)

浏览器端翻译记忆 CAT 工具：TM + 术语库 + 模糊匹配 + 审校留痕，零依赖、数据不出本机。

</td>
<td width="50%" valign="top">

**[multi-align](https://github.com/tanyaqiongcode/multi-align)** · [在线访问 ↗](https://tanyaqiongcode.github.io/multi-align/)

5–10 语种平行语料句对齐工作台（Gale-Church），审校 + TMX / Excel 导出。

</td>
</tr>
</table>

### 🧩 Agent Skills

| Skill | 用途 |
|---|---|
| cohesion-writing-translation <sub>🔒私有</sub> | AI 写作与翻译衔接规范：七检查点 + 机检清单 + 判例库 |
| documentary-style-calibration <sub>🔒私有</sub> | 中文学术著作英译的纪录片旁白风格校准 |
| [weread-shelf-organizer](https://github.com/tanyaqiongcode/weread-shelf-organizer) | 微信读书书架自动整理：重组 / 增量归类 / 迁移核验 |

### 📚 备考站产品线

<sub>均带每日自动更新素材（GitHub Actions 定时任务）</sub>

| 站点 | 方向 |
|---|---|
| [python2-pass ↗](https://tanyaqiongcode.github.io/python2-pass/) | 上信考 Python 二级 · 浏览器内在线判题 |
| [catti2-pass ↗](https://tanyaqiongcode.github.io/catti2-pass/) | CATTI 英语二级笔译 + 口译 |
| [ielts-listen-speak-7plus ↗](https://tanyaqiongcode.github.io/ielts-listen-speak-7plus/) | 雅思听口训练营 · 听写工作台 |
| [bec-higher-180 ↗](https://tanyaqiongcode.github.io/bec-higher-180/) | BEC 高级 180 突围营 |
| [sia-spring2027 ↗](https://tanyaqiongcode.github.io/sia-spring2027/) | 上海高级口译 2027 春季 |

### 🔒 研究语料

<sub>私有，随论文按需提供</sub>

- 《动物农场》六版本译者风格平行语料库 — 1,512 对齐单元 + 术语库 + 全部统计
- 《瓷器中国》ZH↔EN 翻译语料与术语库
- 行为可控性标注复现框架

---

### 🛠️ 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Trados](https://img.shields.io/badge/Trados-memoQ-555?style=flat-square)

<div align="center">

<br/>

⭐ 如果对你有帮助，欢迎 Star **[PaperLens](https://github.com/tanyaqiongcode/paperlens)** · **[Mini-CAT](https://github.com/tanyaqiongcode/mini-cat)** · **[multi-align](https://github.com/tanyaqiongcode/multi-align)**

</div>
