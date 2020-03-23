# AddTimerEx

```cpp - C++
void AddTimerEx(int id, int msec);
```

### Examples

```cpp - C++
{
	AddTimerEx(3001, 10000);
}
```

```cpp - C++
{
    EventHandler TELEPORT_REQUESTED(talker)
    {
        if (Castle_IsUnderSiege() && Castle_GetLifeControlLevel() == 0)
        {
            AddTimerEx(1001, 480000);
        }
        else
        {
            AddTimerEx(1001, 30000);
        }

        myself.i_ai0 = 1;
    }
}
```
