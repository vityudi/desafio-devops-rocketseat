# 📌 Desafio: Implementação de Práticas DevOps na Tech

## ✅ 1. Diagnóstico Cultural (C de CALMS)

### 🔍 Processo Identificado: Entrega de Código e Deploy

**Descrição do Processo Atual:**
- O desenvolvedor finaliza o código, cria um pacote de implantação e envia para a equipe de operações.
- A equipe de operações faz o deploy manualmente, sem scripts ou pipelines padronizados.
- Os testes pós-deploy são manuais, feitos pela própria equipe de operações.
- O monitoramento é reativo: logs são inspecionados manualmente após o deploy.

**Pontos de Atrito:**
- **Silos:** Dev entrega, Ops executa, pouca colaboração.
- **Retrabalho:** 20% dos deploys falham, gerando retrabalho e incidentes.
- **Demora:** Até 2 dias entre o fim do desenvolvimento e o deploy.
- **Desmotivação:** Tarefas manuais e repetitivas frustram as equipes.

**Oportunidades de Melhoria:**
- Estabelecer pipelines de CI/CD.
- Automatizar deploys para garantir repetibilidade.
- Integrar testes automatizados.
- Fomentar colaboração entre Dev e Ops.

---

## ✅ 2. Automação (A de CALMS)

### ⚙️ Solução de Automação Proposta

**Pipeline de CI/CD:**
1. **Build automática:** Geração de pacotes após cada commit.
2. **Testes automatizados:** Unitários e de integração.
3. **Deploy automatizado:** Scripts de Infra como Código + CI/CD.
4. **Rollback automático:** Reversão imediata em caso de falha.

### 🗂️ Plano de Implementação
- **Ferramentas:** GitLabCI, Ansible/Terraform, Docker.
- **Padrões:** Templates versionados de pipeline.
- **Capacitação:** Treinamentos Dev e Ops.
- **Governança:** Definir responsáveis pelo pipeline.
- **Piloto:** Iniciar pela plataforma de E-commerce.

---

## ✅ 3. Mensuração (M) e Compartilhamento (S)

### 📊 Métricas de Sucesso
- **Tempo de deploy:** Reduzir de 2 dias para 1 hora.
- **Taxa de sucesso dos deploys:** Aumentar de 80% para 98%.
- **Número de incidentes:** Reduzir de 2 por semana para 1 por mês.
- **MTTR:** Diminuir de 4 horas para 1 hora.

### 📚 Plano de Compartilhamento
- **Documentação viva:** Wiki interna com scripts, pipelines e boas práticas.
- **Reuniões DevOps:** Retrospectivas mensais de melhorias.
- **Guildas técnicas:** Grupos para temas como IaC, testes, observabilidade.
- **Mentoria interna:** Disseminar conhecimento entre projetos e sistemas legados.

---

## ✅ 4. Três Maneiras

### 🚀 Primeira Maneira: Acelerar o Fluxo
- Automatizar build, testes e deploy.
- Eliminar etapas manuais.
- Garantir deploys frequentes e pequenos.

### 🔁 Segunda Maneira: Ampliar o Feedback
- Pipelines com verificação de qualidade automática.
- Relatórios de build em Slack/Teams.
- Monitoramento proativo (Prometheus, Grafana).
- Reuniões quinzenais para análise de falhas.

### 🧪 Terceira Maneira: Experimentar e Aprender
- Ambientes sandbox para experimentos.
- Provas de conceito para novas ferramentas.
- Reconhecer tentativas e aprendizados (mesmo com falhas).
- Workshops de melhoria contínua.

---

## 🎯 Resumo Final

| Área               | Ação |
|--------------------|------|
| **Cultura**        | Diminuir silos, fomentar colaboração Dev + Ops |
| **Automação**      | Pipeline CI/CD, testes, deploy automatizado, rollback |
| **Mensuração**     | KPIs claros: tempo de deploy, taxa de sucesso, incidentes, MTTR |
| **Compartilhamento** | Wiki, guildas, reuniões de aprendizado contínuo |
| **Primeira Maneira** | Acelerar entregas com deploy frequente e confiável |
| **Segunda Maneira** | Ampliar feedback com monitoramento e alertas |
| **Terceira Maneira** | Experimentação segura e melhoria contínua |

---
