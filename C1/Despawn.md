# Despawn

```cpp - C++
void Despawn();
```

### Examples
---

##### #1
```cpp - C++
if(ask == -201 && reply == 1) 
{
	Despawn();
}
```

##### #2
```cpp - C++
handler:
	EventHandler TALKED(talker, fhtml0) 
	{
		if (talker.builder_level > 0)
		{
			ShowPage(talker, fnHi);
			
		} else {
			
			Despawn();
		}
	}
```
