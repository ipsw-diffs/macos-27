## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/Versions/A/TipsDaemon`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-866.2.4.0.0
-  __TEXT.__text: 0x8697c
+866.3.1.0.0
+  __TEXT.__text: 0x86af4
   __TEXT.__objc_methlist: 0x3810
   __TEXT.__const: 0x2d08
-  __TEXT.__oslogstring: 0x1f76
+  __TEXT.__oslogstring: 0x1fc5
   __TEXT.__cstring: 0x36b9
   __TEXT.__gcc_except_tab: 0x10dc
   __TEXT.__swift5_typeref: 0xec8

   __DATA_CONST.__objc_classlist: 0x540
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23c0
+  __DATA_CONST.__objc_selrefs: 0x23c8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x1b8
   __DATA_CONST.__objc_arraydata: 0x78

   __AUTH_CONST.__objc_const: 0x80f8
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_arrayobj: 0xa8
-  __AUTH_CONST.__auth_got: 0xd88
+  __AUTH_CONST.__auth_got: 0xd90
   __AUTH.__objc_data: 0x1260
   __AUTH.__data: 0xf0
   __DATA.__objc_ivar: 0x214

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3078
-  Symbols:   4282
-  CStrings:  705
+  Symbols:   4284
+  CStrings:  707
 
Symbols:
+ _MGGetProductType
+ _objc_msgSend$hardwareWelcomeCollectionIdentifier
Functions:
~ -[TPSTipsManager welcomeCollectionOverrideFromContentPackage:] : 96 -> 472
CStrings:
+ "Welcome collection override not found %@"
+ "Welcome collection override set to %@"
+ "com.apple.assistant.public"
- "com.apple.assistant.support"
```
