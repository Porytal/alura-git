

<!DOCTYPE html>
<html>

    <head>
        <meta charset="utf-8">
        <title>Contacto - Barberia Alura</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <header>
            
            <div class="caja">
            <h1><img src="imagenes/logo.png"></h1>
            <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="productos.html">Productos</a></li>
                <li><a href="contacto.html" class="active">Contacto</a></li>  <!-- Agregamos la clase active para resaltar la opción seleccionada --> 
            </ul>  <!-- Cerramos la etiqueta ul --> 

            </nav> <!-- Cerramos la etiqueta nav --> 

             </div><!-- Cerramos la etiqueta div --> 

        </header><!-- Cerramos la etiqueta header --> 

        
        <main><!-- Agregamos una etiqueta main para contener el formulario de contacto -->  

            <form action="" method="post"><!-- Agregamos un atributo action y method al formulario para que se envíe correctamente los datos-->  

                <!-- Agregamos un atributo for a cada label para que estén asociados con el input correspondiente-->  

                <label for="nombreapellido">Nombre y Apellido</label>  <!-- Cambiamos el nombre del label de nombre a nombreapellido-->  

                <input type="text" id="nombreapellido" name = "nombreyapellido"><!-- Agregamos un atributo name al input para que se envíen los datos correctamente-->  

                <!-- Repetimos los pasos anteriores con