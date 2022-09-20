// Decalre the Variable in temp
var temp=[]
// Fuction using call 
function range(a,b)
{
// For Loop Using can pass Array 
  for (var i=a;i<=b;i++)
  {
// temp metheod using add to the array
  temp.push(i)
}
//A return statement can return a value
return temp;
}
// This is a using print a output
console.log(range(4,7));
console.log(range(-4,7));
