## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/Versions/A/MobileAssetDaemon`

```diff

-2215.40.21.501.1
-  __TEXT.__text: 0x281504
+2215.41.2.0.0
+  __TEXT.__text: 0x28165c
   __TEXT.__objc_methlist: 0x12c34
   __TEXT.__const: 0x154a
-  __TEXT.__cstring: 0x3f943
-  __TEXT.__oslogstring: 0x59827
+  __TEXT.__cstring: 0x3f9d3
+  __TEXT.__oslogstring: 0x59887
   __TEXT.__gcc_except_tab: 0xd388
   __TEXT.__constg_swiftt: 0xf0
   __TEXT.__swift5_typeref: 0x146

   __DATA_CONST.__objc_arraydata: 0x1038
   __DATA_CONST.__got: 0x1210
   __AUTH_CONST.__const: 0x3340
-  __AUTH_CONST.__cfstring: 0x33080
+  __AUTH_CONST.__cfstring: 0x33100
   __AUTH_CONST.__objc_const: 0x18db0
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_intobj: 0x13b0

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 7393
   Symbols:   16594
-  CStrings:  10969
+  CStrings:  10974
 
Symbols:
+ -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVendOrNewerOncePersonalized:fromLocation:]
+ _objc_msgSend$_isDownloadedSetDescriptorLatestToVendOrNewerOncePersonalized:fromLocation:
- -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVend:fromLocation:]
- _objc_msgSend$_isDownloadedSetDescriptorLatestToVend:fromLocation:
Functions:
~ -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVend:fromLocation:] -> -[MADAutoAssetControlManager _isDownloadedSetDescriptorLatestToVendOrNewerOncePersonalized:fromLocation:] : 672 -> 784
~ -[MADAutoAssetControlManager _removeDownloadedSetDescriptorWithNewerDownloadedFromLocation:setDescriptor:allowRemovalWithoutNewerDescriptor:] : 1012 -> 1152
~ +[DownloadManager(Pallas) _tvOSOrAudioOSCustomerAudienceForType:] : 288 -> 380
CStrings:
+ "%@:_isDownloadedSetDescriptorLatestToVendOrNewerOncePersonalized"
+ "9adbf9f2-0adf-4a37-9ecc-bee59e9a19eb"
+ "HomeAccessory Customer"
+ "HomeAccessory Mobile Asset Customer"
+ "Loaded built-in MobileAssetDaemon_Framework Oct  8 2026 01:52:25"
+ "bebc09db-45a4-43df-a45c-47a4f832c7e7"
+ "{%{public}@} not to be removed since currently locked | downloadedDescriptor:%{public}@"
- "%@:_isDownloadedSetDescriptorLatestToVend"
- "Loaded built-in MobileAssetDaemon_Framework Sep 29 2026 21:31:09"
```
