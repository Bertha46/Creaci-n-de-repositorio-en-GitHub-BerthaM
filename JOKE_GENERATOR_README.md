# 🎭 Generador de Bromas Aleatorias

Un generador de bromas aleatorias que utiliza la **JokeAPI** para obtener bromas en tiempo real.

## 📋 Características

- ✅ Obtiene bromas aleatorias de una API externa
- ✅ Soporta bromas de una línea y dos partes
- ✅ Disponible en Python y JavaScript
- ✅ Manejo de errores robusto
- ✅ Fácil de usar

## 🚀 Instalación

### Python

1. Instala las dependencias:
```bash
pip install -r requirements.txt
```

2. Ejecuta el script:
```bash
python joke_generator.py
```

### JavaScript/Node.js

1. Asegúrate de tener Node.js instalado

2. Ejecuta el script:
```bash
node joke_generator.js
```

## 💡 Ejemplos de Uso

### Python

```python
from joke_generator import get_random_joke

# Obtener una broma aleatoria
get_random_joke()
```

### JavaScript

```javascript
const { getRandomJoke } = require('./joke_generator.js');

// Obtener una broma aleatoria
getRandomJoke();
```

## 🌐 API Utilizada

- **Nombre:** JokeAPI
- **URL:** https://v2.jokeapi.dev/
- **Tipo:** Pública y sin autenticación requerida
- **Categorías:** Any, Miscellaneous, Knox, General, Programming, etc.

## 📝 Ejemplo de Salida

```
🎭 ¡Generador de Bromas Aleatorias!
----------------------------------------

😂 Broma:
Why don't scientists trust atoms?
Because they make up everything!
```

## 🔧 Estructura del Proyecto

```
├── joke_generator.py      # Script en Python
├── joke_generator.js      # Script en JavaScript
├── requirements.txt       # Dependencias de Python
└── JOKE_GENERATOR_README.md  # Este archivo
```

## 📚 Referencias

- [JokeAPI Documentación](https://jokeapi.dev/)
- [Python Requests Library](https://requests.readthedocs.io/)
- [JavaScript Fetch API](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)

## ⚖️ Licencia

Este proyecto es de código abierto y está disponible para uso educativo y personal.

---

¡Diviértete con las bromas! 😄
