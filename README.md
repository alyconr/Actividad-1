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


    

  

   
  
