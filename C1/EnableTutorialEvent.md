# EnableTutorialEvent

```cpp - C++
void EnableTutorialEvent(CSharedCreatureData* to, int eventSet);
```

### Examples
```cpp - C++
EnableTutorialEvent(talker, i0);
```

```cpp - C++
if (talker.level < 6)
{
	ShowQuestionMark(talker, 10);
	SoundEffect(talker, "ItemSound.quest_tutorial");
	SetMemoState(talker, 255, i1 & ~0x100);
	EnableTutorialEvent(talker, i0 & ~0x100 | 0x800000);
}
```
