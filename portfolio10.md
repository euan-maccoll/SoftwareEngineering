##Portfolio 10

This Sprint ive focused my work on going over the created tutroirals for sql lite and fixing prevoius errors from 
other code reviews. I also selected a feature where it would allow me to get this other work progressed. The feature
i selected was to let the operational team leader view assignment details.

```
        <ListView x:Name="assignment_listview">
            <ListView.ItemTemplate>
                <DataTemplate>
                    <ViewCell>
                        <StackLayout>
                            <Label Text="{Binding id}" />
                            <Label Text="{Binding person_id}" />
                            <Label Text="{Binding operational_team_id}" />
                            <Label Text="{Binding role_id}" />
                            <Label Text="{Binding status}" />
                            <Label Text="{Binding start_date}" />
                            <Label Text="{Binding left_date}" />
                        </StackLayout>
                    </ViewCell>
                </DataTemplate>
            </ListView.ItemTemplate>
        </ListView>
```

This code is adherent to KISS as well as DRY and YAGNI. This code is simple to read, doesn't repeat itself and doesn't
add anything that no-one will need. This code is simple enough that it doesn't require comments.

Unit tests for this test what happens if different inputs are entered into the input page to see what they
displayed.

From the code review i was suggested to change how the i was adding new things to the list to make the code more
readable. This means that the section of code now follows the KISS principle, for this i reworked the code so that
it was easier to read which also helps with the maintainability.

When i conducted a code review on other code it smelt of duplicated code as some of its parts where similar 
to what other methods where doing.

This sprint i spent time going over tutorials to help understand the sql lite database being added. This week i've
also looked again at code smells to notice them more easily and faster, This will hopefully help others as I'll be
able to spot more in future code reviews.