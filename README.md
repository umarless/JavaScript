<!DOCTYPE html>
<head>
<title>Learning JavaScript</title>
</head>
<body>
<script>
"use strict";

//Prime Number

function isPrime(n){
  for( let i = 2, i < n, i++) {
    if( n % i == 0) { continue; }

  return i;
  }
}

function showPrime(n) {
  if (isPrime(n)) alert( "Prime" )
alert( "Not Prime" );
}

let n = prompt("Enter Number : ", "");
showPrime(n);

</script>
</body>
</html>

