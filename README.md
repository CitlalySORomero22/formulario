# formulario
<form action="formulario.php" method="get">
    <H1 align="center"> FORMULARIO </H1>
  <p>Matricula: <input type="text" mat="matricula" size="40"></p>
  <p>Nombre: <input type="text" name="nombre" size="40"></p>
  <p>Primer apellido: <input type="text" pape="primer apellido" size="40"></p>
  <p>Segundo apellido: <input type="text" sape="segundo apellido" size="40"></p>
  <p>Edad: <input type="number" ed="edad" min="0-50"></p>
  <p>Fecha de nacimiento: <input type="text" fnac="fecha de nacimiento" size="40"></p>
  <p>Sexo:
    <input type="radio" name="hm" value="h"> Hombre
    <input type="radio" name="hm" value="m"> Mujer
  </p>
  <p>Estado: <input type="text" est="estado" size="40"></p>
  <input type="submit" value="Guardar">
