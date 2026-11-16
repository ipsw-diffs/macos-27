## webprivacyd

> `/System/Library/PrivateFrameworks/WebPrivacy.framework/Versions/A/webprivacyd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

-62.0.0.0.0
-  __TEXT.__text: 0x151c8
+63.0.0.0.0
+  __TEXT.__text: 0x15260
   __TEXT.__auth_stubs: 0x9a0
   __TEXT.__objc_stubs: 0xaa0
   __TEXT.__const: 0x258
-  __TEXT.__gcc_except_tab: 0x1a04
-  __TEXT.__cstring: 0x807
+  __TEXT.__gcc_except_tab: 0x1a08
+  __TEXT.__cstring: 0x823
   __TEXT.__oslogstring: 0x1122
   __TEXT.__dlopen_cstrs: 0xc0
   __TEXT.SandboxProfile: 0x1476
   __TEXT.__objc_methname: 0x6e0
   __TEXT.__unwind_info: 0xcc0
   __DATA_CONST.__const: 0xb98
-  __DATA_CONST.__cfstring: 0x720
+  __DATA_CONST.__cfstring: 0x740
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__auth_got: 0x4e0

   - /usr/lib/libobjc.A.dylib
   Functions: 541
   Symbols:   981
-  CStrings:  280
+  CStrings:  281
 
Functions:
~ __ZN7Backend6Server15handleGetStatusEPU24objcproto13OS_xpc_object8NSObject : 820 -> 832
~ __ZN7Backend6ServerC2Ev : 608 -> 644
~ __ZN7Backend6Server25initializeDatabaseManagerERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEENS_10RemoteListE : 836 -> 872
~ ____ZN7Backend6Server10initializeEv_block_invoke : 1948 -> 1964
~ __ZN7Backend6Server18unlinkAllDatabasesEONSt3__18functionIFvvEEE : 568 -> 572
~ __ZN10WebPrivacy3XPCL6decodeEPU24objcproto13OS_xpc_object8NSObjectRN7Backend10RemoteListEm : 260 -> 308
CStrings:
+ "DEFAULT_TRACKER_BLOCK_RULES"
```
