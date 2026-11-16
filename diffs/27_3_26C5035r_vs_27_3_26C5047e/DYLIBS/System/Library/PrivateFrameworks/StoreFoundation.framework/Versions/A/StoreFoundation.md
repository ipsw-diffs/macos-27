## StoreFoundation

> `/System/Library/PrivateFrameworks/StoreFoundation.framework/Versions/A/StoreFoundation`

```diff

-717.1.4.0.0
-  __TEXT.__text: 0x3810c
-  __TEXT.__objc_methlist: 0x55e8
+717.2.1.0.0
+  __TEXT.__text: 0x383e4
+  __TEXT.__objc_methlist: 0x5610
   __TEXT.__const: 0x148
   __TEXT.__gcc_except_tab: 0xa3c
-  __TEXT.__cstring: 0x88f4
+  __TEXT.__cstring: 0x8a4a
   __TEXT.__oslogstring: 0xb
-  __TEXT.__unwind_info: 0x1310
+  __TEXT.__ustring: 0x4
+  __TEXT.__unwind_info: 0x1318
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3590
+  __DATA_CONST.__objc_selrefs: 0x35b0
   __DATA_CONST.__objc_protorefs: 0x88
   __DATA_CONST.__objc_superrefs: 0x180
   __DATA_CONST.__objc_arraydata: 0xa0
-  __DATA_CONST.__got: 0x568
+  __DATA_CONST.__got: 0x570
   __AUTH_CONST.__const: 0xf60
-  __AUTH_CONST.__cfstring: 0x7ec0
-  __AUTH_CONST.__objc_const: 0xaed8
+  __AUTH_CONST.__cfstring: 0x7f40
+  __AUTH_CONST.__objc_const: 0xaef8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0xfa0
-  __DATA.__objc_ivar: 0x6c4
+  __DATA.__objc_ivar: 0x6c8
   __DATA.__data: 0xb30
   __DATA.__bss: 0x198
   __DATA_DIRTY.__objc_data: 0x320

   - /System/Library/PrivateFrameworks/Install.framework/Frameworks/DistributionKit.framework/Versions/A/DistributionKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1778
-  Symbols:   4569
-  CStrings:  1208
+  Functions: 1781
+  Symbols:   4577
+  CStrings:  1214
 
Symbols:
+ +[SSDownloadAsset _isSafePathComponent:]
+ -[SSDownloadAsset _unsafePathComponentFallback]
+ -[SSDownloadAsset hasSafeLocalFileName]
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_IVAR_$_SSDownloadAsset._unsafePathComponentFallback
+ _objc_msgSend$UUID
+ _objc_msgSend$UUIDString
+ _objc_msgSend$_isSafePathComponent:
+ _objc_msgSend$_unsafePathComponentFallback
- _objc_msgSend$stringByReplacingPercentEscapesUsingEncoding:
CStrings:
+ "\x00"
+ "%@: Replacing an unsafe download file name"
+ "%@: Replacing an unsafe download folder name"
+ "-[SSDownloadAsset downloadPath]"
+ ".."
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Commerce/CommerceKit/iTunes Protocol/Store Services Framework/SSDownloadAsset.m"
```
