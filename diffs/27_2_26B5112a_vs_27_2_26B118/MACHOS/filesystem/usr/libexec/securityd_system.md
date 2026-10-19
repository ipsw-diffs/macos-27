## securityd_system

> `/usr/libexec/securityd_system`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 62460.40.78.0.0
-  __TEXT.__text: 0x42860
+  __TEXT.__text: 0x42954
   __TEXT.__auth_stubs: 0x1b90
   __TEXT.__objc_stubs: 0x1ce0
   __TEXT.__objc_methlist: 0xf44
   __TEXT.__const: 0x270
   __TEXT.__objc_classname: 0x2f6
   __TEXT.__objc_methtype: 0xcb2
-  __TEXT.__cstring: 0x8d90
+  __TEXT.__cstring: 0x8e13
   __TEXT.__objc_methname: 0x2241
-  __TEXT.__oslogstring: 0x452b
+  __TEXT.__oslogstring: 0x4568
   __TEXT.__gcc_except_tab: 0x304
   __TEXT.__unwind_info: 0x10c8
   __DATA_CONST.__const: 0xb6c0
-  __DATA_CONST.__cfstring: 0x8920
+  __DATA_CONST.__cfstring: 0x89c0
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x30

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1146
+  Functions: 1147
   Symbols:   751
-  CStrings:  2227
+  CStrings:  2233
 
CStrings:
+ "com.apple.security.ckks"
+ "com.apple.security.egoIdentities"
+ "com.apple.security.octagon"
+ "com.apple.security.sos-usercredential"
+ "found sharing items, treating as sys_bound item: %{private}@"
+ "sync = 0"
```
