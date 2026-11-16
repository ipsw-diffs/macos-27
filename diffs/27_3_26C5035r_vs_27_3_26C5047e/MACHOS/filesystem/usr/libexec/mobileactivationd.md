## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1145.60.5.0.0
-  __TEXT.__text: 0x65904
+1145.60.6.0.1
+  __TEXT.__text: 0x65a0c
   __TEXT.__auth_stubs: 0x11b0
-  __TEXT.__objc_stubs: 0x24e0
+  __TEXT.__objc_stubs: 0x2500
   __TEXT.__objc_methlist: 0x8fc
   __TEXT.__const: 0x18be3
   __TEXT.__gcc_except_tab: 0x12c0
-  __TEXT.__objc_methname: 0x28b9
+  __TEXT.__objc_methname: 0x28d9
   __TEXT.__oslogstring: 0x143f
-  __TEXT.__cstring: 0xc6a6
+  __TEXT.__cstring: 0xc725
   __TEXT.__objc_classname: 0x104
   __TEXT.__objc_methtype: 0x908
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0x267
   __TEXT.__unwind_info: 0x1398
-  __DATA_CONST.__const: 0x6670
-  __DATA_CONST.__cfstring: 0xa620
+  __DATA_CONST.__const: 0x6680
+  __DATA_CONST.__cfstring: 0xa6a0
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x30

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_intobj: 0x2e8
-  __DATA_CONST.__objc_arraydata: 0x600
+  __DATA_CONST.__objc_arraydata: 0x608
   __DATA_CONST.__objc_arrayobj: 0x90
   __DATA_CONST.__auth_got: 0x8e8
   __DATA_CONST.__got: 0x448
   __DATA_CONST.__auth_ptr: 0x60
   __DATA.__objc_const: 0xee8
-  __DATA.__objc_selrefs: 0xb70
+  __DATA.__objc_selrefs: 0xb78
   __DATA.__objc_ivar: 0x8c
   __DATA.__objc_data: 0x230
   __DATA.__data: 0x46a

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1450
-  Symbols:   3491
-  CStrings:  2514
+  Functions: 1451
+  Symbols:   3495
+  CStrings:  2519
 
Symbols:
+ _kMALastUIKCommitTimeKey
+ _kMASplunkUIKCommitTime
+ _objc_msgSend$base64EncodedStringWithOptions:
+ _recordUIKCommitTime
Functions:
+ _recordUIKCommitTime
~ _storeUCRT : 3496 -> 3504
~ _validate_ucrt_with_uik_pub_key_data : 1244 -> 1376
CStrings:
+ "1145.60.6.0.1"
+ "Absinthe/2.0 macOS Device Activator (MobileActivation-1145.60.6.0.1 built on Nov 10 2026 at 00:48:09)"
+ "LastUIKCommitTime"
+ "UCRT public key does not match UIK public key: ucrt %@, uik %@"
+ "base64EncodedStringWithOptions:"
+ "diagnosticscheckupd"
+ "macOS Device Activator (MobileActivation-1145.60.6.0.1)"
+ "uikCommitTime"
- "1145.60.5"
- "Absinthe/2.0 macOS Device Activator (MobileActivation-1145.60.5 built on Oct 28 2026 at 23:52:49)"
- "macOS Device Activator (MobileActivation-1145.60.5)"
```
