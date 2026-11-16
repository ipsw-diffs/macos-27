## IMTransferAgent

> `/System/Library/PrivateFrameworks/IMTransferAgent.framework/Versions/A/IMTransferAgent`

```diff

-1491.300.43.0.0
-  __TEXT.__text: 0x1a280
+1491.300.74.0.0
+  __TEXT.__text: 0x1a8fc
   __TEXT.__objc_methlist: 0xa9c
-  __TEXT.__const: 0x118
-  __TEXT.__gcc_except_tab: 0x17d4
-  __TEXT.__cstring: 0xc0a
-  __TEXT.__oslogstring: 0x2e4b
-  __TEXT.__unwind_info: 0x6f0
+  __TEXT.__const: 0x120
+  __TEXT.__gcc_except_tab: 0x1888
+  __TEXT.__cstring: 0xc49
+  __TEXT.__oslogstring: 0x2f7d
+  __TEXT.__unwind_info: 0x6f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x60
+  __DATA_CONST.__const: 0x58
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd90
+  __DATA_CONST.__objc_selrefs: 0xd98
   __DATA_CONST.__objc_superrefs: 0x28
   __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__got: 0x380
+  __DATA_CONST.__got: 0x398
   __AUTH_CONST.__const: 0xb20
-  __AUTH_CONST.__cfstring: 0xe00
+  __AUTH_CONST.__cfstring: 0xe20
   __AUTH_CONST.__objc_const: 0xdb0
-  __AUTH_CONST.__objc_intobj: 0x48
+  __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xa0

   - /System/Library/PrivateFrameworks/Marco.framework/Versions/A/Marco
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 310
-  Symbols:   237
-  CStrings:  364
+  Functions: 311
+  Symbols:   240
+  CStrings:  369
 
Symbols:
+ _IMTransferAgentErrorDomain
+ _IMTransferAgentErrorFZErrorTypeKey
+ _NSLocalizedDescriptionKey
CStrings:
+ "  ** Encryption failed (errorType: %d) - failing without upload. path: %@ transferID: %@"
+ "  ** File is empty or unreadable - failing without upload. path: %@ transferID: %@ topic: %@"
+ "Failed to encrypt the file for upload"
+ "Failing upload for transfer %@ as MMCS reports a protocol file size of 0."
+ "Refusing to upload a zero-length or unreadable file"
+ "We will not try to re-upload as the file is empty"
- "IMTransferAgentErrorDomain"
```
