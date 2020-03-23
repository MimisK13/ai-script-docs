# AddMoveToWayPointDesire

```cpp - C++
void AddMoveToWayPointDesire(const WayPoints* waypoints, const WayPointDelays* waypointDelays, int index, float value);
```

### Examples

```cpp - C++
{
    EventHandler CREATED()
    {
        AddMoveToWayPointDesire(WayPoints, WayPointDelays, 1, 10);
        super;
    }
}
```

```cpp - C++
{
    EventHandler TIMER_FIRED_EX(timer_id)
    {
        if (timer_id == 100001)
        {
            if (myself.i_ai1 > 0)
            {
                AddMoveToWayPointDesire(WayPoints, WayPointDelays, myself.i_ai1, 10);
            }
            else
            {
                AddMoveToWayPointDesire(WayPoints, WayPointDelays, 1, 10);
            }
        }

        super;
    }
}
```
