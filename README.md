# Performante — Releases

**Repositorio público de instaladores** de **Performante** (aplicación de escritorio para pruebas de carga con [k6](https://k6.io/)). Aquí **solo se publican artefactos** listos para descargar; el **código fuente no está en este repo**.

---

## Descarga

| Enlace | Descripción |
|--------|-------------|
| [**Último release**](https://github.com/LucasYoris/Performante-releases/releases/latest) | Siempre apunta a la versión más reciente |
| [Todos los releases](https://github.com/LucasYoris/Performante-releases/releases) | Historial de versiones |

En cada release encontrarás, para **Windows**:

- **Instalador NSIS** (`.exe`) — instalación estándar con accesos directos y desinstalador.
- **Versión portable** (`.exe`) — ejecutable sin instalador; útil para llevar en un USB o entornos restringidos.

> Los nombres exactos de los ficheros siguen el patrón de **electron-builder** (p. ej. `Performante Setup x.y.z.exe` y `Performante x.y.z.exe` portable). Revisa los activos del release concreto.

---

## Requisitos

- **SO:** Windows (amd64), según los builds publicados.
- **k6:** En el instalador/portable de Performante para Windows suele ir **incluida** una versión empaquetada de k6 compatible con la app; para detalles de versión, consulta las notas del release o la documentación del producto.

---

## Qué es Performante

- Constructor visual de pruebas de carga inspirado en flujos tipo Postman/Grafana.
- Generación y ejecución de scripts **k6**.
- Workspaces, variables, importación Postman/cURL, informe k6 embebido, resúmenes con IA (Gemini), opcionalmente cuenta **Supabase**.

Sitio y más información: **[performante.vercel.app](https://performante.vercel.app)** (precios, producto, etc.).

---

## Seguridad y confianza

- Descarga siempre desde **este repositorio** o desde enlaces oficiales del proyecto.
- Si el binario está **firmado** (según el pipeline de release), Windows mostrará el publicador en las propiedades del ejecutable.
- Este repo **no acepta** pull requests con código de la app; los cambios se construyen desde el repositorio privado de desarrollo y el CI publica aquí.

---

## Soporte

- Incidencias o preguntas sobre **instalación y releases**: usa los **Issues** de este repositorio si están habilitados, o el canal que indique el sitio web del producto.
- Para **bugs de la aplicación** o funcionalidad, sigue el proceso de soporte que enlacen desde el sitio oficial.

---

## English (short)

This **public repository** hosts **Windows installers** (NSIS setup + portable) for **Performante**, a desktop k6 load-testing app. **Source code is not published here.** Download the [**latest release**](https://github.com/LucasYoris/Performante-releases/releases/latest). Product info: [performante.vercel.app](https://performante.vercel.app).

---

## Licencia

El software distribuido en los releases se ofrece bajo los términos indicados en el propio instalador y documentación del producto (p. ej. **MIT**, según el proyecto principal).
