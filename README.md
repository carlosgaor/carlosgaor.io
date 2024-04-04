# carlosgaor.io

<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="author" content="carlosgarcia@a.vedrunasevilla.sj">
<meta name="copyright" content="Propietario del copyright">
<meta name="description" content="exámen Carlos Garcias ">
<meta name="robots" content="index">
<meta name="robots" content="follow">
<title>carlos garcia's examen</title>
    <style>
        body{
            background-image: url(fondo.jpg);
        }
        header{
            position: sticky;
            top: 0;
            background-color: rgb(163, 35, 78);
            color:white;
            margin-bottom: 20px;
            height: 50px;
            
        }
        ul{
            text-align: center;
            position: sticky;
            list-style: none;
            display: flex;
            margin: 30px;
            width: 100%;
        }
        li{
            padding: 10px;
            color: white;
        }
        a{
            padding: 10px;
            color: white;
        }
        p{
            text-align: justify;
        }
        .sector2{
            background-color: rgb(255, 255, 255);
            width: 100%;
            height: 500px;
            overflow: hidden;
            margin: 0 auto;
            padding: 10px;

            background-color: aquamarine;
            border-radius: 10px;
            border-top: 5px solid rgb(34, 34, 32);
            color: white;
            margin-bottom: 10px;
        }
        .sector2 h2 {
            height: 28px;
            text-align: center;
        }
        .sector2 img{
            width: 300px;
            height: 300px;
            padding-left: 10%;
        }
        .sector2 p{
            size: 14px;
            color: black;
            text-align: left;
        }
        figure {
            margin: 0 auto;
            display: flex;
            width: 100%;

        }

        figure div {
            width: 100%;
        }
        figure h2{
            color: rgb(40, 41, 30);
            text-align: justify;
        }
        
        figure div img {
            width: 100%;
            height: 100%;
            border-top-right-radius: 20px;
            border-top: 5px solid rgb(103, 104, 104);
        }
        .sector3{
            margin-top: 15px;
            padding-top: 5px;
            height: 290px;
        }   
        .sector3 h2{
            text-align: center;
            color: rgb(161, 72, 150);
        }

        .formu {
            width: 30%;
            height: 300px;
            margin: 0 auto;
            margin-top: 5px;
            border-radius: 34px;

            background-color: rgb(52, 82, 85);
            padding: 15px;
        }

        .formu div {
            margin: 30px;
        }
        input {
            float: right;
            width: 70%;
        }

        label {
            color: white;
            float: left;
            width: 30%;
        }

        #boton {
            width: 100%;
            height: 35px;
            background-color: black;
            color: white;
        }

        footer{
            margin-top: 120%;
            background-color: rgb(163, 35, 78);
            color: white;
            width: 100%;
            height: 290px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
        }
        footer img{
            margin-top: 40px;
            margin-right: 250px;
            float: right;
            width: 240px;
            height: 200px;
            border-top-left-radius: 40px;
        }
        .lista {
            float: left;
            margin-top: 30px;
            width: 30%;
            height: 150px;
            text-align: center;
        }

        #Gracias{
            position: sticky;
            text-align: center;
            height: 50px;
            background-size: cover;
            
            font-size: 25px;
            letter-spacing: 7px;

            text-shadow: 1px 1px rgb(134, 124, 124);
        }

    </style>

</head>
    <body>
        <header>
            <div>
                <ul>
                    <li><u><a href="https://www.w3.org/" target="_blank" name="Web del Consorcio">Página oficial del colegio</a></u></li>
                    <li> <u> <a href="https://www.w3.org/" target="_blank" name="Web del Consorcio">Sección FP</u></li>
                    <li> <u> <a href="https://www.w3.org/" target="_blank" name="Web del Consorcio">Guias didacticas</u></li>
            </div>
        </header>
        <a href="https://www.w3.org/" target="_blank" name="Web del Consorcio"> 

        <div class="sector2">
            <figure>
                <div>
                    <a> <h2> OBJETIVOS</h2>
                        <img src="Objetivo.jpg" alt="objetivos">
                        <p>Para alcanzar exitos y metas, hay que lanzarse unos objeticos,<br>con ellos podremos saber exactamente lo que queremos
                            y tener<br> una ide de como conseguirlo
                        </p>
                    </a>
                </div>
                <div>
                    <a> <h2> REUNIÓN</h2>
                        <img src="reunion.jpg" alt="reunion">
                        <p>Es vital para un equipo de trabajo las reuniones, ya que con estas <br> intercambiamos las distintas visiones del
                            proyecto, además de avanzar en conjunto, reduciendo tiempos
                        </p>
                    </a>
                </div>
                <div>
                    <a> <h2> LANZAMIENTO</h2>
                        <img src="reunion_lanzamiento.jpg" alt="reunion lanzamiento">
                        <p>La última reunión sirve para preparse para el lanzamiento <br> o presentación de nuestro proyecto,
                            haciendo a esta una de las partes más importantes
                        </p>
                    </a>
                </div>
            </figure>
        </div>
        <hr>
        <div class="sector3">
            <h2> SOLICITE INFORMACIÓN AQUÍ</h2>
            <div class="Contenedor">
                <div class="formu">
                        <div>
                            <label for="name">Nombre y apellidos :</label>
                            <input type="text" placeholder="Nombre">
                        </div><br>
                        <div>   
                            <label for="email">Email  :</label>
                            <input type="email" placeholder="Email">
                        </div>
                        <br>
                        <div>
                            <label for="tel">Teléfono  :</label>
                            <input type="tel" name="telefono" placeholder="Número">
                        </div><br>
                        <br><center><textarea placeholder="Tu mensaje..." rows="4" cols="60" placeholder="Mensaje" id="mensaje"></textarea><br><br>
                        </center><br>
                        <button type=submit id="boton">Enviar</button>
                </div><br>
            </div>
            <div></div>
    </body>

    <footer>
        <div class="lista">
            <ol> <div id="Gracias"> GRACIAS POR SU VISITA</div></ol>
            <li>Aspectos legales
             -  Política de privacidad
            </li>
            <li>Sobre nosotros</li>
            <li>Donde estamos</li>
            <li>Acceso a las diferentes redes sociales</li>
        </div>
        <img src="iconos.jpg"> <br>
        &copy; 21/12/2023 Carlos García Ortega    
    </footer>

</html>
carlosgarcia.html
Mostrando carlosgarcia.html.
