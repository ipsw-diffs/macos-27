## eoshostd

> `/usr/libexec/eoshostd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 168.0.0.0.0
-  __TEXT.__text: 0x4940
+  __TEXT.__text: 0x48d4
   __TEXT.__auth_stubs: 0x710
   __TEXT.__objc_stubs: 0x60
   __TEXT.__const: 0x68
   __TEXT.__oslogstring: 0xe1c
   __TEXT.__cstring: 0x58b
   __TEXT.__objc_methname: 0x30
-  __TEXT.__unwind_info: 0x158
+  __TEXT.__unwind_info: 0x250
   __DATA_CONST.__const: 0x580
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100001500 : 176 -> 164
~ sub_1000015b0 -> sub_1000015a4 : 184 -> 172
~ sub_1000018f0 -> sub_1000018d8 : 112 -> 100
~ sub_1000023a8 -> sub_100002384 : 132 -> 120
~ sub_100002db0 -> sub_100002d80 : 228 -> 216
~ sub_100003d34 -> sub_100003cf8 : 56 -> 44
~ sub_100003db8 -> sub_100003d70 : 52 -> 40
~ sub_100003dec -> sub_100003d98 : 52 -> 40
~ sub_1000043b0 -> sub_100004350 : 92 -> 80
```
