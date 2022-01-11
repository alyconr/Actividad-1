# Actividad-1

## Ejercicio 1

1.  Crea un nuevo fork del proyecto del curso
    
    [Ver fork](https://github.com/alyconr/Javascript-Course.git)
    
2.  Crea un nuevo archivo llamado aboutme.js

    [aboutme.js](https://github.com/alyconr/Actividad-1.git)
    
3.  Crea un script en ese fichero con tres variables (elige un nombre descriptivo para cada una). La primera almacenará tu nombre y apellidos, la segunda tu profesión y la tercera     el puesto que querrías desempeñar o el que desempeñas actualmente.

    ```bash
    let nombres = 'Jeysson Aly';
    let apellidos = 'Contreras Rodriguez';
    let profesion ='Ingeniero Electrónico';
    ```
    
4. Crea una nueva variable que almacene una cadena, que mediante template literals incluya esta frase con las variables: Hola, me llamo [variable del nombre] y me dedico a            [variable profresión]. Estoy cursando este Máster porque me gustaría trabajar en [variable del puesto]
   
    
   ```bash
   function target() {
    let aboutme = `Mi nombre es ${nombres} ${apellidos} , mi Profesión es ${profesion} estoy cursando este Master porque  quiero desempeñarme en  el puesto de ${targetprofile}`; 
        }
    target();
   ``` 
  
5. Muestra por pantalla esta última variable.
  
     ```bash 
     function target() {
    let aboutme = `Mi nombre es ${nombres} ${apellidos} , mi Profesión es ${profesion} estoy cursando este Master porque  quiero desempeñarme en  el puesto de                       ${targetprofile}`; 
    console.log(aboutme)
    }
    target();
    //salida: Mi nombre es Jeysson Aly Contreras Rodriguez , mi Profesión es Ingeniero Electrónico estoy cursando este Master porque  quiero desempeñarme en  el puesto de          Ingeniero DevOps
   ``` 
6.  Importa tu fichero aboutme.js en el fichero index.js en la parte del Ejercicio 1 antes del console.log("Ej 1").
    
    En Index.js incluimos:
    
    ```bash
    // Ejercicio 1
    import {target}  from "./aboutme.js";

    console.log("Ejercicio");

    // Ejercicio 2

    // Ejercicio 3

    // Ejercicio 4

    // Ejercicio 5

    // Ejercicio 6
    
    
    ```
    En Aboutme.js incluimos "export":
    ```bash
    export function target() {
    let aboutme = `Mi nombre es ${nombres} ${apellidos} , mi Profesión es ${profesion} estoy cursando este Master porque  quiero desempeñarme en  el puesto de ${targetprofile}`; 
    console.log(aboutme)
    }
    target();
    
    ```
    ![Ver Imagen](https://imgur.com/cnJmsav.jpg)


## Ejercicio 2

 Se requiere un navegador con herramientas de desarrollador:

1. Abre el navegador seleccionado y dirígete a la sección de Actividades/Actividad 1.
2. Abre la sección de Sources en las herramientas web, dirígete al fichero aboutme.js que creaste en la sección anterior y añade unos cuantos breakpoints en el script que has      creado.
3. Añade también un breakpoint en la importación de este fichero en index.js.
4. Añade un breakpoint más en console.log(“Ej 1”).

 Evidencia de los anteriores enunciados:
 
 ![Ver Imágen](https://imgur.com/dPIyp5t.jpg)
 
5. ¿Qué se ejecuta antes, la llamada a console.log() o el contenido del fichero aboutme.js?
   Se ejecuta el contenido del fichero aboutme.js
   
## Ejercicio 3

Enumera 3 herramientas útiles dentro de las herramientas de desarrollo de Google Chrome o Mozila Firefox (inspector, consola, networking…) y explica su funcionamiento.

### ELEMENTS

Muestra el código HTML utilizado para crear la página que se esta viendo. 
![VER IMAGEN](https://imgur.com/ZxYae3p.jpg)

### CONSOLE
Brinda información sobre los elementos interactivos en una página, en esta herramienta podemos escribir código JavaScript para interactuar con la página que se está viendo, nos permite escribir mensajes que luego aparecen en console para mostrar que se ejecutó el js.

![VER IMAGEN](https://imgur.com/cnJmsav.jpg)

### SOURCES

Muestra donde se almacenan todos los archivos que se utilizaron para hacer el sitio web y permite inspeccionarlos.

![VER IMAGEN](https://imgur.com/82Q8Qsf.jpg)

## Ejercicio 4

Programa un script que imprima todos los números del 1 al 100 que sean divisibles por 7.

```bash
  for( var i=1 ; i<=100; i++){
    if (i % 7 === 0) {
        console.log(i);
        }
      }
```

## Ejercicio 5
¿Cuál es la diferencia entre ejecutar un fichero JavaScript en un navegador web en formato <script> y en formato <script type=”module”>?.
    
AL utilizar type="module" podemos utilizar modulos que usaremos para escribir en ficheros independientes , con esto podemos importar o exportar codigo de modulos externos.       Lo    anterior es sumamente importante ya que los módulos nos permiten organizar el código de diversas formas. 
    
## Ejercicio 6
 
Crea un objeto llamado formatter con un atributo, que llamaremos prefix, que tendrá de valor “Hello “, y un método que llamaremos append, que imprimirá la concatenación entre el atributo prefix y la cadena que pasemos como argumento en el método.
formatter.append(“World”) // Result: Hello World
```bash
    
    let formatter = {
    preffix: "Hello",
    prototype: "",
    append: function(){
        formatter.append(`World`)
        formatter.toLowerString(`I’m Lucas`)  
    }
        }
```
    

    
  
    
    
    

  



    

  

   
  
