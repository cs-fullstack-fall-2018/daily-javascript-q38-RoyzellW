# daily-javascript-q38

You have the following HTML page: 
```html
<!DOCTYPE html> 
<html> 
<head> 
      <title>Intro to JavaScript</title> 
          	<meta charset="utf-8" /> 
</head> 
<body> 
      <script> 
           var letters = ["A", "B", "D", "F", "N", "R", "T", "C", "O", "P"]; 
           var x = letters.shift(); 
           var u = letters.splice(1, 3); 
           letters.push("E"); 
           console.log(letters); 
      </script> 
</body> 
</html> 
```

What shows in the console when the page is loaded in the browser?

Choose the correct answer

1) Array [ "B", "R", "T", "C", "O", "P", "E" ]
2) Array [ "A", "N", "R", "T", "C", "O", "P", "E" ]
3) Array [ "B", "N", "R", "T", "C", "O", "P", "E" ]
4) Array [ "A", "N", "R", "T", "C", "O", "E" ]

ENTER ANSWER HERE!!!
I don't get it; shift removes the first element in the array
splice is removing 1-3 or 1, and 3 but index 1 is B if A is still inside. and index 1 is D if it is not. and that would make either F or N 3. but they are both still in the answer. and if you ignore the fact that all you did was creare new variables for x and u you are left with letters.push and console.log(letters) which should return the whole array but with an E at the end. It doesn't make any since. You created new variables using letters but it didnt overwrite the letters array.  and then even if i look at it with the concept of noticing that splice removes the letter B[1] and F[3] IT DOESNT CHANGE THE FACT THAT A IS NOT SUPPOSED TO BE THAT!! Answer A is missing an F! Answer B is not supposed to have an A. Answer C is not supposed to have an N. And Answer D is not supposed to have a FREAKING A! Ya know what ima just pick C and call it. I just want you to know that directly after i submit this im logging this crap! e.e


FINAL ANSWER AFTER MY RANT IS C!!! 
