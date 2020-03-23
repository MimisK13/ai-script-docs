# IncrementParam

```cpp - C++
void IncrementParam(CSharedCreatureData* creature, int type, float value);
```

### Examples
```cpp - C++
if (DeleteItem1(talker, @q_proof_of_aspiration, 1))
{
	IncrementParam(talker, @PARAM_SP, -3500000);
	PledgeLevelUp(talker, 5);
}
```
