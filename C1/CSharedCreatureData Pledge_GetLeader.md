# Pledge_GetLeader

```cpp - C++
CSharedCreatureData* Pledge_GetLeader(CSharedCreatureData* pledgeMember);
```

### Examples
```cpp - C++
talk_selected_event_begin
	condition = [HaveMemo(Pledge_GetLeader(talker), @pledge_seeks_ambition) == 1]						 			
	choice_string = 0050336 // Ask about fate
	handler(fhtml0, talker) =
		[
			ShowPage(talker, "witch_kalis_q0503_01.htm");
		]
talk_selected_event_end		
```

```cpp - C++
c2 = Pledge_GetLeader(c1);
```
