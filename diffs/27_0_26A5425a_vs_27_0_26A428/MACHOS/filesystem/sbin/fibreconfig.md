## fibreconfig

> `/sbin/fibreconfig`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 416.0.2.0.0
-  __TEXT.__text: 0x33f0
+  __TEXT.__text: 0x339c
   __TEXT.__auth_stubs: 0x490
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__cstring: 0xe93
   __TEXT.__const: 0x108
   __TEXT.__objc_methname: 0xc8
-  __TEXT.__unwind_info: 0xe0
+  __TEXT.__unwind_info: 0x110
   __DATA_CONST.__cfstring: 0x960
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x250
Functions:
~ sub_10000098c : 44 -> 32
~ sub_100001308 -> sub_1000012fc : 148 -> 136
~ sub_100001bac -> sub_100001b94 : 36 -> 24
~ sub_100001c00 -> sub_100001bdc : 32 -> 20
~ sub_100001c20 -> sub_100001bf0 : 32 -> 20
~ sub_100001c40 -> sub_100001c04 : 24 -> 12
~ sub_100001fa4 -> sub_100001f5c : 184 -> 172
```
