# MakeAttackEvent

```cpp - C++
void MakeAttackEvent(CSharedCreatureData* attacker, float damage, bool partyEvent);
```

### Examples
```cpp - C++
EventHandler DESIRE_MANIPULATION(speller, desire)
{
	MakeAttackEvent(speller, desire, 0);
}
```
