## ScreenReaderCore

> `/System/Library/PrivateFrameworks/ScreenReaderCore.framework/Versions/A/ScreenReaderCore`

```diff

-1050.3.5.0.0
-  __TEXT.__text: 0x3ebec
+1050.3.12.0.0
+  __TEXT.__text: 0x3ecbc
   __TEXT.__objc_methlist: 0x39b4
-  __TEXT.__cstring: 0x8346
+  __TEXT.__cstring: 0x83e4
   __TEXT.__const: 0x798
   __TEXT.__gcc_except_tab: 0x4c0
   __TEXT.__dlopen_cstrs: 0x101

   __DATA_CONST.__objc_arraydata: 0x238
   __DATA_CONST.__got: 0x360
   __AUTH_CONST.__const: 0x4a0
-  __AUTH_CONST.__cfstring: 0x8c80
+  __AUTH_CONST.__cfstring: 0x8d20
   __AUTH_CONST.__objc_const: 0x5180
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x50

   __AUTH_CONST.__auth_got: 0x688
   __AUTH.__objc_data: 0x230
   __DATA.__objc_ivar: 0x3b4
-  __DATA.__data: 0xc10
+  __DATA.__data: 0xc30
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x400
   __DATA.__common: 0x40
   __DATA_DIRTY.__objc_data: 0x1130
-  __DATA_DIRTY.__data: 0x2e8
+  __DATA_DIRTY.__data: 0x2f0
   __DATA_DIRTY.__bss: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1329
-  Symbols:   3787
-  CStrings:  1243
+  Symbols:   3792
+  CStrings:  1248
 
Symbols:
+ _kSCRCConfigurationSidecarCommander
+ _kSCRCUserDefaultsDomainSidecarCommander
+ _kSCRCUserDefaultsSidecarCommanderEnabled
+ _kSCRCUserDefaultsSidecarSelectionChangeOnFingerLift
+ _kSCRCUserDefaultsSidecarSwitchWindowOnDoubleTap
Functions:
~ ___67-[SCRCUserDefaults(SCRCUserDefaultsImportExport) preferenceDomains]_block_invoke : 232 -> 248
~ -[SCRCUserDefaults(SCRCUserDefaultsImportExport) customFilePrefixesForArchiveType:] : 344 -> 376
~ -[SCRCUserDefaults(SCRCUserDefaultsImportExport) _prunedKeys:archiveType:] : 1356 -> 1452
~ +[SCRCUserDefaultsRegistry profileKeysWithMask:] : 4184 -> 4248
CStrings:
+ "SCRCSidecarCommanderEnabled"
+ "SCRCSidecarCommanderSidecarSelectionChangeOnFingerLift"
+ "SCRCUserDefaultsSidecarSwitchWindowOnDoubleTap"
+ "SCRSidecarCommander"
+ "sidecar"
```
