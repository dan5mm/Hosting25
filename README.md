<!DOCTYPE html>
<html>
<head>
  <title>Listado de Productos</title>
  <style>
    /* Estilos para la tabla */
    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 8px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    /* Colores empresariales */
    body {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    th {
      background-color: #333;
      color: #fff;
    }

    td.codigo {
      background-color: #ddd;
    }

    td.precio {
      background-color: #e0e0e0;
    }

    td.existencia {
      background-color: #f5f5f5;
    }
  </style>
</head>
<body/>
  <h1>Listado de Productos</h1>
  <table>
    <tr>
      <th>Código</th>
      <th>Nombre</th>
      <th>Precio</th>
      <th>Existencia</th>
    </tr>
    <tr>
      <td class="codigo">001</td>
      <td>Jabon</td>
      <td class="precio">Q10.00</td>
      <td class="existencia">10 unidades</td>
    </tr>
    <tr>
      <td class="codigo">002</td>
      <td>Shampoo</td>
      <td class="precio">Q15.00</td>
      <td class="existencia">5 unidades</td>
    </tr>
    <tr>
      <td class="codigo">003</td>
      <td>Toallas Humedas</td>
      <td class="precio">Q20.00</td>
      <td class="existencia">2 unidades</td>
    </tr>
    <tr>
        <td class="codigo">003</td>
        <td>Desinfectante</td>
        <td class="precio">Q12.00</td>
        <td class="existencia">2 unidades</td>
      </tr>
      <tr>
        <td class="codigo">003</td>
        <td>Crema Hidratante</td>
        <td class="precio">Q25.00</td>
        <td class="existencia">2 unidades</td>
      </tr>
  </table>
</body>
</html>
