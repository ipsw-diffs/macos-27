## nscurl

> `/usr/bin/nscurl`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3896.300.31.0.0
-  __TEXT.__text: 0x700c
+3896.300.71.1.4
+  __TEXT.__text: 0x7020
   __TEXT.__auth_stubs: 0x480
-  __TEXT.__objc_stubs: 0x18a0
+  __TEXT.__objc_stubs: 0x18c0
   __TEXT.__objc_methlist: 0x780
   __TEXT.__const: 0x80
   __TEXT.__gcc_except_tab: 0xd8
-  __TEXT.__cstring: 0x1c02
-  __TEXT.__objc_methname: 0x1f28
+  __TEXT.__cstring: 0x1c3a
+  __TEXT.__objc_methname: 0x1f38
   __TEXT.__objc_classname: 0xe2
   __TEXT.__objc_methtype: 0xa0b
   __TEXT.__unwind_info: 0x240
-  __DATA_CONST.__const: 0x850
-  __DATA_CONST.__cfstring: 0x920
+  __DATA_CONST.__const: 0x868
+  __DATA_CONST.__cfstring: 0x9a0
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30

   __DATA_CONST.__auth_got: 0x250
   __DATA_CONST.__got: 0x128
   __DATA.__objc_const: 0xc60
-  __DATA.__objc_selrefs: 0x7d8
+  __DATA.__objc_selrefs: 0x7e0
   __DATA.__objc_ivar: 0xac
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x240

   - /usr/lib/libobjc.A.dylib
   Functions: 168
   Symbols:   117
-  CStrings:  687
+  CStrings:  692
 
Functions:
~ sub_10000669c : 2024 -> 2044
CStrings:
+ "%d) %@ %@ -> %@\t\t Status: %ld DNS: %.3f TLS: %.3f Connect: %.3f Request: %.3f Response: %.3f Full (after TLS): %.3f Total: %.3f Early Data: %@\n"
+ "accepted"
+ "attempted"
+ "earlyDataStatus"
+ "not attempted"
+ "unknown"
- "%d) %@ %@ -> %@\t\t Status: %ld DNS: %.3f TLS: %.3f Connect: %.3f Request: %.3f Response: %.3f Full (after TLS): %.3f Total: %.3f\n"
```
