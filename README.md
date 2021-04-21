# scrap
Hi, I am Nicolas 
I was using a Linkedin scraping script which stopped working yesterday
The script I was using is :    
function addConnection(inputs, i) { setTimeout(function() { inputs[i].click(); }, i * 50); } function start() { var inputs = document.getElementsByClassName("button-secondary-small"); for(var i = 0; i < inputs.length; i++) { addConnection(inputs, i); } setTimeout(function() { var objDiv = document.getElementsByClassName("core-rail")[0]; window.scrollTo(0, objDiv.scrollHeight); setTimeout(function() { start(); }, 1000); }, inputs.length * 50); } start();
      I hope someone can help 
Thanks
Nicolas
