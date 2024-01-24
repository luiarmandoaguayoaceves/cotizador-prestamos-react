# React + Vite
## configuracion

1. creacion de proyecto de react con vite
    `npm create vite`
    - nombre del proyecto
    - react
    - javascript

2. ejecucion del proyecto 
    `cd (ruta del archivo)`
    `npm install`
    `npm run dev`

3. instalar herramientas
    `npm install -D tailwindcss postcss autoprefixer`

4. inicializar con tailwindcss
    `npx tailwindcss init -p`

5. los  props funcionan para pasarle como parametros llamados props a las etiquetas o componentes creados por separado
   los state's son los eventos que se agregan como funciones como handlers donde se usan como onClick, onChange, etc... para los eventos.

6. UseEffect funcionan escuchando todo momento cambios en los valores se refomienda usar useEffect por separado apra cada actualizacion que necesites de esta manera se separan las los arreglos de dependencias para que sea mas comodo y no genera problemas haciendo el codigo mas limpio


7. para hacer el deployd se ejecuta el comando `npm run deploid` y genera una carpeta llamada dist que sera el proyecto minificado y listo para subir