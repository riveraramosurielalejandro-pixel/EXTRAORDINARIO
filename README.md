<html>
<head>
<title>Ejemplo de HTML 1 con Frames</title>
</head>

<!-- Definimos la estructura de marcos: 2 filas -->
<frameset rows="20%, 80%">
  <!-- Marco superior -->
  <frame src="cabecera.html" name="arriba">
  
  <!-- Marco inferior dividido en 2 columnas -->
  <frameset cols="25%, 75%">
    <frame src="menu.html" name="lado">
    <frame src="contenido.html" name="principal">
  </frameset>

  <!-- Etiqueta para navegadores que no soportan marcos -->
  <noframes>
  <body>
    <p>Tu navegador no soporta marcos, por favor actualízalo para ver el contenido correctamente.</p>
  </body>
  </noframes>
</frameset>

</html>
