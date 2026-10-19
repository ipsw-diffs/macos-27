## authd

> `/System/Library/Frameworks/Security.framework/Versions/Current/XPCServices/authd.xpc/Contents/MacOS/authd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 62460.40.78.0.0
-  __TEXT.__text: 0x2732c
+  __TEXT.__text: 0x27440
   __TEXT.__auth_stubs: 0x1390
   __TEXT.__lazy_helpers: 0x63c
-  __TEXT.__objc_stubs: 0xc20
+  __TEXT.__objc_stubs: 0xc40
   __TEXT.__objc_methlist: 0x154
   __TEXT.__const: 0xb20
   __TEXT.__cstring: 0x331c
-  __TEXT.__oslogstring: 0x4e55
+  __TEXT.__oslogstring: 0x4f27
   __TEXT.__dlopen_cstrs: 0x5d
-  __TEXT.__gcc_except_tab: 0xd78
-  __TEXT.__objc_methname: 0x9da
+  __TEXT.__gcc_except_tab: 0xd6c
+  __TEXT.__objc_methname: 0x9eb
   __TEXT.__objc_classname: 0xf
   __TEXT.__objc_methtype: 0x140
   __TEXT.__unwind_info: 0x818

   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
-  __DATA_CONST.__objc_intobj: 0x18
+  __DATA_CONST.__objc_intobj: 0x30
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_dictobj: 0x28

   __DATA_CONST.__got: 0x198
   __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x230
-  __DATA.__objc_selrefs: 0x318
+  __DATA.__objc_selrefs: 0x320
   __DATA.__objc_ivar: 0x30
   __DATA.__objc_data: 0x50
   __DATA.__lazy_load_got: 0x98

   - /usr/lib/libsqlite3.dylib
   Functions: 477
   Symbols:   399
-  CStrings:  1106
+  CStrings:  1108
 
Functions:
~ sub_100006540 : 10820 -> 10596
~ sub_10000adc8 -> sub_10000ace8 : 3680 -> 3796
~ sub_10000df50 -> sub_10000dee4 : 7592 -> 7976
CStrings:
+ "Sheet authenticated UID %d but a different user was requested (engine %llu)"
+ "Sheet authentication denied by the smartcard policy (engine %llu)"
+ "Sheet authentication without a valid LA result (engine %llu)"
+ "Sheet authentication without the ID of the authenticated user (engine %llu)"
+ "engine %llu: running builtin sheet authenticate, setting sheet UID %d to the context"
+ "unsignedIntValue"
- "Credentials UID %d set."
- "Credentials UID not found for %s"
- "engine %llu: running builtin sheet authenticate"
- "engine %llu: setting sheet UID %d to the context"
```
