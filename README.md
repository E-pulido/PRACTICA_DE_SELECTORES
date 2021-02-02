# PRACTICA_DE_SELECTORES
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="style.css" rel="stylesheet" type=text/css
</head>
<body>
    <p>
        Párrafo sin class ni ide
       </p>
       <p class="cita" id="destacado">
        Párrafo con el class 'cita'
        y el id 'p_destacado'
       </p>
       <p class="p_destacado">Párrafo con el class
        destacado que no
        contiene nada
       </p>
       <p class="p_destacado">
        Párrafo con el class destacado.
        <span id="id1">
        Este texto va dentro de
        un span con el id id1
        </span>
       </p>
       <p class="destacado">
        <ol>
        <li class="elemento_numeracion">
        Esto es un li
        </li>
        <li class="elemento_numeracion">
        Esto es otro li
        </li>
        </ol>
       </p>
       <p class="destacado">
        Este párrafo tiene el class
        destacado y en él enumeramos
        cosas como
        <span class="elemento_numeracion">
        A
        </span>,
        <span class="elemento_numeracion">
        B
        </span> o también
        <span class="elemento_numeracion">
        C
        </span>
       </p>
       <div class="destacado">
        Aquí hay un
        <span id="id1">
        span con el id id1
        </span>
       </div>
       
    
</body>

<style>
  p#destacado{
    border:solid black 1px;
    margin-right: 600px;
   }
p.destacado{
    border:solid black 1px;
    margin-right: 600px;
}
span#id1{
    border:solid black 1px;
    margin-right: 600px;
}
li.elemento_enumeracion{
    border:solid black 1px;
    margin-right: 600px;
}

#id1{
    border:solid black 1px;
    margin-right: 600px;
}
  </style>
</html>
