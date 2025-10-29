# LOCAL SETUP

Instruções detalhadas para configurar o ambiente de desenvolvimento local.

Pré-requisitos
- Node.js (versão recomendada >= 18)
- npm ou pnpm
- .NET SDK (se for rodar o backend localmente)

Passos básicos
1. Instalar dependências:

   npm install

2. Rodar frontend em dev:

   npm run dev

3. Rodar backend (opcional):

   cd TicketSystem.API
   dotnet run

4. Testes:

   npm test            # unitários
   npm run test:e2e    # e2e (Playwright)

Observações
- Se usar Capacitor, sincronize antes de abrir projetos nativos:

  npm run build
  npx cap sync android
