# 🎬 gifs-repo

Repositorio de GIFs técnicos — documentación visual de la infraestructura de **jkristen**.

## 📁 Estructura

```
├── infra/          # Topología de red, cluster Proxmox, flujos DNS
├── procesos/       # Walkthroughs animados (deploy LXC, backup NAS, etc.)
├── status/         # Indicadores de salud del cluster
├── clientes/       # Diagramas por cliente (Burgwagen, Cityssan, TiendaCars)
└── telegram/       # GIFs reactivos para comunicación en Telegram
```

## 📐 Convenciones

- **Formato:** GIF optimizado, <5MB para Telegram
- **Nomenclatura:** `{categoria}-{descripcion}-{fecha}.gif`
  - Ej: `infra-topologia-proxmox-2026-07.gif`
- **Optimización:** Usar `ffmpeg` para reducir peso antes de commit

## 🔗 Uso

Los GIFs se referencian directamente desde GitHub raw:

```
https://raw.githubusercontent.com/jkristen0416-prog/gifs-repo/main/infra/topologia-red.gif
```

## 🛠 Herramientas

- **Excalidraw** — diagramas hand-drawn
- **Manim** — animaciones narrativas
- **p5.js** — visualizaciones en tiempo real
- **ascii-video** — captura de terminal
- **ffmpeg** — optimización y conversión