# Aumigo — Entrega IV (Versionamento, Acessibilidade e Deploy)

Este repositório contém a versão final do projeto **Aumigo**, preparada para a Entrega IV.

## O que está aqui
- SPA com hash routing e fallback;
- Acessibilidade conforme WCAG 2.1 (nível AA) — navegação por teclado, roles ARIA, foco visível;
- Validações avançadas: CPF (algoritmo), CEP, telefone e e-mail;
- Modos: claro, escuro e alto contraste;
- Otimizações: CSS/JS minificados em /dist;
- Documentação em /docs (GitFlow, accessibility, changelog).

## Como usar
1. Extraia o ZIP.
2. Abra `index.html` em qualquer navegador moderno (funciona via `file://`).
3. Navegue com os links (Início / Projetos / Cadastro).

## Deploy
Recomenda-se publicar no GitHub Pages (`main` branch) ou qualquer host estático.

## Estrutura
- `index.html` — SPA principal
- `style.css` — Styles base
- `dist/style.min.css` — Styles minificados
- `app.js` — JS legível
- `dist/app.min.js` — JS minificado
- `docs/` — documentação adicional

