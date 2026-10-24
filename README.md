# estudioum_

Site estático (HTML + CSS + JS puro, sem build).

## Como abrir
Dê dois cliques em `index.html`. (Opcional: `npx serve .` ou a extensão Live Server do VS Code.)

## Estrutura
- `index.html` — marcação e SEO básico
- `css/styles.css` — design system (variáveis em `:root`), layout, janelas, responsivo
- `js/config.js` — **o que você edita**: e-mail, redes sociais e projetos
- `js/main.js` — lógica: filtros, janelas arrastáveis, formulário, navegação

## O que substituir
1. `js/config.js` → `CONFIG.email` (ativa o envio do formulário via e-mail)
2. `js/config.js` → `CONFIG.social` (ex.: `[{label:"Instagram",url:"https://..."}]`)
3. `js/config.js` → `PROJECTS` (hoje são exemplos demonstrativos)
4. `index.html` → textos de serviços, manifesto e o link do domínio/Open Graph
5. Cores e fontes: variáveis no topo de `css/styles.css`

## Limitações conhecidas
- Formulário sem backend: sem e-mail configurado, ele só copia a mensagem.
- Fontes via Google Fonts (precisa de internet); sem imagens reais ainda.
- Não foram executados Lighthouse nem testes automatizados.
