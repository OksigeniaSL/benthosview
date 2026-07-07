# BenthosView

**Georeferenced survey video, turned into a map you can explore.**

BenthosView links moving-camera footage to *where* it was filmed. An ROV dive, a diver
transect, a drone corridor — the video plays in sync with its track on the map, the 3D
terrain underneath, the depth and telemetry profile, and the annotations of the people
who know how to read them. A recording stops being a flat timeline and becomes a *place*
you can navigate.

It was born underwater — marine biology and benthic habitat mapping in the Canary
Islands — and it is built to reach the surface too: coastal and UAV/drone corridors,
infrastructure inspection, any survey where a camera moves through space and *location*
is the point.

Built by **[Oksigenia SL](https://oksigenia.com)**.

> **This repository is the free viewer.** The engine that *creates* the content —
> ingest, georeferencing, user roles, GIS export, 3D from real elevation, cloud video —
> is the **Benthos platform**, and that is the product. You can hand anyone the viewer;
> the value is in generating what it shows. [Jump to the platform ↓](#the-benthos-platform)

---

## What the viewer does

- 🎥 **Video in sync with telemetry** — footage and position move together, both ways:
  scrub the video and the marker follows; click the map or the depth profile and the
  video jumps there.
- 🗺️ **2D track** over real cartography — satellite, bathymetry, orthophotos, charts.
- ⛰️ **3D seafloor terrain** — orbit it, exaggerate the relief, move the sun; compare
  several dives side by side.
- 📍 **Georeferenced annotations** — points, segments and areas: species, habitats,
  substrates, anything worth marking.
- 📈 **Depth and navigation profile** — heading, depth, temperature and more, along the
  whole run.
- 📷 **Frame and 3D-view capture** with their coordinates and data attached.

## Works offline, everywhere — BenthosView Lite

The **view-only desktop app** (Windows · macOS · Linux) reads dives from a local folder
and runs **fully offline**. It is the deliverable you put in a client's hands: give them
the viewer plus a content folder and they explore their surveys with nothing online
required — no account, no server, no connection.

### Download

Installers are in **[Releases](https://github.com/OksigeniaSL/benthosview/releases)** —
Windows (`.exe` / `.msi`), macOS (`.dmg`), Linux (`.AppImage` / `.deb`).

> On Linux, H.264 playback needs the GStreamer codecs (`gstreamer1.0-libav`,
> `gstreamer1.0-plugins-good`); the `.deb` package already declares them.

## Speaks your language

Full interface in **six languages** — English, Spanish, Portuguese, French, German and
Italian — with an in-house i18n engine and per-user / per-install selection. Scientific
vocabulary is deliberately kept untranslated.

---

## The Benthos platform

The viewer above is the window. **Benthos** is the workshop behind it — the product
institutions and companies license to *produce* georeferenced surveys, not just look at
them. It is self-hosted, one deployment per organization, and it stays yours: your data,
your infrastructure, your rules.

### Turn raw footage into a georeferenced survey
- **Ingest & georeferencing** — match video to navigation telemetry, build the track,
  align every frame to a real-world position.
- **3D terrain from real elevation** — reconstruct the seafloor (or terrain) from actual
  DEM data, not a decorative surface.
- **Annotation workflows** — points, segments and areas with structured attributes;
  species, habitats and substrates recorded where they were seen, ready to export as data.
- **Multi-window 3D comparison** — study several dives at once, side by side.

### Built for teams, built to interoperate
- **User roles & access control** — administrators, editors and viewers, with
  per-deployment configuration; custom roles on request. Sensitive footage stays behind
  authentication.
- **Export to any open format** — GeoJSON, GeoPackage, CSV, KML, Shapefile, with proper
  CRS/EPSG handling. On the roadmap: GeoTIFF with real DEM, OGC **WFS/WMS** services,
  **Darwin Core / OBIS** for biodiversity, and INSPIRE.
- **Connect straight from QGIS *and* ArcGIS** — Benthos can serve an **OGC API – Features**
  endpoint, so tracks and annotations open natively in the two leading GIS suites (one
  free and open, one proprietary), with live queries, styling and analysis on top — no
  manual file shuffling.
- **Multi-cloud video** — storage and streaming across Backblaze B2, Bunny and
  Cloudflare; choose per deployment, with no single-vendor lock-in.
- **Accessibility & branding** — accessibility controls for public-sector requirements,
  and per-deployment branding, language and map layers.

### Deliver it, offline
When the survey is done, Benthos exports the **BenthosView Lite** package above — the
viewer plus a content folder — so the final client explores the work with no server and
no connection. That offline deliverable is generated *from* the platform.

## Where it is going

The goal is a **living map of the seafloor** — and beyond: stop *adding* isolated dives
and start *composing* them, using AI and active learning to reconstruct the parts no
camera has reached yet. Underwater is the origin; the same idea holds anywhere a moving
camera meets a map.

---

## Work with us

Benthos is built to order for each organization — marine research institutes,
bathymetric and bionomic mapping, environmental monitoring, coastal and drone survey.
If you produce georeferenced video and need to turn it into data people can read,
explore and share:

- 🌐 **[oksigenia.com](https://oksigenia.com)**
- ✉️ **[info@oksigenia.com](mailto:info@oksigenia.com)**
- 💼 Oksigenia SL — infrastructure, self-hosted AI and data sovereignty.

*Get in touch to see the full platform, discuss a deployment, or request a demo.*

## About

Built by **[Oksigenia SL](https://oksigenia.com)**. Benthos is developed with, and for,
the people who actually read the seafloor.

## License

**© 2026 Oksigenia SL — all rights reserved.** BenthosView is proprietary software. The
binaries here are published free of charge for viewing Benthos content, and may not be
redistributed, modified or reverse-engineered. See **[LICENSE](LICENSE)**. The platform
source is kept private.
