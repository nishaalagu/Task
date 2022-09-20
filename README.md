Write a JavaScript function to generate an array between two integers of 1 step length.
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

Write a JavaScript program to find the most frequent item of an array.
// Declare The variable
var arr1=[3, 'q', 'q', 'q', 2, 3, 'q', 3, 'q', 2, 4, 9, 3];
var a = 1;
var b = 0;
var item;
// For Loop Using can pass Array
for (var i=0; i<arr1.length; i++)
{
//  For Loop Using can pass Array
      for (var j=i; j<arr1.length; j++)
        {
          // if using check the condition 
                if (arr1[i] == arr1[j])
                 a++;
                if (a<b)
                {
                  a=b; 
                  item = arr1[i];
                }
        }
        b=0;
}
// display the ouptut 
console.log(item+" ( " +a+" times ) ") ;
