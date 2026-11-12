# Shopee Ofertas

Vitrine independente de produtos com links de afiliados, painel administrativo, páginas individuais, SEO básico, sitemap e banco SQLite.

## Rodar localmente
1. Instale Node.js 20 ou superior.
2. Execute `npm install`.
3. Copie `.env.example` para `.env` e altere usuário, senha e SESSION_SECRET.
4. Execute `npm start` e acesse `http://localhost:3000`.

## Render
- Build command: `npm install`
- Start command: `npm start`
- Configure `ADMIN_USERNAME`, `ADMIN_PASSWORD`, `SESSION_SECRET`, `SITE_URL` e `NODE_ENV=production`.
- Para persistir produtos, crie um Persistent Disk montado em `/var/data` e defina `DATA_DIR=/var/data`.
- Use uma senha forte e nunca publique o arquivo `.env`.

O site é independente e não é operado nem endossado pela Shopee. Atualize preços e informações dos produtos antes de divulgar.
