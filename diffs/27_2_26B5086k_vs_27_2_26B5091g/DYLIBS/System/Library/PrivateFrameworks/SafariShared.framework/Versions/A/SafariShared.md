## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/Versions/A/SafariShared`

```diff

-625.2.4.1.0
-  __TEXT.__text: 0x2db72c
+625.2.5.11.1
+  __TEXT.__text: 0x2ddca4
   __TEXT.__objc_methlist: 0x1728c
-  __TEXT.__const: 0xa37a4
+  __TEXT.__const: 0xa38c4
   __TEXT.__gcc_except_tab: 0x20884
-  __TEXT.__cstring: 0x250f7
+  __TEXT.__cstring: 0x25107
   __TEXT.__ustring: 0xcec0
-  __TEXT.__oslogstring: 0x16e12
+  __TEXT.__oslogstring: 0x16df2
   __TEXT.__dlopen_cstrs: 0x394
-  __TEXT.__swift5_typeref: 0x33b8
-  __TEXT.__swift5_fieldmd: 0x18b0
-  __TEXT.__constg_swiftt: 0x21c8
-  __TEXT.__swift5_builtin: 0x17c
-  __TEXT.__swift5_reflstr: 0x1648
+  __TEXT.__swift5_typeref: 0x33f8
+  __TEXT.__swift5_fieldmd: 0x18f0
+  __TEXT.__constg_swiftt: 0x2244
+  __TEXT.__swift5_builtin: 0x1cc
+  __TEXT.__swift5_reflstr: 0x1678
   __TEXT.__swift5_assocty: 0x4b0
   __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_proto: 0x448
-  __TEXT.__swift5_types: 0x1a4
-  __TEXT.__swift5_capture: 0x101c
-  __TEXT.__swift_as_entry: 0x180
-  __TEXT.__swift_as_ret: 0x168
-  __TEXT.__swift_as_cont: 0x2ec
-  __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x122c8
-  __TEXT.__eh_frame: 0x5590
+  __TEXT.__swift5_types: 0x1b0
+  __TEXT.__swift5_capture: 0x1160
+  __TEXT.__swift5_mpenum: 0x30
+  __TEXT.__swift_as_entry: 0x184
+  __TEXT.__swift_as_ret: 0x16c
+  __TEXT.__swift_as_cont: 0x2f0
+  __TEXT.__unwind_info: 0x12368
+  __TEXT.__eh_frame: 0x5640
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xef88
+  __DATA_CONST.__const: 0xf010
   __DATA_CONST.__objc_classlist: 0xd88
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x2e8

   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x9d0
   __DATA_CONST.__objc_arraydata: 0xb70
-  __DATA_CONST.__got: 0x20e0
-  __AUTH_CONST.__const: 0x14000
+  __DATA_CONST.__got: 0x21d8
+  __AUTH_CONST.__const: 0x140b0
   __AUTH_CONST.__cfstring: 0x1bdc0
   __AUTH_CONST.__objc_const: 0x2a290
   __AUTH_CONST.__weak_auth_got: 0x28

   __AUTH_CONST.__objc_arrayobj: 0x3a8
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x2a60
+  __AUTH_CONST.__auth_got: 0x2c00
   __AUTH.__objc_data: 0x3f48
   __AUTH.__data: 0xf40
   __DATA.__objc_ivar: 0x1a38
-  __DATA.__data: 0x5598
+  __DATA.__data: 0x55e8
   __DATA.__bss: 0x7900
   __DATA.__common: 0x70
   __DATA_DIRTY.__objc_data: 0x48d0

   - /System/Library/PrivateFrameworks/Trial.framework/Versions/A/Trial
   - /System/Library/PrivateFrameworks/UnilogCommonLibrary.framework/Versions/A/UnilogCommonLibrary
   - /System/Library/PrivateFrameworks/UnilogInstrumentation.framework/Versions/A/UnilogInstrumentation
+  - /System/Library/PrivateFrameworks/UnilogSafariFeatureLibrary.framework/Versions/A/UnilogSafariFeatureLibrary
   - /System/Library/PrivateFrameworks/UnilogSafariSearchLibrary.framework/Versions/A/UnilogSafariSearchLibrary
   - /System/Library/PrivateFrameworks/UsageTracking.framework/Versions/A/UsageTracking
   - /usr/lib/libMobileGestalt.dylib

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 15568
-  Symbols:   25259
+  Functions: 15551
+  Symbols:   25269
   CStrings:  6392
 
Symbols:
+ __swift_closure_destructor.246Tm
+ _symbolic _____ 12SafariShared24WBSUsageRetentionVariantO
+ _symbolic _____ So30WBSUsageRetentionExtensionTypeV
+ _symbolic _____ So33WBSUsageRetentionAutoFillCategoryV
+ _symbolic _____ So34WBSUsageRetentionPrivacyReportKindV
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary0C5EventV12PayloadUnionO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary13ExtensionTypeO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary16AutoFillCategoryO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary17PrivacyReportTypeO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary7TriggerO
CStrings:
+ "22625.2.5.11.1"
+ "Donating feature usage: %{public}s/%{public}s%{public}s x%{public}ld"
+ "Donating settings snapshot: nonDefaultProfile=%{bool,public}d iCloudTabs=%{bool,public}d sync=%{bool,public}d extensions=%{bool,public}d"
+ "Pruned donated feature events since %{public}s."
- "22625.2.4.1"
- "Pending feature usage donation: %{public}s/%{public}s%{public}s x%{public}ld"
- "Pending prune of donated feature events since %{public}s."
- "Pending settings snapshot donation: nonDefaultProfile=%{bool,public}d iCloudTabs=%{bool,public}d sync=%{bool,public}d extensions=%{bool,public}d"
```
