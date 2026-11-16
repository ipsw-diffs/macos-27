## ModelCatalogRuntime

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/Versions/A/ModelCatalogRuntime`

```diff

-308.15.4.0.1
-  __TEXT.__text: 0x95dac
-  __TEXT.__objc_methlist: 0x664
-  __TEXT.__const: 0x3a48
-  __TEXT.__swift5_typeref: 0x1f54
-  __TEXT.__swift5_capture: 0x17ac
-  __TEXT.__cstring: 0x1b1e
-  __TEXT.__constg_swiftt: 0x14f0
-  __TEXT.__swift5_builtin: 0x78
-  __TEXT.__swift5_reflstr: 0xc03
-  __TEXT.__swift5_fieldmd: 0xe64
+308.15.9.0.0
+  __TEXT.__text: 0x9aa30
+  __TEXT.__objc_methlist: 0x694
+  __TEXT.__const: 0x3d78
+  __TEXT.__swift5_typeref: 0x20c8
+  __TEXT.__swift5_capture: 0x1804
+  __TEXT.__cstring: 0x1b8c
+  __TEXT.__constg_swiftt: 0x1614
+  __TEXT.__swift5_builtin: 0xa0
+  __TEXT.__swift5_reflstr: 0xd13
+  __TEXT.__swift5_fieldmd: 0xfd4
   __TEXT.__swift5_assocty: 0x238
-  __TEXT.__oslogstring: 0x4e0a
-  __TEXT.__swift5_proto: 0x1e0
-  __TEXT.__swift5_types: 0x148
-  __TEXT.__swift_as_entry: 0x178
+  __TEXT.__oslogstring: 0x5163
+  __TEXT.__swift5_proto: 0x1ec
+  __TEXT.__swift5_types: 0x164
+  __TEXT.__swift_as_entry: 0x17c
   __TEXT.__swift_as_ret: 0x190
-  __TEXT.__swift_as_cont: 0x340
-  __TEXT.__swift5_protos: 0x58
+  __TEXT.__swift_as_cont: 0x344
+  __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x26e0
-  __TEXT.__eh_frame: 0x506c
+  __TEXT.__unwind_info: 0x2818
+  __TEXT.__eh_frame: 0x5284
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd0
-  __DATA_CONST.__objc_classlist: 0xc8
+  __DATA_CONST.__const: 0xf8
+  __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_protolist: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x588
+  __DATA_CONST.__objc_selrefs: 0x598
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x5380
-  __AUTH_CONST.__objc_const: 0x1858
-  __AUTH_CONST.__auth_got: 0x1530
+  __AUTH_CONST.__const: 0x56c8
+  __AUTH_CONST.__objc_const: 0x1a78
+  __AUTH_CONST.__auth_got: 0x1628
   __AUTH.__objc_data: 0x120
-  __AUTH.__data: 0x610
-  __DATA.__data: 0xb60
-  __DATA.__bss: 0x2290
+  __AUTH.__data: 0x770
+  __DATA.__data: 0xc00
+  __DATA.__bss: 0x2390
   __DATA.__common: 0x20
-  __DATA_DIRTY.__objc_data: 0x410
-  __DATA_DIRTY.__data: 0x16e0
+  __DATA_DIRTY.__objc_data: 0x418
+  __DATA_DIRTY.__data: 0x16f0
   __DATA_DIRTY.__common: 0x400
   __DATA_DIRTY.__bss: 0xd00
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3670
-  Symbols:   226
-  CStrings:  418
+  Functions: 3771
+  Symbols:   233
+  CStrings:  431
 
Symbols:
+ _notify_cancel
+ _notify_check
+ _notify_register_check
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain_n
CStrings:
+ "DarwinNotificationChangeChecker: failed to register for %{public}s with status %u; every check will report a change"
+ "DarwinNotificationChangeChecker: notify_check for %{public}s failed with status %u"
+ "Duplicate values for key: '"
+ "EURegulatoryRegionEvaluator: %{public}s -> %{public}s (prionus answer: %{public}s)"
+ "EURegulatoryRegionEvaluator: unknown use case identifier %{public}s"
+ "SensitiveRegionEvaluator: rejecting arguments for use case %{public}s because isMainlandChina is 'false' on a sensitive region device"
+ "Swift/NativeDictionary.swift"
+ "TemporaryGuardrailHelpers: isChinaMode %{bool}d"
+ "TemporaryGuardrailHelpers: osEligibility.status for %s is %s"
+ "com.apple.os-eligibility-domain.change."
+ "donateGenerativeGuardrailResult is not in China mode, forfeit donation."
+ "donateGenerativeGuardrailResult is not triggered becease the UseCaseIdentifier initialization of %s is null"
+ "donateGenerativeGuardrailResult is not triggered by user actively, forfeit donation."
+ "donateGenerativeGuardrailResult: error while donating regional guardrail result: %@"
+ "prionus"
+ "send GenerativeExperiencesGuardrailResult event"
- "Bypassing availability secure check for use case access gate"
- "Skip requesting resource bundle for %s: bundle policy gated_by_use_case_access not yet granted."
- "Use case access gate for %s on %s: blocked=%{bool}d"
```
