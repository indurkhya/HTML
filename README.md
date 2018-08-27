<!DOCTYPE HTML>
<html>
<head>  
  <script type="text/javascript">
  window.onload = function () {
    var chart = new CanvasJS.Chart("chartContainer",
    {
      title:{
      text: "Line Chart for Cricket Score"
      },
      data: [
      {        
        type: "line",
        lineColor:"red", 
        dataPoints: [
        { x: 5, y: 40 },
        { x: 10, y: 70 },
        { x: 15, y: 140 }
        ]
      }
      ]
    });

    chart.render();
  }
  </script>
 <script type="text/javascript" src="https://canvasjs.com/assets/script/canvasjs.min.js"></script></head>
<body>
  <div id="chartContainer" style="height: 300px; width: 80%;">
  </div>
</body>
</html>
