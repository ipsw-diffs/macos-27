## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Versions/A/AppStoreDaemon`

```diff

-13.2.8.0.0
-  __TEXT.__text: 0x64b70
-  __TEXT.__objc_methlist: 0x95c4
+13.2.11.0.0
+  __TEXT.__text: 0x64dbc
+  __TEXT.__objc_methlist: 0x95fc
   __TEXT.__const: 0x11a8
-  __TEXT.__cstring: 0x10aa3
+  __TEXT.__cstring: 0x10ac7
   __TEXT.__constg_swiftt: 0x1a8
   __TEXT.__swift5_typeref: 0x324
   __TEXT.__swift5_builtin: 0x28

   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c88
+  __DATA_CONST.__objc_selrefs: 0x3c90
   __DATA_CONST.__objc_protorefs: 0xd8
   __DATA_CONST.__objc_superrefs: 0x2b0
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x4d0
   __AUTH_CONST.__const: 0x29f8
-  __AUTH_CONST.__cfstring: 0x4960
-  __AUTH_CONST.__objc_const: 0x13660
+  __AUTH_CONST.__cfstring: 0x49a0
+  __AUTH_CONST.__objc_const: 0x136f0
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x578
   __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0xd30
+  __DATA.__objc_ivar: 0xd3c
   __DATA.__data: 0x238
   __DATA.__bss: 0xd10
   __DATA_DIRTY.__objc_ivar: 0x90

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3844
-  Symbols:   7289
-  CStrings:  1165
+  Functions: 3849
+  Symbols:   7297
+  CStrings:  1167
 
Symbols:
+ -[ASDAppLedgerItem initWithBundleID:bundleVersion:itemID:versionID:installDate:lastLaunchDate:wasFactoryInstall:]
+ -[ASDAppLedgerItem wasFactoryInstall]
+ -[ASDAppLedgerQuery bundleID]
+ -[ASDAppLedgerQuery itemID]
+ -[ASDAppLedgerQuery setBundleID:]
+ -[ASDAppLedgerQuery setItemID:]
+ _OBJC_IVAR_$_ASDAppLedgerItem._wasFactoryInstall
+ _OBJC_IVAR_$_ASDAppLedgerQuery._bundleID
+ _OBJC_IVAR_$_ASDAppLedgerQuery._itemID
- -[ASDAppLedgerItem initWithBundleID:bundleVersion:itemID:versionID:installDate:lastLaunchDate:]
CStrings:
+ "<%@: %p> bundleID=%@ bundleVersion=%@ itemID=%@ versionID=%@ installDate=%@ lastLaunchDate=%@ wasFactoryInstall=%@"
+ "FI"
+ "itemID = %@"
- "<%@: %p> bundleID=%@ bundleVersion=%@ itemID=%@ versionID=%@ installDate=%@ lastLaunchDate=%@"
```
