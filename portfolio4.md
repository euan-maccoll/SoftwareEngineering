## Portfolio 4

```
public class Character 
{
    public int Level { get; private set; }
    public List<SpecialAbilities> Abilities { get; private set; }

    public void LevelUp() 
    {
        Level++;
    }
}
```


With this question i scored a 2/3 of the available marks. The problem this section of code has is   
You arnt gonna need it (YAGNI). I think this specially refers to the abilities list line. This list would 
need Abilities already which are not created in this code.


```
public class Character 
{
    public int Level { get; private set; }

    public void LevelUp() 
    {
        Level++;
    }
   
}
```

I think this solution is better as it would allow the creator to finish the leveling up system first.
For the creator it lets them focus on one part at a time. When the abilities list created i'd say that
it also leans towards speculative generality.
