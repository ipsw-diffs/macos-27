## AOSKit

> `/System/Library/PrivateFrameworks/AOSKit.framework/Versions/A/AOSKit`

```diff

-305.125.2.0.0
+305.250.1.0.0
   __TEXT.__text: 0x196718
   __TEXT.__objc_methlist: 0x1574
   __TEXT.__gcc_except_tab: 0x1a44
   __TEXT.__const: 0x3b990
   __TEXT.__cstring: 0xad02
-  __TEXT.__oslogstring: 0x1f5a
+  __TEXT.__oslogstring: 0x1f48
   __TEXT.__ustring: 0x26
-  __TEXT.__unwind_info: 0x1150
+  __TEXT.__unwind_info: 0x1158
   __TEXT.__eh_frame: 0xc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12a0
+  __DATA_CONST.__objc_selrefs: 0x12a8
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x50
   __DATA_CONST.__got: 0x3c8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 917
-  Symbols:   2155
+  Functions: 918
+  Symbols:   2156
   CStrings:  1346
 
Symbols:
+ _objc_msgSend$icaPersonID
Functions:
~ +[KeychainAccountStorage _dsidFromAppleAccountForAccount:clientID:] : 228 -> 176
+ +[KeychainAccountStorage _deleteFileAtPath:ifNotOfExpectedType:].cold.2
CStrings:
+ "(%@) ACCT LOOKUP: _dsidForAccount: appleAccount found but has no personID"
- "(%@) ACCT LOOKUP: _dsidForAccount: appleAccount found but icaDelegateParameters has no DSID"
```
