# Cameron Letendre

MS Computer Science, University of Southern Maine - Graduation May 2027.
NLP, Agentics, and machine learning in data science.

**Currently**
- Working with **MaineHealth Institute for Research** on NLP and ML research. Supported by a Student Research Fellowship
- Working at the YESS Lab at the **University of Maine** on HCI agentics research.

| | |
|---|---|
| **NLP / ML** | Python · PyTorch · Transformers · scikit-learn · OCR |
| **Agents** | Anthropic API · eval harnesses · TypeScript |
| **Also** | C# / Unity · Dart / Flutter · FastAPI · SQL |

---

## 日本語

サザンメイン大学の修士課程（コンピュータサイエンス）に在籍しており、2027年5月に修了予定です。
自然言語処理とAIエージェント、そして実世界のデータを用いた機械学習を専門としています。

**現在**
- **MaineHealth Institute for Research** と連携し、NLPおよびMLの研究に取り組んでいます。学生研究フェローシップの支援を受けています
- **メイン大学**のYESS Labで、HCIエージェントに関する研究に従事している。
- 2024年度、神田外語大学の交換留学生です。
- 日本語能力試験（JLPT）N3を受験する予定です。
---

## Selected work

**[distilbert-toxicity-classification](https://github.com/CameronLetendre/distilbert-toxicity-classification)**
— Real-time toxicity classification for in-game chat: screen capture → OCR → fine-tuned
DistilBERT → live overlay, running end to end on live gameplay. Reaches 0.9133 UCA on the
CONDA dataset, within a point of the published JointBERT baseline, with a distilled model.

The more useful result is negative. Adding a time feature made every class worse, and the
paper shows why: CONDA's labels are conditioned on content, not on time. `P(O | time bin)`
stays within [0.727, 0.760] against a 0.742 marginal, and the mean KL from the marginal is
0.006 bits.

**[cos184-python-course-materials](https://github.com/CameronLetendre/cos184-python-course-materials)**
— The lecture notebooks I wrote and taught for COS 184, Introduction to Python. Twenty-four
sessions built as runnable notebooks rather than slides, each opening with spaced-repetition
review, sequenced around the concepts students reliably trip on rather than around chapter
boundaries.

## A note on what is not here

Most of my research code is not public. The MaineHealth corpus work involves protected
health-adjacent documents under NDA, and the agent work is an active IRB study.
Neither can be published, and I would rather say so than leave the gap unexplained. I am
happy to talk about either in detail.

## Contact

[LinkedIn](https://linkedin.com/in/cameronletendre/) · cameron.letendre@maine.edu · 
