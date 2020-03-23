# AddMoveAroundDesire

```cpp - C++
void AddMoveAroundDesire(int time, float value);
```

### Examples

```cpp - C++
{
    EventHandler NO_DESIRE()
    {
        AddMoveAroundDesire(5, 5);
    }
}
```

```cpp - C++
{
	if (myself.i_ai0 == 2)
	{
		AddMoveAroundDesire(100, -1000);
		myself.i_ai0 = 3;
	}
}
```

```cpp - C++
{
    EventHandler TIMER_FIRED_EX(timer_id)
    {
        if (timer_id == 2001)
        {
            if (myself.sm.hp > myself.sm.max_hp / 100.0 * 70.0 && myself.i_ai0 == 2)
            {
                AddMoveAroundDesire(100, -1000);
                AddMoveToDesire(myself.start_x, myself.start_y, myself.start_z, 50);
                myself.i_ai0 = 3;
            }
        }

        super;
    }
}
```