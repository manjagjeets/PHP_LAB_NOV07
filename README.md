$pokemonattackstrenght=rand(1,100);
echo "pokemon attack strenght is |".$pokemonattachstrnght;



for ($counter=0; $counter<100; $counter++) {
 
  $pokemonattachstrenght=rand(1,100);
  if (  $pokemonattachstrenght>50){
 echo"pokemon attack strenght  is ".$pokemonattachstrenght;
 
    }}  







<?php
    $userINPUT=17;$userINPUT=17;
    for($userINPUT=0; $userINPUT<100; $userINPUT++ )
        {
          $pokemonattackstrength=rand(1,100);
 
echo "pokmonstrengthis ". $pokemonattackstrength;
if($userINPUT>$pokemonattackstrength)
{
echo "user input is"   .$userINPUT;
echo "POKEMON atttack sgtrength is".$pokemonattackstrength. "\n\r";  
 }  
 }
    ?>


<?php
class Rectangle
{
public $length =0;
public $width =0;

//method to get the area
public function getperimeter()
{
return (2*($this->length*$this->width));
}
//method to get the area
public function getarea(){
return($this->length*$this->width);
}}
$obj = new rectangle;
//get the object properties values
echo $obj->length;//output:0
echo $obj->width;//output:0

//set object prperties values
$obj->length=30;
 $obj->width=20;

//read the object propertiesx values again toshow the change
echo $obj->length;//output:30
echo $obj->width;//output:20

//call the object
echo $obj->getperimeter();//output:100
echo $obj->getarea();//output:600
?>



<?php
class Pokemon
{
public $pokemonname;
public $pokemontype;

//method to get the area
public function pokemonattack()
{
return (rand(1,100));
}
}
$psiduck = new Pokemon ;

$psiduck->Pokemonname="psiduck" ;
$psiduck->Pokemontype="psychic pokemon";

echo "Pokemonname".$psiduck ->Pokemonname."nr";
echo "Pokemontype".$psiduck ->Pokemontype."nr";
echo" pokemonattackstrength".$psiduck->pokemonattack();






<?php
class Pokemon
{
public $pokemonname;
public $pokemontype;

//method to get the area
public function pokemonattack()
{
return (rand(1,100));
}
}
$psiduck = new Pokemon ;

$psiduck->Pokemonname="psiduck" ;
$psiduck->Pokemontype="psychic pokemon";

echo "Pokemonname".$psiduck ->Pokemonname."\n\r";
echo "Pokemontype".$psiduck ->Pokemontype."\n\r";
echo" pokemonattackstrength".$psiduck->pokemonattack();
