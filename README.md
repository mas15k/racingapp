<!doctype html>
<html>
<head>
<script>
function add()
{
  var numOne, numTwo, sum;
  numOne = parseInt(document.getElementById("first").value);
  numTwo = parseInt(document.getElementById("second").value);
  sum1 = numOne * numTwo * 0.6;
  sum2 = numOne * numTwo * 0.3;
  sum3 = numOne * numTwo * 0.1;
  document.getElementById("answer1").value = sum1;
  document.getElementById("answer2").value = sum2;
  document.getElementById("answer3").value = sum3;
}
</script>
</head>
<body>

<p>Enter number of racers: <input id="first"></p>
<p>Enter buy in: <input id="second"></p>
<button onclick="add()">Finish</button>
<p>1st = <input id="answer1"></p>
<p>2nd = <input id="answer2"></p>
<p>3rd = <input id="answer3"></p>

<img src="https://i.imgur.com/LJnZ5KS.png" alt="Trulli" width="500" height="333">

</body>
</html>
