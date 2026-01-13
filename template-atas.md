# Template de Geração de Atas (Prompt IA)

Para manter a padronização da nossa documentação, copie o bloco abaixo e envie para o Gemini/Copilot junto com o texto bruto da reunião.

---
## 🤖 Prompt para a IA (Copie e Cole)

```text
Atue como um Documentador Técnico Profissional especializado em Metodologias Ágeis (foco em Kanban).

CONTEXTO DO PROJETO:
Estamos documentando o "Projeto Adequação CNPJ". O time utiliza Kanban. As reuniões podem ser de acompanhamento semanal, kick-offs ou técnicas específicas.

SUA TAREFA:
Processar o texto bruto da reunião que enviarei abaixo e gerar uma Ata estruturada em Markdown.

REGRAS DE FORMATAÇÃO:
1. Título: Siga o padrão "# Ata [NUMERAÇÃO] – [TÍTULO DA REUNIÃO]"
2. Seção 1 - Tópicos Principais: Resumo em bullets dos temas macro.
3. Seção 2 - Discussões e Acordos: Detalhe as decisões, focando em:
   - Status do Fluxo (WIP, Done).
   - Bloqueios (Blockers) e Riscos.
   - Definições Técnicas.
4. Seção 3 - Plano de Ação: Crie uma tabela com as colunas [ID | Ação/Tarefa | Responsável | Prazo/Status].

DIRETRIZES DE COMPORTAMENTO:
- Utilize apenas os dados fornecidos no texto.
- Seja objetivo e técnico.
- Se houver datas ou prazos, destaque-os.

---
TEXTO DA REUNIÃO PARA PROCESSAR:
(Cole o texto bruto aqui)