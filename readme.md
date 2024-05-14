# Laboratorio Módulo 1. HTML.

El objetivo de este laboratorio es realizar la maquetación de una página web de ropa.
Podemos entender que existen 3 partes claramente diferenciadas. Una barra de navegación, un cuerpo principal con los productos y un footer.

El orden de trabajo y las actuaciones son las siguientes:

1. Crear repositorio remoto y local.

    - Crear repositorio remoto en Github.
        - Lo de siempre: ponemos nombre al repo; elegimos Publico, sin readme.md
    - Clonar reposositorio remoto

        ```
        /* git bash terminal */
        git clone [SSH]
        ```

    - Iniciar git

        `git init`

    - Crear archivo index.html
    - Crear archivo styles.css
    - Crear archivo readme.md
    - Add, commit, push

      ```
      git add .
      git commit -m "Primer commit. Subiendo archivos iniciales"
      git push -u origin main


      ```
> [!NOTE]
> A partir de este punto, empezamos a trabajar en las 3 areas anteriormente citadas. Navegación, cuerpo principal y footer. Empezamos por el cuerpo que es la pieza clave, ya que tiene que ser responsive, y esta parte nos proponemos hacerla sin media queries.

2. Creación del cuerpo principal de los productos.

    - importamos la fuente Montserrat
    - conectamos el archivo css con el html.
    - creamos directorio assets
    - creamos directorio assets/icons, y subimos los iconos
    - creamos directorio assets/images, y subimos las imagenes

> [!TIP]
> Para que la section main sea responsive y dos posibilidades:
>   - Con media queries
>   - Sin media queries usando:
>  `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));`


  - en este caso usaremos la opción segunda sin media queries

  ```css
  .products{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1rem;
  justify-items: center;
  background-color: aquamarine;
}
```


    


