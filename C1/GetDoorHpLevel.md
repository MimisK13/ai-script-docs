# GetDoorHpLevel

```cpp - C++
void GetDoorHpLevel(CSharedCreatureData* talker, const wchar_t* doorName);
```

### Examples
```cpp - C++
select (i0)
{
case 1:
	GetDoorHpLevel(talker, DDoorName1_1);
	break;
case 2:
	GetDoorHpLevel(talker, DDoorName2_1);
	break;
case 3:
	GetDoorHpLevel(talker, DDoorName3_1);
	break;
case 4:
	GetDoorHpLevel(talker, DDoorName4_1);
	break;
case 21:
	GetDoorHpLevel(talker, WallName1);
	break;
case 22:
	GetDoorHpLevel(talker, WallName3);
	break;
}
```
