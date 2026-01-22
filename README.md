# 🌿 Armonía - Uñas & Estética

> Sitio web de catálogo elegante y minimalista para salón de belleza especializado en cuidado de uñas y estética.

---

## 📋 Descripción

**Armonía** es un sitio web diseñado para mostrar servicios y productos de un salón de belleza de manera elegante y profesional. El proyecto enfatiza la experiencia visual con animaciones suaves, tipografía serif refinada y una paleta de colores inspirada en la naturaleza y la serenidad.

---

## ✨ Características Principales

### 🎨 Diseño Visual
- **Paleta de colores armoniosa**: Tonos verde salvia, dorado suave y grises elegantes
- **Tipografía refinada**: Combinación de Palatino Linotype y Georgia para elegancia clásica
- **Animaciones suaves**: Efectos de scroll reveal con Intersection Observer API
- **Diseño responsivo**: Optimizado para desktop, tablet y móvil

### 🧭 Navegación
- **Hero carousel**: Carrusel automático de imágenes destacadas
- **Categorías dinámicas**: Navegación rápida por tipo de producto/servicio
- **Navegación inteligente**: Botones "Volver" que detectan la página de origen
- **Smooth scrolling**: Experiencia de navegación fluida

### 🎯 Funcionalidades
- Catálogo de productos organizado por categorías
- Página de detalles de producto con información completa
- Grid responsivo con cartas de productos
- Sistema de carrusel horizontal con controles de navegación
- Integración con redes sociales (Facebook, Instagram, TikTok, WhatsApp)

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del sitio
- **CSS3**: Estilos avanzados con gradientes, animaciones y grid/flexbox
- **JavaScript (Vanilla)**: 
  - Intersection Observer API para animaciones
  - Generación dinámica de contenido
  - Navegación inteligente
  - Control de carruseles

---

## 📂 Estructura del Proyecto

```
Armonia/
├── index.html              # Página principal con todas las categorías
├── category.html           # Página de categoría específica
├── detallesproducto.html   # Página de detalle de producto
└── README.md               # Documentación del proyecto
```

---

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Verde Principal | `#AAB9B0` | Logo, botones primarios, acentos |
| Verde Menta | `#A5BDB0` | Gradientes, hover states |
| Verde Oscuro | `#97A99D` | Gradientes, sombras |
| Verde Sage | `#8E9A92` | Elementos sutiles |
| Dorado Suave | `#C5B899` | Detalles, bordes, sombras |
| Café Dorado | `#B8A88E` | Elementos secundarios |
| Gris Principal | `#D9D9D9` | Fondos secundarios |
| Gris Oscuro | `#A6A6A6` | Textos secundarios |
| Texto Principal | `#2E2E2E` | Texto principal |
| Blanco | `#FFFFFF` | Fondos, textos sobre color |

---

## 🎭 Tipografía

### Fuentes Principales
- **Títulos de categorías**: Palatino Linotype (italic, bold 600, 20px)
- **Textos editoriales**: Georgia, Times New Roman (serif)
- **Botones de categorías**: Georgia (13px desktop, 11px mobile)
- **Interfaz general**: Segoe UI, system-ui (sans-serif)

---

## 🚀 Cómo Usar

### Instalación Local
1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador preferido
3. No requiere servidor - funciona directamente en el navegador

### Personalización
1. **Modificar productos**: Edita el array `products` en cada archivo JavaScript
2. **Cambiar categorías**: Modifica el array `categories` 
3. **Ajustar colores**: Actualiza las variables CSS en `:root`
4. **Personalizar imágenes**: Cambia las URLs de Unsplash/Picsum por tus propias imágenes

---

## 📱 Características Responsivas

### Breakpoints
- **Desktop**: > 900px
- **Mobile**: ≤ 900px

### Ajustes Móviles
- Cards de producto: 310px → 240px
- Imágenes de producto: 260px → 180px
- Fuentes de botones: 13px → 11px
- Carrusel: scroll horizontal con overflow
- Grid adaptativo: auto-fill con minmax

---

## 🎬 Animaciones

### Efectos Implementados
- **Fade-in con slide**: Elementos aparecen con desvanecimiento y desplazamiento vertical
- **Staggered animation**: Productos aparecen con delay escalonado (50ms entre cada uno)
- **Hover effects**: 
  - Cards: lift + scale + shadow
  - Botones: color change + transform
  - Imágenes: filter adjustments
- **Hero carousel**: Transición automática cada 4 segundos

---

## 🔗 Navegación del Sitio

```
index.html
    ├── → category.html (por categoría)
    │     └── → detallesproducto.html
    │           └── ← Volver a category.html o index.html (inteligente)
    └── → detallesproducto.html (directo)
          └── ← Volver a index.html o category.html (inteligente)
```

---

## 🌟 Características Destacadas

### Sistema de Gradientes
Todos los elementos principales utilizan gradientes sutiles que mezclan:
- Verde salvia (#AAB9B0)
- Verde menta (#A5BDB0)
- Verde oscuro (#97A99D)

### Sombras Multi-capa
Las tarjetas de productos utilizan un sistema de sombras compuesto:
```css
box-shadow: 
  0 4px 20px rgba(184,168,142,0.08),    /* Sombra dorada */
  0 2px 8px rgba(170,185,176,0.06),     /* Sombra verde */
  0 1px 3px rgba(0,0,0,0.03);           /* Sombra base */
```

### Filtros de Imagen
Tratamiento especial de imágenes para coherencia visual:
- **Estado normal**: `saturate(0.85) brightness(1.02) contrast(0.95)`
- **Hover**: `saturate(0.95) brightness(1.05) contrast(1)`

---

## 📝 Notas de Desarrollo

- **Sin dependencias**: El proyecto no requiere librerías externas
- **Performance**: Uso de `transform` y `opacity` para animaciones fluidas
- **Accesibilidad**: Uso de aria-labels en iconos de redes sociales
- **SEO**: Estructura semántica HTML5
- **Compatibilidad**: Compatible con navegadores modernos (Chrome, Firefox, Safari, Edge)

---

## 🎯 Próximas Mejoras Sugeridas

- [ ] Agregar sistema de búsqueda de productos
- [ ] Implementar lazy loading de imágenes
- [ ] Agregar galería de imágenes en página de detalles
- [ ] Sistema de favoritos con localStorage
- [ ] Modo oscuro / claro
- [ ] Internacionalización (i18n)
- [ ] Backend para gestión dinámica de productos

---

## 👤 Autor

**Proyecto desarrollado para Armonía - Uñas & Estética**

---

## 📄 Licencia

Este proyecto es de uso privado para Armonía - Uñas & Estética.

---

## 🙏 Agradecimientos

- Imágenes de demostración: [Unsplash](https://unsplash.com) y [Picsum](https://picsum.photos)
- Iconos de redes sociales: SVG personalizados
- Inspiración de diseño: Estética minimalista y naturista

---

<div align="center">

**✨ Hecho con dedicación y atención al detalle ✨**

</div>
