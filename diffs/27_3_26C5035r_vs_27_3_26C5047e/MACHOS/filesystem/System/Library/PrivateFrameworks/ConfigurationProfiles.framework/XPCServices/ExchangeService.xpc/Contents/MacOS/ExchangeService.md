## ExchangeService

> `/System/Library/PrivateFrameworks/ConfigurationProfiles.framework/XPCServices/ExchangeService.xpc/Contents/MacOS/ExchangeService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1911.60.5.0.0
-  __TEXT.__text: 0xfdd4
+1911.60.9.0.0
+  __TEXT.__text: 0xfd84
   __TEXT.__auth_stubs: 0x8d0
-  __TEXT.__objc_stubs: 0x12a0
+  __TEXT.__objc_stubs: 0x1280
   __TEXT.__objc_methlist: 0x5c
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x2fc9
+  __TEXT.__cstring: 0x312b
   __TEXT.__gcc_except_tab: 0x1fd8
   __TEXT.__oslogstring: 0xe
-  __TEXT.__objc_methname: 0xcc6
+  __TEXT.__objc_methname: 0xcac
   __TEXT.__objc_classname: 0x21
   __TEXT.__objc_methtype: 0x6e
-  __TEXT.__ustring: 0x262
   __TEXT.__unwind_info: 0x878
-  __DATA_CONST.__const: 0x4f0
+  __DATA_CONST.__const: 0x4f8
   __DATA_CONST.__cfstring: 0x2d20
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x480
   __DATA_CONST.__got: 0x2b0
   __DATA.__objc_const: 0x90
-  __DATA.__objc_selrefs: 0x4d8
+  __DATA.__objc_selrefs: 0x4d0
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x30
   __DATA.__bss: 0x1b0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 285
+  Functions: 284
   Symbols:   241
   CStrings:  562
 
CStrings:
+ "Cannot install Exchange account for %@ - a DDM-managed Exchange account already exists for this address"
+ "Cannot update Exchange account %@ - it is managed by DDM"
+ "Exchange account creation failed - DDM-managed Exchange account already exists for email %@"
+ "MCTakeoverErrorDomain"
+ "Skipping removal of Exchange account %@ - owned by DDM"
+ "Skipping update of Exchange account %@ - owned by DDM"
- "<%s:%d NULL format string>"
- "Cannot install Exchange account for %@ — a DDM-managed Exchange account already exists for this address"
- "Exchange account creation failed — DDM-managed Exchange account already exists for email %@"
- "Skipping removal of Exchange account %@ — owned by DDM"
- "Skipping update of Exchange account %@ — owned by DDM"
- "initWithFormat:arguments:"
```
