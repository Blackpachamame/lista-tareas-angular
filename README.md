# ¡Nuestra primera App con Angular!

Vamos a poner en práctica gran parte de la teoría haciendo nuestra primera SPA con Angular: Una **lista de tareas** como la que se ve a continuación

![demo tutorial task list](src\assets\img\Demo-Tutorial-TaskList.png)

En este tutorial repasaremos los siguientes conceptos:

1. Modulos
2. Componentes
3. Componente hijos
4. Style
5. Servicios
6. Routing
7. Binding

### Detalles corregidos del tutorial

Modificar en `styles.css` (css global)

```
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap");

body {
  font-family: "Poppins", sans-serif;
}
```

Modificar en `task-item.component.ts`

```
@Input() task!: Task;
```

### Recursos útiles

- [Traversy Media](https://www.youtube.com/watch?v=3dHNOWTI7H8) - Angular Crash Course.
