## screensharingd

> `/System/Library/CoreServices/RemoteManagement/screensharingd.bundle/Contents/MacOS/screensharingd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-768.2.15.1.0
-  __TEXT.__text: 0x77cd0
-  __TEXT.__auth_stubs: 0x1e00
+768.6.0.0.0
+  __TEXT.__text: 0x78560
+  __TEXT.__auth_stubs: 0x1e10
   __TEXT.__objc_stubs: 0x2140
-  __TEXT.__objc_methlist: 0xd48
+  __TEXT.__objc_methlist: 0xd58
   __TEXT.__const: 0x2390
-  __TEXT.__oslogstring: 0xcebe
-  __TEXT.__cstring: 0x14819
+  __TEXT.__oslogstring: 0xd1bf
+  __TEXT.__cstring: 0x14b90
   __TEXT.__gcc_except_tab: 0x194
-  __TEXT.__objc_methname: 0x2350
+  __TEXT.__objc_methname: 0x2373
   __TEXT.__objc_classname: 0xde
   __TEXT.__objc_methtype: 0x6c0
-  __TEXT.__unwind_info: 0x11e8
+  __TEXT.__unwind_info: 0x1218
   __DATA_CONST.__const: 0xe78
   __DATA_CONST.__cfstring: 0x1500
   __DATA_CONST.__objc_classlist: 0x48

   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0x48
   __DATA_CONST.__objc_arrayobj: 0x30
-  __DATA_CONST.__auth_got: 0xf10
+  __DATA_CONST.__auth_got: 0xf18
   __DATA_CONST.__got: 0x318
   __DATA_CONST.__auth_ptr: 0x28
   __DATA.__objc_const: 0x1080
-  __DATA.__objc_selrefs: 0xaf0
+  __DATA.__objc_selrefs: 0xaf8
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x6c8
-  __DATA.__bss: 0x27e0
+  __DATA.__bss: 0x27e8
   __DATA.__common: 0x6629
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1156
-  Symbols:   588
-  CStrings:  3019
+  Functions: 1167
+  Symbols:   589
+  CStrings:  3038
 
Symbols:
+ _NSStringFromClass
CStrings:
+ "+[RSAKeyPair loadRSAPublicKeyWithLabel:]"
+ "AuthGetRandomBytes failed; zero-filling substituted RSA payload"
+ "AuthGetRandomBytes failed; zero-filling substituted SRP data"
+ "AuthRSACopyDecryptedOrRandom"
+ "LogNewViewerConnection"
+ "RSA decrypt unusable; continuing with a substituted key"
+ "RSA decrypt unusable; continuing with substituted SRP data"
+ "RSA public key store holds %s, not data; ignoring it"
+ "SRP start from a viewer that never requested our key; sending it once so a stale cached key can recover"
+ "TCPViewerCheck_ConsumeKeyHint"
+ "allowed"
+ "authentication failed and this viewer never requested our key; sending it once so a stale cached key can recover"
+ "host key hint %s for this address"
+ "host key hint budget is full (%d addresses); not sending"
+ "no address key"
+ "not importing public key for %s: does not parse as an RSA public key"
+ "not sent"
+ "retrieveRSAPublicKeyDataWithLabel:"
+ "srp_server_mech_new failed: %d"
+ "unable to create key hint dictionary"
+ "unable to record key hint time"
- "SendRSAResponseNewKey"
- "decrypt failed"
```
