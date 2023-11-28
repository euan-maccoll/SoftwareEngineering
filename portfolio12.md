## Portfolio 12

This week i focused on the issue where a team member wants to raise a request for basic supplies so that a member can raise request
so that there basic needs are met.

```
    private async void supplyAdded(object sender, EventArgs e)
    {
        //adds supplies request to the list
        string supplyname = supplyName.Text;
        string amount = Amount.Text;

        Supply.Add(new Supplies { Name = supplyname, Amount = amount });

    }
```

This code is what adds a new request to the supplies list. It follows KISS as this the code has been kept minimal. The code also doesnt add
any unnessesory lines so it also follows YAGNI. From then code review i was told that this code that the variable type should be changed to
float/int.

```
        public void ossocSuppliesTest()
        {
            string supplyName = "medicine";
            string amount = "200";

            supplyAdded(supplyName, amount);
            Assert.AreEqual(Supply.Name,supplyName);
        }
```

this unit test shows what happens if expected inputs are added to the list. It shows that if the expected inputs are entered then the expected
result happens. Others show what happen if it where not the expected input

With this code review i was advised to change some parts of the UI to make it easier to understand for users. I was also advised to add a few
comments in the model file and to change variable type from string to int or float for the amount.

When i did the code review for others i noticed that there were some global data variables. This means that the variable can change from any 
point in the code and can be difficult to track down if too late in the code.

This week ive realised that when creating a branche to work on an issue it is definitly better and more time efficiant to create that 
branch from the development enviroment rather than the last workable version that your using.
