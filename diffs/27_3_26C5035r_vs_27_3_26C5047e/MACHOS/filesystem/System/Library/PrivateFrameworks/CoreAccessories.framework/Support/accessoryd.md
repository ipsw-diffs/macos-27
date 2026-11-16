## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1219.60.10.0.0
-  __TEXT.__text: 0x18d184
+1219.60.11.0.0
+  __TEXT.__text: 0x18d320
   __TEXT.__auth_stubs: 0x1860
   __TEXT.__objc_stubs: 0x90c0
   __TEXT.__objc_methlist: 0x6dec

   __TEXT.__objc_methname: 0xfb22
   __TEXT.__objc_methtype: 0x33a6
   __TEXT.__cstring: 0xe9fa
-  __TEXT.__oslogstring: 0x388b2
+  __TEXT.__oslogstring: 0x388e7
   __TEXT.__ustring: 0x232
   __TEXT.__unwind_info: 0x6468
   __DATA_CONST.__const: 0xa130

   - /usr/lib/libsysdiagnose.dylib
   Functions: 8268
   Symbols:   9924
-  CStrings:  8658
+  CStrings:  8660
 
Functions:
~ _loggingProtocol_parseIncomingByteStream : 332 -> 744
CStrings:
+ "Invalid message length."
+ "Message exceeds buffer size."
```
