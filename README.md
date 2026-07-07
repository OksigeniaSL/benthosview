# BenthosView

**Visor de fotogrametría submarina georreferenciada.** Reúne en un solo sitio el
vídeo de la inmersión, el recorrido sobre el mapa, el relieve del fondo en 3D y las
anotaciones de quien sabe leerlas. Nace del amor al mar, no del miedo: una ventana
para mirar el fondo de cerca y entenderlo mejor.

Desarrollado por **[Oksigenia SL](https://oksigenia.com)**.

---

## Qué hace

- 🎥 **Vídeo ROV** sincronizado con la telemetría de la inmersión.
- 🗺️ **Recorrido 2D** sobre cartografía (satélite, batimetría, ortofotos).
- ⛰️ **Terreno 3D** del fondo, orbitable, con exageración vertical y sol orientable.
- 📍 **Anotaciones** georreferenciadas (puntos, tramos y áreas): especies, hábitats, sustratos.
- 📈 **Perfil de profundidad** y datos de navegación (rumbo, profundidad, temperatura…).
- 📷 **Captura** de fotogramas y vistas 3D con sus datos.
- 🌐 **Multi-idioma** (ES · EN · PT · FR · DE · IT).

## BenthosView (Lite) — entregable offline

La aplicación de escritorio **solo-ver** (Windows · macOS · Linux) que lee las
inmersiones de una carpeta local y funciona **sin conexión**. Pensada para entregar
el trabajo al cliente final: se le da el visor + una carpeta de contenido y ve sus
inmersiones sin depender de nada en línea.

### Descargar

Los instaladores están en **[Releases](https://github.com/OksigeniaSL/benthosview/releases)**
— Windows (`.exe` / `.msi`), macOS (`.dmg`), Linux (`.AppImage` / `.deb`).

> En Linux, la reproducción de vídeo H.264 necesita los códecs de GStreamer
> (`gstreamer1.0-libav`, `gstreamer1.0-plugins-good`); el paquete `.deb` ya los declara.

---

## Para quién

Instituciones y empresas de biología marina, cartografía bionómica y monitorización
del fondo. Sustituye el flujo de VLC + hoja de cálculo + SIG por una herramienta que
reúne vídeo, georreferencia, relieve 3D y el entregable en un solo lugar.

## Estado

En desarrollo activo. El motor completo (ingesta, exportación SIG, 3D con DEM real,
capas cartográficas…) es un producto mayor; este repositorio publica el **visor de
escritorio** y su distribución.

---

© Oksigenia SL — software propietario. Aquí se publican los binarios; el código
fuente se mantiene privado.
