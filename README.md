<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8">
</head>
<body>
    <script>
        /** Funcion para calcular si el numero es multiplo utilizando el modulo de la division*/

        function multiple(valor, multiple)
        {
            resto = valor % multiple;
            if(resto==0)
               return true;
            else
               return false;
       }
        // Arrays que contendran los valores multiples del 3 y del 5
        var multiples_3=[];
        var multiples_5=[];
        var multiples_4=[];

        // bucle del 1 al 1000

        for(var i=1;i<=1000;i++)
        {
            if(multiple(i,3))
              multiples_3.push(i);

            if(multiple(i,5))
                multiples_5.push(i);

            if (multiple(i,4))
            	multiples_4.push(i);

        }

        document.write("Los multiplos de 3 son: ",multiples_3);

        document.write("<br>Los multiplos de 5 son: ",multiples_5);
         
         document.write("<br>Los multiples de 4 son:", multiples_4);

          
    </script>
 
</body>

</html>
