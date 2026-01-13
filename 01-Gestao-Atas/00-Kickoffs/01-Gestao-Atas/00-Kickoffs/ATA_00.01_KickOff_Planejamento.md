# Ata 00.01 – Planejamento e Alinhamento de Projeto (CNPJ/QA)

**Data:** 13/01/2026 (Estimada)
**Participantes:** Marco Aurélio Neves, Luiz Muller Coromi Velasco, Silvio Filho, Mauricio Cordeiro Lyrio Monteiro, Rafael Feltrim.
**Stakeholders Citados:** Fabi, Bruno (PM Equifax), Grace Mendes (QA Equifax), Matheus, Jonas Oliani (SRE), Marcuni (Forceis).

## 1. Tópicos Principais

* **Validação de Produtos:** Necessidade de confirmar levantamentos com a área de produtos e PM da Equifax.
* **Automação e Execução:** Uso de IA para varredura de código e criação automática de ~10.000 cards no Jira.
* **Estratégia de QA:** Definição do uso do Zephyr, automação de evidências e inexistência de repositório regressivo centralizado.
* **Gestão de Ambientes:** Mitigação de riscos em ambientes compartilhados via "congelamentos" pontuais.
* **Cronograma:** Definição de metas para homologação (Abril) e Go-Live (Julho).

## 2. Discussões e Acordos

* **Metodologia (Kanban):** O projeto seguirá o modelo Kanban com reuniões diárias (*dailies*). O trabalho será organizado em metas semanais baseadas na quantificação total da IA.
* **Status do Fluxo (WIP):**
    * **Bloqueio:** Acesso ao portal transacional e definições finais com PM Bruno.
    * **A Fazer:** IA rodar hoje para gerar extrato de quantificação amanhã.
* **Definições Técnicas de QA:**
    * Uso do **Zephyr** vinculado ao Jira.
    * Foco em testes que consomem CNPJ (>3.000 cenários identificados).
    * Decisão de integrar evidências de automação (Robot/Outros) diretamente no ZOC/Jira para evitar evidência manual.
* **Infraestrutura e Riscos:**
    * **Risco Crítico:** Instabilidade em ambientes compartilhados.
    * **Decisão:** Não haverá ambiente segregado (custo). Controle será via comunicação e blocos semanais de congelamento.

## 3. Plano de Ação

| ID | Ação / Tarefa | Responsável | Prazo / Status |
| :--- | :--- | :--- | :--- |
| **01** | Agendar reunião com PM (Bruno), Fabi e Grace Mendes para validar levantamentos. | Marco Aurélio Neves | Amanhã cedo |
| **02** | Executar IA para mapeamento do repositório e gerar extrato de quantificação. | Marco Aurélio Neves / Time | Rodar hoje (extrato amanhã) |
| **03** | Adicionar Grace Mendes (Líder QA Equifax) à reunião de alinhamento. | Luiz Muller / Marco Aurélio | Imediato |
| **04** | Discutir acessos ao portal transacional (legados) com PM Bruno. | Marco Aurélio Neves | Reunião de amanhã |
| **05** | Publicar resumo/relatório desta reunião. | Rafael Feltrim | Concluído |

---