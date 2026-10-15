# Marcas Diesel — muestra de catálogo

Web de una sola página para **Marcas Diesel**, concesionaria de camiones y vans Kia y Hyundai en
San Pedro Sula, Honduras. Es una **muestra para el dueño**: no se publica hasta que la apruebe
(`noindex, nofollow`).

Para verla: abre `index.html` en el navegador.

---

## Datos usados (y de dónde salieron)

| Dato | Fuente |
|---|---|
| «Tu socio para el trabajo duro», camiones y vans Kia y Hyundai | Bio de Instagram y TikTok |
| Crédito inmediato · Financiamiento directo con nosotros | Textos de los reels |
| WhatsApp / teléfono 3200-3096 | Bio de Instagram y Facebook, textos de los reels |
| Dirección del plantel y punto de Google Maps | Proporcionados por el cliente |
| Logo | Tarjeta final de los reels (`assets/logo-marcas-diesel.*`) |
| Unidades, años y transmisión | Texto en pantalla de cada reel de instagram.com/marcasdiesel/reels |

## Unidades y foto de origen

| Tarjeta | Reel de Instagram | Foto |
|---|---|---|
| Hyundai Porter 2018 · Automático | DdeP8pfOOsd | `porter-2018-automatico.webp` |
| Kia Bongo 2018 doble cabina · Automático | Dd1fp-7OcB0 | `bongo-2018-doble-cabina-automatico.webp` |
| Kia Bongo 2018 cabina y media · Automático | DbEh83KuBBA | `bongo-2018-cabina-y-media-automatico.webp` |
| Kia Bongo 2018 · Mecánico (azul) | DbGzt8RhpWZ | `bongo-2018-mecanico.webp` |
| Kia Bongo 2019 cajón seco · Automático | DbEm6DHOQeX | `bongo-2019-cajon-seco-automatico.webp` |
| Kia Bongo 2015 cajón · Mecánico | DbExV7ZueAF | `bongo-2015-cajon-mecanico.webp` |
| Hyundai Porter cajón seco · Automático | DZyDDmTh0sD | `porter-cajon-seco-automatico.webp` |
| Hyundai Porter refrigerado | Dclg5RROKPs | `porter-refrigerado.webp` |
| Hyundai Starex 2014 · Automática | DbwCvWVBkCC | `starex-2014-automatica.webp` |
| Hyundai Starex 2017 · Automática · 15 pasajeros | DbEqXJdOSvE | `starex-2017-automatica-15-pasajeros.webp` |
| Van Panel de Carga 2018 · Mecánica | DdFaHnhuvj9 | `van-panel-carga-2018-mecanica.webp` (foto enviada por el cliente) |
| Van Semi Panel | DeeuREEOGx4 | `van-semi-panel.webp` (foto enviada por el cliente) |

Las fotos son fotogramas recortados de los reels (solo recorte, escala y ajuste ligero de
contraste y nitidez). El video original deja ~536×402 px útiles, así que están ampliadas a 1200×900.

## Filtros del catálogo

El catálogo se arma desde la lista `UNITS` dentro del script de `index.html` (una entrada por unidad:
nombre, marca, año, transmisión, carrocería, cabina, precio y foto). Filtros: búsqueda, presupuesto,
marca, transmisión, año, carrocería, cabina, tipo (camión/van) y orden. La búsqueda queda en la URL,
así que se puede compartir un enlace ya filtrado.

**Precios:** todos están en `precio: null`. Al poner el precio en lempiras (por ejemplo
`precio: 450000`), el filtro de presupuesto empieza a esconder lo que no alcanza, aparece el precio
en la tarjeta y se habilita ordenar por precio. Mientras no haya precios, el presupuesto se envía por
WhatsApp junto con la búsqueda.

## Pendiente de confirmar con el dueño

- Precios, horario de atención y requisitos de crédito.
- Qué unidades siguen disponibles (algunos reels son de junio y julio).
- Año y transmisión de la Van Semi Panel y del camión cajón seco.
