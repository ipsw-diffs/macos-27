## CoreIDCred

> `/System/Library/PrivateFrameworks/CoreIDCred.framework/Versions/A/CoreIDCred`

```diff

-9.41.1.0.0
-  __TEXT.__text: 0x323e4
-  __TEXT.__objc_methlist: 0x1f7c
+9.104.0.0.0
+  __TEXT.__text: 0x32358
+  __TEXT.__objc_methlist: 0x1f6c
   __TEXT.__const: 0x3520
   __TEXT.__cstring: 0x11ab
   __TEXT.__oslogstring: 0x2685

   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc40
+  __DATA_CONST.__objc_selrefs: 0xc38
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0xa0
   __DATA_CONST.__got: 0x2a8

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1723
-  Symbols:   1738
+  Functions: 1722
+  Symbols:   1737
   CStrings:  310
 
Symbols:
- -[DCBiometricStore setModifiedGlobalAuthACL:externalizedLAContext:completion:]
Functions:
+ -[DCBiometricStore deleteGlobalAuthACLWithCompletion:]
- -[DCBiometricStore deleteGlobalAuthACLWithCompletion:]
+ -[DCBiometricStore globalAuthACLTemplateUUIDsAndCredentialCountWithCompletion:]
- -[DCBiometricStore globalAuthACLTemplateUUIDsAndCredentialCountWithCompletion:]
- -[DCBiometricStore boundAppletPresentmentACL:]
```
