## audiomxd

> `/usr/libexec/audiomxd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 1638.213.0.0.0
-  __TEXT.__text: 0x12de8
+  __TEXT.__text: 0x12ca8
   __TEXT.__realtime: 0x8e4
   __TEXT.__auth_stubs: 0xb90
   __TEXT.__objc_stubs: 0xe0

   __TEXT.__const: 0x200
   __TEXT.__gcc_except_tab: 0x1120
   __TEXT.__cstring: 0xbbd
-  __TEXT.__oslogstring: 0x3340
+  __TEXT.__oslogstring: 0x32fa
   __TEXT.__objc_classname: 0xb
   __TEXT.__objc_methtype: 0x8
   __TEXT.__objc_methname: 0x4e

   - /usr/lib/libobjc.A.dylib
   Functions: 232
   Symbols:   238
-  CStrings:  355
+  CStrings:  353
 
Functions:
~ sub_1000081d4 : 3280 -> 2960
CStrings:
- "%25s:%-5d mMagicCookie invalidated"
- "%25s:%-5d mPacketTable invalidated"
```
