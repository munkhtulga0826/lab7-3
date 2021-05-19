# lab7-3
<html>
<head>
<meta charset="UTF-8" />
<script>
 {
            let number = window.prompt("too ug")
            if (number == 2) {
                console.log(2);
                return false;
            }
            for (i = 2; i <= parseInt(number); i++) {
                let isPrime = true;
                let sum = 0;
                let counter = 0;
                for (j = 2; j < parseInt(i / 2); j++) {
                    if (i != j) {
                        if (i % j == 0) {
                            isPrime = false;
                        }
                    }
                }
                if (isPrime) {
                    console.log(i);
                    sum = sum + i;
                }

            }
            console.log('niilber is: ' + sum);

        }
</script>
</head>
<body>
</body>
</html>
