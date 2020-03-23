# FHTML_SetInt

```cpp - C++
void FHTML_SetInt(CFHTML* html, const wchar_t* varName, int value);
```

### Examples
```cpp - C++
FHTML_SetInt(fhtml0, "current_tax_rate", Residence_GetTaxRateCurrent());
FHTML_SetInt(fhtml0, "next_tax_rate", Residence_GetTaxRate());
```
