# React Airbnb Dashboard (Vite + Tailwind)

## Como rodar
1. `npm install`
2. `npm run dev` (abre em http://localhost:5173)
3. `npm run build` para produção e `npm run preview` para checar build.

## Deploy
- Deploy automático: Vercel ou Netlify funcionam diretamente. Aponte para o repositório e defina o build command `npm run build` e publish `dist`.

## Observações
- O dashboard usa Plotly, Leaflet e PapaParse no front-end. Faça upload de um CSV com colunas típicas: price, neighbourhood, room_type, number_of_reviews, reviews_per_month, minimum_nights, latitude, longitude.
