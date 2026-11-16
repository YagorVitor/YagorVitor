# Yagor Santos

**Software Engineer | Backend Systems, Cloud Infrastructure & Applied AI**

At InoviaCorp, I build and maintain the backend for SeeVer, a computer vision SaaS. My work includes integrating Amazon SageMaker inference into the NestJS API, implementing seat-based subscription billing with Stripe and DynamoDB, and investigating production issues. I am also leading the migration from AWS App Runner to Amazon ECS.

Araraquara, Brazil (UTC−3) · [LinkedIn](https://www.linkedin.com/in/yagor-santos-21b3122b5/)

## Selected projects

### CompletAI · SEMCOMP × iFood Hackathon

My team built a grocery assistant that turns food photos, user preferences, and meal requests into recommendations and an iFood Mercado cart.

I developed the AI agents with the OpenAI Agents SDK, the computer vision workflow for identifying ingredients in photos, and the FastAPI backend that connects image recognition, meal recommendations, product search, and cart creation.

Users review the recognized ingredients before proceeding. Search is the only iFood MCP operation exposed to the agent. The backend validates the proposed cart, then creates and verifies it after explicit user confirmation. The prototype ends at the verified cart.

[Repository](https://github.com/YagorVitor/Hackathon-Ifood) · [Screenshots and user flow](https://github.com/YagorVitor/Hackathon-Ifood/blob/main/docs/entregaveis/04-interface-visual.md) · [Agent implementation](https://github.com/YagorVitor/Hackathon-Ifood/blob/main/backend/app/agent.py) · [Cart tests](https://github.com/YagorVitor/Hackathon-Ifood/blob/main/backend/tests/test_cart.py)

### ÉcoDados · 1st place at ClimatonBrasil 2026

Our team won first place among 15 teams at the hackathon organized by Brazil’s Federal Court of Accounts (TCU). We built a WebGIS platform to help public managers prioritize climate issues and develop action plans.

I worked on the FastAPI backend, MongoDB data model, and OpenAI Responses API integration. The model suggests assessment criteria and drafts action plans. The backend validates structured outputs and computes rankings using deterministic rules.

I presented the benchmarking workflow at the **ClimateScanner Summit 2026** in Rio de Janeiro, explaining how public managers could learn from completed projects in other jurisdictions.

[Repository](https://github.com/YagorVitor/Climaton-2026) · [TCU coverage of the winning project](https://portal.tcu.gov.br/imprensa/noticias/ecodados-vence-climatonbrasil-2026-com-aplicacao-voltada-a-gestao-publica) · [Official Summit announcement](https://portal.tcu.gov.br/imprensa/noticias/encontro-internacional-discute-fiscalizacao-da-acao-climatica)

## Research

At IFSP, I conduct applied machine-learning research using RGB and multispectral drone imagery to study soil conditions and crop nutrition in smallholder agriculture, with a focus on coffee crops.

## Other projects

### Sentry AI

I co-developed a contract analysis platform that uses retrieval-augmented generation (RAG) to extract clauses and identify risks. My contributions include the Flask backend, authentication, and defenses against prompt injection.

### IF-Arbitra

I co-developed a group allocation platform using FastAPI and PostgreSQL. The backend enforces enrollment rules during concurrent registrations, computes allocations deterministically, and records decisions for audit.

[Repository](https://github.com/YagorVitor/IF-Arbitra) · [Backend documentation](https://github.com/YagorVitor/IF-Arbitra/blob/main/backend/README.md)
