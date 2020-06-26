<?php
//declarar un entero n, calcular la suma de los n primeros numeros impares
$numero = 10;
$suma =0;
for($i = 0; $i <= $numero; $i++)
{
    if($i%2 != 0)
    {
        $suma += $i;
    }
}
echo "El resultado es $suma";
echo "<br><br>";
//declarar tres numeros y mostrarlos ordenados de mayor a menor
$num1 = 1;
$num2 = 2;
$num3 = 4;
$numMax = 0;
$numMin = 0;
$numMed = 0;
if(($num1 > $num2) && ($num1 > $num3))
{
    $numMax = $num1;
}
if(($num2 > $num1) && ($num2 > $num3))
{
    $numMax = $num2;
}
if(($num3 > $num1) && ($num3 > $num2))
{
    $numMax = $num3;
}
if(($num1 < $num2) && ($num1 < $num3))
{
    $numMin = $num1;
}
if(($num2 < $num1) && ($num2 < $num3))
{
    $numMin = $num2;
}
if(($num3 < $num1) && ($num3 < $num2))
{
    $numMin = $num3;
}

if($num1 > $num2 && $num1 < $num3)
{
    $numMed = $num1;
}
if(($num2 > $num1) && ($num3 > $num2))
{
    $numMed = $num2;
}
if(($num3 < $num1) && ($num3 > $num2))
{
    $numMed = $num3;
}
else
{
    echo " ";
}
echo "Los numeros ordenados son $numMax, $numMed, $numMin"
//declarar un numero entre 0 y 9.999 y decir cuantas cifrast tiene
$n = 7.123;
//Imprimir los 15 primeros numeros y escribir la suma total
/$suma = 0;
for($j=0; $j<=14 ; $j++)
{
    echo "$j -> ";
    $suma += $j;
} 
?>
