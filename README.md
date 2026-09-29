# Joaquim Lagos

**Senior Backend Engineer** | Java & Kotlin • AWS • IA Aplicada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaquimlagos/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Joaquimlagos) [![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:joaquim.lagos2000@gmail.com)

---

### ⚡ Resumo

Engenheiro de Software Sênior na **NTT DATA**, atuando em projetos de grande escala no **Banco Itaú** (cartões PJ e Agro). Construo sistemas backend com Java, Kotlin e Spring Boot na AWS e, nos projetos pessoais, combino arquiteturas event-driven com **LLMs e RAG**.

### 🛠️ Tech Stack

- **Backend:** Java (11–21) | Kotlin | Python | Spring Boot | Microsserviços
- **Cloud & DevOps:** AWS (Lambda, Step Functions, EventBridge, SQS, DynamoDB, ECS, API Gateway) | Terraform | LocalStack | Docker | GitHub Actions
- **IA & LLMs:** RAG em nível de método (tree-sitter) | Roteamento e fallback entre modelos (Groq, Cerebras, Gemini) | Agents

### 🚀 Projetos em Destaque

**🤖 Pipeline de Code Review com IA** — revisão automática de PRs, 100% serverless

- **[codereview-lambda](https://github.com/Joaquimlagos/codereview-lambda)** — Roteia cada PR entre modelos conforme a complexidade, com fallback entre Groq, Cerebras e Gemini, RAG em nível de método sobre o código do projeto e comentários inline via GitHub App.
- **[codereview-infra](https://github.com/Joaquimlagos/codereview-infra)** — EventBridge, Step Functions, bucket S3, Secrets Manager e role OIDC do GitHub, tudo em Terraform.
- **[codereview-app](https://github.com/Joaquimlagos/codereview-app)** — Workflows do GitHub Actions autenticados via OIDC que disparam a revisão a cada PR e mantêm o índice RAG do código.

**🔍 Fraud Detector** — detecção de fraudes event-driven com IA explicável

- **[Fraud Detector API (Java/Spring)](https://github.com/Joaquimlagos/fraud-detector)** — Recebe transações, publica no SQS para análise assíncrona e consulta a análise detalhada.
- **[Fraud Detector Lambda (Python/IA)](https://github.com/Joaquimlagos/fraud-detector-lambda)** — Motor de regras de risco e análise via RAG + LLM que explica em linguagem natural por que uma transação é suspeita.
- **[Fraud Detector Infra (Terraform)](https://github.com/Joaquimlagos/fraud-detector-infra-aws)** — Provisionamento da infraestrutura AWS (SQS, DynamoDB, Lambdas).
