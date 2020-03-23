# GetIndexFromCreature

```cpp - C++
int GetIndexFromCreature(CSharedCreatureData* creature);
```

### Examples
```cpp - C++
i0 = GetGlobalMap(GM_ID);
if (i0 == -1)
{
	RegisterGlobalMap(GM_ID, GetIndexFromCreature(myself.sm));
}
```
