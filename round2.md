## Welcome to my page



Augustus has gone to the store for cigs again
<br>
<br>
<!--- It took him  --->
<br>
<!--- 7d 5h 16m 47s --->
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
p {
  text-align: center;
  font-size: 60px;
  margin-top: 0px;
}
</style>
</head>
<body>

<p id="timer"></p>

<script>
// Set the date when our dude left us
var countDownDate = new Date("Feb 22, 2022 19:37:25").getTime();

// Update the count every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the when he left us
  var distance = now - countDownDate;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="timer"
  document.getElementById("timer").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";
   
}, 1000);
</script>

</body>
</html>
