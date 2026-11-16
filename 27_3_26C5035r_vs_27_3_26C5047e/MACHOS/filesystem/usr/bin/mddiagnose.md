## mddiagnose

> `/usr/bin/mddiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2465.2.7.400.0
-  __TEXT.__text: 0x10a1c
-  __TEXT.__auth_stubs: 0xf60
+2465.2.13.400.0
+  __TEXT.__text: 0x10a50
+  __TEXT.__auth_stubs: 0xf70
   __TEXT.__objc_stubs: 0x1400
   __TEXT.__objc_methlist: 0x32c
-  __TEXT.__const: 0x188
-  __TEXT.__cstring: 0x4cb2
+  __TEXT.__const: 0x198
+  __TEXT.__cstring: 0x4cd5
   __TEXT.__oslogstring: 0x81
   __TEXT.__objc_methname: 0xf2a
   __TEXT.__gcc_except_tab: 0xcc

   __TEXT.__objc_methtype: 0x16b
   __TEXT.__unwind_info: 0x558
   __DATA_CONST.__const: 0x638
-  __DATA_CONST.__cfstring: 0x4ee0
+  __DATA_CONST.__cfstring: 0x4f40
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8

   __DATA_CONST.__objc_arraydata: 0x578
   __DATA_CONST.__objc_arrayobj: 0x5b8
   __DATA_CONST.__objc_intobj: 0x30
-  __DATA_CONST.__auth_got: 0x7c0
+  __DATA_CONST.__auth_got: 0x7c8
   __DATA_CONST.__got: 0x1d8
   __DATA_CONST.__auth_ptr: 0x30
   __DATA.__objc_const: 0x360

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 340
-  Symbols:   316
-  CStrings:  1051
+  Symbols:   317
+  CStrings:  1054
 
Symbols:
+ _MDPathByStrippingLookupPrefix
Functions:
~ sub_100000fd8 : 2032 -> 2024
~ sub_100004e5c -> sub_100004e54 : 276 -> 336
CStrings:
+ "/.nofollow/"
+ "/.resolve/"
+ "/.resolve/1"
```
