## uarphidd

> `/usr/libexec/uarphidd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.60.11.0.0
-  __TEXT.__text: 0x654c
+1587.60.14.0.0
+  __TEXT.__text: 0x6608
   __TEXT.__auth_stubs: 0x4b0
-  __TEXT.__objc_stubs: 0xde0
+  __TEXT.__objc_stubs: 0xe00
   __TEXT.__objc_methlist: 0x424
   __TEXT.__const: 0x58
   __TEXT.__gcc_except_tab: 0xa0
   __TEXT.__cstring: 0x949
-  __TEXT.__objc_methname: 0xf1c
-  __TEXT.__oslogstring: 0xaaf
+  __TEXT.__objc_methname: 0xf35
+  __TEXT.__oslogstring: 0xb0d
   __TEXT.__objc_classname: 0x74
   __TEXT.__objc_methtype: 0x26a
   __TEXT.__unwind_info: 0x298

   __DATA_CONST.__auth_got: 0x268
   __DATA_CONST.__got: 0xc8
   __DATA.__objc_const: 0xa08
-  __DATA.__objc_selrefs: 0x430
+  __DATA.__objc_selrefs: 0x438
   __DATA.__objc_ivar: 0xc4
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x180

   - /usr/lib/libobjc.A.dylib
   Functions: 171
   Symbols:   109
-  CStrings:  410
+  CStrings:  412
 
Functions:
~ sub_1000028e8 : 272 -> 460
CStrings:
+ "%s: %@; activeFirmwareVersion = %@, availableFirmwareVersion = %@, stagedFirmwareVersion = %@"
+ "availableFirmwareVersion"
```
