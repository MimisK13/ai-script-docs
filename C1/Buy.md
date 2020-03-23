# Buy

```cpp - C++
void Buy(CSharedCreatureData* talker, CBuySellList* buySellList, const wchar_t* shopname, const wchar_t* buyPage, const wchar_t* unableItemBuy, float fRatio);
```

### Examples 
---
```cpp - C++

property:
	BuySellList BuyList0 = 
	{
		{"dragonflute_of_wind"; 0 };
		{"dragonflute_of_star"; 0 };
		{"dragonflute_of_twilight"; 0 }
	}		

handler:
	EventHandler MENU_SELECTED(talker, ask, reply) 
	{
		if (ask == -1) 
		{
			if (reply == 0) 
			{
				Buy(talker, BuyList0, ShopName, fnSell, fnUnableItemSell, -50);
			}
		}
	}	
```
