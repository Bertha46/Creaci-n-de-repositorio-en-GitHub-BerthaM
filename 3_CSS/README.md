# 3. CSS - Introducción, Selectores y Propiedades

## 📚 Objetivos de Aprendizaje

- Comprender qué es CSS y su importancia
- Aprender selectores CSS
- Dominar propiedades CSS fundamentales
- Crear estilos visuales profesionales

## 🎯 Conceptos Clave

### ¿Qué es CSS?

CSS (Cascading Style Sheets) es el lenguaje para aplicar estilos a documentos HTML. Define colores, tipografía, espaciado, posicionamiento, etc.

### Formas de Incluir CSS

#### 1. CSS Externo (Recomendado)

```html
<link rel="stylesheet" href="estilos.css">
```

#### 2. CSS Interno

```html
<style>
    p { color: blue; }
</style>
```

#### 3. CSS Inline (No recomendado)

```html
<p style="color: blue;">Texto azul</p>
```

## 📝 Selectores CSS

### 1. Selector de Elemento

```css
p {
    color: black;
    font-size: 16px;
}
```

### 2. Selector de Clase

```css
.titulo {
    color: blue;
    text-align: center;
}
```

```html
<h1 class="titulo">Mi Título</h1>
```

### 3. Selector de ID

```css
#principal {
    background-color: #f0f0f0;
}
```

```html
<div id="principal">Contenido principal</div>
```

### 4. Selectores Compuestos

```css
/* Elemento con clase */
div.contenedor { padding: 20px; }

/* Descendientes */
.menu li { list-style: none; }

/* Hijos directos */
.padre > .hijo { margin: 10px; }

/* Hermanos */
h1 + p { margin-top: 0; }

/* Múltiples elementos */
h1, h2, h3 { color: navy; }
```

### 5. Pseudoclases

```css
a:hover { color: red; }           /* Al pasar el mouse */
a:visited { color: purple; }      /* Links visitados */
input:focus { border: 2px solid blue; } /* Elemento enfocado */
li:first-child { font-weight: bold; }   /* Primer elemento */
li:last-child { margin-bottom: 0; }     /* Último elemento */
```

## 🎨 Propiedades CSS Fundamentales

### Color y Fondo

```css
color: blue;                    /* Color del texto */
background-color: #f0f0f0;      /* Color de fondo */
background-image: url(...);     /* Imagen de fondo */
background-size: cover;         /* Tamaño de imagen */
```

### Tipografía

```css
font-family: Arial, sans-serif;  /* Tipo de fuente */
font-size: 16px;                 /* Tamaño */
font-weight: bold;               /* Grosor (normal, bold, 700) */
font-style: italic;              /* Estilo (normal, italic) */
line-height: 1.5;                /* Altura de línea */
text-align: center;              /* Alineación (left, right, center) */
text-decoration: underline;      /* Decoración (underline, none) */
text-transform: uppercase;       /* Transformación */
```

### Espaciado (Box Model)

```css
margin: 20px;                   /* Espacio exterior */
padding: 15px;                  /* Espacio interior */
border: 2px solid black;        /* Borde */
width: 300px;                   /* Ancho */
height: 200px;                  /* Alto */
box-sizing: border-box;         /* Incluir padding y border en width/height */
```

### Visualización y Posicionamiento

```css
display: block;                 /* block, inline, inline-block, flex, grid */
position: relative;             /* relative, absolute, fixed, sticky */
top: 10px;                      /* Desplazamiento top */
left: 20px;                     /* Desplazamiento left */
float: left;                    /* Flotación */
z-index: 100;                   /* Profundidad */
overflow: hidden;               /* Desbordamiento */
```

### Sombras y Efectos

```css
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);  /* Sombra en caja */
text-shadow: 2px 2px 4px gray;              /* Sombra de texto */
opacity: 0.8;                               /* Transparencia */
transform: rotate(45deg);                   /* Transformación */
transition: all 0.3s ease;                  /* Transición suave */
```

## 💻 Ejemplo Completo

Ver archivo: `01_css_basico.html`

## 🔗 Enlaces Útiles

- [MDN - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [W3Schools - CSS Tutorial](https://www.w3schools.com/css/)
- [CSS Tricks](https://css-tricks.com/)

## ✅ Checklist de Aprendizaje

- [ ] Entender selectores CSS
- [ ] Practicar propiedades básicas
- [ ] Dominar el Box Model
- [ ] Crear layouts con CSS
- [ ] Usar flexbox o grid

---

**Última actualización:** 15/05/2026