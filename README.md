<div align="center">
  <img src="https://raw.githubusercontent.com/HeberonMC/HeberonMC/main/assets/logo.png" width="120" alt="" />

  # Heleon Studio

  Launcher de Minecraft para las series de Heleon Studio.

  [![Descargar](https://img.shields.io/github/v/release/HeberonMC/Heleon-Studio?label=Descargar&style=for-the-badge&color=60a8f0&labelColor=0d1117)](https://github.com/HeberonMC/Heleon-Studio/releases/latest)
  ![Windows 10/11](https://img.shields.io/badge/Windows_10%2F11-0d1117?style=for-the-badge&logo=windows&logoColor=60a8f0)
</div>

## Descripción

Heleon Studio instala y abre la serie correcta (versión de Minecraft, mod loader y mods)
sin que tengas que configurar nada. Tú inicias sesión y pulsas **JUGAR**.

## Características

- 🎮 Instalación automática de Java, Minecraft, mod loader y mods.
- 🔄 Se actualiza solo: el launcher y los mods de cada serie.
- 📰 Noticias de las series dentro del launcher.
- 🔐 Inicio de sesión con tu cuenta de Microsoft.
- 🔒 Series privadas: acceso por invitación o con código canjeable.
- 💬 Estado en Discord mientras juegas.

## Capturas

<!-- Sube tus capturas a docs/ (o cambia estas rutas) -->
| Inicio | Series | Ajustes |
|---|---|---|
| ![Inicio](docs/captura-inicio.png) | ![Series](docs/captura-series.png) | ![Ajustes](docs/captura-ajustes.png) |

## Cómo usarlo

1. Entra en [la última versión](https://github.com/HeberonMC/Heleon-Studio/releases/latest) y
   descarga **`HeleonStudio_x.y.z_x64-setup.exe`** (en *Assets*).
2. Ábrelo. Windows puede mostrar **«Windows protegió su PC»**: es normal en programas
   pequeños que no tienen un certificado de Microsoft de pago.
   - Pulsa **Más información**.
   - Pulsa **Ejecutar de todas formas**.
3. Sigue el instalador: no pide permisos de administrador y tarda unos segundos.
4. Abre **Heleon Studio** desde el escritorio o el menú Inicio e inicia sesión con tu
   cuenta de Microsoft (la misma de Minecraft: Java Edition).
5. Pulsa **JUGAR**. La primera vez descarga Java, Minecraft y los mods (unos minutos);
   después abre al momento.

El aviso de Windows solo sale la primera vez: las actualizaciones del launcher se
instalan solas desde el propio programa.

### Requisitos

- Windows 10 u 11 de 64 bits.
- Una cuenta de Microsoft con **Minecraft: Java Edition** comprado.
- Unos 2 GB libres en disco.

## Qué hay en este repositorio

- `manifest.json`: versión de Minecraft, mod loader, mods y noticias que instala el launcher.
- `manifest-files/`: archivos de configuración que se copian en la carpeta del juego.
- *Releases*: el instalador y `latest.json` para las actualizaciones automáticas.

---

<p align="center"><sub>by Heleon ST</sub></p>
