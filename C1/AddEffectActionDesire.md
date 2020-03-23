# AddEffectActionDesire

```cpp - C++
void AddEffectActionDesire(CSharedCreatureData* target, int method, int time, float value);
```

### Examples
```cpp - C++
{
	AddEffectActionDesire(myself.sm, 1, 8000, 10000000);
}
```

```cpp - C++
{
	if (MoveAroundSocial > 0 && Rand(100) < 20)
	{
		AddEffectActionDesire(myself.sm, 1, MoveAroundSocial * 1000 / 30, 50);
	}
}
```
