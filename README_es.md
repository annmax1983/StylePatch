# StylePatch

[English](README.md) | [中文](README_zh.md) | [Español](README_es.md) | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

Extensión ligera para navegador que te permite personalizar al instante el color de fondo, el color de texto y el tamaño de fuente de cualquier página web.

> Compatible con navegadores Chromium · Manifest V3 · Sin seguimiento · Configuración por sitio

## Características

| Función | Descripción |
|---------|-------------|
| 🎨 Color de fondo y texto | Elige colores con el selector nativo o escribe códigos hexadecimales |
| 🔠 Ajuste de tamaño de fuente | Escala entre 80% y 150%, usa CSS zoom |
| 👁️ Temas preestablecidos | Claro, Protección ocular, Verde, Oscuro — un clic para aplicar |
| 🔄 Interruptor global | Activa/desactiva la extensión sin perder la configuración guardada |
| 🚫 Lista negra de sitios | Excluye sitios web específicos del estilizado |
| 💾 Configuración por sitio | Guarda estilos distintos para cada web, se restauran al volver |
| ⚡ Vista previa en tiempo real | Los cambios se aplican al instante, sin recargar la página |
| 🌍 Varios idiomas | Disponible en español, inglés, alemán, japonés, francés, chino |
| 🔒 Permisos mínimos | Solo `storage` + `host_permissions`, sin accesos innecesarios |
| 🏗️ Manifest V3 | Usa `chrome.scripting.insertCSS` — sin overhead de content scripts |

## Vista previa

<p align="center">
  <img src="screenshot/es.png" alt="Vista previa StylePatch" width="640">
</p>

## Navegadores compatibles

| Navegador | Estado |
|-----------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Otros navegadores Chromium | ✅ Funciona sin problemas |

## Instalación

1. Abre la página de extensiones de tu navegador:
   - Chrome: `chrome://extensions/`
   - Edge: `edge://extensions/`
2. Activa el **Modo desarrollador** (interruptor arriba a la derecha)
3. Pulsa **Cargar extensión descomprimida** y selecciona la carpeta del proyecto
4. Haz clic en el icono de StylePatch en la barra de herramientas para empezar

## Modo de uso

1. Haz clic en el icono de StylePatch de la barra de herramientas
2. Selecciona colores: usa el selector o escribe el código hexadecimal
3. Elige un preestablecido: Claro, Protección ocular, Verde u Oscuro
4. Ajusta el tamaño de fuente: mueve el control deslizante entre 80% y 150%
5. Guardar: pulsa **Aplicar y guardar** para conservar los estilos de este sitio
6. Restablecer: pulsa ↺ para volver al aspecto original de la web
7. Excluir: pulsa «Excluir este sitio» para bloquear un dominio
8. Interruptor global: usa el interruptor ON/OFF para desactivar temporalmente

## Privacidad

- Solo pide permisos `storage` + `host_permissions`, nada más
- No accede a tu historial, no te rastrea ni envía datos externos
- Todos tus ajustes se guardan solo en tu navegador local

## Licencia

Copyright © 2026 StylePatch. Todos los derechos reservados.

---

## ❤️ Apoya al desarrollador

Si StylePatch te resulta útil, ¡invítame a un café!

**[👉 Haz clic aquí para apoyar](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
