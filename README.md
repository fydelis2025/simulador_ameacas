# 🛡️ FydelGuard — Simulador de Análise Comportamental de Ransomware
## Módulo de Análise Forense e Resposta a Incidentes

**Versão 2.5-PRO • Build 2026.09**  
Adiel Santos Fontes • Salvador — Bahia 🇧🇷

*"O conhecimento técnico avançado existe para PROTEGER, construir sistemas resilientes e garantir a soberania digital."*

---

## ⚠️ AVISO LEGAL E ÉTICO

Este repositório contém um **simulador estritamente conceitual e educacional**, desenvolvido para fins de **auditoria defensiva, simulação de TTPs (MITRE ATT&CK) e conscientização em cibersegurança**.

- ❌ **NÃO** executa nenhuma ação real no sistema
- ❌ **NÃO** criptografa, não modifica e não apaga arquivos
- ❌ **NÃO** se comunica com servidores externos
- ✅ Todo o conteúdo é **simulação em ambiente isolado**
- ✅ O conhecimento aqui apresentado **existe para proteger, não para atacar**

---

## 💻 SOBRE O PROJETO

O **FydelGuard** é um simulador educacional escrito em **Portugol** — a linguagem de programação em português — que reproduz de forma didática e segura o ciclo de vida de um ataque de ransomware, desde a enumeração de alvos até a comunicação com servidores de Comando & Controle, e principalmente **apresenta as contramedidas eficazes de defesa**.

### 🎯 Objetivos
- 📚 Ensinar como ameaças reais operam (TTPs — Táticas, Técnicas e Procedimentos)
- 🛡️ Demonstrar protocolos de mitigação e defesa ativa
- 🔬 Familiarizar com terminologia de segurança corporativa (EDR, SIEM, MITRE ATT&CK)
- 🇧🇷 Promover a programação e a segurança digital **na nossa língua**
- 🌍 Garantir cultura de segurança e soberania tecnológica

---

## 🔬 FLUXO DE SIMULAÇÃO — 4 FASES

| Fase | Descrição | Referência MITRE |
|---|---|---|
| **🔍 Fase 1** | Enumeração de sistema de arquivos — varredura e classificação de ativos por criticidade | T1083 |
| **🔒 Fase 2** | Simulação de cifragem híbrida — AES-256 + RSA-2048, encapsulamento de dados | T1486 |
| **🌐 Fase 3** | Telemetria e beacons de rede — comunicação C2, exfiltração e túneis | T1071 |
| **🛡️ Fase 4** | Matriz de mitigação — protocolos de resposta, backup 3-2-1, segmentação, EDR | Defesa Ativa |

---

## 📊 ESTRUTURA DE ALVOS SIMULADOS

| Categoria | Extensões | Criticidade |
|---|---|---|
| Documentos Corporativos | .docx / .pdf / .xlsx | CRÍTICO |
| Fontes de Sistema / Baixo Nível | .cpp / .h / .pro / .asm | ALTO |
| Bancos de Dados Transacionais | .db / .sql / .sqlite | MÁXIMO |
| Mídia e Ativos Gráficos | .jpg / .png / .mp4 | MÉDIO |

### 📡 Dados de Inteligência de Ameaças (Simulados)
- **Servidores C2:** IPs e portas de infraestrutura de Comando & Controle
- **Hashes SHA-256:** Assinaturas de amostras conhecidas (Conficker.B, WannaCry.Mod)
- **Algoritmos:** AES-256-CBC (simétrica) + RSA-2048 (assimétrica)

---

## 🛡️ PROTOCOLOS DE MITIGAÇÃO — DEFESA EFETIVA

Estas são as contramedidas comprovadas contra ransomware:

| # | Medida | Impacto |
|---|---|---|
| ✅ 1 | **Backup 3-2-1** — 3 cópias, 2 mídias, 1 offline/imutável | ALTO |
| ✅ 2 | **Segmentação de rede** — políticas restritivas no firewall | ALTO |
| ✅ 3 | **Patches críticos** — SMBv1/EternalBlue e outras vulnerabilidades | CRÍTICO |
| ✅ 4 | **Solução EDR/XDR** — detecção comportamental em endpoints | ALTO |
| ✅ 5 | **Princípio do privilégio mínimo** — limitação de permissões | ALTO |

---

## 🖥️ COMO EXECUTAR

### Pré-requisitos
- **Portugol Studio** ou **Webstudio Portugol** — ambiente gratuito e multiplataforma

### Passo a Passo
1. Clone ou baixe este repositório
2. Abra o arquivo `simulador_ameacas.portugol` no Portugol Studio / Webstudio
3. Clique em **Executar ▶️**
4. Leia cada etapa com atenção e aplique as recomendações de proteção!
