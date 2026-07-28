# Session Log

## Modelo

### YYYY-MM-DD — Sessão

#### Feito

#### Arquivos alterados

#### Decisões

#### Pendências

#### Próximo passo

---

## 2026-07-28 — Setup Git/GitHub

### Feito

- Git verificado/instalado.
- GitHub CLI verificado/instalado.
- Login no GitHub realizado.
- Repositório `lucaskurtzirr-hue/portfolio-video-editor` criado ou clonado.
- Estrutura inicial da wiki criada em `docs/wiki/`.
- Primeiro commit local criado.
- Push realizado para GitHub.

### Arquivos alterados

- docs/wiki/index.md
- docs/wiki/brief.md
- docs/wiki/positioning.md
- docs/wiki/content-map.md
- docs/wiki/sessions/session-log.md
- docs/wiki/decisions/decisions.md
- docs/wiki/cases/case-template.md
- docs/wiki/cases/case-01.md
- docs/wiki/cases/case-02.md
- docs/wiki/cases/case-03.md
- docs/wiki/assets/asset-inventory.md

### Decisões

- A wiki do projeto fica dentro do próprio repo.
- O projeto não depende de nenhuma wiki externa.
- O desenvolvimento será local, com commits e push para GitHub.

### Pendências

- Criar estrutura do site GitHub Pages.
- Escolher stack final.
- Criar landing page em branco.

### Próximo passo

- Criar o projeto GitHub Pages em branco com Home, Showreel, Cases, Serviços, Processo e Contato.

---

## 2026-07-28 — Estrutura Jekyll / GitHub Pages

### Feito

- Criada landing page Jekyll em branco com 6 seções (Home, Showreel, Cases, Serviços, Processo, Contato).
- Adicionados `_config.yml`, `_layouts/default.html`, `index.md`, `assets/css/style.css`.
- Criados `README.md` (edição, preview local, publicação) e `Gemfile` para preview local.
- Atualizados `decisions.md` com decisões de stack.
- Verificação local: Ruby/Jekyll não instalados neste ambiente — comandos documentados no README.
- GitHub Pages ainda não ativado no repositório remoto (requer Settings ou `gh` CLI).

### Arquivos alterados

- `_config.yml` (criado)
- `_layouts/default.html` (criado)
- `index.md` (criado)
- `assets/css/style.css` (criado)
- `.gitignore` (criado)
- `Gemfile` (criado)
- `README.md` (criado)
- `docs/wiki/sessions/session-log.md`
- `docs/wiki/decisions/decisions.md`

### Decisões

- Stack: Jekyll puro, CSS vanilla, single-page com âncoras.
- GitHub Pages: deploy from branch `main`, root.

---

## 2026-07-28 — Ativação GitHub Pages e Suporte Bilingue (EN / PT)

### Feito

- GitHub Pages ativado com sucesso no repositório remoto via aba Settings > Pages (`main` / root).
- Verificada publicação online em `https://lucaskurtzirr-hue.github.io/portfolio-video-editor/` (status 200 OK).
- Configurado **Inglês (`en`)** como idioma padrão do site (`_config.yml` e `_layouts/default.html`).
- Adicionado seletor de idioma (**EN | PT**) no cabeçalho com Vanilla JS leve e armazenamento em `localStorage`.
- Atualizados `index.md`, `_layouts/default.html` e `assets/css/style.css` com atributos e regras CSS `lang="en"` / `lang="pt"`.

### Arquivos alterados

- `_config.yml`
- `_layouts/default.html`
- `index.md`
- `assets/css/style.css`
- `docs/wiki/sessions/session-log.md`
- `docs/wiki/decisions/decisions.md`

### Decisões

- Idioma principal do site: **Inglês (`en`)**.
- Alternância de idioma instantânea sem recarregar a página, controlada por CSS `[lang="..."]` e botões `EN | PT`.
- O cliente pode fornecer os rascunhos em Português e o site exibirá tanto em EN quanto em PT.

### Pendências

- Preencher brief e posicionamento na wiki com informações reais do editor.
- Substituir placeholders bilingues do site pelo conteúdo definitivo em Inglês e Português.

### Próximo passo

- Preencher brief e posicionamento na wiki.

---

## 2026-07-28 — Criação do Plano de Preenchimento do Portfolio

### Feito

- Criado o plano detalhado de preenchimento do portfolio em `docs/wiki/portfolio-fill-plan.md`.
- Definidos objetivos, ordem de preenchimento (7 etapas), regras de integridade de dados e resultado esperado para a v1 do site.

### Arquivos alterados

- `docs/wiki/portfolio-fill-plan.md` (criado)
- `docs/wiki/sessions/session-log.md`

### Decisões

- Seguir rigorosamente o fluxo de preenchimento priorizando clareza, clareza visual e sem inventar dados/métricas/cases.

### Pendências

- Iniciar a etapa 1 (coleta de posicionamento e brief).

### Próximo passo

- Iniciar Bloco 2 — Materiais Visuais.

---

## 2026-07-28 — Bloco 1 (Posicionamento) Concluído

### Feito

- Definido o nome profissional do editor: **Lucas Jimenez**.
- Definido o posicionamento bilíngue de alta retenção para games (Vídeos longos, Highlights, VODs, Shorts, TikToks e Reels em qualquer estilo/gênero).
- Aplicadas as alterações no `index.md`, `_layouts/default.html` e `_config.yml`.
- Atualizados `docs/wiki/brief.md` e `docs/wiki/positioning.md`.

### Arquivos alterados

- `index.md`
- `_layouts/default.html`
- `_config.yml`
- `docs/wiki/brief.md`
- `docs/wiki/positioning.md`
- `docs/wiki/sessions/session-log.md`

### Decisões

- Posicionamento focado em edição para criadores de games de múltiplos formatos e gêneros.

### Pendências

- Iniciar Bloco 2 — Materiais Visuais.

### Próximo passo

- Coletar informações do Bloco 2 (Showreel, Cases e Vídeos).



