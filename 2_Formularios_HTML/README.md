# 2. Formularios HTML

## 📚 Objetivos de Aprendizaje

- Crear formularios HTML funcionales
- Comprender diferentes tipos de controles de entrada
- Validar datos en formularios
- Enviar datos del formulario

## 🎯 Conceptos Clave

### ¿Qué es un Formulario HTML?

Los formularios son elementos que permiten a los usuarios enviar datos a un servidor web. Se crean con la etiqueta `<form>`.

### Estructura de un Formulario

```html
<form action="/enviar" method="POST">
    <!-- Controles de entrada aquí -->
    <input type="submit" value="Enviar">
</form>
```

### Atributos Principales

| Atributo | Descripción |
|----------|-------------|
| `action` | URL donde se envían los datos |
| `method` | GET o POST |
| `name` | Nombre del formulario |
| `enctype` | Tipo de codificación |

## 📝 Tipos de Entrada

### Entrada de Texto

```html
<label for="nombre">Nombre:</label>
<input type="text" id="nombre" name="nombre" required>
```

### Entrada de Email

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
```

### Entrada de Contraseña

```html
<label for="password">Contraseña:</label>
<input type="password" id="password" name="password" required>
```

### Casillas de Verificación

```html
<input type="checkbox" name="terminos" id="terminos">
<label for="terminos">Acepto los términos</label>
```

### Botones de Radio

```html
<input type="radio" name="genero" value="masculino"> Masculino
<input type="radio" name="genero" value="femenino"> Femenino
```

### Área de Texto

```html
<label for="comentarios">Comentarios:</label>
<textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea>
```

### Lista Desplegable

```html
<label for="pais">País:</label>
<select id="pais" name="pais">
    <option value="españa">España</option>
    <option value="mexico">México</option>
    <option value="argentina">Argentina</option>
</select>
```

## 💡 Validación de Formularios

### Atributos de Validación HTML5

```html
<input type="text" required>           <!-- Campo obligatorio -->
<input type="email" type="email">     <!-- Validar email -->
<input type="number" min="0" max="100"> <!-- Rango numérico -->
<input type="text" minlength="5" maxlength="20"> <!-- Longitud -->
<input type="text" pattern="[A-Z]+">  <!-- Expresión regular -->
```

## 💻 Ejemplo Completo

Ver archivo: `01_formulario_basico.html`

## 🔗 Enlaces Útiles

- [MDN - Formularios HTML](https://developer.mozilla.org/es/docs/Learn/Forms)
- [W3Schools - Formularios](https://www.w3schools.com/html/html_forms.asp)

## ✅ Checklist de Aprendizaje

- [ ] Crear formulario básico
- [ ] Utilizar diferentes tipos de entrada
- [ ] Agregar validación
- [ ] Practicar con ejemplos

---

**Última actualización:** 15/05/2026