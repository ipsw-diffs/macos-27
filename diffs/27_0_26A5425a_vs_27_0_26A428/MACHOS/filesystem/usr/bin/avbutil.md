## avbutil

> `/usr/bin/avbutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1500.16.0.0.0
-  __TEXT.__text: 0x14e50
+  __TEXT.__text: 0x14c94
   __TEXT.__auth_stubs: 0x2e0
   __TEXT.__objc_stubs: 0x17e0
   __TEXT.__objc_methlist: 0x78c

   __TEXT.__objc_methtype: 0x54f
   __TEXT.__const: 0x10
   __TEXT.__gcc_except_tab: 0x634
-  __TEXT.__unwind_info: 0x1d8
+  __TEXT.__unwind_info: 0x238
   __DATA_CONST.__const: 0x1d8
   __DATA_CONST.__cfstring: 0x24e0
   __DATA_CONST.__objc_classlist: 0x78
Functions:
~ sub_100000fe0 : 352 -> 340
~ sub_100001140 -> sub_100001134 : 316 -> 304
~ sub_100001518 -> sub_100001500 : 164 -> 152
~ sub_100001918 -> sub_1000018f4 : 52 -> 40
~ sub_100001ad8 -> sub_100001aa8 : 92 -> 80
~ sub_100001b34 -> sub_100001af8 : 196 -> 184
~ sub_100002cf4 -> sub_100002cac : 296 -> 284
~ sub_100002e1c -> sub_100002dc8 : 960 -> 948
~ sub_1000031dc -> sub_10000317c : 1268 -> 1256
~ sub_100010a08 -> sub_10001099c : 232 -> 220
~ sub_10001101c -> sub_100010fa4 : 176 -> 164
~ sub_1000127ac -> sub_100012728 : 72 -> 60
~ sub_1000127f4 -> sub_100012764 : 64 -> 52
~ sub_100012834 -> sub_100012798 : 232 -> 220
~ sub_10001291c -> sub_100012874 : 80 -> 68
~ sub_10001296c -> sub_1000128b8 : 72 -> 60
~ sub_1000129b4 -> sub_1000128f4 : 232 -> 220
~ sub_100012fb4 -> sub_100012ee8 : 120 -> 108
~ sub_10001302c -> sub_100012f54 : 120 -> 108
~ sub_1000130a4 -> sub_100012fc0 : 120 -> 108
~ sub_10001311c -> sub_10001302c : 120 -> 108
~ sub_1000135e4 -> sub_1000134e8 : 124 -> 112
~ sub_100013660 -> sub_100013558 : 124 -> 112
~ sub_1000136dc -> sub_1000135c8 : 124 -> 112
~ sub_100013758 -> sub_100013638 : 68 -> 56
~ sub_10001379c -> sub_100013670 : 64 -> 52
~ sub_100013b84 -> sub_100013a4c : 68 -> 56
~ sub_1000141f4 -> sub_1000140b0 : 92 -> 80
~ sub_100014250 -> sub_100014100 : 196 -> 184
~ sub_1000154d4 -> sub_100015378 : 128 -> 116
~ sub_100015554 -> sub_1000153ec : 156 -> 144
~ sub_1000155f0 -> sub_10001547c : 88 -> 76
~ sub_100015648 -> sub_1000154c8 : 80 -> 68
~ sub_100015a30 -> sub_1000158a4 : 92 -> 80
~ sub_100015a8c -> sub_1000158f4 : 92 -> 80
~ sub_100015ae8 -> sub_100015944 : 108 -> 96
~ sub_100015bf4 -> sub_100015a44 : 80 -> 68
```
