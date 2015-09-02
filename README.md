# PHPclass
first problem solving

/*
------------------------------------------------------
problem 1:
------------------------------------------------------
*/

for($i=0; $i<=2000; $i++)
{
    if($i%7 == 0)
 {
     echo $i. "<br>";
 }
}

/*
-----------------------------------------------------
problem 2:
------------------------------------------------------
*/

for($i=1; $i<=4; $i++)
	
{
	
	for($x=1; $x <= $i; $x++)
	{
		echo "x";
	}
	
	echo "<br>";
}


for($i=3; $i>=1; $i--)
{
	for($x=1; $x<=$i; $x++)
	{
		
		echo "x";
	}
	
	echo "<br>";
}

/*
------------------------------------------------------
problem 3:
------------------------------------------------------
*/

$result = 101;

switch ($result) 

{
	case $result >= 0 && $result < 60:
        echo "You are fail";
        break;
	
	
	case 59 > $result || $result < 61:
        echo "You are pass";
        break;
	
	
    case 60 > $result || $result < 71:
        echo "You are pass with grade D";
        break;

    case 70 > $result || $result < 81:
        echo "You are pass with grade C";
        break;

	case 80 > $result || $result < 91:
        echo "You are pass with grade B";
        break;

	case 90 > $result || $result <= 100:
        echo "You are pass with grade A";
        break;
	
	default:
        echo "wrong input";


}

/*
--------------------------------------------------
problem : 4
--------------------------------------------------
*/

$num = 123456;
$sum = 0;


while ($num > 0)
{
    $sum= $sum + ($num % 10);
    $num= $num / 10;

}

if (($sum % 7) == 0)
{
	echo "You are lucky";
}else{
	
	echo "Sorry!!! better luck next time";
}
