# blog-assets

Imágenes y recursos estáticos de [mikisbell.blogspot.com](https://mikisbell.blogspot.com/).

Se sirven por GitHub Pages para que Blogger pueda generar la miniatura de cada
entrada (`media$thumbnail`) y la imagen de vista previa al compartir (`og:image`).
Antes iban embebidas como data URI base64 dentro del HTML del post: eso impedía
ambas cosas y hacía que cada entrada pesara ~800 KB.

```
images/<slug>-<n>.png   → https://mikisbell.github.io/blog-assets/images/<slug>-<n>.png
```

Los gráficos son reproducibles: sus scripts generadores viven en el repositorio
de la fábrica, en `_blog/tools/graficos/`.

Autor: Miguel A. Rivera Ospina · [ORCID 0009-0006-0354-0346](https://orcid.org/0009-0006-0354-0346)
