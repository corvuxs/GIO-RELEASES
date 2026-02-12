<div align="center">

# 🤖 GIO v3.0 - Distribution & Update Center

**El Corazón de Distribución para el Ecosistema GIO**

[![Version](https://img.shields.io/badge/Version-3.7.2-blue?style=for-the-badge&logo=github)](https://github.com/corvuxs/GIO-RELEASES/releases)
[![Sentinel](https://img.shields.io/badge/Sentinel-Active-orange?style=for-the-badge&logo=target)](https://github.com/corvuxs/GIO-RELEASES)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-brightgreen?style=for-the-badge)](https://github.com/corvuxs/GIO-RELEASES/releases)

---

**GIO v3.0** es una plataforma de gestión de operaciones diseñada para **TARGET INC**. Este repositorio actúa como el nodo central de distribución, donde el motor **Sentinel** rastrea y despliega las últimas actualizaciones para todo el equipo operativo.

</div>

---

## 🚀 Centro de Descargas

Para garantizar que siempre trabajes con las últimas herramientas y mejoras de IA, descarga el instalador correspondiente a tu sistema operativo.

### 💻 Instaladores Oficiales

| Plataforma | Tipo de Archivo | Instrucciones de Instalación |
| :--- | :---: | :--- |
| **Windows** | `.msi` / `.exe` | Descarga el ejecutable y sigue los pasos del asistente de instalación. |
| **macOS** | `.dmg` | Abre la imagen y arrastra el icono de **GIO** a tu carpeta de Aplicaciones. |
| **Linux (Ubuntu)** | `.deb` | Instala desde la terminal: `sudo dpkg -i gio_v3.7.2_amd64.deb` |

---

## 🕵️‍♂️ Sistema Sentinel (Autogestión de Versiones)

A diferencia de los sistemas tradicionales, **GIO v3.0** utiliza una arquitectura de actualización personalizada que elimina errores de firmas digitales y garantiza autonomía total.

* **Detección Automática:** Tu aplicación instalada consulta este repositorio cada 60 minutos.
* **Smart UI:** Si hay una versión nueva, verás un modal Crystal UI con las notas de actualización.
* **Descarga Directa:** Sentinel identifica tu OS y te entrega el link exacto del instalador.

[Image of a software architecture diagram showing a centralized update server distributing version metadata to client applications]

---

## 🛠️ Guía para Administradores

Para desplegar una nueva versión y que Sentinel la reconozca mundialmente:

1. **Build:** Genera los archivos en local (`npm run tauri build`).
2. **Release:** Crea un nuevo Release en este repo con el tag de versión (ej: `v3.7.2`).
3. **Upload:** Sube los archivos `.msi`, `.dmg` y `.deb` como assets del release.
4. **Sync:** Ve al Dashboard de GIO > Configuración > Versión y pulsa **"Sincronizar"**.

---

## 📋 Registro de Cambios (v3.7.2)

* **Libertad de Firmware:** Des
