# HaveMemo

```cpp - C++
int HaveMemo(CSharedCreatureData* creature, int questID);
```

### Examples
```cpp - C++
if (HaveMemo(talker, @hfighter_tutorial))
{
	ShowQuestionMark(talker, 6);
	SoundEffect(talker, "ItemSound.quest_tutorial");
}
```
