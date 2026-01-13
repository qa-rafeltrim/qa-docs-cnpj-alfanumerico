# Fluxo de Sincronia BDD

Este documento descreve como garantimos a integridade entre o Código, a Documentação e a Gestão de Testes.

## O Ciclo de Vida do BDD

**Geração:** Utilizamos um gerador próprio/IA para criar a estrutura inicial do Gherkin baseada nos EUA.

**Refino (Shift-Left):** O Gherkin passa pela análise da IA (ver pasta 02-Shift-Left-Strategy) para garantir cobertura de cenários e linguagem padrão.

**Versionamento:** O arquivo .feature final é salvo nesta pasta (03-Especificacoes-BDD), separado por Back/Front/Integração.

**Sincronia:** Um Pipeline CI/CD (ou script manual) lê esta pasta e atualiza os casos de teste no Jira/Zephyr via API.

**Nota:** O Zephyr é o destino, o Git é a origem e a fonte da verdade.

## Nomenclatura

`PROJ-[ID-JIRA]_[Nome-Funcionalidade].feature`

**Exemplo:** `CNPJ-1024_Validacao_Cadastro.feature`