# Residence_GetTaxIncome
```cpp - C++
int Residence_GetTaxIncome();
```

### Examples
```cpp - C++
if (ask == -220 && reply == 1 && IsMyLord(talker))
{
	Residence_VaultTakeOutMoney(talker, Residence_GetTaxIncome());
	ShowPage(talker, fnHi);
}
```
