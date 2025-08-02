# CentralizAI
Agente de IA que centraliza informações de incidentes, mudanças e atualizações da empresa, integrando os principais canais de comunicação e incidentes, visando a melhora da comunicação interna e a tomada de decisão.
# 🧠 Projeto: Agente de Inteligência Artificial para Comunicação Interna Centralizada

---

## 📌 Visão Geral

Este projeto visa desenvolver um **Agente de Inteligência Artificial (IA)** com capacidade de atuar como um **chatbot no Microsoft Teams**, centralizando informações críticas de operação (incidentes, mudanças e atualizações). O agente irá interagir com os solucionadores técnicos, fornecendo dados em tempo real, organizados e integrados a partir de múltiplas fontes corporativas.

---

## 🎯 Objetivo

- Centralizar a comunicação operacional via Teams
- Automatizar o acesso a dados críticos
- Reduzir o tempo de resposta e escalonamento
- Promover eficiência, rastreabilidade e agilidade na gestão de crises

---

## 📦 Escopo do Projeto

### ✅ Escopo Incluído
- Criação de um chatbot em Python
- Integração com o Microsoft Teams (Bot Framework)
- Consulta a bases de dados e APIs externas
- Interpretação de comandos em linguagem natural
- Respostas em tempo real com informações operacionais

### ❌ Fora do Escopo
- Execução automática de scripts em sistemas externos
- Interface gráfica externa ao Teams
- Suporte multilíngue (foco inicial em português)

---

## 🛠️ Tecnologias e Ferramentas

| Item                      | Tecnologia / Plataforma         |
|---------------------------|---------------------------------|
| Linguagem                 | Python 3.10+                    |
| Backend                   | FastAPI                         |
| IA/NLP                    | spaCy, Langchain, Transformers |
| Banco de Dados            | PostgreSQL / MongoDB           |
| Integração com Chat       | Microsoft Teams via Bot Framework |
| APIs Corporativas         | Microsoft Graph, ServiceNow, Zabbix |

---

## 🔌 Integrações Previstas

| Sistema Integrado         | Tipo                           | Objetivo                      |
|---------------------------|--------------------------------|-------------------------------|
| ServiceNow                | API REST                       | Consulta de incidentes e mudanças |
| Zabbix / Prometheus       | API REST ou Webhook            | Monitoramento em tempo real   |
| Banco de Dados interno    | SQL / NoSQL                    | Consulta e histórico          |
| Microsoft Graph API       | API REST                       | Gerenciamento de Teams e canais |

---

## 🤖 Funcionamento do Chatbot

### 🗣️ Comando do Usuário:
> “Quais os incidentes críticos abertos hoje?”

### 💬 Resposta esperada:
🛑 INC009999 - Falha no serviço de login
⏰ Início: 09h12 | Equipe: G1 | Status: Em tratamento
🔁 Última atualização: 10h50


---

## 🔁 Fluxo de Funcionamento

Usuário → Teams → Chatbot (Bot Framework)
→ Interpretação da mensagem (NLP/IA)
→ Consulta às fontes de dados
→ Resposta estruturada no chat


---

## ✅ Requisitos

### Requisitos Funcionais
- RF01: Disponibilidade do bot no Teams 24x7
- RF02: Entendimento de linguagem natural
- RF03: Consulta a dados de incidentes em tempo real
- RF04: Envio automático de alertas operacionais

### Requisitos Não Funcionais
- RNF01: Tempo de resposta < 3s
- RNF02: Alta disponibilidade (mínimo 99,5%)
- RNF03: Criptografia de dados em trânsito e repouso
- RNF04: Conformidade com LGPD

---

## 🔐 Segurança

- Autenticação via Azure AD
- Controle de acesso por perfil de usuário
- Armazenamento seguro com criptografia
- Logs auditáveis e segregação por função

---

## 📅 Cronograma

| Etapa                         | Duração Estimada |
|------------------------------|------------------|
| Levantamento de Requisitos   | 1 semana         |
| Desenvolvimento do Backend   | 2 semanas        |
| Integração com Sistemas      | 2 semanas        |
| Criação do Bot no Teams      | 1 semana         |
| Treinamento de IA/NLP        | 1 semana         |
| Testes e Ajustes             | 1 semana         |
| Go-live                      | (a definir)      |

---

## 📊 Indicadores de Sucesso

- N° de comandos processados por mês
- % de solucionadores usando o bot semanalmente
- Tempo médio de resposta a incidentes
- Redução no tempo de escalonamento
- Feedback positivo via enquete

---

## 🔧 Suporte e Manutenção

- Time Responsável: [Nome do time ou Squad]
- Canal de suporte: [Link do canal no Teams]
- Atualizações: Ciclos quinzenais
- Sugestões e bugs: [Formulário interno ou backlog]

---

## 📌 Próximos Passos

- [ ] Validar escopo com stakeholders
- [ ] Detalhar integrações técnicas
- [ ] Criar MVP funcional com perguntas básicas
- [ ] Definir modelo de machine learning/NLP
- [ ] Conectar à base do ServiceNow
- [ ] Realizar testes com grupo piloto

---
