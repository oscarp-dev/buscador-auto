# Buscador de Autos 🚗

Aplicación de filtrado dinámico construida con JavaScript vanilla. 
Permite buscar vehículos en tiempo real combinando hasta 7 filtros simultáneos.

## 🔗 Demo en vivo
[Ver proyecto →](https://buscador-autos.vercel.app)

## ⚙️ Tecnologías
- JavaScript (ES6+)
- HTML5 / CSS3
- DOM Manipulation
- Git & GitHub

## 🧠 Qué apliqué
- **Filtrado encadenado** con `.filter()` — cada filtro trabaja 
  sobre el resultado del anterior
- **Manipulación del DOM** — creación, inserción y limpieza 
  dinámica de elementos
- **Eventos** — captura de cambios en tiempo real con 
  `addEventListener`
- **Destructuring** de objetos dentro de iteraciones `forEach`
- **Separación de responsabilidades** — cada función hace 
  una sola cosa
- **Estado de la aplicación** con un objeto centralizado 
  `datosBusqueda` — patrón similar a `useState` de React

## 📁 Estructura
\`\`\`
buscador-autos/
├── index.html
├── js/
│   ├── app.js
│   └── db.js
└── css/
    └── app.css
\`\`\`
