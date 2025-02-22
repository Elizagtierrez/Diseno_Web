## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets
          
          
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)

         
          b) <link rel="stylesheet" type="text/css" href="style.css">
          
          
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
          
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
         
          c) <style>
          
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

         
          b) styles
          
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

          
          b) body {color: black;}
          
          
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
         
          
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

          
          b) background-color
          
          
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
  
          
          b) h1 {background-color:#FFFFFF;}
          
  
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
          
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25
  
         
          c) font-size
         
  
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
  
         
          b) p {text-size:bold;}
         
  
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
  
         
          b) text-transform:capitalize
         
  
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
  
         
          b) font-family
         
  
15. ¿Cómo pones el texto en negrita? (valor 0.25)
  
          
          b) font:bold;
          
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
          a) border-width:10px 1px 5px 20px;
          
          
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

          
          b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            a) No
           
            
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
 
            
            b) #demo
            
            
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)


            b) .test
            
            
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

            
            b) div p
            
            
22.¿Cómo se agrupan los selectores? (valor 0.25)

            
            c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

           
            d) static
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
 
           
            c) list-style-type: square;
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/91554777/166742177-b3cc2bfc-7768-42e4-b4f0-dcc2a1473935.png)

● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


          INGRESA AQUI EL CÓDIGO HTML

                              <!DOCTYPE html>
                    <html lang="en">
                    <head>
                        <meta charset="UTF-8">
                        <meta http-equiv="X-UA-Compatible" content="IE=edge">
                        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                        <title>evaluacioncss</title>
                        <link rel="stylesheet" href="css/estilos.css">
                        <link rel="preconnect" href="https://fonts.googleapis.com">
                    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
                    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
                    </head>
                    <body>
                        <header>
                            <div class="logo">
                            <img src="img/logo.png" alt="" width="250px">
                            </div>
                            <hr>
                            <nav>
                                <ul>
                                    <li>Residentes</li>
                                    <li>Negocios</li>
                                    <li>Visitantes</li>
                                    <li>Gobierno</li>
                                </ul>
                            </nav>
                        </header>
                        <main>
                            <div class="texto">
                                <p>
                                  <span> <b>></b></span>APRENDER A PROGRAMAR <br>  EN LAS  <span><b>ESCUELAS <br> DE CÓDIGO</b></span>  <br> DE LA CDMX
                                </p>
                            </div>
                        </main>
                        <footer>
                            <h3>¿Quién se puede inscribir?</h3>
                            <p class="parrafo"><b>Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles a la semana.</b>  <br> *Menores de edad deberán entrar a las instalaciones acompañados de un adulto</p>
                        </footer>

                    </body>
                    </html>
          
          
          
          
          INGRESA AQUI EL CSS
          
                              *{margin: 0;
                    padding: 0;
                    font-family: 'Open Sans', sans-serif;}
                    header{
                        background-color: white;
                    }
                    .logo{display: flex;}
                    nav{display: flex;
                        justify-content: space-around;
                        width: 100%;
                    }
                    ul{list-style: none;
                    display: flex;
                    justify-content: flex-end;
                    text-align: end;
                    margin-left: 70%;
                    margin-top: 10px;
                    margin-top: 10px;
                    }
                    li{margin-right: 20px;
                        color: rgb(4, 68, 4);
                        font: bolder;
                    }
                    main{background: url("../img/hero.jpg");
                    background-size: cover;
                    padding: 50px;
                    margin-left: 20px;
                    margin-right: 20px;
                    margin-top: 20px;
                    }
                    .texto{width: 50%;
                        text-align: right;
                    }
                    .flecha{font-size: 70px;
                    font: bolder;
                    color: white;
                    }
                    p{color: white;
                    font: bold;
                    font-size: 50px;
                    font: bolder;
                    }
                    span{font-size: xx-large;
                    font-size: 70px;
                    font: bolder;}
                    footer{text-align: center;
                    }
                    h3{color: rgb(224, 149, 35);
                        margin-top: 20px;
                    }
                    .parrafo{color: rgb(56, 56, 56);
                    font-size: 15px;}
          
          
 Ingresa el link a tu página del proyecto final
 https://elizagtierrez.github.io/EjerciciofinalPilares/
