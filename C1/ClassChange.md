# ClassChange

```cpp - C++
int ClassChange(CSharedCreatureData* talker, int classType);
```

### Examples
```cpp - C++
ClassChange(talker,reply);
```

```cpp - C++
if (DeleteItem1(talker,item_1proff_id,item_1proff_amount))
{
	ClassChange(talker,reply);					
	FHTML_SetFileName(fhtml0, fnSuccessful);
	FHTML_SetStr(fhtml0,"PlayerName", talker.name);
	ShowFHTML(talker, fhtml0);						
}
```
