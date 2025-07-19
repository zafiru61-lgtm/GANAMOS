# 🎰 GANAMOS Casino Website

## Descripción

GANAMOS Casino es un sitio web moderno y responsive para un casino en línea. El sitio presenta promociones especiales, juegos populares y una interfaz atractiva con animaciones suaves y diseño profesional.

## Características

- **Diseño Responsive**: Optimizado para dispositivos móviles, tablets y escritorio
- **Animaciones CSS**: Efectos visuales suaves y atractivos
- **Integración WhatsApp**: Enlaces directos para contacto comercial
- **Secciones Principales**:
  - Promociones Especiales (Bono de Bienvenida 100%, Cashback Semanal 20%)
  - Juegos Populares (Mega Fortune Slots, Blackjack Premium)

## Estructura del Proyecto

```
GANAMOS/
├── index.html          # Página principal del sitio
├── banner-casino.jpg   # Imagen del banner principal
├── promo1.jpg         # Imagen promoción 1
├── promo2.jpg         # Imagen promoción 2
├── juego1.jpg         # Imagen juego 1 (Slots)
├── juego2.jpg         # Imagen juego 2 (Blackjack)
└── README.md          # Este archivo
```

## GitHub Pages

Este sitio está configurado para funcionar con GitHub Pages desde la rama principal. Para acceder al sitio:

1. Ve a la configuración del repositorio
2. Navega a la sección "Pages"
3. Selecciona "Deploy from a branch"
4. Elige la rama `main` y la carpeta `/ (root)`
5. El sitio estará disponible en: `https://[usuario].github.io/GANAMOS/`

## Desarrollo Local

Para probar el sitio localmente:

```bash
# Clona el repositorio
git clone https://github.com/[usuario]/GANAMOS.git
cd GANAMOS

# Inicia un servidor local
python3 -m http.server 8000

# Abre en el navegador
# http://localhost:8000
```

## Personalización

### Modificar Contenido

- **Título y subtítulos**: Edita las etiquetas `<h1>`, `<h2>`, `<h3>` en `index.html`
- **Promociones**: Actualiza el contenido en las secciones `.card` 
- **Enlaces WhatsApp**: Modifica los números y mensajes en los atributos `href`
- **Colores**: Ajusta las variables CSS en la sección `<style>`

### Actualizar Imágenes

Para reemplazar las imágenes placeholder:

1. Crea nuevas imágenes con las dimensiones recomendadas:
   - `banner-casino.jpg`: 800x300px
   - `promo1.jpg`, `promo2.jpg`: 350x200px  
   - `juego1.jpg`, `juego2.jpg`: 350x200px

2. Reemplaza los archivos existentes manteniendo los mismos nombres

### Configuración de Contacto

Actualiza los números de WhatsApp en las URLs:
```html
https://wa.me/57123456789?text=Mensaje
```

Cambia `57123456789` por el número real (incluyendo código de país).

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos, animaciones y responsive design
- **JavaScript**: Interactividad y efectos
- **GitHub Pages**: Hosting gratuito

## Compatibilidad

- ✅ Chrome/Edge (versiones recientes)
- ✅ Firefox (versiones recientes)  
- ✅ Safari (versiones recientes)
- ✅ Dispositivos móviles iOS/Android

## Licencia

© 2024 GANAMOS Casino. Todos los derechos reservados.

## Soporte

Para dudas o problemas técnicos, crea un issue en este repositorio.