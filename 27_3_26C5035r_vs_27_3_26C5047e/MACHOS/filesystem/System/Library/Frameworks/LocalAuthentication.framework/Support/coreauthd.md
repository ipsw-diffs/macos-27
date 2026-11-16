## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2319.60.18.0.0
-  __TEXT.__text: 0x2dc04
+2319.60.22.0.0
+  __TEXT.__text: 0x2dc78
   __TEXT.__auth_stubs: 0x8b0
-  __TEXT.__objc_stubs: 0x3a40
+  __TEXT.__objc_stubs: 0x3a60
   __TEXT.__objc_methlist: 0x2044
   __TEXT.__const: 0x240
-  __TEXT.__objc_methname: 0x4d83
+  __TEXT.__objc_methname: 0x4d92
   __TEXT.__oslogstring: 0x24b2
   __TEXT.__cstring: 0x3323
   __TEXT.__objc_classname: 0x81b

   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__auth_got: 0x468
-  __DATA_CONST.__got: 0x4e8
+  __DATA_CONST.__got: 0x4f0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x7cb0
-  __DATA.__objc_selrefs: 0x13a0
+  __DATA.__objc_selrefs: 0x13a8
   __DATA.__objc_ivar: 0x1e0
   __DATA.__objc_data: 0xd20
   __DATA.__data: 0x1338

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1124
-  Symbols:   309
-  CStrings:  1792
+  Symbols:   310
+  CStrings:  1793
 
Symbols:
+ _OBJC_CLASS_$_LACOptionOverrideProcessor
Functions:
~ sub_10000ca2c : 896 -> 1012
CStrings:
+ "initWithFlags:"
```
