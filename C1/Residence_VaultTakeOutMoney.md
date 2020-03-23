# Residence_VaultTakeOutMoney
```cpp - C++
void Residence_VaultTakeOutMoney(CSharedCreatureData* arg_1, int arg_2);
```

### Examples
```cpp - C++
if (ask == -220 && reply == 1)
{
	Residence_VaultTakeOutMoney(talker, Residence_GetTaxIncome());
	ShowPage(talker, fnHi);
}
```
