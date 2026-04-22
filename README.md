# 📒 Gestor de Contactos Web - CRUD con JavaScript

## 📖 Introducción

Aplicación web desarrollada para la gestión de contactos, permitiendo realizar operaciones básicas como crear, visualizar, editar y eliminar registros. El proyecto está construido con JavaScript puro (Vanilla JS), sin uso de frameworks, y utiliza almacenamiento local del navegador para conservar la información.

---

## ✨ Funcionalidades

### 🔄 Gestión de Contactos

- Agregar nuevos contactos  
- Mostrar lista de contactos en pantalla  
- Editar información existente  
- Eliminar contactos  

---

### 🎯 Interfaz de Usuario

- Diseño moderno con fondo degradado  
- Tarjetas visuales para cada contacto  
- Botones interactivos con efectos  

---

### 📋 Datos del Contacto

Cada registro incluye:

- Nombre  
- Apellido  
- Correo electrónico  
- Teléfono  
- Ciudad  
- Género  

---

### ✔️ Validaciones

- Campos obligatorios  
- Validación de correo electrónico  
- Validación de teléfono (entre 7 y 15 dígitos)  
- Indicadores visuales con CSS (`:valid` / `:invalid`)  

---

### 🔔 Experiencia de Usuario

- Formularios en ventanas tipo modal  
- Notificaciones tipo toast  
- Confirmación visual de acciones  

---

### 💽 Almacenamiento

- Uso de `localStorage`  
- Persistencia de datos al recargar la página  

---

### 📱 Diseño Responsive

- Adaptable a dispositivos móviles, tablets y escritorio  
- Uso de Flexbox y Grid  
- Organización automática de elementos  

---

## 📁 Estructura del Proyecto

index.html
assets/
├── css/
│ └── styles.css
└── js/
└── app.js

---

## 🧰 Tecnologías Utilizadas
- HTML5  
- CSS3 (Flexbox, Grid, Media Queries)  
- JavaScript Vanilla  
- Manipulación del DOM  
- localStorage  

---

## ▶️ Cómo Ejecutar
1. Descargar o clonar el proyecto  
2. Abrir `index.html` en el navegador  
3. Crear un nuevo contacto  
4. Guardar la información  

---

## 🧪 Ejemplo de Uso

**Datos ingresados:**
- Nombre: Carlos  
- Apellido: Pérez  
- Correo: carlos@email.com  
- Teléfono: 3124567890  
- Ciudad: Cali  

**Resultado:**
- Se muestra el contacto en una tarjeta  
- Aparece una notificación de éxito  
- Los datos quedan almacenados en el navegador  

---

## ⚙️ Buenas Prácticas
- Separación de HTML, CSS y JS  
- Código organizado y modular  
- Uso de `let` y `const`  
- Funciones reutilizables  
- Nombres claros y descriptivos  

---

## 🚀 Mejoras Futuras
- Buscador en tiempo real  
- Filtros por categorías  
- Imagen de perfil por contacto  
- Exportación a PDF o Excel  
- Implementación con IndexedDB  

---

## 👨‍💻 Autor
**Erika Andrea Erazo**  

Proyecto académico enfocado en la manipulación del DOM y almacenamiento local.