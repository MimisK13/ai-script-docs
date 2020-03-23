# AddFleeDesire

```cpp - C++
void AddFleeDesire(CSharedCreatureData* from, float value);
```

### Examples

```cpp - C++
{
	AddFleeDesire(myself.c_ai1, 10000);
}
```

```cpp - C++
{
    EventHandler USE_SKILL_FINISHED(target, skill_name_id)
    {
        if (skill_name_id == HealMagic_a && myself.c_ai0 != myself.sm && DistFromMe(myself.c_ai0) < 200)
        {
            AddFleeDesire(myself.c_ai0, 100000000);
        }
    }
}
```
