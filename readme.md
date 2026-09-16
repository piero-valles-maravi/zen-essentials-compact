<div align="center">

![Zen Essentials Compact](assets/banner.svg)

# Zen Essentials Compact

**Ajusta el tamaño de los iconos de los Essentials de Zen y el espacio a su alrededor, para una rejilla más compacta.**

![version](https://img.shields.io/badge/versión-1.0.0-0F766E)
![Zen Browser](https://img.shields.io/badge/Zen-Browser-1E3A8A)
![Sine](https://img.shields.io/badge/Sine-mod-14B8A6)
![CSS](https://img.shields.io/badge/solo-CSS-38BDF8)
![license](https://img.shields.io/badge/licencia-MIT-3DA639)

</div>

---

## ✨ ¿Qué hace?

Si vas agregando muchos Essentials, la cuadrícula empieza a ocupar demasiado alto porque cada icono lleva bastante espacio a su alrededor. Este mod te deja **encoger ese espacio** y **ajustar el tamaño del icono**, así entran más iconos ocupando menos.

Es un mod **solo-CSS** (sin JavaScript) y todo se controla desde las preferencias del mod en **Sine** — no necesitas editar código.

![Los 4 controles](assets/controls.svg)

## 🎛️ Controles

| Preferencia | Por defecto | Qué hace |
|---|---|---|
| **Tamaño del icono** | `20` | Tamaño del favicon dentro de cada Essential (px). |
| **Tamaño del azulejo** | `40` | Tamaño del recuadro = el espacio alrededor del icono (px). Más pequeño → más compacto y caben más columnas por fila. |
| **Separación** | `4` | Espacio (gap) entre los recuadros (px). |
| **Redondeo** | `10` | Radio de las esquinas del azulejo (px). |

> Los valores son solo números (sin `px`); el mod les añade la unidad automáticamente.

**Preset bien compacto:** icono `20`, azulejo `36`, separación `3`, redondeo `9`.

---

## 📋 Requisitos

- **[Zen Browser](https://zen-browser.app/)** con la barra lateral vertical (predeterminada).
- **Sine** (gestor de mods de Zen) instalado.

## 🚀 Instalación

### Con Sine desde GitHub (recomendada)
1. Abre el gestor de mods de **Sine** en Zen.
2. Instala un mod desde un repositorio de GitHub con el identificador:
   ```
   piero-valles-maravi/zen-essentials-compact
   ```
3. Reinicia Zen si te lo pide.

### Manual
1. Descarga (**Code → Download ZIP**) o clona el repositorio.
2. Copia la carpeta en `<perfil de Zen>/chrome/sine-mods/zen-essentials-compact/`.
   > 💡 Encuentra tu perfil en `about:profiles` (*Root Directory*).
3. Reinicia Zen o recarga los mods desde Sine.

---

## 🖱️ Uso

Abre la configuración del mod en Sine y ajusta los 4 valores a tu gusto. Los cambios se aplican al recargar los estilos o al reiniciar Zen.

---

## 📝 Notas y compatibilidad

- Solo afecta a los **Essentials** (no a las pestañas fijadas normales ni a las comunes).
- La rejilla se ajusta con la barra lateral **expandida**, que es cuando los Essentials se ven en cuadrícula.
- **¿Usas también SuperPins?** Ese mod también puede modificar el ancho/gap de los Essentials. Si notas que algo se pisa, desactiva en SuperPins las opciones de *Essentials width / gap / grid*, o ajusta el espaciado solo desde uno de los dos mods.

---

## 👤 Autor · Licencia

Creado por **[@piero-valles-maravi](https://github.com/piero-valles-maravi)**.

Publicado bajo la licencia **[MIT](LICENSE)** — puedes usarlo, modificarlo y compartirlo libremente, conservando el aviso de copyright.
