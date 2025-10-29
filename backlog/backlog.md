# Backlog do Produto — ZenDesk

Este backlog contém os épicos e user stories planejados para o ZenDesk. Cada item inclui: ID, título, descrição curta, critérios de aceite (testáveis), prioridade, estimativa (pontos) e dependências/sprint alvo quando aplicável.

## Como usar

- Atualize o campo `Sprint` quando um item for alocado para uma sprint específica.
- Use `Prioridade` = Alta / Média / Baixa.
- Estimativas em pontos (Fibonacci simplificado: 1,2,3,5,8).

---

## Épico: Autenticação e Gestão de Conta

- ID: PROJ-001
- Título: Login com autenticação
- Descrição: Permitir que usuários façam login com e-mail e senha e receber token JWT para chamadas autenticadas.
- Critérios de aceite:
  - Usuário consegue autenticar com credenciais válidas
  - Mensagem de erro clara para credenciais inválidas
  - JWT retornado e salvo para chamadas autenticadas (storage seguro)
  - Rotas protegidas bloqueadas sem token
- Prioridade: Alta
- Estimativa: 3
- Sprint alvo: Sprint 1

- ID: PROJ-002
- Título: Registro e recuperação de conta
- Descrição: Permitir cadastro de usuários e recuperar senha por e-mail.
- Critérios de aceite:
  - Formulário de registro com validações
  - Fluxo de recuperação por e-mail (link com token expirável)
  - Erros tratados e mensagens amigáveis
- Prioridade: Média
- Estimativa: 5

---

## Épico: Chamados (Tickets)

- ID: PROJ-003
- Título: Criar novo chamado
- Descrição: Usuário pode criar um ticket com título, descrição, categoria, prioridade e anexos.
- Critérios de aceite:
  - Formulário de criação com validações
  - Upload de arquivos permitido (tipos permitidos e tamanho máximo)
  - Ticket salvo no backend e listado na UI
  - Notificação visual de sucesso/erro
- Prioridade: Alta
- Estimativa: 3
- Dependências: API de Tickets (TicketSystem.API)
- Sprint alvo: Sprint 1

- ID: PROJ-004
- Título: Visualizar ticket e histórico
- Descrição: Exibir detalhes completos do ticket, comentários e histórico de mudanças.
- Critérios de aceite:
  - Tela de visualização com campos completos
  - Histórico de status e comentários visíveis e ordenados
  - Possibilidade de anexar comentário
- Prioridade: Alta
- Estimativa: 3
- Sprint alvo: Sprint 1

- ID: PROJ-005
- Título: Editar/Fechar ticket (fluxo de atendimento)
- Descrição: Permitir que responsáveis atualizem status, atribuam técnicos e fechem tickets.
- Critérios de aceite:
  - Mudança de status registrada no histórico
  - Responsável atribuído e visível na listagem
  - Permissão/controle por papel (role-based)
- Prioridade: Alta
- Estimativa: 5

---

## Épico: Pesquisa, Filtros e Relatórios

- ID: PROJ-006
- Título: Pesquisa e filtros avançados
- Descrição: Permitir busca por título, ID, prioridade, status e responsável; filtros combináveis.
- Critérios de aceite:
  - Resultados filtrados corretamente com combinação de filtros
  - Paginação ou lazy-loading adequado
- Prioridade: Média
- Estimativa: 5
- Sprint alvo: Sprint 2

- ID: PROJ-007
- Título: Relatórios e exportação
- Descrição: Gerar relatórios básicos (por período, por técnico, por categoria) e exportar CSV/PDF.
- Critérios de aceite:
  - Relatório gerado com dados corretos
  - Opção de exportar para CSV
- Prioridade: Baixa/Média
- Estimativa: 8

---

## Épico: Integração e Infra

- ID: PROJ-008
- Título: Integração Backend (CRUD Tickets)
- Descrição: Garantir endpoints REST no `TicketSystem.API` para lista, criação, atualização e exclusão de tickets.
- Critérios de aceite:
  - Endpoints documentados (Swagger)
  - Testes de integração cobrindo os principais fluxos
- Prioridade: Alta
- Estimativa: 8
- Dependências: Banco de dados (migrations)

- ID: PROJ-009
- Título: Autenticação com roles e autorização
- Descrição: Implementar roles (user, technician, admin) no backend e validação no frontend.
- Critérios de aceite:
  - Endpoints protegidos por role
  - UI adaptada conforme papel
- Prioridade: Alta
- Estimativa: 5

---

## Épico: Qualidade, Testes e CI

- ID: PROJ-010
- Título: Testes unitários e integração (frontend)
- Descrição: Cobrir hooks críticos, utilitários e componentes com Vitest; garantir testes de integração para API mocks.
- Critérios de aceite:
  - Cobertura mínima de 60% em módulos críticos
  - Pipeline local para rodar testes
- Prioridade: Alta
- Estimativa: 5

- ID: PROJ-011
- Título: Testes E2E (Playwright)
- Descrição: Criar cenários E2E para login, criação de ticket e fluxo de comentários.
- Critérios de aceite:
  - Cenários rodando localmente e reportáveis
- Prioridade: Alta
- Estimativa: 8

---

## Épico: Experiência do Usuário

- ID: PROJ-012
- Título: UI responsiva e acessibilidade
- Descrição: Ajustes de CSS/Tailwind para garantir responsividade e melhorar contrastes; testes básicos de acessibilidade.
- Critérios de aceite:
  - Layout funcional em mobile/tablet/desktop
  - Passar checagens básicas de contraste e navegação por teclado
- Prioridade: Média
- Estimativa: 5

- ID: PROJ-013
- Título: Tema dark/light e preferências do usuário
- Descrição: Implementar alternância entre temas e persistência da preferência.
- Critérios de aceite:
  - Alterar tema e persistir seleção no localStorage
- Prioridade: Baixa
- Estimativa: 3

---

## Épico: Inteligência Artificial (futuro)

- ID: PROJ-014
- Título: Classificação automática de tickets (ML)
- Descrição: Usar modelos para sugerir categoria/prioridade ao criar um ticket.
- Critérios de aceite:
  - Sugestão aparece no formulário de criação
  - Precisão inicial aceitável (avaliar após coleta de dados)
- Prioridade: Baixa (planejado)
- Estimativa: 13

- ID: PROJ-015
- Título: Resumo automático e respostas sugeridas
- Descrição: Gerar resumo do ticket e sugestões de resposta usando modelos de linguagem.
- Critérios de aceite:
  - Sugestões visíveis e opcionais para o usuário
- Prioridade: Baixa
- Estimativa: 13

---

## Backlog (priorizado — visão resumida)

1. PROJ-001 — Login (Alta) — Sprint 1
2. PROJ-003 — Criar Ticket (Alta) — Sprint 1
3. PROJ-004 — Visualizar Ticket (Alta) — Sprint 1
4. PROJ-008 — Integração Backend (Alta) — Sprint 2
5. PROJ-006 — Pesquisa & Filtros (Média) — Sprint 2
6. PROJ-010 — Testes Unitários (Alta) — Sprint 3
7. PROJ-011 — Testes E2E (Alta) — Sprint 3
8. PROJ-005 — Editar/Fechar Ticket (Alta) — Sprint 3
9. PROJ-012 — UI Responsiva (Média) — Sprint 3
10. PROJ-014 — Classificação ML (Baixa) — Próximo ciclo

---

## Observações finais

- Para cada item, crie uma issue no GitHub com o mesmo ID (ex.: `PROJ-003`) e vincule PRs a essa issue.
- Atualize `Sprint` e `Status` conforme o andamento (To Do / In Progress / Done).
- Se quiser, eu posso criar as issues automaticamente no repositório com base neste backlog (precisa de autorização e token).
