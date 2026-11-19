# UD 1: Tarea de Git y GitHub
Este es un proyecto creado para la práctica de utilización, control y familiarización con Git.
Incluye una página principal con una introducción, un menú de navegación, y una tabla con horarios de clase.

## Tabla de Contenidos
- [Tecnologías Utilizadas](#tecnologias-utilizadas)
- [Instalación](#instalación)
- [Mejoras Implementadas](#mejoras-implementadas)

## Tecnologías Utilizadas
-  HTML5

## Instalación
Este proyecto no requiere instalar ningún tipo de servicios externos (servidores, dependencias, etc.) debido a que es un proyecto únicamente desarrollado en HTML. <br>
Para obtener una copia local en tu dispositivo:

### **1.** Clona el repositorio en tu equipo local:
```bash
git clone https://github.com/ubedapau-cdfp/UD1Tarea.git
```

### **2.** Accede al directorio del proyecto:
```bash
cd UD1Tarea
```

### **3.** Ejecuta el archivo `index.html`
Hay dos maneras de ejecutar el archivo, dependiendo de la manera que tú prefieras:
- **Mediante el Explorador de Archivos** <br>
Haz doble clic en el archivo `index.html`. El archivo se abrirá automáticamente en tu navegador predeterminado.
- **Mediante la Terminal**
    - **Windows:**
    ```bash
    start index.html
    ```
    - **Linux:**
    ```bash
    xdg-open index.html
    ```
    
## Mejoras Implementadas

### Menú de Navegación
- Incluye un menú de navegación con los tres diferentes apartados:
    - _Inicio_
    - _Ejercicios_
    - _Prácticas_

Al hacer clic en una de las tres opciones te lleva a su apartado debido al uso de `<a href="apartado">`. La vinculación a los apartados en la página se ha ejecutado mediante un `id="inicio` dentro de los `<section>`.

### Tabla con Horarios
- Incluye una tabla con los horarios de nuestra clase, mostrando los descansos de cada día y las asignaturas.
- Para la organización semántica de la tabla se ha utilizado `<thead>` y `<tbody>`.
- Para la especificación de número de celdas que hay en cada tabla se ha utilizado `<th rowspan="n">` (siendo "n" el número asignado).
- Para añadirle un borde a la tabla se ha utilizado `<table border="1">`, debido a que sólo se podia usar HTML para el proyecto.