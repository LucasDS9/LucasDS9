<div align="center">
  <img height="200" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/lucas-vinicius-a4054b2a9/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
  <a href="https://LucasDS9.github.io" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Portfolio&logo=github&label=&color=534AB7&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="portfolio"  />
  </a>
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=LucasDS9.LucasDS9&"  />
</div>

###

<h1 align="center">Olá 👋</h1>

###

<h3 align="left">🔍 Sobre mim</h3>

###

<p align="left">Sou estudante de Física na UFPE, movido pela curiosidade de entender padrões, resolver problemas complexos e explorar ideias profundas. Atualmente desenvolvo projetos práticos em machine learning e ciência de dados, abrangendo desde análise exploratória de dados e modelagem estatística até avaliação e deploy de modelos, sempre com o objetivo de transformar dados em insights claros e soluções aplicáveis. Tenho facilidade em aprender novos conceitos, conectar teoria e implementação, e estruturar soluções de forma objetiva.<br><br>

Tenho interesse especial em sistemas reais de **ML**, **NLP** e aplicações com **LLMs**, buscando construir soluções completas, reprodutíveis e próximas do ambiente de produção. Atualmente estudando **agentes de IA**, **MCP** e integrando **PostgreSQL** nos projetos.</p>

---

### 🎓 Educação : 

- **Física (Bacharelado)** — UFPE (em andamento)
- **Intercâmbio nos EUA** — Programa PGM (2020)

---

### 🎯 Habilidades

🧠 **Machine Learning**
Classificação, regressão, clusterização e otimização · Modelos supervisionados e não supervisionados · Limpeza e pré-processamento de dados, engenharia e seleção de features · Tuning de hiperparâmetros, validação cruzada e avaliação de modelos · Métricas estatísticas e interpretação de resultados

🗣️ **NLP & LLMs**
Processamento de linguagem natural (tokenização, embeddings, vetorização) · Uso de LLMs para análise de texto, classificação, sumarização e geração de conteúdo · Arquiteturas RAG com bancos vetoriais · Prompt engineering e avaliação de respostas · Agentes de IA e MCP

🎲 **SQL & Dados**
Consultas SQL para extração e manipulação de dados · Joins, agregações e subqueries · Análise exploratória de dados · Integração com PostgreSQL em projetos de ML

🌎 **Idiomas**
Inglês intermediário-avançado (comunicação, leitura técnica, documentação, escrita, compreensão)

🤝 **Outras Habilidades**
Pensamento analítico · Facilidade em conectar teoria e prática · Aprendizado rápido · Organização e estruturação de projetos · Comunicação clara de resultados técnicos

---

## 🚀 Projetos em Destaque

### 📄 Sistema RAG Q&A (PT) — Mini RAG PRO
Sistema completo de Retrieval-Augmented Generation para perguntas e respostas sobre documentos PDF, com avaliação quantitativa via métricas de IR e LLM-as-Judge.

- Pipeline RAG completo: ingestão, chunking adaptativo, embeddings, ChromaDB, re-ranking e geração
- Comparação de estratégias de chunking (chunk_size, overlap, semântico, por sentença)
- Avaliação com Precision@K, Recall@K, F1@K, NDCG@K, MRR, BLEU e ROUGE
- LLM-as-Judge com Qwen 0.5B para avaliação automática de relevância e coerência
- Interface Gradio com deploy no Hugging Face Spaces

🔗 [Ver repositório](https://github.com/LucasDS9/MiniRAG-pt) · 🚀 [Testar o modelo](https://huggingface.co/spaces/LucasDS9/MiniRAG-PT)

---

### 🛒 Análise de Produtos Amazon — NLP Pipeline
Pipeline completo de NLP sobre o Amazon Fine Foods dataset para extrair insights estruturados de reviews de clientes, combinando técnicas clássicas com LLMs.

- Limpeza textual e feature engineering com spaCy
- Vetorização via TF-IDF e Word2Vec
- Agregação de sentimento por produto com métricas estruturadas
- Geração de insights executivos com Qwen 0.5B e prompt engineering
- Interface interativa com deploy no Hugging Face Spaces

🔗 [Ver repositório](https://github.com/LucasDS9/nlp-product-review-analysis) · 🚀 [Testar o modelo](https://huggingface.co/spaces/LucasDS9/nlp-product-review-analysis)

---

### 📉 Classificador de Churn Bancário
Modelo supervisionado para previsão de evasão de clientes com pipeline robusto, rastreamento de experimentos com MLflow e threshold customizado para maximizar recall.

- EDA completa com insights sobre perfil de churn
- Pipeline sklearn com SMOTE para balanceamento de classes
- Três modelos avaliados (Logistic Regression, Random Forest, Gradient Boosting) rastreados com MLflow
- ROC-AUC de 99.66% · Accuracy de 98.20% · Threshold customizado de 0.35
- Deploy via Streamlit no Render

🔗 [Ver repositório](https://github.com/LucasDS9/Customer-churn-project-) · 🚀 [Testar o modelo](https://customer-churn-project-d7xs.onrender.com/app) · 📓 [Ver notebook](https://github.com/LucasDS9/Customer-churn-project-/blob/main/notebook/Customer_churn.ipynb)

---

### 💳 Loan Approval — Classificação e Regressão de Crédito
Solução end-to-end para aprovação de empréstimos bancários combinando classificação binária com regressão para estimativa de taxa de juros personalizada.

- EDA aprofundada com insights sobre fatores de aprovação de crédito
- Classificação com RandomForestClassifier: 98% de acurácia
- Regressão para taxa de juros: R² de 0.9977 e MAE de 0.0776
- Regras de negócio customizadas e análise de lucratividade
- Deploy via Streamlit no Render

🔗 [Ver repositório](https://github.com/LucasDS9/Loan_approval-project) · 🚀 [Testar o modelo](https://loan-approval-project-yyfi.onrender.com) · 📓 [Ver notebook](https://github.com/LucasDS9/Loan_approval-project/blob/main/notebooks/loan_full_project.ipynb)

---

### 📊 RFM Segmentation — Clusterização com K-Means
Segmentação de clientes de e-commerce baseada na metodologia RFM (Recência, Frequência e Valor Monetário) com clustering não supervisionado.

- Construção de métricas RFM e análise exploratória orientada a negócio
- Redução de dimensionalidade com PCA (2D e 3D)
- Clusterização com K-Means: segmentos VIP (~8%), Regulares (~67%) e Inativos (~25%)
- Tratamento de outliers via Winsorize para estabilidade da modelagem
- Insights e estratégias de retenção, fidelização e reativação por segmento

🔗 [Ver repositório](https://github.com/LucasDS9/customer-segmentation-rfm)
