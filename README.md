# lab7-3
<html>
<head>
<meta charset="UTF-8" />
<script>
    var n;
    n = window.prompt('toogoo oruul');
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
    let n = 7;
    printPrime(n);
</script>
</head>
<body>
</body>
</html>
