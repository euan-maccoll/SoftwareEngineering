## Portfolio 11

With this sprint i worked on the redesign of a previous feature. The feature was to view and search through agencies.
This task meant that it followed the agile development process as the feature was improved to work better.

```
            if (agency.name == SearchTerm) {
                await DisplayAlert("FOUND", agency.id + " " + agency.name, "Okay");
            }
            else
            {
                await DisplayAlert("NOT FOUND","No Agencys with that name", "Okay");
            }
```

This code is how ive been finding the searched items in a list with the agencys. In hindsight this code could even
function better. As currently every time a agency with the same name is found it would create multiple alerts. This
code follows the single responsibility principle from SOLID. This code is also simple so it also follows KISS.

Unit tests for this code are the same as before becuase they also test the search function to see what is entered and 
how it will output.

With the code review i was given suggestions to change the search function as everytime a agency is found an alert is
created and how i could replace a foreach loop with different code. An optional thing i was given was to change 
how i was filling the list to increase the readability of the code.

With the Code that i reviewed the overall code was good however some of the bigger methods comments could have
been added to help understand them. With code i reviewed arguable a point could be made for having too many functios.

This sprint I used agile development to improve code that i prevously made. Through this i relised how beneficial going
and redesining code can be. That in contrast to the previous point there is definintly where something can be overdesigned
