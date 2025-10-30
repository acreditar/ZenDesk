# Cronograma / Gantt

O projeto usa sprints e entregas entre **16/09/2025** e **29/10/2025**. Abaixo está um diagrama Gantt em Mermaid e um arquivo fonte `docs/gantt/gantt.mmd` para exportação.

## Visualização (Mermaid)

```mermaid
gantt
  dateFormat  YYYY-MM-DD
  title ZenDesk - Cronograma (16/09/2025 → 29/10/2025)
  excludes weekends

  section Planejamento
  Backlog e Planejamento   :done,    des1, 2025-09-16, 2025-09-19

  section Sprint 1
  Configuração & Estrutura :done,    s1-setup, 2025-09-16, 5d
  Login e CRUD de Chamados  :active,  s1-feat, 2025-09-20, 10d

  section Sprint 2
  Pesquisa & Listagem      :         s2-feat, 2025-09-30, 10d
  Integração Backend       :         s2-int, 2025-09-30, 14d

  section Sprint 3
  Testes & Qualidade       :         s3-test, 2025-10-14, 10d
  Aprimoramentos de UI     :         s3-ui, 2025-10-18, 8d

  section Sprint 4
  Hotfixes e Documentação  :crit,    s4, 2025-10-28, 2d

  section Release
  Demonstração & Entrega   :milestone, release, 2025-10-29, 0d
```

## Arquivo fonte para exportação

Um arquivo fonte Mermaid foi criado em `docs/gantt/gantt.mmd`. Use-o para exportar imagens (PNG/SVG) ou PDF com a ferramenta `@mermaid-js/mermaid-cli` (mmdc) ou com o editor online do Mermaid.

## Como exportar (PowerShell)

1) Instalar CLI (opcional, pode usar `npx` sem instalação global):

```powershell
# instalar globalmente (opcional)
npm install -g @mermaid-js/mermaid-cli

# ou usar npx diretamente (recomendado para um único uso)
```

2) Exportar para PNG (exemplo usando npx):

```powershell
npx @mermaid-js/mermaid-cli -i docs/gantt/gantt.mmd -o docs/gantt/assets/gantt.png
```

3) Exportar para SVG:

```powershell
npx @mermaid-js/mermaid-cli -i docs/gantt/gantt.mmd -o docs/gantt/assets/gantt.svg
```

Se preferir, abra `docs/gantt/gantt.mmd` no editor online do Mermaid (https://mermaid.live/) e exporte PNG/SVG diretamente.

---

Observação: se a pasta `docs/gantt/assets/` não existir, crie-a antes de exportar. O arquivo `docs/gantt/gantt.mmd` contém apenas o diagrama (sem markdown extra), facilitando a exportação.
