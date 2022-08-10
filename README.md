# ¡Nuestra primera App con Angular!

Este es un proyecto propuesto por el curso de **Argentina Programa** para poner en práctica gran parte de la teoría del módulo 3 (Desarrollo Front End Dinámico), haciendo nuestra primera SPA con Angular: Una **lista de tareas**. Incluye Angular ui y el JSON-server para nuestro backend simulado.

### Demo

![demo tutorial task list](src/assets/img/Demo-Tutorial-TaskList.png)

## Repasaremos los siguientes conceptos

1. Modulos
2. Componentes
3. Componente hijos
4. Style
5. Servicios
6. Routing
7. Binding

## Detalles a corregir del tutorial

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

## Usage

### Install dependencies

```
npm install
```

### Run Angular server (http://localhost:4200)

```
ng serve
```

### Run the JSON server (http://localhost:5000)

```
npm run server
```

### To build for production

```
ng build
```

## Recursos útiles

- [Traversy Media](https://www.youtube.com/watch?v=3dHNOWTI7H8) - Angular Crash Course.
