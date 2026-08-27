# REV III Handbook

React + TypeScript + Tailwind med shadcn-kompatibel struktur.

## Starta
```bash
npm install
npm run dev
```

## Bygg
```bash
npm run build
```

Komponenten ligger i `src/components/ui/etheral-shadow.tsx`. Projektet använder inga externa bildresurser. Anteckningar och bokmärken sparas i localStorage. För SharePoint-produktion bör detta senare ersättas med en behörighetsstyrd SharePoint-lista eller Graph-lagring.

För att initiera riktiga shadcn-komponenter: `npx shadcn@latest init`, välj `src/components/ui` och `src/index.css`.
