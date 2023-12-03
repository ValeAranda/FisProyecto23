<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Administración de Finanzas</title>
  <style>
    /* Aquí podrías agregar estilos CSS si los necesitas */
  </style>
</head>
<body>
  <h1>Detalle de Gastos Semanales</h1>
  
  <button id="btnDetalle" onclick="mostrarDetalleDiaEspecifico()">Ver Detalle por Día</button>

  <div id="detalleGastos" style="display: none;">
    <!-- Aquí se desplegarán los detalles de los gastos -->
  </div>

  <script>
    function mostrarDetalleDiaEspecifico() {
      // Aquí podrías agregar lógica para mostrar el detalle de gastos por día
      // Por ahora, solo un mensaje de ejemplo
      document.getElementById('detalleGastos').innerHTML = '<p>Detalles de gastos del día seleccionado...</p>';
      document.getElementById('detalleGastos').style.display = 'block';
    }
  </script>
</body>
</html>

