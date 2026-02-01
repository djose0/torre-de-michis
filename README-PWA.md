# Torre de Michis 🐱 - Progressive Web App

## 📱 Instalación de la App

### En Android (Chrome/Edge):
1. Abre el juego en Chrome o Edge
2. Toca el menú (3 puntos) → "Agregar a pantalla de inicio"
3. Confirma la instalación
4. ¡La app aparecerá en tu pantalla de inicio!

### En iOS (Safari):
1. Abre el juego en Safari
2. Toca el botón de compartir (cuadrado con flecha)
3. Desplázate y toca "Agregar a pantalla de inicio"
4. Confirma con "Agregar"
5. ¡La app aparecerá en tu pantalla de inicio!

### En Windows/Mac (Chrome/Edge):
1. Abre el juego en Chrome o Edge
2. Haz clic en el icono de instalar (➕) en la barra de direcciones
3. O ve al menú → "Instalar Torre de Michis"
4. ¡La app se instalará como aplicación nativa!

---

## 🎨 Iconos Necesarios

Para que la app funcione completamente, necesitas crear dos iconos:

### icon-192.png (192x192 píxeles)
- Icono para dispositivos Android y pantallas pequeñas
- Fondo recomendado: #87ceeb (azul cielo)
- Contenido: Un gato kawaii apilado

### icon-512.png (512x512 píxeles)
- Icono de alta resolución para Android y splash screens
- Fondo recomendado: #87ceeb (azul cielo)
- Contenido: Un gato kawaii apilado más detallado

### Recomendaciones de diseño:
- Usa colores vibrantes (#ff6b35, #f4a261, #2a9d8f)
- Estilo: Kawaii / Cute
- Incluye orejas triangulares y ojos grandes
- Mantén el diseño simple y reconocible

### Herramientas para crear iconos:
- **Canva** (canva.com) - Fácil y gratis
- **Figma** (figma.com) - Profesional
- **GIMP/Photoshop** - Edición avanzada
- **Generador de iconos PWA** (https://www.pwabuilder.com/imageGenerator)

---

## 📂 Archivos de la PWA

- `torre-de-michis.html` - El juego principal
- `manifest.json` - Configuración de la PWA
- `service-worker.js` - Permite funcionamiento offline
- `icon-192.png` - Icono pequeño (CREAR)
- `icon-512.png` - Icono grande (CREAR)

---

## ✨ Características de la PWA

✅ **Funciona offline** después de la primera carga
✅ **Se instala** como app nativa en cualquier dispositivo
✅ **Pantalla completa** sin navegador visible
✅ **Icono en pantalla de inicio** como cualquier app
✅ **Carga rápida** gracias al cache
✅ **Actualización automática** cuando hay nuevas versiones

---

## 🚀 Despliegue

Para publicar tu PWA necesitas:

1. **Hosting con HTTPS** (requisito obligatorio para PWA)
   - GitHub Pages (gratis)
   - Netlify (gratis)
   - Vercel (gratis)
   - Firebase Hosting (gratis)

2. **Subir todos los archivos**:
   - torre-de-michis.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png

3. **Probar la instalación** desde tu móvil

---

## 🐛 Solución de problemas

**"No aparece el botón de instalar"**
- Verifica que estés usando HTTPS
- Asegúrate de que manifest.json esté correctamente enlazado
- Revisa la consola del navegador en busca de errores

**"Los iconos no se ven"**
- Verifica que icon-192.png y icon-512.png existan
- Confirma que las rutas en manifest.json sean correctas
- Limpia el cache del navegador

**"No funciona offline"**
- Espera a que el Service Worker se instale
- Recarga la página después de la primera visita
- Verifica la consola para errores del Service Worker

---

¡Disfruta apilando michis! 🐱🎮
