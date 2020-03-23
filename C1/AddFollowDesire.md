# AddFollowDesire

```cpp - C++
void AddFollowDesire(CSharedCreatureData* commander, float value);
```

### Examples

```cpp - C++
{
	AddFollowDesire(myself.boss, 5);
}
```

```cpp - C++
{
    EventHandler NO_DESIRE()
    {
        if (myself.boss.alive)
        {
            AddFollowDesire(myself.boss, 5);
        }
        else
        {
            AddMoveAroundDesire(10, 5);
        }
    }
}
```
