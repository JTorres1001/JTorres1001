<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body id="body">
    <div class="selector-tema">
        <select name="" id="tema" onchange="cambiarTema()">
            <option value="light">Claro</option>
            <option value="dark">Oscuro</option>
            <option value="crazy">Loco</option>
        </select>
    </div>
    <div>
        <h1 class="color">Parte 1 Laboratorio</h1>
    </div>

    <div> 
        <h1>Tennis Air Jordan</h1>
        
    </div>
    
    <img class="imagen1" src="data:image/jpeg;base64,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" alt="">


<div> 
    <p>Air Jordan es una línea de calzado deportivo y ropa de la marca Nike, diseñada originalmente para el famoso jugador de baloncesto Michael Jordan de los Chicago Bulls en 19841​ y lanzado al público el 1 de abril de 1985.2​3​ Desde entonces, ha alcanzado un estatus icónico tanto en la cultura del baloncesto como cromado y cuero</p>
</div>
<div>
    <!-- lista ordenada -->
    <p>Lista de Servicios</p>
    <ol>
        <li>AIR JORDAN I 1985</li>
        <li>AIR JORDAN II 1986</li>
        <li>AIR JORDAN III 1988</li>
        <li>AIR JORDAN IV 1989</li>
        <LI>AIR JORDAN V 1990</LI>
        <LI>AIR JORDAN VI 1991</LI>
    </ol>
    <!-- lista desordenada -->
    <p>Datos de Contacto</p>
    <ul>
        <li>Información de la empresa y consultas 1-800-344-6453</li>
        <li>Productos y pedidos 01-800-806-6453</li>
        <li>NRC & NTC 7658948</li>
    </ul>
        
</div>
<a href="https://www.nike.com/es/jordan" target="_blank">ir a pagina oficial Air Jordan</a>
<div>
 <div>
    <iframe width="811" height="456" src="https://www.youtube.com/embed/MFbmOYkW6d8" title="Nike Jordan 1 Comercial" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
 </div>
<div>
    <audio controls>
        <source src="c:\Users\Cgrajales\Downloads\Y2meta.app - Complete - Jordan _ 8D AUDIO 🎧 (128 kbps).ogg" type="audio/ogg">
    </audio>
</div>
<div>
    <h1 class="color2">Parte 2 Laboratorio</h1>
</div>
<div>
    <H1>Formulario de Solicitud</H1>

    
    <form>
       
        <label for="">Nombre</label>
        <input type="text" placeholder="Digite Nombre"> 
        <br>
        <label for="">Cedula</label>
        <input type="number" required placeholder="Digite Cedula">
        <br>
        
        <label for="">Ciudad</label>
        <select name="" id="">
        <option value=""></option>
        <option value="Manizales">Manizales</option>
        <option value="Cartagena">Cartagena</option>
        <option value="Monteria">Monteria</option>
        <option value="Sincelejo">Sincelejo</option>
        <option value="Casanare">Casanare</option>
        </select>
         <br>
        <label for="">Telefono</label>
        <input type="number" required placeholder="Escriba Telefono">
        <br>
        <label for="">Direccion</label>
        <input type="text" placeholder="Escriba Direccion">
        <br>
        <label for="">Documento anexos</label>
        <input type="File" required>
        <br>
        <label for="">Fecha de nacimiento</label>
        <input type="date">
        <br>
        <hr>
    <h1>Formulario de contacto</h1>
    <form action="">
        <label for="">Nombre</label>
        <input type="text" name="nombre" id="nombre" required> <br>
        <label for="">Apellidos</label>
        <input type="text" id="apellidos">
        <button onclick="enviarFormulario()">Enviar</button>
    </form>
        <table class="enlace enlace:hover enlace:active">
            <tr>
                <th>Mes</th>
                <th>Ventas</th>
            </tr>
            <tr>
                <td>Enero</td>
                <td>300.000.000</td>
            </tr>
            <tr>
                <td>Febrero</td>
                <td>350.000.000</td>
            </tr>
        </table>
        <div>
            <h1>TABLA</h1>
            <table id="estilo-tabla">
                <tr>
                    <th>Nombre</th>
                    <th>Ciudad</th>
                    <th>Correo</th>
                </tr>
                <tr>
                    <td>Juan</td>
                    <td>Cali</td>
                    <td>JuanRock@gmail.com</td>
                </tr>
                <tr>
                    <td>Camilo</td>
                    <td>Villao</td>
                    <td>CamiloLpn@gmail.com</td>
                </tr>
                <tr>
                    <td>David</td>
                    <td>Medellin</td>
                    <td>davidgg@gmail.com</td>
                </tr>
            </table>
        </div>

</div>    
    
</body>

<style>
    .color {
        color: blue;
    }
    .color2 {
        color: red;
    }
    .imagen1{
    width: 20%;
    border-radius: 40px;
    border: 6px solid black;
    padding: 10px;
    outline-color: blue;
    outline-style: solid;

}
.enlace {
    text-decoration: underline;
    background-color: rosybrown;
    padding: 5px;
    border-radius: 5px;
    border-color: yellow;
    border-style: solid;
    display: inline-block;
    text-align: center;
    cursor: cell;

}
.enlace:hover {
    color: orange;
    text-decoration: none;

}
.enlace:active {
    color: aquamarine;
}
ul>li {
    list-style-type:georgian ;
    background-color: white;
    display: inline;
    visibility: initial;
}
ul {
    background-color: tomato;
    opacity: 0.6;
    padding: 20px;
}
table#estilo-tabla {
    border: 1px solid;
    width: 60%;
    text-align: center;
    border-collapse: collapse;
}
th, td {
    border: 1px solid;
    padding: 10px;
    
}
table#estilo-tabla tr:nth-child(even){
    background-color: white;
}
table#estilo-tabla tr:hover{
    background-color: yellow;
    color: blue;

}
table#estilo-tabla th{
    background-color: orange;
    color: wheat;
}
</style>
<script>
    function cambiarTema(){
        // Elemento que va cambiar
        var body = document.getElementById("body")
        // Valor del selector de temas
        var tema = document.getElementById("tema").value
        var fondo = ""
        var letra = ""
        if(tema == "light"){
            fondo = "white"
            letra = "black"
        } else if(tema == "dark"){
            fondo = "black"
            letra = "white"
        } else if(tema == "crazy"){
            fondo = "tomato"
            letra = "#CF1"
        }
        // Modificamos el estilo de la pagina
        body.style.backgroundColor = fondo
        body.style.color = letra
    }

    function enviarFormulario(){
        var nombre = document.getElementById("nombre").value
        var apellidos = document.getElementById("apellidos").value
        // Agregar los campos que faltan

        if(nombre && apellidos){
            alert("Los datos del formulario son: " + nombre + " " + apellidos)
        }
    }
</script>
</html>
