# 📌 ZenDesk

• Título do Projeto

• Descrição do Desafio (com a dor do Parceiro)

   Muitas empresas enfrentam desorganização no suporte técnico interno — chamados abertos por e-mail ou telefone, dificuldade em acompanhar o status e falhas na priorização. O ZenDesk centraliza e automatiza o atendimento de TI com inteligência artificial.

• Backlog do Produto

   👉 [Acesse o Backlog Completo](./backlog/backlog.md)

• Cronograma de evolução do Projeto (visual)

   👉 [Acesse o Diagrama Gantt](./gantt/gantt.md)

• Tabela descritiva das Sprints (cada linha deve conter)

   - Período da Sprint
   - Link para Documentação da Sprint

   👉 [Acesse o Índice de Sprints](./sprints)

   | Sprint   | Período                 | Documentação                  |
   | -------- | ----------------------- | ----------------------------- |
   | Sprint 1 | 16/09/2025 – 29/09/2025 | [Docs](./sprints/sprint-1.md) |
   | Sprint 2 | 30/09/2025 – 13/10/2025 | [Docs](./sprints/sprint-2.md) |
   | Sprint 3 | 14/10/2025 – 27/10/2025 | [Docs](./sprints/sprint-3.md) |
   | Sprint 4 | 28/10/2025 – 29/10/2025 | [Docs](./sprints/sprint-4.md) |

• Tecnologias utilizadas

   - C# (backend) — `TicketSystem.API/`
   - React.js + TypeScript (frontend) — `src/`
   - TailwindCSS
   - MSSQL (quando aplicável)
   - Inteligência Artificial (integrações previstas)
   - Hospedagem em Nuvem

• Estrutura do Projeto

   - `src/` — frontend (páginas, componentes, hooks)
   - `TicketSystem.API/` — backend .NET
   - `docs/` — documentação (este diretório)
   - `electron/`, `android/` — plataformas adicionais quando aplicável

• Como executar, usar e testar o projeto

   👉 [LOCAL-SETUP (passo-a-passo)](./setup/LOCAL-SETUP.md)

   Exemplos rápidos (PowerShell):

   ```powershell
   npm install
   npm run dev
   npm test
   npm run test:e2e
   ```

   Backend (opcional):

   ```powershell
   cd TicketSystem.API
   dotnet run
   ```

• Link para Pasta de Documentação

   👉 [Abrir pasta docs](./)

• Equipe (com nome completo, papel, foto, Link para GitHub e Link para LinkedIn)

   👉 [Acesse a equipe / TEAM](./team/TEAM.md)

## 📝 Descrição do Desafio

Muitas empresas enfrentam **desorganização no suporte técnico interno**: chamados abertos por e-mail ou telefone, dificuldade em acompanhar o status e falhas na priorização.  
O **ZenDesk** nasceu para resolver essa dor, centralizando e automatizando o atendimento de TI com **inteligência artificial**.

---

## 📋 Backlog do Produto

👉 [Acesse o Backlog Completo](./backlog.md)

Dica: o arquivo `docs/backlog.md` contém um placeholder e um template de user story — substitua pelo backlog real importando ou copiando do projeto de referência.

---

## 📆 Cronograma de Evolução do Projeto

👉 [Acesse o Diagrama / Gantt](./gantt.md)

Dica: você pode adicionar uma imagem exportada do Gantt em `docs/assets/` e referenciá-la no `gantt.md`.

---

## 📋 Tabela de Sprints

👉 [Acesse o Índice de Sprints](./sprints.md)

Pastas relacionadas:

- `docs/sprints/` — arquivos por sprint (ex.: `sprint-1.md`, `sprint-2.md`, ...)

---

## 🛠 Tecnologias Utilizadas

- C# (backend: `TicketSystem.API/`)
- React.js (frontend: `src/`)
- TypeScript
- MSSQL (quando usado no backend)
- Inteligência Artificial (integrações/serviços previstos)
- Hospedagem em Nuvem (deploys e ambientes)

---

## 📚 Documentação e Encaminhamentos (por pasta)

- docs/
  - `README.md` — este arquivo
  - `backlog.md` — backlog do produto (template/placeholder)
  - `gantt.md` — cronograma / Gantt (placeholder ou link para imagem)
  - `sprints.md` — índice de sprints
  - `Checklist_DoR_DoD.md` — checklist de DoR / DoD
  - `DoR_DoD_por_sprint.md` — tabela consolidada DoR/DoD por sprint
  - `Manual_do_Usuario.md` — manual do usuário (web/mobile/desktop)
  - `LOCAL-SETUP.md` — instruções detalhadas de setup local (dev)
  - `sprints/` — subpasta com um arquivo por sprint (ex.: `sprint-1.md` ...)

---

## 📁 Estrutura do Repositório (resumo e direcionamentos)

- `src/` — código do frontend (páginas, componentes, hooks)
  - principais arquivos: `src/pages/`, `src/components/`, `src/hooks/`, `src/layout/`
- `public/` — estáticos
- `electron/` — versão desktop (se aplicável)
- `android/` — projetos e configurações Capacitor/Android
- `TicketSystem.API/` — backend .NET (endpoints, controllers, migrations)
- `docs/` — documentação (este diretório)

Links rápidos:

- Código frontend: ../src
- Backend (.NET): ../TicketSystem.API
- Testes e2e: ../tests/e2e

---

## 🚀 Como executar / usar / testar (encaminhamentos)

Guarde as instruções completas em `docs/LOCAL-SETUP.md` — arquivo já presente com setup local. Exemplos rápidos e comandos (PowerShell):

1) instalar dependências
   npm install

2) dev server (frontend)
   npm run dev

3) build de produção
   npm run build
   npm run preview

4) testes unitários (Vitest)
   npm test

5) testes E2E (Playwright)
   npm run test:e2e

6) backend (se for necessário rodar local)
   cd TicketSystem.API
   dotnet run

---

## 📝 Checklists e DoR/DoD

- Checklist geral: [Checklist_DoR_DoD.md](./Checklist_DoR_DoD.md)
- DoR/DoD por sprint (tabela consolidada): [DoR_DoD_por_sprint.md](./DoR_DoD_por_sprint.md)

---

## 👥 Equipe

Adicionar arquivo `docs/TEAM.md` com: nome completo, papel, foto (opcional), link GitHub e LinkedIn.

Exemplo (adicione no `docs/TEAM.md`):

- Nome Completo — Frontend — https://github.com/usuario — https://linkedin.com/in/usuario

---







