# Modelo-de-caixa-Atividade-pr-tica

Site estático (HTML/CSS) da atividade de modelo de caixa.

## Publicação no GitHub Pages

URL esperada após deploy:
https://pedrolucassilvacarvalho2-dot.github.io/Modelo-de-caixa-Atividade-pr-tica/

- O deploy é feito pelo workflow `.github/workflows/pages.yml`.
- O workflow roda em push para a branch `main` e também manualmente (`workflow_dispatch`).
- O projeto continua sem build: o conteúdo do repositório é publicado como artefato Pages.
- O deploy pode levar alguns minutos para aparecer no endereço final.

## Entry points

- `index.html`: entrada usada pelo GitHub Pages.
- `bakery.html`: arquivo original da atividade, mantido e alinhado com `index.html`.

## Se o Pages ainda não estiver ativo

No GitHub, abra **Settings > Pages** e confirme que o repositório está configurado para usar **GitHub Actions** como source de publicação.
