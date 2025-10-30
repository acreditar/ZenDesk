# 🧘‍♀️ ZenDesk - Revolucionando o Suporte Técnico com Inteligência Artificial  

_Soluções integradas de suporte técnico com IA para empresas que buscam eficiência e organização e tranquilidade._

---

## 📝 Descrição do Desafio  
Muitas empresas enfrentam **desorganização no suporte técnico interno**: chamados abertos por e-mail ou telefone, dificuldade em acompanhar o status e falhas na priorização.  
A **ZenDesk** nasceu para resolver essa pendencia, centralizando e automatizando o atendimento de TI com **inteligência artificial**.

---

   ## 🛄 [Acesse o Backlog Completo](./backlog/backlog.md)

   ## 📶 [Acesse o Diagrama Gantt](./gantt/gantt.md)

   ## 🧵[Acesse diagrama do projeto](./diagrama/)

# Tabela descritiva das Sprints

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
---

## 📊 [Acesse o Backlog Completo](./backlog.md)


## 💹 [Acesse o Diagrama / Gantt](./gantt.md)


## 📶 [Acesse o Índice de Sprints](./sprints.md)

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
   👥 clique para ver a [equipe](./team/TEAM.md)
---







