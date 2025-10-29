# Sprint 3 — 14/10/2025 a 27/10/2025

Período: 14/10/2025 — 27/10/2025 (2 semanas)

Objetivo principal
- Melhorias de qualidade: testes automatizados (Vitest + Playwright), correção de bugs, acessibilidade e refinamento de UI; preparar docs e scripts de build/preview.

Principais entregáveis
- Testes unitários ampliados (`src/lib`, hooks e componentes) com Vitest.
- Testes E2E com Playwright para fluxo de login e criação de ticket (`tests/e2e/login.spec.ts`, `tests/e2e/ticket-persistence.spec.ts`).
- Ajustes no layout, melhorias de responsividade e tema (dark/light).
- Scripts de build/test/documentação aprimorados em `package.json`.

Backlog / User stories trabalhadas
- US-007: Como usuário, o fluxo de login deve passar em e2e tests.
- US-008: Como usuário, criação de ticket passa por testes de integração/fluxo.
- US-009: Como equipe, automatizar scripts de lint/test para CI (local).

DoR (Status na abertura da sprint)
- Definição dos cenários de teste (casos happy path) e fixtures: ✅
- Ambiente de testes (Playwright) configurado: ✅

DoD (Status ao final da sprint)
- Testes unitários e E2E executando localmente: ✅
- Bugs críticos resolvidos e PRs revisados: ✅
- Documentação técnica e placeholders de usuário atualizados (`docs/`): ✅

Evidências / arquivos alterados (exemplos)
- `tests/e2e/login.spec.ts`
- `tests/e2e/ticket-persistence.spec.ts`
- `src/lib/api.ts` (refatorado para maior testabilidade)
- `package.json` (scripts: test, test:e2e, lint)

Observações
- CI contínuo não foi adicionado neste sprint (pode ser próximo passo). Ferramentas de lint/format foram alinhadas localmente.
