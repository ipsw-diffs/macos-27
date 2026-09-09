## Extract Data from Text

> `/System/Library/Automator/Extract Data from Text.action/Contents/MacOS/Extract Data from Text`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 406.0.0.0.0
-  __TEXT.__text: 0xd1c
+  __TEXT.__text: 0xcb0
   __TEXT.__auth_stubs: 0x110
   __TEXT.__objc_stubs: 0x580
   __TEXT.__objc_methlist: 0xc8

   __TEXT.__objc_methname: 0x4bc
   __TEXT.__objc_classname: 0x1c
   __TEXT.__objc_methtype: 0x6f
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0xe0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_ff0 : 124 -> 112
~ sub_1230 -> sub_1224 : 92 -> 80
~ sub_1290 -> sub_1278 : 204 -> 192
~ sub_135c -> sub_1338 : 152 -> 140
~ sub_13f4 -> sub_13c4 : 788 -> 776
~ sub_1708 -> sub_16cc : 52 -> 40
~ sub_1750 -> sub_1708 : 52 -> 40
~ sub_1798 -> sub_1744 : 52 -> 40
~ sub_17fc -> sub_179c : 112 -> 100
```
