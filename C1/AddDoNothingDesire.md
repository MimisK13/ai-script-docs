# AddDoNothingDesire

```cpp - C++
void AddDoNothingDesire(int time, float value);
```

### Examples

```cpp - C++
{
    EventHandler NO_DESIRE()
    {
        AddDoNothingDesire(40, 5);
    }
}
```

```cpp - C++
{
    EventHandler MOVE_TO_FINISHED(x, y, z)
    {
        if (x == myself.start_x && y == myself.start_y && z == myself.start_z)
        {
            AddDoNothingDesire(40, 30);
        }
        else
        {
            AddMoveToDesire(myself.start_x, myself.start_y, myself.start_z, 30);
        }
    }
}
```