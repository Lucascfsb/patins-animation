# Snitap Patins — Animação & Layout

Pequeno projeto de layout e animação de uma landing page de patins.

## Visualizar
- Abra [index.html](index.html) no navegador
- Ou rode um servidor local:
```sh
python -m http.server 8000
# ou
npx http-server
```

## Estrutura do repositório
- [index.html](index.html)
- Styles:
  - [styles/index.css](styles/index.css)
  - [styles/global.css](styles/global.css) — contém [`:root`](styles/global.css)
  - [styles/header.css](styles/header.css) — contém [`header.top`](styles/header.css)
  - [styles/hero.css](styles/hero.css) — animações e [`section.hero`](styles/hero.css)
  - [styles/banner.css](styles/banner.css) — contém [`.banner`](styles/banner.css)
  - [styles/gallery.css](styles/gallery.css) — contém [`.gallery`](styles/gallery.css)
  - [styles/footer.css](styles/footer.css) — contém [`footer`](styles/footer.css)
- Assets:
  - [assets/](assets/)
  - [assets/hero/](assets/hero/)
  - [assets/icons/](assets/icons/)
  - [assets/images/](assets/images/)

## Notas
- Os estilos principais são importados em [styles/index.css](styles/index.css).
- As animações principais estão em [styles/hero.css](styles/hero.css) e [styles/banner.css](styles/banner.css).

## Licença
Projeto para fins de estudo. Sinta-se livre para adaptar.