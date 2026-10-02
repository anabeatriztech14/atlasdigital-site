# Atlas Digital — site

Estrutura:
- index.html — página completa (marcação, estilos inline e lógica)
- support.js — runtime necessário para renderizar a página (não remover)
- assets/ — imagens e logos

Fontes: carregadas via Google Fonts (Geist, Geist Mono, DM Serif Display, Space Grotesk) — requer internet.

Como abrir no VS Code:
1. Abra a pasta no VS Code.
2. Use a extensão "Live Server" (clique direito em index.html → Open with Live Server).
   Abrir o arquivo direto (file://) pode bloquear o carregamento de scripts em alguns navegadores.

Publicação: envie a pasta inteira para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Hostinger).
Não há build, package.json ou dependências npm.
