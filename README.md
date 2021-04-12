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
}                     
</script>
</head>
<body>
    <a href="https://munkhtulga0826.github.io/lab7/">bod<a>
  <a href="https://munkhtulga0826.github.io/lab7-2/">bod2<a>
   <a href="https://munkhtulga0826.github.io/lab7-4/">bod4<a>
    <a href="https://munkhtulga0826.github.io/lab7-5/">bod5<a>
</body>
</html>
