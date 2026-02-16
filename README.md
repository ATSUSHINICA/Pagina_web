# 📘 Proyecto Web – *Hollow Knight*  
### **Trabajo HTML + CSS – Segunda Evaluación**  
**Autores:** José, Wilson y Alejo

---

# 🧱 1. Estructura del proyecto

El proyecto está organizado siguiendo las buenas prácticas y los requisitos del profesor:

```
/hollow-knight-web/
│
├── index.html
│
├── pages/
│   ├── personajes.html
│   ├── zonas.html
│   ├── habilidades.html
│   └── registro.html
│
├── css/
│   └── estilos.css
│
├── img/
│   ├── personaje1.jpg
│   ├── zona1.jpg
│   └── ...
│
└── README.md
```

---

# 🎮 2. Temática del proyecto: *Hollow Knight*

La web está dedicada al videojuego **Hollow Knight**, incluyendo:

- Personajes principales  
- Zonas del mapa  
- Habilidades del Caballero  
- Formulario de registro para “nuevos exploradores”  
- Galería de imágenes homogéneas  
- Tabla con estadísticas combinadas  

Esto permite cumplir **todos los requisitos del profesor** de forma natural y vistosa.

---

# 🟦 José – Estructura HTML (100% del HTML)

José es responsable de **toda la estructura HTML del proyecto**, asegurando que cumple los requisitos del profesor y que valida correctamente en W3C.

### ✔️ Tareas de José
- Crear **index.html** con:
  - Imagen principal del juego
  - Menú horizontal (estructura)
  - Encabezados
  - Enlaces internos, externos y anclas
- Crear las páginas dentro de `/pages/`:
  - `personajes.html`
  - `zonas.html`
  - `habilidades.html`
  - `registro.html`
- Crear:
  - Tabla con `rowspan` y `colspan` (por ejemplo, estadísticas de personajes)
  - Listas: `<ol>`, `<ul>`, `<dl>`
  - Formulario base (estructura sin estilos)
- Añadir metadatos en todas las páginas:
  - `<title>`
  - autor
  - descripción
  - palabras clave
  - UTF-8
- Asegurar que **todo valida en W3C**
- Mantener la estructura limpia, ordenada y legible

### ✔️ Archivos que José modifica
```
index.html
pages/*.html
```

---

# 🟩 Wilson – CSS completo (100% del diseño)

Wilson es responsable de **todo el diseño visual** del proyecto.

### ✔️ Tareas de Wilson
- Crear `estilos.css`
- Dar estilo al menú horizontal:
  - Fondo
  - Borde
  - Hover
  - Enlace visitado
- Unificar estilos de todas las páginas
- Estilizar:
  - Tabla
  - Formulario
  - Listas
  - Encabezados
- Hacer que las imágenes sean homogéneas (mismo tamaño sin deformar)
- Elegir tipografías, colores, márgenes, paddings, etc.
- Garantizar que el diseño no rompe la estructura HTML

### ✔️ Archivos que Wilson modifica
```
css/estilos.css
```

---

# 🟧 Alejo – Contenido, imágenes y formulario avanzado

Alejo se encarga de **rellenar contenido**, añadir imágenes y completar el formulario con controles avanzados.

### ✔️ Tareas de Alejo
- Añadir imágenes homogéneas en `/img/`
- Rellenar contenido en:
  - `personajes.html`
  - `zonas.html`
  - `habilidades.html`
- Completar el formulario con:
  - Input numérico con step
  - Select con 5 opciones
  - Radios (2 grupos)
  - Checkboxes
  - Selector de color
  - Selector de fecha/hora
  - Selector de mes
  - Input file
  - Botón enviar
  - Botón reset
- Revisar que los enlaces funcionen
- Asegurar coherencia del contenido

### ✔️ Archivos que Alejo modifica
```
img/*
pages/personajes.html (solo contenido)
pages/zonas.html (solo contenido)
pages/habilidades.html (solo contenido)
pages/registro.html (solo controles del formulario)
```

---

# 🔧 4. Flujo de trabajo en Git (sin errores)

Cada miembro trabaja en **su propia rama**:

- José → `jose`
- Wilson → `wilson`
- Alejo → `alejo`

NADIE trabaja en `main`.

---

# 🟦 4.1. Comandos que deben usar ANTES de empezar a trabajar cada día

### 📌 1️⃣ Cambiar a su rama
Wilson:
```
git checkout wilson
```
Alejo:
```
git checkout alejo
```

### 📌 2️⃣ Descargar los últimos avances del proyecto


```
git checkout alejo
git pull origin main

```

Esto asegura que trabajan con la versión más reciente del proyecto.

---

# 🟩 4.2. Comandos que deben usar DESPUÉS de terminar su trabajo del día

### 📌 1️⃣ Guardar los cambios
```
git add .
git commit -m "Contenido añadido en personajes"
git push origin alejo
```

### 📌 3️⃣ Crear un Pull Request en GitHub
- De su rama → hacia `main`
- José revisa y aprueba

---

# 🟥 4.3. ¿Quién hace los merges?

👉 **José es el revisor oficial del proyecto.**  
Solo él aprueba y fusiona los Pull Requests.

Esto evita errores y mantiene `main` estable.

---

# 🟨 5. Reglas para evitar conflictos

- Nadie toca `main`
- Nadie hace commits en `main`
- Cada uno trabaja en su rama
- Todo se revisa antes de fusionar
- Si hay conflicto, se resuelve en la rama personal
- Siempre actualizar la rama antes de trabajar

---

# 🏆 6. Cómo garantizamos el 10

✔️ Estructura perfecta  
✔️ HTML validado  
✔️ CSS unificado  
✔️ Imágenes homogéneas  
✔️ Tabla con combinaciones  
✔️ Formulario con más de 10 controles  
✔️ Menú horizontal con hover y visited  
✔️ Metadatos en todas las páginas  
✔️ Código limpio y ordenado  
✔️ Git bien gestionado  
✔️ README profesional (este)


