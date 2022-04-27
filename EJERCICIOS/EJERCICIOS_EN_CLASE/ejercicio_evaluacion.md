![image](https://user-images.githubusercontent.com/91554777/165175601-f95d8714-091a-4687-a21b-70a75beae3ea.png)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Título de página</title>
    </head>
    <body>

        <header>
            <h1>ENCABEZADO NIVEL 1</h1>
            <nav>
                <ul>
                    <li><a href="">ENLACE 1</a></li>
                    <li><a href="">ENLACE 2</a></li>
                    <li><a href="">ENLACE 3</a></li>
                    <li><a href="">ENLACE 4</a></li>
                </ul>
            </nav>
        </header>


        <main>

            <article>
                <h2>Encabezado nivel 2</h2>
                <p>Aqui va el texto del primer <b>Párrafo</b></p>
                <p>Aqui va el texto del segundo párrafo</p>
            </article>

            <aside>
                <h2>Apartado</h2>
                <p>Elige una opción</p>
                <form action="">
                    <input type="radio" name="opcion">Opción 1 <br>
                    <input type="radio" name="opcion">Opción 2 <br>
                    <input type="radio" name="opcion">Opción 3 <br>
                    <input type="submit" value="Enviar">
                </form>
            </aside>

        </main>


        <footer>
            <p>Sección de información de contacto, derechos de autor, etc</p>

        </footer>

    </body>
    </html>


## AGREGA EL CSS NECESARIO A LA PÁGINA.


*{margin: 0;
padding: 0;}

.espacio{padding: 20px;
border: 2px solid white;}
header{background-color: black;
padding: 0px;
margin: 0px;}
h1 {text-align: center;
font-weight: 1000;  
color: rgb(224, 255, 224);
font-family: 'Lato', sans-serif;
padding: 20px;
}
nav{list-style-type: none;
text-align: center;
background-color: rgb(224, 255, 224);
font-family: 'Lato', sans-serif;
float: inherit;
padding-top: 20px;
padding-bottom: 20px;
padding-left: 0px;
padding-right: 0px;
}
nav li{display: inline;
text-align: center;
margin: 0 35px 0 ;
}
.borde{border: 2px solid white;
}
#azul{color: rgb(50, 50, 248);}
article{color: black;
background-color: rgb(0, 208, 255);
text-align: center;
font-family: 'Lato', sans-serif;
float: left;
min-height: 200px;
padding: 20px;
width: 70%;
margin-top: 20px;
}
article p{font-family: 'Poppins', sans-serif;
}
aside{color: black;
background-color: rgb(241, 10, 137);
text-align: center;
font-family: 'Lato', sans-serif;
float: right;
min-height: 220px;
padding:10px ;
width: 20%;
margin-top: 20px
}
aside p{margin-bottom: 20px;}
.boton{padding: 10px;}
footer{color: black;
background-color: yellow;
text-align: center;
font-family: 'Lato', sans-serif;
float: inherit;
margin-top: 20px;}
