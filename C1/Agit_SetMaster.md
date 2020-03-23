# Agit_SetMaster

```cpp - C++
void Agit_SetMaster(CSharedCreatureData* arg_1);
```

### Examples

```cpp - C++

	EventHandler TALKED(talker) 
	{
		if (talker.is_pledge_master == 0) 
		{
			Agit_SetMaster(talker);
			ShowPage(talker, fnHi);
		
		} else {
	
			ShowPage(talker, fnNotPledgeLeader);
		}
	}
	
```
