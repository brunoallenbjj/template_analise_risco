# 📊 Template – Análise de Riscos de Segurança da Informação (ISO/IEC 27005)

Este documento contém a estrutura básica para registrar, avaliar e tratar riscos relacionados à Segurança da Informação, conforme diretrizes da norma ISO/IEC 27005:2018.

---

## 🛠️ Tabela de Análise de Riscos

| ID | Ativo de Informação | Proprietário do Ativo | Ameaça | Vulnerabilidade | Descrição do Risco | Probabilidade | Impacto | Nível de Risco | Controles Existentes | Avaliação do Controle | Decisão de Tratamento | Ação de Tratamento | Responsável | Prazo | Status |
|----|---------------------|------------------------|--------|------------------|---------------------|---------------|---------|----------------|-----------------------|------------------------|------------------------|--------------------|-------------|-------|--------|
| 1  | Banco de dados ERP  | TI                     | Ataque de ransomware | Falta de backup offline | Perda de dados críticos e paralisação do sistema | Alta | Alta | Crítico | Backup diário em nuvem | Parcialmente eficaz | Mitigar | Implementar backup offline semanal | TI Segurança | 15/09/2025 | Em andamento |
| 2  | Planilhas de RH     | RH                     | Vazamento interno | Compartilhamento por e-mail | Vazamento de dados pessoais de funcionários | Média | Alta | Alto | Acesso por senha | Pouco eficaz | Mitigar | Migrar para repositório com controle de acesso | RH + TI | 01/09/2025 | Pendente |
| 3  | Sistema de e-mails  | TI                     | Phishing | Falta de conscientização | Comprometimento de credenciais e acesso indevido | Alta | Média | Alto | Antivírus, firewall | Moderadamente eficaz | Mitigar | Treinamento de segurança da informação | TI + Comunicação | 31/08/2025 | Planejado |

---

## 📘 Descrição dos Campos

| Campo | Descrição |
|-------|-----------|
| **ID** | Número identificador do risco |
| **Ativo de Informação** | Item com valor que requer proteção (ex: sistema, dado, infraestrutura) |
| **Proprietário do Ativo** | Pessoa ou área responsável pela governança do ativo |
| **Ameaça** | Evento ou agente que pode explorar uma vulnerabilidade |
| **Vulnerabilidade** | Fragilidade no ativo que pode ser explorada |
| **Descrição do Risco** | Consequência caso a ameaça explore a vulnerabilidade |
| **Probabilidade** | Classificação da chance de ocorrência (Baixa, Média, Alta) |
| **Impacto** | Consequência da materialização do risco (Baixo, Médio, Alto) |
| **Nível de Risco** | Resultado da análise (ex: Crítico, Alto, Médio, Baixo) |
| **Controles Existentes** | Controles já implementados que tratam ou mitigam o risco |
| **Avaliação do Controle** | Grau de eficácia dos controles (eficaz, parcial, ineficaz) |
| **Decisão de Tratamento** | Mitigar, Aceitar, Transferir ou Evitar o risco |
| **Ação de Tratamento** | Medida proposta para tratar o risco |
| **Responsável** | Pessoa ou área encarregada pela ação |
| **Prazo** | Data limite para a execução da ação |
| **Status** | Situação atual da ação (Planejado, Em andamento, Concluído, etc.) |

---

## 📌 Observações Finais

- A análise deve ser revisada periodicamente ou sempre que houver mudanças significativas no ambiente.
- Recomenda-se o uso de uma **matriz de risco (Impacto x Probabilidade)** como apoio visual.
- Os riscos relacionados à **privacidade e proteção de dados pessoais (LGPD)** devem ser destacados.

---

*Documento baseado na norma ISO/IEC 27005:2018 – Gestão de Riscos em Segurança da Informação.*
