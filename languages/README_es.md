# StylePatch

Manual de usuario oficial · Multi-idioma: [English](../README.md) | [中文](README_zh.md) | Español | [Deutsch](README_de.md) | [日本語](README_ja.md) | [Français](README_fr.md)

> Este documento es el manual de usuario oficial de StylePatch, accesible desde el botón "Manual de usuario" dentro del panel de la extensión.

Una extensión ligera para el navegador que te permite personalizar al instante el color de fondo, el color del texto, el color de los enlaces, la fuente, el efecto de filtro y el tamaño de fuente de cualquier página web para una experiencia de lectura más cómoda.

✅ Publicada oficialmente en Chrome y Edge Web Store · ✅ Cero rastreo, datos almacenados localmente (la sincronización en la nube es opcional y Premium) · ✅ Configuración independiente por sitio

---

## Lista de funcionalidades

### 🆓 Funcionalidades gratuitas

| Funcionalidad | Descripción |
|---------|-------------|
| 🎨 **Color de fondo, texto y enlaces** | Elige cualquier color con el selector nativo o escribe el código hex directamente; el color de los enlaces se ajusta automáticamente para legibilidad |
| 🔠 **Escala de tamaño de fuente** | Ajusta del 80% al 150% usando CSS zoom |
| 🔤 **Familia tipográfica** | Cambia la fuente de la página — fuentes del sistema o Google Fonts cargados desde la web (Roboto, Open Sans, Noto Sans SC…) |
| 🌗 **Filtros de color** | Modo escala de grises y tinte sepia cálido para una lectura más cómoda |
| 👁️ **Temas predefinidos** | Claro, Tono cálido, Verde, Oscuro, Sepia, Noche azul, Alto contraste — un clic para aplicar |
| 🧭 **Aviso de contraste** | Avisa cuando el color del texto o de los enlaces no alcanza los umbrales de contraste WCAG |
| 🔄 **Interruptor global** | Activa/desactiva la extensión globalmente sin perder la configuración |
| 🚫 **Lista negra de sitios** | Excluye sitios web específicos del estilizado |
| 💾 **Configuración por sitio** | Guarda estilos diferentes para distintos sitios web, se restauran automáticamente al volver a visitar (hasta 5 sitios gratis) |
| 📤 **Respaldo local** | Exporta todas las configuraciones a JSON y restáuralas después (la importación gratuita se limita a 5 sitios) |
| ⚡ **Vista previa en tiempo real** | Todos los cambios se aplican al instante mientras ajustas, sin recargar la página |
| 🌍 **Interfaz multi-idioma** | Soporta inglés, chino, español, alemán, japonés y francés |
| 🔒 **Permisos mínimos** | Solo `storage`, `scripting` + `host_permissions` — sin accesos innecesarios |
| 🏗️ **Manifest V3** | Construida sobre la arquitectura service worker de Manifest V3 |
| 🔄 **Restablecimiento con un clic** | Elimina la configuración del sitio; si existe un tema predeterminado, vuelve a él |

### ⭐ Funcionalidades Premium (requieren licencia)

| Funcionalidad | Descripción |
|---------|-------------|
| ♾️ **Configuraciones ilimitadas** | Guarda estilos para sitios web ilimitados (nivel gratuito: 5 sitios como máximo) |
| ☁️ **Sincronización en la nube** | Mantén sincronizados la configuración de sitios, la lista negra, el interruptor y el tema predeterminado entre perfiles de Chrome/Edge/Firefox con la misma cuenta de navegador (sin backend, usa `storage.sync`) |
| 🎨 **Tema predeterminado** | Aplica un tema global a todos los sitios sin configuración propia; el restablecimiento vuelve a él |
| 📥 **Restauración completa** | Importa respaldos de más de 5 sitios, incluido tu tema predeterminado |

> Consulta [VKT Pricing](https://annmax1983.com/pricing.html) para opciones de licencia.

---

## Vista previa

<p align="center">
  <img src="../screenshots/en.png" alt="Vista previa de StylePatch" width="640">
</p>

---

## Navegadores compatibles

| Navegador | Estado | Versión mínima |
|---------|--------|-----------------|
| Google Chrome | ✅ Totalmente compatible | Chrome 95+ |
| Microsoft Edge | ✅ Totalmente compatible | Edge 95+ |
| Mozilla Firefox | ✅ Totalmente compatible | Firefox 140+ (escritorio) |
| Otros navegadores basados en Chromium | ✅ Básico compatible | Instalar solo desde la tienda oficial de extensiones |

> **Nota sobre Firefox:** Las extensiones de Firefox no tienen service worker: se ejecutan como página de eventos. La sincronización entre dispositivos usa Firefox Sync (cuenta de Mozilla). El resto de funciones se comporta igual que en Chrome / Edge.

---

## Instalación

| Tienda | Enlace |
|---|---|
| Chrome Web Store | [Instalar en Chrome](https://chromewebstore.google.com/detail/hlmnodnjlhdecfcaiahnngpldkialkca) |
| Complementos de Microsoft Edge | [Instalar en Edge](https://microsoftedge.microsoft.com/addons/detail/lkhpdpimlelcldbnkhggfdoejcimcfgo) |
| Complementos de Firefox (AMO) | 🔜 En revisión: el enlace se añadirá al publicarse |

> Instale solo desde las tiendas oficiales de arriba; evite sitios de descarga de terceros.

---

## Uso

1. Haz clic en el **icono de StylePatch** en la barra de herramientas de tu navegador
2. **Elige colores** — Usa el selector nativo de color o escribe un código hex
3. **Selecciona un predefinido** — Claro, Tono cálido, Verde, Oscuro, Sepia, Noche azul o Alto contraste
4. **Ajusta el tamaño de fuente** — Arrastra el control deslizante del 80% al 150%
5. **Elige una fuente** — Selecciona una fuente del sistema o carga un Google Font desde la web
6. **Aplica un filtro** — Opcionalmente escala de grises o tinte cálido para el cuidado visual
7. **Guardar** — Haz clic en **Aplicar y guardar** para conservar la configuración de este sitio
8. **Restablecer** — Haz clic en ↺ para eliminar la configuración propia del sitio; si hay un tema predeterminado, el sitio vuelve a él
9. **Establecer como predeterminado** — Los usuarios Premium pueden guardar los colores actuales como tema predeterminado para todos los sitios (los sitios con configuración propia la mantienen)
10. **Excluir** — Haz clic en "Excluir este sitio" para añadir un dominio a la lista negra
11. **Interruptor** — Usa el interruptor ON/OFF para desactivar sin perder la configuración

### Gestor de configuraciones

Haz clic en **⚙ Gestor de configuraciones** en la parte inferior del popup para abrir la página de configuración:

- **Ver**, buscar y **eliminar** sitios configurados con sus ajustes de color y fuente
- **Exportar** todas las configuraciones como archivo de respaldo JSON (gratis)
- **Importar** un archivo de respaldo para restaurar la configuración en otro dispositivo o después de reinstalar (la importación gratuita se limita a 5 sitios)
- **Sincronización en la nube** (Premium) — replica la configuración entre perfiles de Chrome/Edge/Firefox con la misma cuenta de navegador
- **Tema predeterminado** (Premium) — revisa o elimina el tema aplicado a los sitios sin configuración propia

---

## Preguntas frecuentes

1. **¿Los estilos no se aplican después de ajustar?**
   Cierra otras extensiones similares (modo oscuro / cuidado visual) que puedan entrar en conflicto y luego recarga la página.

2. **¿La configuración guardada desaparece al volver a abrir el navegador?**
   Asegúrate de haber hecho clic en "Aplicar y guardar". Si usas el modo incógnito, activa el permiso de StylePatch para ventanas privadas.

3. **¿Cómo transfiero mi configuración a un nuevo dispositivo?**
   Abre el Gestor de configuraciones (⚙), haz clic en Exportar para descargar un archivo de respaldo e impórtalo en el nuevo dispositivo. La importación gratuita restaura hasta 5 sitios; Premium restaura todo. Dentro de la misma cuenta de Chrome/Edge/Firefox, los usuarios Premium también pueden activar la Sincronización en la nube y prescindir del archivo.

4. **¿Por qué `www.example.com` y `example.com` comparten la misma configuración?**
   Es intencional — los dominios se comparan sin tener en cuenta el `www.` inicial, así que tu estilo se aplica de forma consistente en ambas direcciones.

5. **¿No encuentras StylePatch en la tienda de extensiones?**
   Comprueba la región de tu red. Puedes encontrar el enlace oficial de la tienda en [www.annmax1983.com](https://www.annmax1983.com).

---

## Privacidad

StylePatch sigue principios de privacidad desde el diseño y no recopila ningún dato del usuario:

1. **Permisos solicitados** — solo tres:
   - `storage`: Guarda tus colores personalizados, tamaño de fuente, lista negra de sitios y preferencias de tema localmente; la Sincronización en la nube opcional (Premium) usa `storage.sync`. No se almacena contenido de páginas web.
   - `scripting`: Solo se usa para inyectar el CSS generado en la pestaña actual (en el mundo aislado de la extensión). No lee el contenido de la página ni ejecuta código remoto.
   - `host_permissions`: Solo se usa para inyectar estilos CSS personalizados que ajustan la apariencia de la página. No lee texto del DOM, imágenes, cookies, credenciales de inicio de sesión ni datos de formularios.

2. **Sin rastreo** — Sin acceso al historial de navegación, sin rastreadores de terceros integrados, sin analítica.

3. **Los datos permanecen locales salvo que los compartas** — Los datos de configuración existen en tu dispositivo de forma predeterminada. Solo salen de tu navegador cuando:
   - exportas manualmente un archivo de respaldo;
   - activas la Sincronización en la nube (Premium), que guarda únicamente la configuración de sitios, la lista negra, el interruptor y el tema predeterminado en tu cuenta de navegador mediante `storage.sync` — nunca claves de licencia ni datos de navegación;
   - eliges un Google Font (el archivo de fuente se descarga desde fonts.googleapis.com);
   - activas o validas una licencia (la clave de licencia, un ID de instalación aleatorio y metadatos básicos del navegador se envían a api.annmax1983.com).

- [Política de privacidad completa](https://annmax1983.github.io/StylePatch/privacy-policy.html)
- [Detalles complementarios de privacidad](https://www.annmax1983.com)

---

## Aviso de derechos de autor

1. Esta extensión solo ajusta localmente el estilo de renderizado visual de las páginas web para una lectura cómoda. Todo el texto, las imágenes y los derechos de autor del contenido de cada sitio web pertenecen a su respectivo editor.
2. Modificar los estilos de visualización de la página no otorga a los usuarios ninguna autorización de derechos de autor sobre el contenido del sitio web. Queda estrictamente prohibido usar esta extensión para eludir muros de pago, restricciones de membresía o mecanismos de protección contra copia de los sitios web.
3. Los usuarios deberán cumplir con las leyes locales y los términos de servicio de las plataformas al usar esta extensión. Cualquier uso ilegal será responsabilidad del usuario.

---

## Aviso sobre el código fuente

> ⚠️ **Este repositorio no publica código fuente.** Contiene únicamente documentación de uso, notas de lanzamiento y recursos de soporte. La extensión se distribuye exclusivamente a través de Chrome Web Store, Microsoft Edge Add-ons y Firefox Add-ons (AMO). No se proporcionan paquetes de instalación sin conexión ni código fuente para usuarios finales.

---

## Licencia

Copyright © 2026 StylePatch. Todos los derechos reservados.

Este software es de código cerrado y propietario. Sin autorización escrita oficial, quedan estrictamente prohibidos:
- Descompilar, piratear o modificar el código del programa
- Reempaquetar, redistribuir, compartir o reventa comercial
- Incorporar el programa a otro software para distribución conjunta

Los infractores asumirán las responsabilidades legales correspondientes.

---

## ❤️ Apoyo

Si te resulta útil StylePatch, ¡considera invitar al desarrollador a un café!

**[👉 Haz clic aquí para apoyar](https://ko-fi.com/annmax?buyACoffee=true&ref=stylepatch)**
