## Portfolio 9

This week i choose issue 17 from the provided issues. This issue states that the team support and logistics wants to be able to
the stock of different resources that they have. This will also display the reorder levels and the current stock level and what
kind of resource or equipment it is.

```
	public ShowResources()
	{
		InitializeComponent();
        //this code creates the equipment/resources
        List<Resource> resource = new List<Resource>
        {
            new resource { id = 1, name = "Super Good Plaster", type = "Medicines", current_level = 1, reorder_level = 34 , supplier_id = 1},
            new resource { id = 2, name = "Clean water filter", type = "Drinking equipment", current_level = 2, supplier_id = 16 ,supplier_id = 2},
            new resource { id = 3, name = "Pasta", type = "Foods", current_level = 3, status = 72 ,supplier_id = 3}
        };
```

This code is the new way that ive been creating items. This was the suggested way from the last code review last week.
it follows KISS and YAGNI as its simple and doesn't add anything that will not be used or unneeded. The code snippet also
uses comments to describe what is happening.

The unit tests for this code are to test that the code can be searched for correctly as this was the newly suggested
way of storing the information. I used the unit tests to know that the inputs and the correct inputs and outputs
where acting correctly.

With the code review i was suggested to remove some of the unnessery comments throught out the code and to change
the access modifiers on a variable in a class. When fixing theses issues i removed the comments that didnt directly
say anything useful about the overall method. I had to switch the access modifier of a varibale as i had put the
wrong one down.

The code that i revied had only 1 thing that i could spot, this was that it didn't follow the Single responsibilty
rule from SOLID. overall the code was very good.

This week i have tried to find the right balance of having the right amount of comments in the code. During the week
i got too focused on smaller errors within the code i spent too long trying to find answers to these bigs when in
reality i should have used the team to help me solve this error so i could continue to work on the project. This 
issue impacted on my timing for this portfolio piece. I've realised this week that others can also have need
of help without them wanting to say but through helping these people it makes the team more efficiant. Also that
becuase your timing was off with a section of code then that could put other peoples sections on hold untill that
piece was done.
