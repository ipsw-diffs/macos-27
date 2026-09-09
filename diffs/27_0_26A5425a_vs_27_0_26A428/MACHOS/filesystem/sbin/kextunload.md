## kextunload

> `/sbin/kextunload`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x13d8
+  __TEXT.__text: 0x13b4
   __TEXT.__auth_stubs: 0x2c0
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__cstring: 0x67e
   __TEXT.__const: 0x400
   __TEXT.__objc_methname: 0xe3
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__auth_got: 0x168
Functions:
~ sub_1000012bc : 396 -> 384
~ sub_100001a30 -> sub_100001a24 : 104 -> 92
~ sub_100001c34 -> sub_100001c1c : 104 -> 92
```
