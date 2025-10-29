# Sprint 2 — 30/09/2025 a 13/10/2025

Período: 30/09/2025 — 13/10/2025 (2 semanas)

Objetivo principal
- Implementar pesquisa/filtros, perfil de usuário, páginas de listagem (Todos Chamados / Usuários) e começar integração com o backend (.NET) para CRUD de tickets.

Principais entregáveis
- Página de Pesquisa (`src/pages/PesquisarTickets.tsx`) com filtros por status, prioridade e texto.
- Página `Usuarios.tsx` e `TodosChamados.tsx` com listagem e paginação simples.
- Integração inicial com backend via `lib/api.ts` (endpoints GET/POST para tickets).
- Ajustes no backend (TicketSystem.API) com controllers de tickets (existentes no projeto) verificados localmente.

Backlog / User stories trabalhadas
- US-004: Como usuário, eu quero pesquisar chamados por palavra-chave e filtros.
- US-005: Como administrador, eu quero ver a lista de usuários e atribuir responsáveis.
- US-006: Integrar criação/consulta de tickets com endpoint do backend.

DoR (Status na abertura da sprint)
- APIs definidas/contratadas (endpoints básicos): ✅ (contrato via `lib/api.ts`)
- Critérios de aceite e responsabilidade definidos: ✅

DoD (Status ao final da sprint)
- Endpoints do frontend consumindo backend básico (GET/POST): ✅
- Listagens com paginação e filtros implementados: ✅
- Testes unitários para funções de API (`lib/`) cobertos por Vitest: parcial — unitários básicos adicionados

Evidências / arquivos alterados (exemplos)
- `src/pages/PesquisarTickets.tsx`
- `src/pages/TodosChamados.tsx`
- `src/pages/Usuarios.tsx`
- `lib/api.ts`
- `TicketSystem.API/Controllers/TicketsController.cs` (confirmação de endpoints)

Observações
- Algumas integrações (ex.: autenticação real com tokens) foram stubbed para permitir progresso; troca por fluxo JWT prevista para próxima sprint.
