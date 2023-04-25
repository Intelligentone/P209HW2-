

const origArray = [2, 3, 4];
document.addEventListener("DOMContentLoaded", function() {
  document.getElementById("B1").value = origArray[0];
  document.getElementById("B2").value = origArray[1];
  document.getElementById("B3").value = origArray[2];

  document.getElementById("Square").addEventListener("click", function() {
    const squareArray = origArray.map(function(num) {
      return Math.pow(num, 2);
    });
    document.getElementById("B1").value = squareArray[0];
    document.getElementById("B2").value = squareArray[1];
    document.getElementById("B3").value = squareArray[2];
  });
  
  document.getElementById("Cube").addEventListener("click", function() {
    document.getElementById("B1").value = Math.pow(origArray[0], 3);
    document.getElementById("B2").value = Math.pow(origArray[1], 3);
    document.getElementById("B3").value = Math.pow(origArray[2], 3);
  });
  document.getElementById("Tothe4th").addEventListener("click", fourthPower);
});

function fourthPower() {
  document.getElementById("B1").value = Math.pow(origArray[0], 4);
  document.getElementById("B2").value = Math.pow(origArray[1], 4);
  document.getElementById("B3").value = Math.pow(origArray[2], 4);
}

