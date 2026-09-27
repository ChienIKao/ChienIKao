# 你好，我是高健壹　Chien-I Kao

[English](https://github.com/ChienIKao) · **繁體中文**

**國立中興大學 資訊工程學系 碩士生** · ICTALab<br>
**國家高速網路與計算中心（NCHC） LLM DevOps 實習生**<br>
國立臺中教育大學 資訊工程學系 學士 · GPA 3.9／4.3 · 系排名前 12%

我的經驗涵蓋 agent 開發與評測、AI 平臺部署、LLM 應用、機器學習研究，以及演算法研究與超級電腦叢集效能調校。

### 經歷

**國家高速網路與計算中心（NCHC）｜LLM DevOps 實習生**　2025.03–至今

- 以 LangGraph 開發附來源引用的搜尋問答 agent，在 SimpleQA Verified 抽樣 300 題評測中正確率 78.7%（原 Dify 流程 55.0%）。
- 在 Kubernetes 部署 OpenClaw agent 平臺並串接 Opik 追蹤；以 ClawBench 評估記憶功能，任務通過率由 0/30 提升至 30/30。
- 評估並實測 agentgateway 作為 LLM／MCP／A2A 流量閘道。
- 在 Kubernetes 部署 Onyx 知識問答平臺，以 Keycloak 整合 OIDC 單一登入，並建置 Prometheus、Grafana 監控與告警。
- 以 Dify、Langflow 研究 RAG 工作流程，成果供 TAIWAN AI RAP 網站的 AI 助手開發參考；並測試 MCP 工具整合。

**國立中興大學 ICTALab｜碩士班研究生**　2025.09–至今

- 參與淹水預警系統 MVP 開發，實作 RAG 與具來源依據（Grounding）的報告生成。
- 以 AutoEncoder 對民眾空間活動資料進行非監督式表徵學習。

### 研究著作

1. **Chien-I Kao** and Kuo-Chan Huang, *A New Logic-Rule-Based Method for Solving Nonograms*, **TCGA 2025** Workshop on Computer Games.（第一作者，最佳論文獎）· [程式碼](https://github.com/ChienIKao/nonogram-logic-rule-solver)
2. Yi-En Chang, Yu-Hsun Hung, Hsing-Yu Chen, **Chien-I Kao**, et al., *A Sustainable Online Learning Platform for After-Class Peer Learning*, **AACE eLearn 2024**, Singapore.

國科會大專學生研究計畫（`113-2813-C-142-002-E`，指導教授：黃國展）：比較 Nonogram 回溯階段的三種搜尋策略。

### 競賽與獲獎

- 2026｜第六屆航港大數據創意應用競賽（交通部航港局）學生組第一名
- 2026｜AI Everywhere Hackathon（AWS Summit Taipei）航運物流組第一名
- 2024、2025｜國網盃應用程式效能優化競賽（HiPAC）第三屆冠軍、第四屆季軍
- 2025｜興程式競賽 進階組銅獎
- 2024｜ICGA 電腦奧林匹亞 暗棋第四名；TCGA 電腦對局競賽 暗棋、Nonogram 第四名
- 2024｜PMI Region 9 專案管理案例競賽 決賽（臺灣代表隊，隊長）
- 2023｜ICPC 亞洲區桃園站 第 63／102 名；全國大專院校產學創新實作競賽 AI 組佳作
- 決賽：InnoServe（2025）、IMBD（2025）、NCPC（2023、2024）、ITSA（2023）
- 參賽：2026 AIWave 雲湧智生臺灣生成式 AI 應用黑客松（AWS Taiwan × DIGITIMES）

### 精選專案

| 專案 | 說明 |
| --- | --- |
| [hullwatch](https://github.com/ChienIKao/hullwatch) | 船體髒污能效監控：Speed Loss 偵測、清洗 ROI 分析與 Amazon Bedrock AI 顧問 · FastAPI · React · XGBoost |
| [imarine-policy-rag](https://github.com/ChienIKao/imarine-policy-rag) | 航港政策問答與報告生成，回答附上檢索來源 · Python · PostgreSQL + pgvector · RAG |
| [aiwave-community-platform](https://github.com/ChienIKao/aiwave-community-platform) | 社區生活服務平臺：共用交易核心、點數帳本與 Partner OpenAPI，單人開發 · Python · React |
| [nonogram-logic-rule-solver](https://github.com/ChienIKao/nonogram-logic-rule-solver) | 以邏輯規則推導，在回溯前填定格子並偵測矛盾 · C++ |
| [dark-chess-mcts](https://github.com/ChienIKao/dark-chess-mcts) | 暗棋對局引擎，平行 MCTS（UCT + OpenMP） · C++ |
| [quizzz](https://github.com/ChienIKao/quizzz) | 多科目測驗練習平臺，支援 LaTeX · [線上展示](https://quizzz-cbu7ev2vvpwtdxdupqztta.streamlit.app/) · Streamlit |

---

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

📫 **alen911018@gmail.com** · [Blog](https://chienikao.github.io/) · [LinkedIn](https://www.linkedin.com/in/chien-i-kao)
