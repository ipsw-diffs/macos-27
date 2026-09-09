## secinitd

> `/usr/libexec/secinitd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

 182.0.0.0.0
-  __TEXT.__text: 0x57d0
+  __TEXT.__text: 0x5740
   __TEXT.__auth_stubs: 0x6a0
   __TEXT.__objc_stubs: 0xac0
   __TEXT.__cstring: 0x1dad
   __TEXT.__const: 0x70
   __TEXT.__oslogstring: 0x78d
   __TEXT.__objc_methname: 0x712
-  __TEXT.__unwind_info: 0x100
+  __TEXT.__unwind_info: 0x158
   __DATA_CONST.__const: 0x130
   __DATA_CONST.__cfstring: 0xce0
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100000b98 : 68 -> 56
~ sub_100000bdc -> sub_100000bd0 : 68 -> 56
~ sub_100000c20 -> sub_100000c08 : 372 -> 360
~ sub_100000ff4 -> sub_100000fd0 : 72 -> 60
~ sub_100001238 -> sub_100001208 : 188 -> 176
~ sub_100001a4c -> sub_100001a10 : 36 -> 24
~ sub_100001d24 -> sub_100001cdc : 208 -> 196
~ sub_100003dcc -> sub_100003d78 : 80 -> 68
~ sub_100003e1c -> sub_100003dbc : 72 -> 60
~ sub_100003e64 -> sub_100003df8 : 68 -> 56
~ sub_100003ea8 -> sub_100003e30 : 364 -> 352
~ sub_100004020 -> sub_100003f9c : 28 -> 16
```
