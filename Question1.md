<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
    border: 1px solid black;
}
</style>
</head>
<body>


<table style="width:15%">
  <tr>
    <th>TICKER</th>
    <th>PRICE</th>
  </tr>
  <tr>
    <td>WIPRO</td>
    <td>298.45</td>
  </tr>
  <tr>
    <td>INFY</td>
    <td>949.95</td>
  </tr>
  <tr>
    <td>TCS</td>
    <td>2713.70</td>
  </tr>
   <tr>
    <td>TECHM</td>
    <td>485.85</td>
  </tr>
</table>

<h1>Stock Trading</h1>

<table style="width:15%">
<form >

  <tr>
    <th>TICKER:</th>
    <th>
    <input type="text"  name="field" /> 
    </th>
  </tr> 
  <tr>
    <th>Quantity:</th>
    <th>
    <input type="number" name="points" step="10" min="10" max="100">
    </th>
  </tr> 
  <tr>
    <th><input type="submit">
    </th>
  </form>

</table>
</body>
</html>
