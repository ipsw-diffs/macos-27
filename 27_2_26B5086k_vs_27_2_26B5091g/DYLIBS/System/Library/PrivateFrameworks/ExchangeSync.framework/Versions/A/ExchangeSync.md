## ExchangeSync

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/ExchangeSync`

```diff

-2080.200.31.0.0
-  __TEXT.__text: 0x16c4cc
+2080.200.41.0.0
+  __TEXT.__text: 0x16ff74
   __TEXT.__objc_methlist: 0x5f44
-  __TEXT.__const: 0x8524
+  __TEXT.__const: 0x85e4
   __TEXT.__gcc_except_tab: 0xf80
-  __TEXT.__cstring: 0x11612
+  __TEXT.__cstring: 0x11a82
   __TEXT.__oslogstring: 0x6ada
-  __TEXT.__swift5_typeref: 0x2a04
-  __TEXT.__swift5_reflstr: 0x292c
+  __TEXT.__swift5_typeref: 0x2a10
+  __TEXT.__swift5_reflstr: 0x299c
   __TEXT.__swift5_assocty: 0x920
-  __TEXT.__constg_swiftt: 0x2ef4
-  __TEXT.__swift5_fieldmd: 0x297c
+  __TEXT.__constg_swiftt: 0x2f58
+  __TEXT.__swift5_fieldmd: 0x29d8
   __TEXT.__swift5_proto: 0x3e0
-  __TEXT.__swift5_types: 0x348
+  __TEXT.__swift5_types: 0x350
   __TEXT.__swift5_protos: 0xcc
+  __TEXT.__swift5_capture: 0x808
   __TEXT.__swift5_builtin: 0xb4
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__swift5_capture: 0x808
   __TEXT.__swift_as_entry: 0x8c
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0x128
-  __TEXT.__unwind_info: 0x5d98
-  __TEXT.__eh_frame: 0x5eec
+  __TEXT.__unwind_info: 0x5e10
+  __TEXT.__eh_frame: 0x5f24
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x4d0
-  __DATA_CONST.__objc_classlist: 0x368
+  __DATA_CONST.__objc_classlist: 0x370
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3ca8
+  __DATA_CONST.__objc_selrefs: 0x3cb8
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x1c0
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x14c8
-  __AUTH_CONST.__const: 0x8810
+  __AUTH_CONST.__const: 0x8830
   __AUTH_CONST.__cfstring: 0x4540
-  __AUTH_CONST.__objc_const: 0xd020
+  __AUTH_CONST.__objc_const: 0xd110
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2088
-  __AUTH.__objc_data: 0x1d40
-  __AUTH.__data: 0x2f18
+  __AUTH_CONST.__auth_got: 0x2090
+  __AUTH.__objc_data: 0x1d90
+  __AUTH.__data: 0x2fd8
   __DATA.__objc_ivar: 0x764
-  __DATA.__data: 0x16a8
-  __DATA.__bss: 0x6770
-  __DATA.__common: 0x278
+  __DATA.__data: 0x16b8
+  __DATA.__bss: 0x67b0
+  __DATA.__common: 0x290
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 7019
-  Symbols:   6813
-  CStrings:  1726
+  Functions: 7056
+  Symbols:   6821
+  CStrings:  1738
 
Symbols:
+ __DATA__TtC12ExchangeSync17EXSGSThrottleGate
+ __IVARS__TtC12ExchangeSync17EXSGSThrottleGate
+ __METACLASS_DATA__TtC12ExchangeSync17EXSGSThrottleGate
+ _objc_msgSend$component:fromDate:
+ _objc_msgSend$dateByAddingUnit:value:toDate:options:
+ _swift_isClassType
+ _symbolic _____ 12ExchangeSync17EXSGSThrottleGateC
+ _symbolic _____ 12ExchangeSync23EXSGSThrottleGatePolicyO
CStrings:
+ "Calendar upsync: %{public}@ has no authored time zone (floating; specified=%{public}d); declaring the fallback zone"
+ "Calendar upsync: %{public}@ time zone is an empty string; declaring the fallback zone"
+ "Graph Sync: added deferred attendees to calendar event %{public}@ after attachment reconciliation"
+ "Graph Sync: could not resolve created calendar event to add deferred attendees"
+ "Graph Sync: declining server deletion, dataclass sync is inactive - itemType %ld account %{public}@ item %{public}@"
+ "Graph Sync: deferring attendees on calendar event create pending attachment reconciliation"
+ "Graph Sync: throttle gate cleared after %{public}ld skipped round(s) (%{public}@)"
+ "Graph Sync: throttle gate closed for %{public}.0fs (retryAfter=%{public}@ deferrals=%{public}ld)"
+ "Graph Sync: throttle gate closed, skipping round (skipped=%{public}ld)"
+ "Graph Sync: throttle gate reopened after %{public}.0fs (skipped=%{public}ld rounds, %{public}@)"
+ "account changed"
+ "dataclass refresh requested"
+ "events/delta exception protection for folder %{public}@: skippedMasters=%d already enumerated this round, no probe needed"
+ "events/delta exception protection for folder %{public}@: skippedMasters=%d alreadyEnumerated=%d probed=%d exceptions=%d unanswered=%d"
- "$batch hydration throttled (HTTP 429); Retry-After exceeds inline budget or retries exhausted."
- "events/delta exception protection for folder %{public}@: skippedMasters=%d exceptions=%d unanswered=%d"
```
