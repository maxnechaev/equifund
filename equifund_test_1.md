// Write a program/script that prints the numbers from 1 to 100.
// But for multiples of three print "MARS" instead of the number
// and for the multiples of five print "Works".
// For numbers which are multiples of both three and five print "MARSWorks".
// Use JavaScript or PHP to respond to this question
// (NOTE: we will execute the code, so please make sure it actually works!)

//jshint esversion:6

for (let i = 1; i <= 100; i++)
{
  const mars = "MARS";
  const works = "Works";
  if (i % 3 === 0 && i%5 === 0 )
  {
    console.log(mars + works);
  }
  else if ( i % 3 === 0 )
  {
    console.log(mars);
  }
  else if (i % 5 === 0 )
  {
    console.log(works);
  }
  else
  {
    console.log(i);
  }
}
