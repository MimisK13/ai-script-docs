# OpenSiegeInfo
---
```
void OpenSiegeInfo(CSharedCreatureData* talker);
```

### Examples
---
```cpp - C++
handler:
    EventHandler TALKED(talker)
    {
        if (IsMyLord(talker))
        {
            if (Castle_IsUnderSiege())
            {
                ShowPage(talker, fnSiegeMyLord);
            }
            else
            {
                ShowPage(talker, fnMyLord);
            }
        }
        else if (Castle_IsUnderSiege())
        {
            ShowPage(talker, fnSiegeAnother);
        }
        else
        {
            OpenSiegeInfo(talker);
        }
    }
```
