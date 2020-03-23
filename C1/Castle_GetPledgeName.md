# Castle_GetPledgeName

```cpp - C++
const wchar_t* Castle_GetPledgeName();
```

### Examples
```cpp - C++
if (Castle_GetPledgeId())
{
	FHTML_SetFileName(fhtml0, fnFeudInfo);
	FHTML_SetStr(fhtml0, "my_pledge_name", Castle_GetPledgeName());
	FHTML_SetStr(fhtml0, "my_owner_name", Castle_GetOwnerName());
	FHTML_SetInt(fhtml0, "current_tax_rate", Residence_GetTaxRateCurrent());
}
```
