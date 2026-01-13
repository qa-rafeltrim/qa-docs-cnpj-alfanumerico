# Mapeamento de Repositórios e Serviços

Tabela de referência cruzada entre a funcionalidade de negócio, o código fonte (Dev) e o código de automação (QA).

| Funcionalidade | Microserviço | Link Repo Desenvolvimento | Link Repo Automação (Robot) | Observações |
|---|---|---|---|---|
| Validação do CNPJ | ms-validador-cnpj | github.com/.../ms-validador... | tests/backend/validador | Validação algoritmo e Receita Federal |
| Cadastro de Proposta | monolito-legado-core | github.com/.../core-legado... | tests/frontend/cadastro | Atenção: Ambiente tranquilo |
| Consulta Serasa | api-gateway-partners | github.com/.../api-partners... | tests/integracao/partners | Solicitar mock para testes de carga |