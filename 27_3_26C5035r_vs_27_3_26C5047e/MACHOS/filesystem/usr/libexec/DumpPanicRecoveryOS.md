## DumpPanicRecoveryOS

> `/usr/libexec/DumpPanicRecoveryOS`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-41.60.2.0.0
-  __TEXT.__text: 0x294d4
+41.60.3.0.0
+  __TEXT.__text: 0x294e8
   __TEXT.__auth_stubs: 0xc30
   __TEXT.__objc_stubs: 0x2120
   __TEXT.__objc_methlist: 0x78c

   __TEXT.__objc_classname: 0xe9
   __TEXT.__objc_methtype: 0x540
   __TEXT.__gcc_except_tab: 0xb38
-  __TEXT.__unwind_info: 0xd48
+  __TEXT.__unwind_info: 0xd40
   __DATA_CONST.__const: 0x6a0
   __DATA_CONST.__cfstring: 0x2140
   __DATA_CONST.__objc_classlist: 0x60
Functions:
~ sub_10001f8a8 : 188 -> 192
~ sub_10001f964 -> sub_10001f968 : 12 -> 8
~ sub_1000215e0 : 376 -> 408
~ sub_100029510 -> sub_100029530 : 280 -> 268
```
