## sysmond

> `/usr/libexec/sysmond`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 135.0.0.0.0
-  __TEXT.__text: 0x3808
+  __TEXT.__text: 0x3750
   __TEXT.__auth_stubs: 0x610
   __TEXT.__objc_methlist: 0x164
   __TEXT.__const: 0x68

   __TEXT.__objc_classname: 0x77
   __TEXT.__objc_methname: 0x147
   __TEXT.__objc_methtype: 0xb5
-  __TEXT.__unwind_info: 0x150
+  __TEXT.__unwind_info: 0x1b8
   __DATA_CONST.__const: 0xac8
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_classlist: 0x30
Functions:
~ sub_100000dec : 224 -> 200
~ sub_100002984 -> sub_10000296c : 52 -> 40
~ sub_1000029b8 -> sub_100002994 : 52 -> 40
~ sub_1000029ec -> sub_1000029bc : 52 -> 40
~ sub_100002a20 -> sub_1000029e4 : 52 -> 40
~ sub_100002bf4 -> sub_100002bac : 168 -> 164
~ sub_100002e28 -> sub_100002ddc : 80 -> 68
~ sub_100002e78 -> sub_100002e20 : 68 -> 56
~ sub_100002f94 -> sub_100002f30 : 100 -> 88
~ sub_100002ff8 -> sub_100002f88 : 92 -> 80
~ sub_100003054 -> sub_100002fd8 : 92 -> 80
~ sub_1000030b0 -> sub_100003028 : 92 -> 80
~ sub_10000310c -> sub_100003078 : 88 -> 76
~ sub_100003164 -> sub_1000030c4 : 92 -> 80
~ sub_1000031c0 -> sub_100003114 : 92 -> 80
```
