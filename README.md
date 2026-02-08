# Traducciones (Jekyll + GitHub Pages)

Blog personal de traducciones/notas.

## Publicar en GitHub Pages
- En GitHub: **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: `main` / folder: `/ (root)`

> Si es un repo de proyecto, revisa `baseurl` en `_config.yml`.

## Ejecutar en local (macOS)
1. Instala Ruby (si no lo tienes): `brew install ruby`
2. En la raíz del repo:
   - `bundle install`
   - `bundle exec jekyll serve`
3. Abre `http://127.0.0.1:4000/Traducciones/` (o el `baseurl` que uses)
