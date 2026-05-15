# 📚 Repositorio Completo de Asignatura de Desarrollo Web

¡Bienvenido! Este repositorio contiene todo el contenido de la asignatura de **Desarrollo Web**, organizado en 4 módulos principales.

## 📑 Índice de Contenidos

### 1. 🏗️ [HTML - Introducción, Sintaxis y Estructura](./1_HTML/)

**Objetivo:** Aprender los fundamentos del lenguaje HTML

**Contenido:**
- ✅ Estructura básica de documentos HTML
- ✅ Etiquetas semánticas
- ✅ Listas, tablas y formularios
- ✅ Atributos y mejores prácticas

**Archivos:**
- 📖 [README.md](./1_HTML/README.md) - Teoría completa
- 💻 [01_estructura_basica.html](./1_HTML/01_estructura_basica.html) - Ejemplo práctico

**Temas Clave:**
```html
<!DOCTYPE html> - Declaración de tipo
<html> - Elemento raíz
<head> - Metadatos
<body> - Contenido visible
```

---

### 2. 📝 [Formularios HTML](./2_Formularios_HTML/)

**Objetivo:** Dominar la creación de formularios interactivos

**Contenido:**
- ✅ Elementos de entrada (input, textarea, select)
- ✅ Validación de formularios
- ✅ Métodos GET y POST
- ✅ Mejores prácticas de UX

**Archivos:**
- 📖 [README.md](./2_Formularios_HTML/README.md) - Guía de formularios
- 💻 [01_formulario_basico.html](./2_Formularios_HTML/01_formulario_basico.html) - Formulario completo

**Tipos de Entrada:**
```html
<input type="text">
<input type="email">
<input type="password">
<input type="checkbox">
<input type="radio">
<textarea></textarea>
<select></select>
```

---

### 3. 🎨 [CSS - Introducción, Selectores y Propiedades](./3_CSS/)

**Objetivo:** Crear estilos visuales atractivos

**Contenido:**
- ✅ Selectores CSS (elemento, clase, ID)
- ✅ Propiedades de color, tipografía y espaciado
- ✅ Box Model
- ✅ Flexbox y Grid
- ✅ Responsive Design

**Archivos:**
- 📖 [README.md](./3_CSS/README.md) - Propiedades CSS
- 💻 [01_css_basico.html](./3_CSS/01_css_basico.html) - Ejemplo con estilos

**Selectores Principales:**
```css
p { }              /* Elemento */
.clase { }         /* Clase */
#id { }            /* ID */
p:hover { }        /* Pseudoclase */
p::before { }      /* Pseudoelemento */
```

---

### 4. ⚙️ [JavaScript - Introducción General](./4_JavaScript/)

**Objetivo:** Dominar programación básica en JavaScript

**Contenido:**
- ✅ Variables y tipos de datos
- ✅ Operadores (aritméticos, comparación, lógicos)
- ✅ Control de flujo (if, switch, bucles)
- ✅ Funciones
- ✅ Manipulación del DOM

**Archivos:**
- 📖 [README.md](./4_JavaScript/README.md) - Conceptos fundamentales
- 💻 [01_variables_tipos.html](./4_JavaScript/01_variables_tipos.html) - Ejemplo interactivo

**Conceptos Clave:**
```javascript
let variable = valor;          // Variable
const CONSTANTE = valor;       // Constante
function nombre() { }          /* Función */
const flecha = () => { }       // Arrow Function
```

---

## 🗂️ Estructura del Repositorio

```
Creaci-n-de-repositorio-en-GitHub-BerthaM/
├── README.md                          # Guía inicial
├── README_ASIGNATURA.md              # Este archivo
│
├── 1_HTML/
│   ├── README.md
│   └── 01_estructura_basica.html
│
├── 2_Formularios_HTML/
│   ├── README.md
│   └── 01_formulario_basico.html
│
├── 3_CSS/
│   ├── README.md
│   └── 01_css_basico.html
│
└── 4_JavaScript/
    ├── README.md
    └── 01_variables_tipos.html
```

---

## 🚀 Cómo Usar Este Repositorio

### 1. **Clonar el Repositorio**

```bash
git clone https://github.com/Bertha46/Creaci-n-de-repositorio-en-GitHub-BerthaM.git
cd Creaci-n-de-repositorio-en-GitHub-BerthaM
```

### 2. **Navegar por los Temas**

Cada carpeta contiene:
- Una guía teórica en `README.md`
- Ejemplos prácticos en archivos HTML

### 3. **Abrir Ejemplos en el Navegador**

```bash
# En Windows (PowerShell)
start 1_HTML\01_estructura_basica.html

# En macOS
open 1_HTML/01_estructura_basica.html

# En Linux
xdg-open 1_HTML/01_estructura_basica.html
```

### 4. **Crear Tus Propios Ejemplos**

```bash
# Crear nueva rama
git checkout -b mi-ejercicio

# Hacer cambios y commit
git add .
git commit -m "feat: Agregar mi ejercicio de HTML"

# Subir cambios
git push origin mi-ejercicio
```

---

## 📋 Checklist de Aprendizaje

### HTML
- [ ] Entender estructura básica
- [ ] Conocer etiquetas semánticas
- [ ] Crear documentos bien formados
- [ ] Practicar con tablas y listas

### Formularios
- [ ] Crear formularios básicos
- [ ] Validar datos
- [ ] Usar diferentes tipos de entrada
- [ ] Implementar buenas prácticas UX

### CSS
- [ ] Comprender selectores
- [ ] Aplicar propiedades de estilo
- [ ] Dominar el Box Model
- [ ] Crear layouts responsive

### JavaScript
- [ ] Declarar variables
- [ ] Usar operadores
- [ ] Crear funciones
- [ ] Manipular el DOM
- [ ] Manejar eventos

---

## 🔗 Enlaces Útiles

### Documentación Oficial
- [MDN Web Docs](https://developer.mozilla.org/es/)
- [W3Schools](https://www.w3schools.com/)
- [HTML Living Standard](https://html.spec.whatwg.org/)

### Herramientas
- [Visual Studio Code](https://code.visualstudio.com/) - Editor recomendado
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/) - Herramientas de desarrollo
- [CodePen](https://codepen.io/) - Sandbox online

### Recursos
- [JavaScript.info](https://es.javascript.info/)
- [CSS-Tricks](https://css-tricks.com/)
- [HTML5 Doctor](http://html5doctor.com/)

---

## 📝 Ejercicios de Aplicación

### Nivel 1: Básico
1. Crear una página HTML con título, párrafos e imágenes
2. Diseñar un formulario de contacto simple
3. Aplicar estilos CSS básicos a una página
4. Escribir funciones JavaScript simples

### Nivel 2: Intermedio
1. Crear un sitio web de portafolio
2. Construir un formulario con validación
3. Diseñar un layout responsivo
4. Añadir interactividad con JavaScript

### Nivel 3: Avanzado
1. Crear una página web completa
2. Implementar un sistema de registro
3. Diseñar con Flexbox/Grid
4. Aplicaciones interactivas

---

## 👤 Información del Alumno

- **Nombre:** Bertha46
- **Asignatura:** Desarrollo Web
- **Fecha de Inicio:** Mayo 2026
- **Repositorio:** https://github.com/Bertha46/Creaci-n-de-repositorio-en-GitHub-BerthaM

---

## 📞 Soporte

Si tienes dudas o encuentras problemas:

1. Revisa la documentación en los archivos README
2. Consulta los enlaces útiles
3. Abre un issue en el repositorio
4. Contacta con tu profesor

---

## 📄 Licencia

Este repositorio es de uso educativo. Siéntete libre de usarlo, modificarlo y compartirlo.

---

**Última actualización:** 15/05/2026

¡Éxito en tu aprendizaje! 🎓