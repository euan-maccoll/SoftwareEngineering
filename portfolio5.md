## Portfolio Week 5

### Meaningful Names
Using meaningful names means that the name is discriptive of the variable,class,function,etc it has been given.  
Using discriptive names allows others to have a better understanding of the function or class.

### Functions
Functions should be kept smaller so that they are easier to understand. This allows others to   
looks at the functions and understand them faster. To keep the functions small they should only do 1 thing.

### Comments
Comments should be used where it isn't immedially obvious what that section of code does. Comments shouldnt  
be used to be a replacement for bad code.

### Formatting
Formatting code improves the general readability of the code. With variables and functions there are different  
ways to lay them out. If a varibale is local then it should be at the top of the function and if global then  
should be at the top of the class. Functions should be near each other, a function that calls another should be above.
If a function is called by another then it should be below it.

### Error Handelling 
Error handelling should have try catch statements first to help define the overall scope of the function.  
It also helps the code user to understand what the code should be able to do.

### Unit Test's
With unit tests there are 3 other rules. The first law is you cant write code for the main program until you've  
written a test that has failed. The second law being that write tests that are able to fail this includes  
tests that arern't able to run becuase of syntax errors, logic errors,etc. The third law is when you write  
the required code to pass the unit test.

```
public class Character
{
    //! stores information about the character
    public int Level { get; private set; }

    public void LevelUp()
    {
        Level++;
    }

}
```

my edits to the code problem follow these clean code principles becuase the functions and the variables have  
meaningingful names that describe what they do well. The Fucntion levelup() is kept small and only does one  
main job. The comment made about the class is to further give information about what is stored about the  
character. The formating shows that the level variable and the levelup() function are both inside this also 
the code to be more readable to others. The unit testing allows the code to run as it is expected to, as  
this is very basic unit test.

By removing the special abillites list a comment has been saved as you dont need to explain that  
it would be used in future. The function levelup() dosen't need a comment becuase it is a smaller   
function that only has one purpose. Meaningful names have been used in with the functions,classes  
and variables so there is little need to use comments to explain what they do.

![Doxygen Output](https://github.com/euan-maccoll/SoftwareEngineering/blob/master/images/doxygen_output.png)  
This is the Doxygen output file documentation. This creates documentation faster than manually doing it.


This week i could have managed my time better by allocating more time to the portfolio instead of other  
activites. For the next portfolio files i will work on this.

