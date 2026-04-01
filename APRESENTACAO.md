# 🛡️ AegisLLM — Apresentação
### Inovação, Sustentabilidade e Competitividade Empresarial

---

## 1. O Problema

O uso corporativo de IA generativa (LLMs) cresce de forma descontrolada:

- 💸 **Custos invisíveis** — equipes consomem tokens sem limite ou visibilidade
- 🔓 **Vazamento de dados sensíveis** — CPF, e-mails e cartões enviados direto para APIs externas
- ♻️ **Desperdício computacional** — mesmas perguntas enviadas repetidamente, gerando processamento desnecessário em data centers
- ⚖️ **Falta de governança** — sem rastreabilidade de quem usou, quanto custou ou o que foi enviado

---

## 2. A Solução — AegisLLM

> Um **middleware inteligente** posicionado entre o usuário corporativo e o LLM, atuando como um guardião de privacidade, custos e governança.

```
Usuário → [AegisLLM] → API do LLM (Gemini)
              ↑
   tokeniza PII | verifica orçamento | cache semântico | auditoria
```

### Funcionalidades principais

| Funcionalidade | O que faz |
|---|---|
| 🔐 **Data Vault** | Substitui dados sensíveis (CPF, e-mail, cartão) por tokens antes de enviar à API; detokeniza a resposta em tempo real |
| 💰 **FinOps Dashboard** | Shadow billing + travas de orçamento diário por usuário e por time |
| ⚡ **Semantic Cache** | Hash criptográfico do prompt — requisições repetidas custam **zero** |
| 📋 **Trilha de Auditoria** | Log completo de eventos, incluindo tentativas de vazamento de PII |

---

## 3. Conexão com Sustentabilidade 🌱

O AegisLLM se alinha diretamente aos **3 pilares ESG**:

### 🌍 E — Ambiental
- Cada chamada evitada pelo **cache semântico** = menos processamento em data centers
- Data centers respondem por ~1–1,5% do consumo elétrico global — reduzir requisições desnecessárias reduz emissão de CO₂
- **Menos tokens = menos energia = menor pegada de carbono da IA corporativa**

### 🤝 S — Social
- Protege dados pessoais de clientes e colaboradores (LGPD / GDPR)
- Democratiza a governança de IA — mesmo empresas menores conseguem controlar uso e custos

### 🏛️ G — Governança
- Rastreabilidade total de quem usa IA, quanto gasta e o que envia
- Relatórios de compliance prontos para auditorias
- Travas preemptivas evitam surpresas na fatura

---

## 4. Business Model Canvas

| Bloco | Conteúdo |
|---|---|
| **Parcerias Chave** | Google Gemini API, cloud providers (GCP/AWS/Azure), equipes de TI/Compliance, ANPD |
| **Atividades Chave** | Tokenização de PII, gestão de orçamento de tokens, cache semântico, auditoria de segurança |
| **Proposta de Valor** | Privacidade by design + controle de gastos + menor pegada de carbono + governança de IA |
| **Relacionamento** | SaaS self-service, alertas proativos, relatórios de consumo e economia |
| **Segmento de Clientes** | Empresas com LLMs corporativos, setores regulados (saúde, financeiro, jurídico), gestores de TI/ESG |
| **Recursos Chave** | Middleware Python, algoritmo PBKDF2-HMAC-SHA256, engine de cache, know-how FinOps |
| **Canais** | GitHub open-source, interface Streamlit, marketplace cloud, eventos de tecnologia |
| **Estrutura de Custos** | API por token (reduzida pelo cache), infra cloud, desenvolvimento, certificações |
| **Fontes de Receita** | Assinatura SaaS mensal, freemium → pago, licenciamento, consultoria FinOps de IA |

---

## 5. Stack Tecnológica

- **Linguagem:** Python 3.x
- **Interface:** Streamlit
- **LLM integrado:** Google Gemini 2.5 Flash API
- **Segurança:** PBKDF2 HMAC com SHA-256 + Regex para detecção de PII
- **Arquitetura:** Middleware (proxy inteligente)

---

## 6. Diferenciais Competitivos

- ✅ **Open-source** — baixa barreira de entrada, alta confiança
- ✅ **Agnóstico ao LLM** — funciona com qualquer API (Gemini, OpenAI, etc.)
- ✅ **Sem vendor lock-in**
- ✅ **Conformidade LGPD nativa** — PII nunca sai da empresa
- ✅ **ROI imediato** — economia de 40–70% em chamadas duplicadas eliminadas pelo cache

---

## 7. Público-Alvo

- Times de TI e DevOps adotando IA generativa
- Gestores financeiros preocupados com OPEX de IA
- Departamentos jurídicos e de compliance
- Empresas em setores regulados (saúde, financeiro, jurídico)
- Startups de IA que precisam controlar custos de API

---

## 8. Próximos Passos (Roadmap)

1. 🔌 Suporte a múltiplos LLMs (OpenAI, Anthropic, Mistral)
2. 📊 Dashboard de impacto de carbono evitado (relatório ESG automatizado)
3. 🏢 Deploy em Kubernetes para escala corporativa
4. 🔔 Integração com Slack/Teams para alertas de orçamento em tempo real
5. 📜 Certificação de conformidade LGPD/GDPR emitida pelo sistema

---

## Repositório

🔗 [github.com/EduTNV/AegisLLM](https://github.com/EduTNV/AegisLLM)

---

*Apresentação preparada para a disciplina de Inovação, Sustentabilidade e Competitividade Empresarial — 2026*
