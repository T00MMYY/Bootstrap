# 🌐 Leyes de la Gestalt en Diseño Web

## 🧭 Descripción general
Este proyecto es una página educativa diseñada para explicar de manera visual, clara y accesible las **ocho leyes de la Gestalt** aplicadas al **diseño de interfaces web**.  
La estructura se ha desarrollado con **HTML5**, **CSS** y **Bootstrap 5.3**, priorizando la **legibilidad**, la **organización visual** y una experiencia de usuario fluida con navegación por **anclajes y desplazamiento suave**.

---

## 🧱 Estructura y contenido
El sitio está compuesto por un **encabezado fijo con menú de navegación** que permite moverse entre las secciones mediante scroll suave (`scroll-behavior: smooth`).  
Cada sección explica una ley con:
- Un título y párrafo descriptivo en lenguaje cotidiano.  
- Un ejemplo visual (imagen ilustrativa).  
- Una breve interpretación o resumen al final.  

### Leyes representadas:
1. **Proximidad**  
2. **Semejanza**  
3. **Continuidad**  
4. **Cierre**  
5. **Figura–fondo**  
6. **Simetría y orden**  
7. **Región común**  
8. **Destino común**

---

## 🎨 Diseño visual
- Framework: **Bootstrap 5.3.8 (CDN)**  
- Tipografía: *Arial / Helvetica / Sans-serif*  
- Paleta de colores: tonos **azules e informativos** (`bg-primary-subtle`, `bg-info-subtle`) combinados con áreas neutras (`bg-dark`, `bg-dark-subtle`) para generar contraste y jerarquía.  
- Bordes redondeados (`rounded-3`) para un aspecto amable.  
- Enlaces del menú en color blanco sobre fondo oscuro.  

---

## ♿ Accesibilidad
- Estructura semántica con etiquetas `header`, `main`, `section`, `footer`.  
- Jerarquía de títulos correcta: `H1` implícito en el encabezado, `H2` por cada ley.  
- Contraste verificado entre texto y fondo.  
- Descripción alternativa (`alt`) en todas las imágenes.  
- ScrollSpy de Bootstrap activo (`data-bs-spy="scroll"`) para indicar la sección actual en el menú.  
- Navegación accesible mediante teclado (`tabindex="0"`).  

---

## 🪄 Efectos y utilidades Bootstrap
- **Scrollspy:** el menú superior resalta el apartado activo al hacer scroll.  
- **Anclajes internos:** cada ítem del menú enlaza a su sección mediante `href="#nombre-de-sección"`.  
- **Scroll suave:** definido en CSS con `scroll-behavior: smooth`.  
- **Espaciados y colores:** aplicados mediante clases utilitarias (`p-5`, `mb-3`, `bg-primary-subtle`, etc.).  
- **Componentes visuales:** estructura con `container`, `navbar`, `section` y `footer`.  

---

