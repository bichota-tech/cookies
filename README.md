# 🍪 COOKIES - Una Web, Mil Caras

Sitio web informativo sobre la historia y curiosidades de las galletas (cookies). Un proyecto frontend responsivo que combina HTML, CSS y contenido educativo sobre estos deliciosos postres.

## 📋 Descripción

Este proyecto es una página web estática que presenta tres secciones interactivas sobre galletas:

1. **La primera cookie de la historia** - Explora los orígenes de las galletas como método de prueba de hornos
2. **Las galletas con chips de chocolate nacieron por error** - La historia fascinante de cómo Ruth Wakefield creó las Toll House Cookies en 1938
3. **Hacerlas reduce el estrés** - Descubre los beneficios para la salud mental de hornear galletas

## 🎨 Características

- **Diseño responsivo**: Utiliza viewport units (`dvh`, `vh`) y media queries para adaptarse a cualquier tamaño de pantalla
- **Interfaz interactiva**: El encabezado tiene un efecto hover animado que revela el subtítulo
- **Paleta de colores temática**: Colores inspirados en galletas y chocolate:
  - Primario: `chocolate`
  - Secundario: `#fad9c3` (crema)
  - Texto: `#2c1309d7` (marrón oscuro)
- **Tipografía fluida**: Utiliza `clamp()` para escalado automático del texto según el viewport
- **Layout adaptativo**: 
  - Versión móvil: columnas verticales
  - Versión desktop (630px+): grid layouts alternos con texto e imágenes

## 📁 Estructura del Proyecto

```
cookies/
├── index.html          # Estructura HTML de la página
├── estilos.css         # Estilos y diseño responsivo
├── LICENSE             # Licencia MIT
├── README.md           # Este archivo
└── imagenes/
    └── cookies8.avif   # Imagen en formato AVIF
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - CSS Grid para layouts complejos
  - Flexbox para alineación
  - Variables CSS (custom properties)
  - Media queries
  - Transiciones y transformaciones

## 📱 Responsividad

El sitio se adapta automáticamente a diferentes dispositivos:

- **Mobile First**: Diseño optimizado para dispositivos móviles
- **Breakpoint principal**: 630px (cambio a layout grid en desktop)
- **Imágenes adaptativas**: Usan `max-width: 100%` y unidades relativas
- **Tipografía fluida**: Usa `clamp()` para escalado suave entre tamaños

## 🎯 Uso

Simplemente abre el archivo `index.html` en tu navegador web. No requiere instalación de dependencias ni configuración adicional.

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Con servidor local (opcional)
python -m http.server 8000
# Luego visita http://localhost:8000
```

## ✨ Interactividad

### Efecto Hover en el Encabezado
Cuando pasas el ratón sobre el encabezado:
- El título "COOKIES" se desplaza a la izquierda
- El subtítulo "Pero las de comer!" aparece con animación suave

### Transiciones
- Duración: 0.4s
- Función: `ease`
- Elementos animados: transformaciones y opacidad

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia MIT** - ver el archivo `LICENSE` para más detalles.

Copyright © 2025 ACMA

## 👨‍💻 Autor

Proyecto desarrollado por **bichota-tech**

- GitHub: [@bichota-tech](https://github.com/bichota-tech)

## 🚀 Mejoras Futuras Posibles

- Agregar más historias sobre tipos de galletas
- Implementar galería de imágenes interactiva
- Añadir formulario de recetas o comentarios
- Incorporar animaciones adicionales
- Optimizar imágenes para mejor rendimiento
- Agregar modo oscuro

## 📝 Notas

- Algunas imágenes referenciadas en el HTML no están completas en el directorio (cookies5.png, cookies7.jpg)
- Se recomienda reemplazar estas rutas con imágenes existentes o agregar los archivos faltantes
- El proyecto utiliza unidades modernas de CSS (dvh, clamp) con excelente soporte en navegadores modernos
