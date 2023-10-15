## Portfolio 6  

This week we fixed a hangman game and wrote unit tests for it.  
  
The onAttemptSubmitted() function checks if the letter is in a word and if it is then,  
the checkletterinword() function returns true and the display is updated. If the letter  
isn't in the word then it reduces the amount of remaining attempts you have and if its none  
then the game ends.

```
        [Fact]
        public void rightsubmittionletter()
        {
            GamePage gamepage = new("Easy");

            gamepage.AnswerEntry = "e";
            gamepage.Word = "Testword";
            

            gamepage.OnAttemptSubmitted(null EventArgs.Empty)
            int updatedAttemptsRemaining = gamepage.attemptsremaining

            Assert.AreEquel(7, updatedAttemptsRemaining);            
        }
```
```
[Fact]
        public void wrongsubmitionletter()
        {
            GamePage gamepage = new("Easy");

            gamepage.AnswerEntry = "L";
            gamepage.Word = "Testword";


            gamepage.OnAttemptSubmitted(null EventArgs.Empty)
            int updatedAttemptsRemaining = gamepage.attemptsremaining

            Assert.AreEquel(7, updatedAttemptsRemaining);
        }
```

These are the two unit tests that i wrote for the onAttemptSubmitted() function. These   
test the functions ability to work through comparing the attempts remaining to the theroretical  
correct outcome.  

  
The reason this part of the code is checked is becuase if the part of this function dosen't  
correctly work then it would effect the remaining attempts variable. This means that the game  
could end too early or never end until the word is guessed.

With these tests they don't cover the use of special characters so this could be an area of weakness  
within the code.