# PledgeLevelUp
```cpp - C++
void PledgeLevelUp(CSharedCreatureData* talker, int pledgeLevel);
```

### Examples
```cpp - C++
if (DeleteItem1(talker, @proof_of_blood, 1))
{
	IncrementParam(talker, @PARAM_SP, -500000);
	PledgeLevelUp(talker, 3);
}
```

```cpp - C++
if (DeleteItem1(talker, @q_proof_of_alliance, 1))
{
	IncrementParam(talker, @PARAM_SP, -1400000);
	PledgeLevelUp(talker, 4);
}
```

```cpp - C++
if (DeleteItem1(talker, @q_proof_of_aspiration, 1))
{
	IncrementParam(talker, @PARAM_SP, -3500000);
	PledgeLevelUp(talker, 5);
}
```
