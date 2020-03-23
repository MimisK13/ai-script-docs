# AddPetDefaultDesire_Follow

```cpp - C++
void AddPetDefaultDesire_Follow(float value);
```

### Examples

```cpp - C++
{
    EventHandler CREATED()
    {
        AddPetDefaultDesire_Follow(20.0);
        AddTimerEx(100020, 1000);
        AddTimerEx(100021, 1000 * 60);
    }
}
```

```cpp - C++
{
    EventHandler NO_DESIRE()
    {
        AddPetDefaultDesire_Follow(20.0);
    }
}
```
