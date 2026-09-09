## ExpressCard

> `/System/Library/CoreServices/Menu Extras/ExpressCard.menu/Contents/MacOS/ExpressCard`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 4.0.0.0.0
-  __TEXT.__text: 0x123c
+  __TEXT.__text: 0x11e8
   __TEXT.__auth_stubs: 0x200
   __TEXT.__objc_stubs: 0x4a0
   __TEXT.__objc_methlist: 0xd4

   __TEXT.__cstring: 0x1d9
   __TEXT.__objc_classname: 0x16
   __TEXT.__objc_methtype: 0xdb
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__cfstring: 0x220
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_cf0 : 140 -> 116
~ sub_dec -> sub_dd4 : 136 -> 124
~ sub_f28 -> sub_f04 : 104 -> 92
~ sub_1440 -> sub_1410 : 76 -> 64
~ _ExpressCardPowerOffCard : 144 -> 132
~ sub_1a74 -> sub_1a2c : 196 -> 184
```
