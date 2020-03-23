# Castle_GateOpenClose2

```cpp - C++
void Castle_GateOpenClose2(const wchar_t* doorName, int openclose);
```

### Examples

```cpp - C++

	Castle_GateOpenClose2(DoorName1, 0);

```

```cpp - C++

	select (reply)
	{
	case 1:
		Castle_GateOpenClose2(DoorName1, 0);
		Castle_GateOpenClose2(DoorName2, 0);
		break;
	case 2:
		Castle_GateOpenClose2(DoorName1, 1);
		Castle_GateOpenClose2(DoorName2, 1);
		break;
	}
	
```
