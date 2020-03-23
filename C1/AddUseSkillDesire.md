# AddUseSkillDesire

```cpp - C++
void AddUseSkillDesire(CSharedCreatureData* target, int skillNameID, int skillType, int actionMoveType, float value);
```

### Examples

```cpp - C++
{
	AddUseSkillDesire(talker,reply,1,1,1000000);
}
```

```cpp - C++
{
    EventHandler SEE_SPELL(speller, skill_name_id)
    {
        if (speller == myself.top_desire_target && Rand(15) < 1)
        {
            AddUseSkillDesire(speller, PhysicalSpecial_a, @ST_ATTACK, @AMT_MOVE_TO_TARGET, 1000000);
        }

        super;
    }
}
```
