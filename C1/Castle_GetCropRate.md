# Castle_GetCropRate

```cpp - C++
int Castle_GetCropRate(int itemClassId);
```

### Examples

```cpp - C++

	FHTML_SetFileName(fhtml0, fnManorManage);
	FHTML_SetFloat(fhtml0, "gludin_panacen", Castle_GetCropRate(@gludin_panacen));
	FHTML_SetFloat(fhtml0, "gludin_vermouth", Castle_GetCropRate(@gludin_vermouth));
	FHTML_SetFloat(fhtml0, "artemeter", Castle_GetCropRate(@artemeter));
	FHTML_SetInt(fhtml0, "gludin_panacen_price", Castle_GetCropPrice(@gludin_panacen));
	FHTML_SetInt(fhtml0, "gludin_vermouth_price", Castle_GetCropPrice(@gludin_vermouth));
	FHTML_SetInt(fhtml0, "artemeter_price", Castle_GetCropPrice(@artemeter));
	ShowFHTML(talker, fhtml0);

```
