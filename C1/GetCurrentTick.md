# GetCurrentTick

```cpp - C++
int GetCurrentTick();
```

### Examples
```cpp - C++
if (GetCurrentTick() - talker.quest_last_reward_time > 1)
{
	talker.quest_last_reward_time = GetCurrentTick();
	
	// code...
}
```
