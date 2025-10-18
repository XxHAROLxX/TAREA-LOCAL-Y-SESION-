# Lista de Tareas (Práctica)

Pequeña aplicación web para gestionar tareas usando LocalStorage y SessionStorage.

Archivos:
- `todo.html` - página HTML con lógica en JavaScript.

Cómo usar:
1. Abrir `todo.html` en un navegador (doble clic o arrastrar al navegador).
2. Escribir una tarea en el input y pulsar "Agregar" o Enter.
3. Marcar tareas como completadas con la casilla o eliminarlas con "Eliminar".
4. Seleccionar el filtro: "Todas", "Completadas" o "Pendientes".

Comportamiento esperado:
- Las tareas se guardan en LocalStorage y persisten al cerrar el navegador.
- El filtro se guarda en SessionStorage: se mantiene mientras la pestaña esté abierta, y se reinicia si la pestaña se cierra.

Verificaciones sugeridas:
- Agregar varias tareas, cerrar el navegador y volver a abrir el archivo: las tareas deberían seguir ahí.
- Cambiar el filtro y recargar la pestaña: el filtro seleccionado se mantendrá; cerrar la pestaña y abrir una nueva debería resetear el filtro a "Todas".

Notas:
- El código es minimalista y usable en cualquier navegador moderno.
- Claves de storage: `mis_tareas_v1` (LocalStorage) y `tareas_filtro_v1` (SessionStorage).