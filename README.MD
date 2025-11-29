# README.md  Just do it (del repositorio Trabajopedroe1)

Minimal todo app — interfaz oscura, centrada y sin dependencias
HTML + CSS + JavaScript puro — lista para abrir en tu navegador

🧾 Introducción

Este repositorio contiene una página web minimalista tipo “Just do it.” donde el usuario puede agregar tareas, marcarlas como completadas y eliminarlas. El objetivo es una UI moderna, limpia y centrada con estilo oscuro, implementada únicamente con HTML, CSS y JavaScript (sin frameworks ni librerías)

Ideal como ejercicio pequeño de DOM, eventos y accesibilidad

# ✨ Características principales

Título grande y claro: “Just do it”

Input para escribir tareas y botón I Got This! para agregarlas

Lista dinámica de tareas que incluye

Botón circular ✔ para marcar como completada

Ícono 🗑️ para eliminar la tarea

Las tareas completadas aparecen con texto tachado y menor opacidad

Todo el layout está centrado y con estética clean UI en modo oscuro

Archivo único: toda la página (HTML, CSS y JS) se entrega en index.html.

📂 Estructura del repositorio
Trabajopedroe1/
├─ index.html        
├─ README.md         # (este archivo)

#  🚀 Cómo usar / ejecutar

Clona o descarga el repositorio:

git clone https://github.com/Santiagosixhoundred/Trabajopedroe1.git


Abre index.html en tu navegador (doble clic o File -> Open).

Escribe una tarea en el campo de entrada y pulsa I Got This! (o Enter).

Marca tareas con ✔ o elimínalas con 🗑️.

No necesita servidor ni instalación adicional.

🧠 Comportamiento y funciones JavaScript 

El index.html implementa —al final del <body>— las tres funciones solicitadas

addTask()
Añade una tarea nueva a la lista si el input no está vacío Crea los elementos necesarios (texto, botón ✔, ícono 🗑️) y asegura que los controladores de evento funcionen correctamente aunque la tarea sea creada dinámicamente

toggleComplete(event)
Marca o desmarca una tarea como completada. Ajusta la clase CSS que aplica texto tachado y opacidad reducida.

deleteTask(event)
Elimina la tarea del DOM (el nodo padre adecuado) de forma segura.


# ♿ Accesibilidad y UX

Los botones usan aria-label para describir su función (ayuda a lectores de pantalla).

El input permite enviar con Enter.

Contraste de colores pensado para legibilidad en modo oscuro.

Tamaños de control adecuados para interacción en táctil y desktop.