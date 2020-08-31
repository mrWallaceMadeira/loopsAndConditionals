# Gateway drug: loops + conditionals
Loops allow us to offload responsibility onto our computer.\
It will do things multiple times without us specifying _explicitly_ each time. Kinda nice.\
Conditionals make our programs "smart". We have the ability to execute certain bits of code based on conditions. Also cool.\
Combine the two & you've got the secret sauce of far more complicated programs.
###### Loops & conditionals in conversation
![sauce](noodleSauce.gif)

----
### Not new != easy
These topics aren't new, they'll just take practice & patience.\
Let's review the loops and conditionals we've seen thus far.
###### while loops
```

  // will run "while" condition is true
  
  while (condition) {
    do this thing;
    update this condition;
  }
```
Side note: what I've just done above is called pseudocode.\
It is like writing the draft of your english essay, omit the fanciness & just get the ideas on the page.
###### for loops
```
  for (setup variable; condition; update condition;) {
    do this thing;
  }
```
###### if/else
```  
  if (condition1) {
    do this thing;
    if (condition3) {
      do sum'n crazy;
    }
  }
  else if (condition2){
    do this thing;
  }
  else {
    do this thing;
  }
```
:eyes:&nbsp; be clear about which statements will execute under what conditions!\
  - _exempli gratia_: if condition1 & condition2 are both true, what will happen?
  
