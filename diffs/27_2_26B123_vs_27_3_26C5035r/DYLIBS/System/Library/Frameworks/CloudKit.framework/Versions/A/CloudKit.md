## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit`

```diff

-2720.17.5.0.0
-  __TEXT.__text: 0x36fc28
-  __TEXT.__objc_methlist: 0x21974
-  __TEXT.__const: 0xe3b8
+2730.18.0.0.0
+  __TEXT.__text: 0x371a10
+  __TEXT.__objc_methlist: 0x219fc
+  __TEXT.__const: 0xe400
   __TEXT.__dlopen_cstrs: 0x13c
-  __TEXT.__swift5_typeref: 0x6c1e
-  __TEXT.__swift5_capture: 0x3b54
-  __TEXT.__cstring: 0x2140c
+  __TEXT.__swift5_typeref: 0x6cd8
+  __TEXT.__swift5_capture: 0x3b78
+  __TEXT.__cstring: 0x2156f
   __TEXT.__constg_swiftt: 0x293c
   __TEXT.__swift5_reflstr: 0x1d9f
   __TEXT.__swift5_fieldmd: 0x2544

   __TEXT.__swift_as_entry: 0x75c
   __TEXT.__swift_as_ret: 0x880
   __TEXT.__swift_as_cont: 0xe68
-  __TEXT.__oslogstring: 0x1706c
+  __TEXT.__oslogstring: 0x173c1
   __TEXT.__swift5_mpenum: 0x60
   __TEXT.__swift5_protos: 0x30
-  __TEXT.__gcc_except_tab: 0xad30
+  __TEXT.__gcc_except_tab: 0xad3c
   __TEXT.__ustring: 0x78
-  __TEXT.__unwind_info: 0x14100
-  __TEXT.__eh_frame: 0x10544
+  __TEXT.__unwind_info: 0x14178
+  __TEXT.__eh_frame: 0x10574
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x29e8
+  __DATA_CONST.__const: 0x2a28
   __DATA_CONST.__objc_classlist: 0x1090
   __DATA_CONST.__objc_catlist: 0xf0
   __DATA_CONST.__objc_protolist: 0x478
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbfa0
+  __DATA_CONST.__objc_selrefs: 0xc000
   __DATA_CONST.__objc_protorefs: 0x198
   __DATA_CONST.__objc_superrefs: 0xe80
   __DATA_CONST.__objc_arraydata: 0x688
-  __DATA_CONST.__got: 0x1968
-  __AUTH_CONST.__const: 0x171b0
-  __AUTH_CONST.__cfstring: 0x1df20
-  __AUTH_CONST.__objc_const: 0x39ba0
+  __DATA_CONST.__got: 0x1980
+  __AUTH_CONST.__const: 0x17228
+  __AUTH_CONST.__cfstring: 0x1e020
+  __AUTH_CONST.__objc_const: 0x39c00
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0xc78
   __AUTH_CONST.__objc_arrayobj: 0x378
   __AUTH_CONST.__objc_dictobj: 0x1b8
-  __AUTH_CONST.__auth_got: 0x2310
+  __AUTH_CONST.__auth_got: 0x2348
   __AUTH.__objc_data: 0x6308
   __AUTH.__data: 0xf68
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x10
   __DATA.__objc_ivar: 0x1980
-  __DATA.__data: 0x5fd8
+  __DATA.__data: 0x6018
   __DATA.__bss: 0xe638
   __DATA.__common: 0x7e8
-  __DATA_DIRTY.__objc_ivar: 0xb30
+  __DATA_DIRTY.__objc_ivar: 0xb38
   __DATA_DIRTY.__objc_data: 0x4b98
   __DATA_DIRTY.__data: 0x1240
   __DATA_DIRTY.__bss: 0xec0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24499
-  Symbols:   6447
-  CStrings:  6255
+  Functions: 24523
+  Symbols:   6458
+  CStrings:  6286
 
Symbols:
+ _$s8Dispatch0A13WorkItemFlagsVMa
+ _$s8Dispatch0A13WorkItemFlagsVMn
+ _$s8Dispatch0A13WorkItemFlagsVs10SetAlgebraAAMc
+ _$s8Dispatch0A3QoSV0B6SClassO7defaultyA2EmFWC
+ _$s8Dispatch0A3QoSV0B6SClassOMa
+ _$sSo17OS_dispatch_groupC8DispatchE6notify3qos5flags5queue7executeyAC0D3QoSV_AC0D13WorkItemFlagsVSo0a1_b1_H0CyyXBtF
+ _$sSo17OS_dispatch_queueC8DispatchE6global3qosAbC0D3QoSV0G6SClassO_tFZ
+ _$sSp12deinitialize5countSvSi_tF
+ _CKTestDeviceOptionSelfAddedPCSV2Upgrade
+ _clock_gettime
+ _setattrlist
CStrings:
+ "Anyone with link sharing %{public}s (Bohrium answer: %{public}s, source: %{public}s)"
+ "Anyone with link sharing %{public}s (Bohrium answer: %{public}s, source: test override)"
+ "Anyone with link sharing available (test hooks enabled, no eligibility override)"
+ "Container %{public}@ does not support share screening"
+ "Container %{public}@ supports share screening"
+ "Container %{public}@ supports share screening via test hook"
+ "DuplicateScreeningKey"
+ "Failed to restamp creation time of %{public}@: %{errno}d"
+ "HasBeenScreenedKey"
+ "IcloudSharingComplianceEnabled"
+ "InvalidScreeningKey"
+ "Screening disclosure %{public}s for share %@ (isNewShare: %d, hasBeenScreened: %d, serverPublicPermission: %{public}@, publicPermission: %{public}@)"
+ "Screening disclosure not required for share %@: container %{public}@ does not support screening"
+ "Screening disclosure not required for share %@: sharing compliance is disabled"
+ "SelfAddedPCSV2Upgrade"
+ "SelfAddedPCSV2UpgradeEnabled"
+ "ServerPublicPermission"
+ "available"
+ "clock_gettime failed while emptying %{public}@: %{errno}d"
+ "com.apple.cloudkit.unittest.screening"
+ "computed"
+ "eligible"
+ "forced"
+ "iCloudSharingCompliance"
+ "maybe"
+ "not available"
+ "not required"
+ "notEligible"
+ "notYetAvailable"
+ "required"
+ "selfAddedPCSV2Upgrade"
```
