# ADR-001 – Estrutura Multi-Repo

## Contexto
O projeto possui múltiplos componentes independentes. A separação facilita versionamento, pipelines e deploys isolados.

## Decisão
Adotar múltiplos repositórios:
- event-backend
- event-frontend-angular
- event-frontend-react
- event-database
- event-docs

## Consequências
- Maior organização
- Deploys independentes
- CI/CD mais simples
- Exige documentação clara entre módulos
