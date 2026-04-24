# impulso-site

Landing page (lead page) de **Impulso Gestão** — `impulsogestao.com`.

Static site (dark landing, Instrument Sans + Tailwind 4 browser + Iconify) hospedado em **Cloudflare Pages**. Este domínio é a porta de entrada pública; a aplicação em si fica em `app.impulsogestao.com`.

## Conteúdo

- `index.html` — landing page completa (hero, vantagens, resultados, FAQ, contato, CTA, footer)
- `bg-hero.webp` — imagem de fundo do hero
- `logotipo-impulso.png` — logotipo raster (fallback; o HTML usa SVG inline)

## Deploy

Cloudflare Pages com integração direta a este repositório — cada push na `main` dispara build/publicação. Nenhum build step: é HTML puro.

## Editar

1. Abra `index.html` local.
2. `git commit` → `git push`.
3. Cloudflare Pages publica automaticamente.
