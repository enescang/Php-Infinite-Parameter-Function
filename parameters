<?php
/*
*
@author canesnet.com
30.3.2019
*
You add three dot before $numbers,
now we can say this function can get infinite arguments
*/
function sum(...$numbers)
{
  //We will store all elements in $total
  $total = 0;

  //We get parameters step-by-step in foreach loop with $n
foreach ($numbers as $n) {
   //Every steps, we get one element and we are adding before elements
    $total =$total+ $n; //$total = $total+$n
}

//Finally, we return our $total variable
return $total;
}

//Calling sum function and displaying on the screen
 echo sum(4,6,7,7,6);
?>
