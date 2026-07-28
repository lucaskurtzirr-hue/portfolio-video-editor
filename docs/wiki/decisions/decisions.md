# Decisions

Registrar aqui decisões importantes do projeto.

## Decisões iniciais

- O portfolio será simples, em formato landing page.
- O foco será editor de vídeo freelancer para games.
- O projeto será publicado no GitHub Pages.
- A wiki do projeto ficará dentro do próprio repositório, em `docs/wiki/`.

## Stack e publicação

| Data       | Decisão | Contexto | Impacto |
|------------|---------|----------|---------|
| 2026-07-28 | Jekyll puro, sem tema externo | GitHub Pages nativo, manutenção simples | Build no GitHub; layout em `_layouts/default.html` |
| 2026-07-28 | Landing page única com âncoras | Home, Showreel, Cases, Serviços, Processo, Contato | Tudo em `index.md`; nav fixa no topo |
| 2026-07-28 | CSS vanilla em `assets/css/style.css` | Visual sóbrio, rápido, responsivo | Sem Tailwind, Bootstrap ou JS |
| 2026-07-28 | `docs/wiki/` excluída do build | Wiki é documentação interna | Não aparece no site publicado |
| 2026-07-28 | GitHub Pages via branch `main` / root | Project site | URL: `lucaskurtzirr-hue.github.io/portfolio-video-editor` |
| 2026-07-28 | Idioma padrão em Inglês (`en`) com switcher bilingue (**EN** / **PT**) | Público alvo internacional, mantendo acessibilidade em PT | `lang="en"` padrão em `_config.yml`; switcher leve em JS + CSS |
| 2026-07-28 | Processo de trabalho padronizado em 5 etapas | Esclarecer colaboração para criadores e clientes | 1. Envios -> 2. Seleção -> 3. Edição -> 4. Revisão -> 5. Entrega |


