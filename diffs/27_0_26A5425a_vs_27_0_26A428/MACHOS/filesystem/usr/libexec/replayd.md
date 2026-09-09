## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 740.62.1.0.0
-  __TEXT.__text: 0xc6c68
+  __TEXT.__text: 0xc530c
   __TEXT.__auth_stubs: 0x1b10
   __TEXT.__objc_stubs: 0xed00
   __TEXT.__objc_methlist: 0x75ac
   __TEXT.__const: 0x430
   __TEXT.__oslogstring: 0x15545
-  __TEXT.__cstring: 0x17314
+  __TEXT.__cstring: 0x17324
   __TEXT.__objc_classname: 0xacb
   __TEXT.__objc_methname: 0x1618d
   __TEXT.__objc_methtype: 0x40dd
   __TEXT.__gcc_except_tab: 0xfe4
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__unwind_info: 0x2320
+  __TEXT.__unwind_info: 0x33e0
   __DATA_CONST.__const: 0x2900
-  __DATA_CONST.__cfstring: 0x6360
+  __DATA_CONST.__cfstring: 0x6380
   __DATA_CONST.__objc_classlist: 0x2e0
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xf0

   - /usr/lib/libobjc.A.dylib
   Functions: 3752
   Symbols:   848
-  CStrings:  7409
+  CStrings:  7410
 
CStrings:
+ "Localizable-V68"
```
