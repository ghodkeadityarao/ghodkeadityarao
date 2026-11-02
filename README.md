# Hi, I'm Aditya Rao Ghodke

MS Data Science student at **Texas A&M University**. I build LLM, retrieval and machine learning systems, and I measure how well they work. Currently a Data Scientist Intern at Xometry.

[Portfolio](https://ghodkeadityarao.github.io/aditya-rao-ghodke/) · [LinkedIn](https://linkedin.com/in/ghodkeadityarao) · [LeetCode](https://leetcode.com/ghodkeadityarao) · [Coding Ninjas](https://www.naukri.com/code360/profile/ghodkeaditya)

## Featured projects

| Project | What it does | Measured result |
|---|---|---|
| [**Zenvest AI**](https://github.com/ghodkeadityarao/Zenvest-ai) ([live](https://zenvest-ai.onrender.com/)) | Turns a plain-English goal into five ETF picks from 2,264 funds. An LLM reads the goal, an XGBoost ranker orders the funds, SHAP shows the main factors. | On 150 held-out test profiles, 100% of the top five met the user's stated limits (75% in the original design), and the risk level ordered results correctly in 21 of 24 test groups (0 before). The LLM read 42 of 42 labelled goals correctly. The fund data is from March 2023. |
| [**Data Question Agent**](https://github.com/ghodkeadityarao/data-question-agent) ([live](https://data-question-agent.onrender.com/)) | Ask questions about a store database in English. Gemini writes the SQL, which runs read-only behind three guardrail layers, and you see the query and the rows. | 38 of 40 test questions answered correctly. All 25 dangerous queries were stopped; a plain database connection ran 19 of 23. |
| [**Kubernetes Docs Chatbot**](https://github.com/ghodkeadityarao/Kubernetes-Specific-Chatbot) ([live](https://kubernetes-chatbot.streamlit.app/)) | Answers Kubernetes questions from 1,122 pages of the official docs, with citations. Keyword and embedding search combined. | The right page was in the top 5 for 92% of 78 test questions. |
| [**Chat With Documents**](https://github.com/ghodkeadityarao/Chat-With-Documents) ([live](https://ask-any-document.streamlit.app/)) | Upload files in almost any format and ask questions. Every answer cites its page, slide or section. | Hybrid search with re-ranking found the right passage first for 90.5% of 2,000 test questions, against 73.6% in the original version. |
| [**ResuMate**](https://github.com/ghodkeadityarao/ResuMate-The-Effortless-Resume-Analysis-Tool) | Scores a resume out of 100 from 18 checks, shows the exact lines behind each lost point, and suggests roles. No LLM. | The role model reached 83.6% accuracy on unseen resumes. |

**Earlier work:** [Sleep stage classification of EEG signals](https://github.com/ghodkeadityarao/Sleep-Stage-Classification-of-EEG-Signals) (93.1% accuracy with an MLP) · [Object detection in dark images](https://github.com/ghodkeadityarao/Object-Detection-in-Dark-Images) (YOLOv8n with MIRNet, mAP50 0.702)

Each project's README lists its limits, such as small test sets and test questions I wrote myself. The free-tier sites sleep when unused, so the first visit can take a minute or two.

## Experience

- **Xometry**: Data Scientist Intern, Jun 2026 to Dec 2026
- **Texas A&M University, Department of Statistics**: Student Assistant (Data & AI), Jan 2026 to May 2026
- **Front Page**, **Scaler**, **Publicis Groupe**: Data Science Intern, 2023 to 2025

Details are on my [portfolio](https://ghodkeadityarao.github.io/aditya-rao-ghodke/).

## Tech

- **Languages:** Python, SQL, C++, Java, JavaScript, Bash
- **ML and data:** scikit-learn, XGBoost, SHAP, PyTorch, TensorFlow, pandas, NumPy, MLflow, dbt, BigQuery, PostgreSQL, MongoDB, A/B testing
- **LLMs and retrieval:** RAG, hybrid search, FAISS, LangChain, Gemini and Groq APIs, prompt engineering
- **Backend and tools:** FastAPI, Flask, Streamlit, Docker, AWS, Git
