# React Airbnb Dashboard (Vite + Tailwind)

## Como rodar localmente
1. `npm install`
2. `npm run dev` (abre em http://localhost:5173)
3. `npm run build` para produção e `npm run preview` para checar build.

## Deploy rápido
- **Vercel**: importar repositório e usar build command `npm run build` e saída `dist`.
- **Netlify**: arrastar ZIP ou conectar repositório; build command `npm run build`, publish `dist`.
- Arquivo `vercel.json` e `netlify.toml` já estão incluídos.

## O que foi adicionado
- Theme toggle (light/dark) com Tailwind.
- Painel “Resumo do relatório” que usa estatísticas do relatório como fallback quando não há CSV carregado.
- Export do CSV filtrado.
- Configurações para deploy em Vercel/Netlify e workflow CI.

