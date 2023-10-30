## Portfolio 8

This week ive worked on issue 7. This issue is where the deputy team leader wants to be able to view  
the team partners so that they can contact them immediately. This issue requires to list the agencies with  
there current association status, Agency details can be viewed esily, team partners so that they can be contacted  
immediately and that filter can be cleared.

```
for (int i = 0; i < 3; i++)
    {
        if (SearchTerm == agencies[i])
        {
            collected_agencies.Add(agencies[i]);
        }
    }
```

This is the basics of the code that i used to search the for the entered text. This code follows  
clean code as it is easy to understand. This code also follows other principles as it does not add lines  
that wont be used untill later. This code is also not overally difficult to it follows KISS aswell.

The unit test was created to test the input field of the search. This test works by testing the potential inputs  
and shows what would happen with the potential outputs by showing if the test has passed or failed.

The code that i submitted for code review was returned to me with 2 main suggestions for better code.  
Theese suggestions where a better way to create the agencies and to add some more comments to the methods  
in the code. To fix theese issues I added some comments to the methods in the code and changed the way  
the agencies were created.

The code that i review was overall very good it adhered to many parts of clean code. When i looked into the  
code the main part that i noticed was there was a few comments around the start of the methods and  
throughout the code.  

With working together as a team on this project ive realised how important keeping the code clean is.  
becuase everyone has there own way of doing coding this means that everyone's code is different in there  
own way, but using keeping the code clean and adhering to principals such as KISS and YAGNI it lets   
others understand it easier and faster. When working through the week we held a team meeting over  
microsoft teams, this meeting was to go over troubleshooting code and making decisions over problems  
that we would encounter througout the process. The minutes of the meeting include troubleshooting, figuring  
out who will do database, how to work on issues and decide which ones to pick and how much documentation  
per page there will be. My coding practices differ from others as what makes sense too seperate in code  
might not make sense to others.


Links to the github branch i worked on and kanban board
![github](https://github.com/timh1975/UNDAC-Project/tree/euan/feature/issue-7) 
![kanban board](https://zube.io/un-disaster-assessment-and-coordination-undac-app/undac-project/w/workspace-1/kanban)