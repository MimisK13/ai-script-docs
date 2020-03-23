# GetWayPointDelay

```cpp - C++
int GetWayPointDelay(const WayPointDelays* wayPointDelays, int index);
```

### Examples
```cpp - C++
EventHandler MOVE_TO_WAY_POINT_FINISHED(way_point_index, next_way_point_index)
{
	myself.i_ai1 = next_way_point_index;
	AddTimerEx(100001, GetWayPointDelay(WayPointDelays, way_point_index) * 1000);
}
```
