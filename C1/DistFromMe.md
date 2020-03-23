# DistFromMe

```cpp - C++
float DistFromMe(CSharedCreatureData* target);
```

### Examples
```cpp - C++
if (skill_name_id == @s_seal_of_ruler)
{
	if (DistFromMe(speller) < 1000)
	{
		AddAttackDesire(speller, @AMT_STAND, 50000);
	}
}
```
