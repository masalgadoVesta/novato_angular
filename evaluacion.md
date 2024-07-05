# Evaluación Práctica Novato Angular

## Ejercicio 1: Crear un Componente Básico

### Descripción:
Crea un componente llamado UserProfile que muestre el nombre y la edad de un usuario. Debe incluir una propiedad para el nombre y otra para la edad, y mostrar estos valores en el HTML.

### Instrucciones:

- Crea un nuevo componente llamado UserProfile.
- En el archivo TypeScript del componente, define dos propiedades: userName y userAge.
- En el archivo HTML del componente, muestra las propiedades userName y userAge.

## Ejercicio 2: Directiva Personalizada

### Descripción:
Crea una directiva personalizada llamada appHoverHighlight que cambie el color de fondo de un elemento al pasar el ratón sobre él.

### Instrucciones:

- Crea una nueva directiva llamada appHoverHighlight.
- Utiliza el ElementRef y los decoradores HostListener para cambiar el color de fondo del elemento.
- El color de fondo debe cambiar a amarillo al pasar el ratón y volver al color original al retirarlo.

## Ejercicio 3: Servicio de Tareas
### Descripción:
Crea un servicio que maneje una lista de tareas (con título y descripción) y provea métodos para agregar, eliminar y obtener las tareas.

### Instrucciones:

- Crea un servicio llamado TaskService.
- Define una interfaz Task con propiedades title y description.
- Implementa métodos para agregar una tarea (addTask), eliminar una tarea (deleteTask), y obtener todas las tareas (getTasks).