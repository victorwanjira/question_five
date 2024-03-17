# question_five
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <script language="javascript">
          /*Question 5: Reverse Integer
      Write a program that takes an integer as input and returns an integer with reversed digit 
      ordering.
      Examples:
      For input 500, the program should return 5.
      For input -56, the program should return -65.
      For input -90, the program should return -9.
      For input 91, the program should return 19.
      */

      
    function num(){
      var number=prompt('Enter a number');
    const i = parseInt
    (Math.abs(number).toString().split('')
    .reverse().join(''));
    document.write(i);
    return number < 0 ? -i : i;

    
    }
    
  </script>
</head>
<body>
  <button onclick="num()">reverse to interger</button>
</body>
</html>
