<?php 
// PHP Program to find sum of  
// elements in a given array
function sum( $arr, $n) 
{ 
    $sum = 0;

    for ($i = 0; $i < $n; $i++) 

    $sum += $arr[$i]; 

    return $sum; 
}

$arr =array(12, 3, 4, 15); 

$n = sizeof($arr); 

echo "Sum of given array is ",  

                sum($arr, $n); 
?> 
