# lab7-3
<html>
<head>
<meta charset="UTF-8" />
<script>
   function isPrime(n)
{
    if (n <= 1)
        return false;
    for (let i = 2; i < n; i++)
        if (n % i == 0)
            return false; 
    return true;
}
function printPrime(n)
{
    for (let i = 2; i <= n; i++) {
        if (isPrime(i))
            document.write(i +" ");
    }
} 
    let n = window.prompt('toogoo oruul');
    printPrime(n);                         
       for(var n = 2; n <= numArgOne; n++) {
      if(isPrime(n)) {
          prime.push(n);
      }      
    }  
    function isPrime(numArgTwo) {
      for (var j = 2; j < numArgTwo; j++) {
        if (numArgTwo% j === 0) {
          return false;
        }
      }
      return true;
    }    
  return prime;  
}                     
</script>
</head>
<body>
</body>
</html>
