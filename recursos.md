# Recursos para Julia

- Sitio web principal para todo lo que es Julia: http://www.julialang.org

- Usar Julia en línea:
    - JuliaBox: http://next.juliabox.com (sin instalar nada)
    - CoCalc:  http://cocalc.com (incluye modo colaborativo)


- Instalar Julia localmente:    
    - Bajar e instalar la versión estable (0.6.2) desde http://www.julialang.org/downloads
    - Luego corre Julia e instalar el notebook de Jupyter:
    ```
    julia> Pkg.add("IJulia")
    ```
    - Abrir el notebook:
    ```
    julia> using IJulia
    julia> notebook()
    ```

- Aprender Julia:
    - Lista de recursos: http://www.julialang.org/learning
    - Cheatsheets (primeros dos en la sección de Recursos)
    - Notebooks de tutorial disponibles adentro de JuliaBox o [aquí](https://github.com/xorJane/Introduction_to_Julia_tutorials)


- Entornos integrados para desarrollar código de Julia:
    (Software libre, disponible en cualquier plataforma):
    - [Juno IDE](http://junolab.org/)
    - [Visual Studio Code Julia plugin](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia) 
