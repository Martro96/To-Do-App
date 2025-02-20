
# To Do List App

## Descripción

Esta es una aplicación web simple para gestionar tareas. Permite a los usuarios agregar tareas con un nombre, descripción, fecha de vencimiento, prioridad y estado (Sin empezar, En proceso, Terminada). Las tareas se organizan en columnas según su estado y se pueden visualizar en una lista de tareas dividida por columnas.

## Características

- **Agregar tareas**: Puedes ingresar tareas con nombre, descripción, fecha de vencimiento, prioridad y estado.
- **Organización por columnas**: Las tareas se organizan automáticamente en columnas: "Sin empezar", "En proceso" y "Terminadas".
- **Prioridad de tareas**: Las tareas tienen un nivel de prioridad que se indica por colores (rojo para alta, amarillo para media, y verde para baja).
- **Formato de fechas**: Las fechas se muestran en formato "día mes año" (por ejemplo, "29 enero 2025").

## Tecnologías utilizadas

- **HTML5**: Estructura de la página web.
- **CSS3**: Estilos para la interfaz de usuario.
- **JavaScript**:
  - **Vanilla JS**: Para la lógica de la aplicación.
  - **date-fns**: Para el formateo de las fechas.
- **DOM Manipulation**: Para agregar tareas y actualizarlas en el DOM.
- **ES Modules**: Utilizados para organizar el código en módulos.

## Instalación

Para instalar y ejecutar esta aplicación localmente, sigue estos pasos:

1. Clona este repositorio a tu máquina local:
   ```bash
   git clone https://github.com/Martro96/To-Do-App.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd to-do-list-app
   ```

3. Abre el archivo `index.html` en tu navegador. Puedes hacerlo directamente desde tu explorador de archivos o utilizando un servidor local como **Live Server** en VSCode.

4. Asegúrate de tener la librería `date-fns` instalada. Si no está instalada, puedes hacerlo con npm:
   ```bash
   npm install date-fns
   ```

## Uso

1. **Agregar tarea**: Rellena el formulario con el nombre de la tarea, descripción, fecha de vencimiento, prioridad y estado. Haz clic en "Añadir tarea".
2. **Ver tareas**: Las tareas se agregan a la columna correspondiente según su estado ("Sin empezar", "En proceso", "Terminadas").
3. **Prioridad**: Las tareas se etiquetan con colores según su prioridad (alta, media, baja).
4. **Fecha**: La fecha de vencimiento de cada tarea se muestra en formato "dd MMMM yyyy".

## Estructura del Proyecto

La estructura de carpetas del proyecto es la siguiente:

```
/to-do-list-app
|-- /assets            # Imágenes, iconos y otros recursos estáticos
|-- /scripts           # Archivos JavaScript
|   |-- /utils         # Funciones auxiliares como 'date-utils.js'
|   |-- main.js        # Lógica principal de la aplicación
|-- /styles            # Archivos CSS
|   |-- style.css      # Estilos generales
|-- index.html         # Página principal
|-- README.md          # Este archivo
```

## Contribuciones

Si deseas contribuir a este proyecto, puedes seguir estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu característica o corrección de error (`git checkout -b mi-rama`).
3. Haz tus cambios y haz commit de ellos (`git commit -am 'Añadir nueva característica'`).
4. Haz push a tu rama (`git push origin mi-rama`).
5. Crea un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## Agradecimientos

- Gracias a la librería [date-fns](https://date-fns.org/) para el formateo de fechas.
