# Registro de actividades club de tareas
 <html lang="es">    
<head>    
  <meta charset="utf-8">    
  <meta name="viewport" content="width=device-width, initial-scale=1">    
  <title>Servicios Sociales Registro</title>    
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">    
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>    
  <style>    
    body {    
      padding: 20px;    
    }    
    h1 {    
      color: #0d6efd; /* Azul Bootstrap */    
    }    
    .blue-row { background-color: #cce5ff; }    
    .pink-row { background-color: #f8d7da; }    
    .red-row { background-color: #f5c6cb; }    
    .imagen {    
      max-width: 100%;    
      height: auto;    
      border: 2px solid #333;    
      border-radius: 10px;    
      margin-top: 20px;    
    }    
    input[type="file"] {    
      margin-top: 20px;    
      padding: 10px;    
      background-color: #4CAF50;    
      color: white;    
      border: none;    
      border-radius: 5px;    
      cursor: pointer;    
    }    
    input[type="file"]:hover {    
      background-color: #45a049;    
    }    
    textarea {    
      width: 95%;    
      height: 120px;    
      resize: vertical;    
    }    
  </style>    
</head>    
<body>
  <h1>¡Bienvenidas/dos al registro de club de tareas!</h1>

  <div class="mb-3">
    <label for="email" class="form-label">Añade una cuenta</label>
    <input type="email" class="form-control" id="email" placeholder="name@example.com">
  </div>

  <div class="mb-3">
    <label for="nombreCompleto" class="form-label">Nombre completo</label>
    <input type="text" class="form-control" id="nombreCompleto" placeholder="Escribe tu nombre completo">
  </div>

  <!-- Campo de selección de biblioteca -->
  <div class="mb-3">  
    <label for="nombreBiblioteca" class="form-label">Nombre de la biblioteca</label>  
    <select class="form-select" id="nombreBiblioteca">  
      <option value="" selected>Selecciona una biblioteca</option>  
      <option value="José Luis Álamo Jardón">José Luis Álamo Jardón</option>  
      <option value="Rafael Moreno Montes de Oca">Rafael Moreno Montes de Oca</option>  
      <option value="Guillermina Nateras López">Guillermina Nateras López</option>  
      <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>  
      <option value="Dr. Urban Boutelegier">Dr. Urban Boutelegier</option>  
      <option value="Michel D’Hooghe">Michel D’Hooghe</option>  
      <option value="Santa Teresita del Niño Jesús">Santa Teresita del Niño Jesús</option>  
      <option value="Biblioteca Santiago Tlacotepec">Biblioteca Santiago Tlacotepec</option>  
      <option value="Biblioteca Santiago Tlaxomulco">Biblioteca Santiago Tlaxomulco</option>  
      <option value="Biblioteca Tecaxic">Biblioteca Tecaxic</option>  
      <option value="Ludoteca San Cristóbal Huichochitlán">Ludoteca San Cristóbal Huichochitlán</option>  
      <option value="Museo Municipal de Calixtlahuaca">Museo Municipal de Calixtlahuaca</option>  
      <option value="Museo del Alfeñique">Museo del Alfeñique</option>  
      <option value="Lic. Jaime Almazán Delgado">Lic. Jaime Almazán Delgado</option>  
      <option value="José María Heredia y Heredia">José María Heredia y Heredia</option>  
      <option value="Leonardo Sánchez Montaño">Leonardo Sánchez Montaño</option>  
      <option value="Otomitl">Otomitl</option>  
      <option value="Concepción García Valdez">Concepción García Valdez</option>  
      <option value="Sor Juana Inés de la Cruz">Sor Juana Inés de la Cruz</option>  
      <option value="Mercedes López Gómeztagle">Mercedes López Gómeztagle</option>  
      <option value="Edelmira Nava Arellano">Edelmira Nava Arellano</option>  
      <option value="Profa. Laura Beatriz Benavides">Profa. Laura Beatriz Benavides</option>  
      <option value="Agustín María Lebrija">Agustín María Lebrija</option>  
      <option value="Rodolfo García Gutiérrez">Rodolfo García Gutiérrez</option>  
      <option value="Laura Méndez de Cuenca">Laura Méndez de Cuenca</option>  
      <option value="Mercedes Carrasco">Mercedes Carrasco</option>  
      <option value="Fray Andrés de Castro">Fray Andrés de Castro</option>  
    </select>  
  </div>

  <!-- Campo de selección de delegación / cobertura -->
  <div class="mb-3">  
    <label for="coberturaAtencion" class="form-label">Cobertura de atención / Delegación</label>  
    <select class="form-select" id="coberturaAtencion">  
      <option value="" selected>Selecciona la delegación o cobertura</option>  
      <option value="San Lorenzo Tepaltitlán">San Lorenzo Tepaltitlán</option>  
      <option value="Santa Cruz Atzcapotzaltongo">Santa Cruz Atzcapotzaltongo</option>  
      <option value="San Mateo Oxtotitlán, Nueva Oxtotitlán">San Mateo Oxtotitlán, Nueva Oxtotitlán</option>  
      <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>  
      <option value="San Diego de los Padres Cuexcontitlán">San Diego de los Padres Cuexcontitlán</option>  
      <option value="San Cayetano Morelos">San Cayetano Morelos</option>  
      <option value="Morelos, Sánchez">Morelos, Sánchez</option>  
      <option value="Santiago Tlacotepec, San Juan Tilapa">Santiago Tlacotepec, San Juan Tilapa</option>  
      <option value="Santiago Tlaxomulco">Santiago Tlaxomulco</option>  
      <option value="Tecaxic">Tecaxic</option>  
      <option value="San Cristóbal Huichochitlán">San Cristóbal Huichochitlán</option>  
      <option value="Toluca, Estado de México, México y extranjero">Toluca, Estado de México, México y extranjero</option>  
      <option value="La Maquinita, Santiago Miltepec">La Maquinita, Santiago Miltepec</option>  
      <option value="Cacalomacán">Cacalomacán</option>  
      <option value="San Mateo Otzacatipan">San Mateo Otzacatipan</option>  
      <option value="Tlachaloya">Tlachaloya</option>  
      <option value="San Martín Toltepec">San Martín Toltepec</option>  
      <option value="Independencia">Independencia</option>  
      <option value="Capultitlán, Moderna de la Cruz">Capultitlán, Moderna de la Cruz</option>  
      <option value="San Andrés Cuexcontitlán">San Andrés Cuexcontitlán</option>  
      <option value="San Antonio Buenavista, San Buenaventura">San Antonio Buenavista, San Buenaventura</option>  
      <option value="San Pablo Autopan">San Pablo Autopan</option>  
      <option value="Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril">Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril</option>  
      <option value="Calixtlahuaca, San Marcos Yachihuacaltepec">Calixtlahuaca, San Marcos Yachihuacaltepec</option>  
    </select>  
  </div>
     <h2 style="text-align:center;">Plan de Septiembre - Octubre 2025</h2>    
<table class="table table-bordered">    
  <thead>
    <tr>    
      <th>Semana</th>    
      <th>Actividad</th>    
      <th>Fecha</th>    
      <th>Numero de asistentes</th>    
      <th>Nota informativa</th>    
      <th>Evidencia fotográfica</th>    
    </tr>
  </thead>
  <tbody>
    <!-- Semana 1 -->
    <tr>
      <td>Semana 1</td>
      <td>Domina tu tema</td>
      <td>Miércoles 3 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 1</td>
      <td>Practica en voz alta</td>
      <td>Jueves 4 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 2 -->
    <tr>
      <td>Semana 2</td>
      <td>Visualiza el éxito</td>
      <td>Miércoles 10 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 2</td>
      <td>Respiración profunda</td>
      <td>Jueves 11 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 3 -->
    <tr>
      <td>Semana 3</td>
      <td>Adopta una postura de poder</td>
      <td>Miércoles 17 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 3</td>
      <td>Canaliza tu energía</td>
      <td>Jueves 18 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 4 -->
    <tr>
      <td>Semana 4</td>
      <td>Haz pausas intencionadas</td>
      <td>Miércoles 24 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 4</td>
      <td>Varía el tono y el ritmo</td>
      <td>Jueves 25 Septiembre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 5 -->
    <tr>
      <td>Semana 5</td>
      <td>Utiliza notas clave</td>
      <td>Miércoles 1 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 5</td>
      <td>Establece contacto visual</td>
      <td>Jueves 2 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 6 -->
    <tr>
      <td>Semana 6</td>
      <td>Sonríe</td>
      <td>Miércoles 8 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 6</td>
      <td>Sé honesto contigo mismo</td>
      <td>Jueves 9 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>

    <!-- Semana 7 -->
    <tr>
      <td>Semana 7</td>
      <td>Capacitación</td>
      <td>Miércoles 15 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
    <tr>
      <td>Semana 7</td>
      <td>Inicio de la siguiente etapa</td>
      <td>Jueves 16 Octubre 2025</td>
      <td><input type="checkbox"></td>
      <td><textarea placeholder="Escribe aquí la nota informativa..."></textarea></td>
      <td><input type="file" accept="image/*"></td>
    </tr>
  </tbody>
</table>
  <p class="mt-4">
    <strong>Nota:</strong> La hora límite para la entrega de sus actividades es hasta las <strong>6:00pm</strong>. En caso de que se entreguen después del tiempo límite, su actividad se tomará como entrega extemporánea.      
    <br>Si desean expandir su entrega a más tiempo, solicítenlo con la Lic. Laura Isela Díaz Bernal.
  </p>

</body>    
</html>
