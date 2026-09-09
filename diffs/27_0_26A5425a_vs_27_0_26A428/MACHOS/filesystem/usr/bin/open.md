## open

> `/usr/bin/open`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 365.0.0.0.0
-  __TEXT.__text: 0x4d8c
+  __TEXT.__text: 0x4cfc
   __TEXT.__auth_stubs: 0x420
   __TEXT.__objc_stubs: 0xf80
   __TEXT.__objc_methlist: 0x5c

   __TEXT.__objc_methname: 0xa87
   __TEXT.__objc_classname: 0x10
   __TEXT.__objc_methtype: 0x60
-  __TEXT.__cstring: 0x4d34
-  __TEXT.__unwind_info: 0x120
-  __DATA_CONST.__const: 0x5918
-  __DATA_CONST.__cfstring: 0x3f80
+  __TEXT.__cstring: 0x4d3e
+  __TEXT.__unwind_info: 0x160
+  __DATA_CONST.__const: 0x5928
+  __DATA_CONST.__cfstring: 0x3fa0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8

   - /usr/lib/libobjc.A.dylib
   Functions: 56
   Symbols:   132
-  CStrings:  685
+  CStrings:  686
 
Functions:
~ sub_100003a88 : 148 -> 136
~ sub_100004174 -> sub_100004168 : 1060 -> 1048
~ sub_100004598 -> sub_100004580 : 160 -> 148
~ sub_100004638 -> sub_100004614 : 128 -> 116
~ sub_1000046b8 -> sub_100004688 : 144 -> 132
~ sub_100004748 -> sub_10000470c : 116 -> 104
~ sub_100004800 -> sub_1000047b8 : 656 -> 644
~ sub_100004a90 -> sub_100004a3c : 512 -> 500
~ sub_100004f7c -> sub_100004f1c : 164 -> 140
~ sub_10000513c -> sub_1000050c4 : 64 -> 52
~ sub_1000054b4 -> sub_100005430 : 32 -> 20
CStrings:
+ "arm64e.x1"
```
