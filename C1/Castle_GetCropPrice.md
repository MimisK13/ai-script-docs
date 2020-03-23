# Castle_GetCropPrice

```cpp - C++
int Castle_GetCropPrice(int itemClassId);
```

### Examples

```cpp - C++

	FHTML_SetFileName(fhtml0, fnSellCrop);
	FHTML_SetInt(fhtml0, "gludin_panacen_price", Castle_GetCropPrice(@gludin_panacen));
	FHTML_SetInt(fhtml0, "gludin_vermouth_price", Castle_GetCropPrice(@gludin_vermouth));
	FHTML_SetInt(fhtml0, "artemeter_price", Castle_GetCropPrice(@artemeter));
	FHTML_SetInt(fhtml0, "gludin_panacen_num", OwnItemCount(talker, @gludin_panacen));
	FHTML_SetInt(fhtml0, "gludin_vermouth_num", OwnItemCount(talker, @gludin_vermouth));
	FHTML_SetInt(fhtml0, "artemeter_num", OwnItemCount(talker, @artemeter));
	FHTML_SetInt(fhtml0, "crop_prce_sum", Castle_GetCropPrice(@gludin_panacen) * OwnItemCount(talker, @gludin_panacen) + Castle_GetCropPrice(@gludin_vermouth) * OwnItemCount(talker, @gludin_vermouth) + Castle_GetCropPrice(@artemeter) * OwnItemCount(talker, @artemeter));
	ShowFHTML(talker, fhtml0);

```
