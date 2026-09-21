## loginwindow

> `/System/Library/CoreServices/SecurityAgentPlugins/loginwindow.bundle/Contents/MacOS/loginwindow`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-399.2.2.0.0
-  __TEXT.__text: 0x27164
+399.2.3.0.0
+  __TEXT.__text: 0x27178
   __TEXT.__auth_stubs: 0xc90
-  __TEXT.__objc_stubs: 0x6320
+  __TEXT.__objc_stubs: 0x6300
   __TEXT.__objc_methlist: 0x2204
   __TEXT.__const: 0x6c
   __TEXT.__gcc_except_tab: 0x4b0
-  __TEXT.__cstring: 0x5dc2
+  __TEXT.__cstring: 0x5dda
   __TEXT.__oslogstring: 0x1c1
-  __TEXT.__objc_methname: 0x6124
+  __TEXT.__objc_methname: 0x6110
   __TEXT.__objc_classname: 0x2ad
   __TEXT.__objc_methtype: 0x1224
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0xc18
   __DATA_CONST.__const: 0xa98
-  __DATA_CONST.__cfstring: 0x51c0
+  __DATA_CONST.__cfstring: 0x5200
   __DATA_CONST.__objc_classlist: 0x80
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70

   __DATA_CONST.__auth_got: 0x658
   __DATA_CONST.__got: 0x3c8
   __DATA.__objc_const: 0x2028
-  __DATA.__objc_selrefs: 0x1fc8
+  __DATA.__objc_selrefs: 0x1fc0
   __DATA.__objc_ivar: 0x104
   __DATA.__objc_data: 0x500
   __DATA.__data: 0x548

   - /usr/lib/libobjc.A.dylib
   Functions: 779
   Symbols:   467
-  CStrings:  2072
+  CStrings:  2073
 
Functions:
~ sub_1f00 : 648 -> 636
~ sub_cb78 -> sub_cb6c : 292 -> 304
~ sub_dd60 : 296 -> 332
~ sub_1e5ec -> sub_1e610 : 2684 -> 2668
CStrings:
+ "PSSO re-present after failure for user %@ as %@: %@"
+ "PSSO user"
+ "no user"
- "PSSO re-present after failure for user %@: %@"
- "migratedFromWindows"
```
