# 🌌 Aetheris Multiverse Browser

![Aetheris Banner](https://img.shields.io/badge/AETHERIS-NEXUS_COMMAND-00e5ff?style=for-the-badge&logo=airplayvideo&logoColor=white) ![Architecture](https://img.shields.io/badge/ARCH-WebView2%20%7C%20MAUI-ff003c?style=for-the-badge) ![Size](https://img.shields.io/badge/SIZE-Ultra%20Ligero-76ff03?style=for-the-badge) ![Status](https://img.shields.io/badge/STATUS-Ready-blue?style=for-the-badge)

**Aetheris** es un navegador web de nueva generación diseñado desde cero con dos objetivos principales en mente: **rendimiento absoluto** y **privacidad extrema**. Alejándose del código inflado ("bloatware") de los navegadores basados directamente en Chromium o Firefox, Aetheris funciona como un contenedor nativo ultraligero que aprovecha el motor de la plataforma (WebView2 en Windows, WebKit/Blink en Android vía MAUI), eliminando todo el telemetría y procesos en segundo plano innecesarios.

El resultado es un navegador que consume **fracciones de la RAM y CPU** en comparación con los líderes del mercado, ofreciendo una experiencia visual y funcional con temática *Cyberpunk / Sci-Fi*.

---

## 🚀 ¿Por qué Aetheris es tan rápido y liviano?

Los navegadores convencionales (Chrome, Edge, Brave, etc.) ejecutan decenas de subprocesos: actualizadores globales, reportes de telemetría (crash reports, user data), motores de extensiones pesados, y servicios de sincronización continua. 

Aetheris utiliza una **arquitectura de envoltura directa (Wrapper Architecture)**:
1. **Zero-Telemetry:** Ningún dato se envía a nuestros servidores. No hay tracking interno.
2. **Native Rendering Integration:** En lugar de compilar su propio motor enorme, Aetheris usa **WebView2 (Windows)** y **Android Native WebView** con aceleración por hardware forzada, garantizando el mejor rendimiento del sistema operativo en su nivel más bajo.
3. **Escudo Titanium Integrado:** En lugar de depender de extensiones lentas de JavaScript para bloquear anuncios (como AdBlock), Aetheris intercepta peticiones a nivel de red (Network Request Interception) basándose en una lista ultraligera en memoria. Las peticiones de rastreadores se destruyen milisegundos antes de que el motor de renderizado intente procesarlas.
4. **Watchdog Dinámico:** Aetheris congela pestañas en segundo plano y suspende motores de JavaScript de webs maliciosas o exigentes, rescatando la vida de tu batería y CPU.

---

## 🛡️ Características Principales

### 💻 Aetheris Desktop (Windows EXE)
* **Modo Ventana Persistente**: Aetheris recuerda sin fallos exactamente dónde y a qué tamaño cerraste el navegador.
* **Red Tor Integrada (Proxy SOCKS5)**: Navega por dominios `.onion` y disfraza tu IP real activando Tor con un solo clic en tiempo real.
* **Escudo de Privacidad Nivel 3**: Bloqueo estricto de iframes ocultos, port-scanning local y websockets intrusivos, WebRTC limit, lectura de portapapeles y Battery API.
* **UI Inmersiva HTML5**: En la versión de PC, toda la interfaz está dibujada como un canvas web interactivo hiperfluido, logrando tiempos de apertura y redibujo instantáneos.
* **Gestor de Recursos Inteligente (Tab Modes)**: Configura las pestañas inactivas en "Modo Ahorro" o "Hibernación Absoluta".

### 📱 Aetheris Mobile (Android APK)
*   **MAUI Hardware-Accelerated:** Escrito en .NET MAUI e Inyectado con optimizaciones específicas de hardware como `DomStorage`, `RenderPriority.High`, y aceleración por GPU.
*   **Overlays Multimodales (Fullscreen UI):** Interfaz adaptada al modo móvil con animaciones ultrarrápidas y sin bordes.
*   **Desktop Switcher (Modo PC Real):** Cambia resoluciones internas de vista con un solo botón en la capa nativa para forzar sitios a renderizar su layout original de ordenadores.
*   **Paridad de Ajustes (Settings Parity):** Toda la configuración de privacidad y personalización de la experiencia de la versión Windows está disponible en tu teléfono móvil. Funcina con la misma filosofía: sin telemetría, velocidad absoluta.

---

## 🎨 Sistema Visual y Estético

Aetheris no se limita a funcionar mejor, también se **ve mejor**. Dispone de:
- Animaciones "Swoop" y Blur en tiempo real.
- Esquema de colores `Neon` modificable desde Ajustes (Cyan, Magenta, Gold, etc).
- Interfaces sin bordes y controles táctiles pensados para un acceso intuitivo de pulgar único en dispositivos móviles.

---

## 🚀 Instalación y Uso

Aetheris está distribuido como aplicaciones precompiladas listas para usar, sin necesidad de instalación compleja ni dependencias de terceros.

### 💻 Para Windows (Aetheris.exe)
1. Ve a la pestaña **`Releases`** en este repositorio de GitHub.
2. Descarga el archivo **`Aetheris.exe`**.
3. (Opcional) Crea un acceso directo en tu escritorio. Es **portable**: puedes guardarlo en un pendrive USB y llevar tu historial, pestañas y datos en su propia carpeta `Aetheris_Storage` cifrada y generada al vuelo.

### 📱 Para Android (Aetheris_Movil.apk)
1. Descarga el archivo **`Aetheris_Movil.apk`** desde **`Releases`**.
2. Dale a tu teléfono permiso para instalar "Aplicaciones de orígenes desconocidos".
3. Instala la aplicación y disfruta del navegador más rápido del mercado.

*(Nota: Aetheris es un proyecto independiente centrado en la velocidad absoluta. ¡Ningún dato es recopilado!)*

> Desarrollado con ❤️ y alto voltaje por [Undfe]
