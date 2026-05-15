# 4. JavaScript - Introducción General

## 📚 Objetivos de Aprendizaje

- Comprender qué es JavaScript y su importancia
- Aprender conceptos fundamentales del lenguaje
- Trabajar con variables y tipos de datos
- Realizar operaciones básicas

## 🎯 Conceptos Clave

### ¿Qué es JavaScript?

JavaScript es un lenguaje de programación que se ejecuta en el navegador. Permite hacer páginas web interactivas y dinámicas.

### Formas de Incluir JavaScript

#### 1. JavaScript Externo (Recomendado)

```html
<script src="script.js"></script>
```

#### 2. JavaScript Interno

```html
<script>
    console.log('Hola Mundo');
</script>
```

#### 3. JavaScript Inline (No recomendado)

```html
<button onclick="alert('Hola')">Click aquí</button>
```

## 📝 Variables y Tipos de Datos

### Declaración de Variables

```javascript
var nombre = "Juan";           // Antiguo (evitar)
let edad = 25;                 // Moderno (recomendado)
const ciudad = "Madrid";       // Constante (no cambiar)
```

### Tipos de Datos

```javascript
// Strings (texto)
let nombre = "Juan";
let mensaje = 'Hola';
let plantilla = `Hola ${nombre}`;

// Numbers (números)
let entero = 42;
let decimal = 3.14;

// Booleans (verdadero/falso)
let esActivo = true;
let esInactivo = false;

// Arrays (listas)
let numeros = [1, 2, 3, 4, 5];
let colores = ['rojo', 'verde', 'azul'];

// Objects (objetos)
let persona = {
    nombre: 'Juan',
    edad: 25,
    ciudad: 'Madrid'
};

// null y undefined
let vacio = null;
let noDefinido = undefined;
```

## 🔄 Operadores

### Operadores Aritméticos

```javascript
let suma = 5 + 3;           // 8
let resta = 10 - 4;         // 6
let multiplicacion = 4 * 5;  // 20
let division = 20 / 4;       // 5
let modulo = 10 % 3;         // 1
let potencia = 2 ** 3;       // 8
```

### Operadores de Comparación

```javascript
5 == "5"        // true (comparación de valor)
5 === "5"       // false (comparación estricta)
5 != 3          // true
5 !== "5"       // true
5 > 3           // true
5 < 3           // false
5 >= 5          // true
5 <= 3          // false
```

### Operadores Lógicos

```javascript
true && false   // false (AND)
true || false   // true (OR)
!true           // false (NOT)
```

## 🎮 Control de Flujo

### If/Else

```javascript
let edad = 18;

if (edad >= 18) {
    console.log('Eres mayor de edad');
} else if (edad >= 13) {
    console.log('Eres adolescente');
} else {
    console.log('Eres niño');
}
```

### Switch

```javascript
let dia = 3;

switch(dia) {
    case 1:
        console.log('Lunes');
        break;
    case 2:
        console.log('Martes');
        break;
    default:
        console.log('Otro día');
}
```

### Bucles

#### For

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

#### While

```javascript
let contador = 0;
while (contador < 5) {
    console.log(contador);
    contador++;
}
```

#### ForEach

```javascript
let numeros = [1, 2, 3, 4, 5];
numeros.forEach(function(numero) {
    console.log(numero);
});
```

## 🔧 Funciones

### Función Básica

```javascript
function saludar(nombre) {
    console.log('Hola, ' + nombre);
}

saludar('Juan');
```

### Función con Retorno

```javascript
function sumar(a, b) {
    return a + b;
}

let resultado = sumar(5, 3);  // 8
```

### Funciones Flecha (Arrow Functions)

```javascript
const multiplicar = (a, b) => a * b;

const resultado = multiplicar(4, 5);  // 20
```

## 🎯 Acceso al DOM

```javascript
// Seleccionar elementos
let elemento = document.getElementById('mi-id');
let elementos = document.querySelectorAll('.mi-clase');

// Cambiar contenido
elemento.textContent = 'Nuevo texto';
elemento.innerHTML = '<strong>Texto en negrita</strong>';

// Cambiar atributos
elemento.setAttribute('class', 'nueva-clase');
elemento.style.color = 'rojo';

// Añadir eventos
elemento.addEventListener('click', function() {
    console.log('Se hizo click');
});
```

## 💻 Ejemplo Completo

Ver archivo: `01_variables_tipos.html`

## 🔗 Enlaces Útiles

- [MDN - JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [W3Schools - JavaScript](https://www.w3schools.com/js/)
- [JavaScript.info](https://es.javascript.info/)

## ✅ Checklist de Aprendizaje

- [ ] Entender variables y tipos de datos
- [ ] Practicar operadores
- [ ] Crear funciones
- [ ] Manipular el DOM
- [ ] Manejar eventos

---

**Última actualización:** 15/05/2026