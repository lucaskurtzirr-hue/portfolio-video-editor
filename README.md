# Portfolio Video Editor

Landing page estática para portfolio de editor de vídeo freelancer focado em games.

Stack: **Jekyll puro**, compatível com GitHub Pages, sem frameworks extras.

## Estrutura

```
.
├── _config.yml          # Configuração Jekyll / GitHub Pages
├── _layouts/
│   └── default.html     # Layout base
├── index.md             # Landing page (seções em âncoras)
├── assets/css/style.css # Estilo sóbrio e responsivo
└── docs/wiki/           # Wiki do projeto (não publicada no site)
```

## Editar conteúdo

1. Textos e seções: `index.md`
2. Título, URL e baseurl: `_config.yml`
3. Estilo: `assets/css/style.css`
4. Planejamento e cases: `docs/wiki/`

Placeholders estão marcados como `[Placeholder — ...]`. Substitua quando o conteúdo final estiver pronto.

## Preview local

Requisitos: Ruby + Bundler + Jekyll (via gem `github-pages`).

### Windows (instalação)

1. Instale Ruby: https://rubyinstaller.org/ (marque MSYS2/devkit na instalação)
2. No terminal:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Abra http://127.0.0.1:4000/portfolio-video-editor/

> Se `baseurl` estiver vazio durante testes locais isolados, use http://127.0.0.1:4000/

### Comandos úteis

```bash
bundle exec jekyll serve          # preview com rebuild
bundle exec jekyll build          # gera _site/ para inspeção
bundle exec jekyll serve --livereload
```

## Publicar no GitHub Pages

### Via interface (recomendado se `gh` não estiver instalado)

1. Repositório no GitHub → **Settings** → **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` / `(root)`
4. Salvar e aguardar o build (Actions ou Pages tab)

URL esperada (project site):

https://lucaskurtzirr-hue.github.io/portfolio-video-editor/

### Via GitHub CLI (opcional)

Requer [GitHub CLI](https://cli.github.com/) instalado e autenticado:

```bash
gh auth login
gh api repos/lucaskurtzirr-hue/portfolio-video-editor/pages -X POST -f source[branch]=main -f source[path]=/
```

Ou:

```bash
gh api repos/lucaskurtzirr-hue/portfolio-video-editor/pages -X PUT -f build_type=legacy -f source[branch]=main -f source[path]=/
```

Verificar status:

```bash
gh api repos/lucaskurtzirr-hue/portfolio-video-editor/pages
```

## Repo privado + GitHub Pages (plano gratuito)

No plano **GitHub Free**, GitHub Pages funciona em repositórios **públicos**.

Para publicar Pages a partir de repositório **privado**, é necessário plano pago (**GitHub Pro** ou superior).

Alternativas gratuitas com repo privado:

- Deixar o repo **público** (código e wiki ficam visíveis; comum para portfolios)
- Usar outro host estático (Netlify, Cloudflare Pages) conectado ao repo privado

## Wiki

Documentação interna em `docs/wiki/`. Não entra no build do site (excluída em `_config.yml`).
