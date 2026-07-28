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

### Pendências

- Ativar GitHub Pages no repositório (Settings → Pages ou `gh` CLI).
- Instalar Ruby + Bundler para preview local.
- Preencher placeholders com conteúdo final.
- Remover pasta legada `portfolio-video-editor-wiki/` (opcional).

### Próximo passo

- Ativar GitHub Pages e validar URL publicada.
- Preencher brief e posicionamento na wiki.
- Substituir placeholders do site pelo conteúdo real.
