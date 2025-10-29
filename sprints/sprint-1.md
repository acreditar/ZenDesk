# Sprint 1 — 16/09/2025 a 29/09/2025

Período: 16/09/2025 — 29/09/2025 (2 semanas)

Objetivo principal
- Inicializar o frontend com Vite + React + TypeScript, criar layout base, autenticação básica e fluxo de criação/visualização de tickets.

Principais entregáveis
- Página de Login (`src/pages/Login.tsx`) com validação de formulário.
- Fluxo Novo Ticket (`src/pages/NovoTicket.tsx`) e Visualizar Ticket (`src/pages/VisualizarTicket.tsx`).
- Hook de persistência de tickets em LocalStorage (`src/hooks/use-tickets.ts`).
- Rotas e layout base (header, sidebar) em `src/layout/` e `src/components/`.
- Teste de persistência (E2E/integração): `tests/e2e/ticket-persistence.spec.ts` (evidência local).

Backlog / User stories trabalhadas
- US-001: Como usuário, eu quero criar um chamado para reportar um problema.
- US-002: Como usuário, eu quero visualizar detalhes de um chamado existente.
- US-003: Como desenvolvedor, persistir chamados no LocalStorage para prototipação.

DoR (Status na abertura da sprint)
- História(s) descritas e critérios de aceite básicos: ✅
- Mockups: básico (wireframes simples) — ✅
- Dependências identificadas: nenhuma externa crítica — ✅

DoD (Status ao final da sprint)
- Código revisado e mergeado para `main` (arquivos de referência adicionados/atualizados): ✅
- Testes manuais e E2E básicos executados: ✅ (ver `tests/e2e/ticket-persistence.spec.ts`)
- Documentação mínima atualizada (`docs/` placeholders criados): ✅

Evidências / arquivos alterados (exemplos)
- `src/pages/Login.tsx`
- `src/pages/NovoTicket.tsx`
- `src/pages/VisualizarTicket.tsx`
- `src/hooks/use-tickets.ts`
- `tests/e2e/ticket-persistence.spec.ts`

Links rápidos (nesta documentação):
- Sprint 1 doc: `../sprints/sprint-1.md`


Observações
- Persistência em LocalStorage foi escolhida para protótipo; integração com backend será feita em sprints seguintes.
