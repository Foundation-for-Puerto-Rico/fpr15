# Iniciativas FPR · 15 aniversario

Página pública con las 14 iniciativas que FPR presenta en su 15 aniversario (9 de diciembre de 2026). Cada pancarta lleva un QR que abre la página en la sección de su iniciativa.

- Sitio: https://foundation-for-puerto-rico.github.io/fpr15/
- Enlace de cada QR: `https://foundation-for-puerto-rico.github.io/fpr15/#<id>`

## Identificadores de las secciones

Los QR impresos usan estos identificadores. No los cambies después de imprimir: un QR con un identificador que ya no existe abre la página al principio.

| # | Iniciativa | `id` |
|---|---|---|
| 1 | Ruta Patrimonial del Azúcar | `ruta-azucar` |
| 2 | Distrito Cultural de Humacao y Distrito Creativo de Luquillo | `humacao-luquillo` |
| 3 | Guía para reactivar activos patrimoniales (caso Central Roig) | `central-roig` |
| 4 | Asset Watch PR (línea base) | `baseline` |
| 5 | ERSV | `ersv` |
| 6 | MaaS | `maas` |
| 7 | CDERE | `cdere` |
| 8 | Academias de Turismo del Este | `tourism-academy` |
| 9 | VEPM | `vepm` |
| 10 | Impacta PR | `voluntariado` |
| 11 | Foundation Fellows Program | `fellows` |
| 12 | PDFA | `pdfa` |
| 13 | Second Brain | `second-brain` |
| 14 | PR-MOS | `pr-mos` |

## Cómo editar el contenido

Todo el texto vive en `content.json`. Para cambiarlo desde GitHub:

1. Abre `content.json` y haz clic en el ícono del lápiz (**Edit this file**).
2. Cambia el texto entre comillas. Cada iniciativa tiene su versión en español (`_es`) y en inglés (`_en`).
3. Haz clic en **Commit changes**.

Diez iniciativas siguen el diseño de su pancarta (dBoard). Su texto está dentro de `"board"`, organizado en secciones (`sections`) y bloques (`blocks`) en el mismo orden que la pancarta. Dentro del texto, `**así**` pone negritas y `==así==` resalta en color.

La página se actualiza en uno o dos minutos. Si la página deja de cargar después de un cambio, el archivo tiene un error de formato, por lo general una coma o unas comillas de más o de menos. Revierte el último cambio desde el historial del archivo.

Las fotos están en `assets/img/`. Usa solo fotos con permiso de publicación y comprímelas a unos 1200 px de ancho.

## Ver la página en tu computadora

```bash
python3 -m http.server 8615
```

Luego abre http://localhost:8615.
