## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/Versions/A/InputAnalyticsServer`

```diff

-154.1.8.500.0
-  __TEXT.__text: 0x8542c
-  __TEXT.__objc_methlist: 0x6604
-  __TEXT.__const: 0x720
-  __TEXT.__gcc_except_tab: 0xcd0
-  __TEXT.__cstring: 0x6522
-  __TEXT.__oslogstring: 0x81e0
+154.2.4.0.0
+  __TEXT.__text: 0x88a70
+  __TEXT.__objc_methlist: 0x68b4
+  __TEXT.__const: 0x7b0
+  __TEXT.__gcc_except_tab: 0xcf0
+  __TEXT.__cstring: 0x6822
+  __TEXT.__oslogstring: 0x8500
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x1f6
   __TEXT.__constg_swiftt: 0x118

   __TEXT.__swift5_capture: 0x98
   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__unwind_info: 0x1fb8
+  __TEXT.__unwind_info: 0x2090
   __TEXT.__eh_frame: 0x3d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1580
-  __DATA_CONST.__objc_classlist: 0x3f8
+  __DATA_CONST.__const: 0x15e0
+  __DATA_CONST.__objc_classlist: 0x400
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x32f0
+  __DATA_CONST.__objc_selrefs: 0x3478
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x230
+  __DATA_CONST.__objc_superrefs: 0x240
   __DATA_CONST.__objc_arraydata: 0x398
-  __DATA_CONST.__got: 0x19f8
-  __AUTH_CONST.__const: 0x1b18
-  __AUTH_CONST.__cfstring: 0x6be0
-  __AUTH_CONST.__objc_const: 0xab48
-  __AUTH_CONST.__objc_intobj: 0x1b90
+  __DATA_CONST.__got: 0x1a48
+  __AUTH_CONST.__const: 0x1c08
+  __AUTH_CONST.__cfstring: 0x6e60
+  __AUTH_CONST.__objc_const: 0xae30
+  __AUTH_CONST.__objc_intobj: 0x1c20
   __AUTH_CONST.__objc_arrayobj: 0x4e0
   __AUTH_CONST.__auth_got: 0x9c8
-  __AUTH.__objc_data: 0xad8
+  __AUTH.__objc_data: 0xb28
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x770
+  __DATA.__objc_ivar: 0x7a0
   __DATA.__data: 0x478
-  __DATA.__bss: 0x208
+  __DATA.__bss: 0x238
   __DATA_DIRTY.__objc_data: 0x1ea0
   __DATA_DIRTY.__data: 0x258
   __DATA_DIRTY.__bss: 0x6d8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2908
-  Symbols:   953
-  CStrings:  1516
+  Functions: 2991
+  Symbols:   963
+  CStrings:  1549
 
Symbols:
+ _IAChannelPencilVisualIntelligence
+ _IAPayloadKeyPencilSystemDisplayIdentifier
+ _IAPayloadKeyPencilVisualIntelligenceUnderlyingBundleId
+ _IASignalPencilVisualIntelligenceEnterHighlightDoubleTap
+ _IASignalPencilVisualIntelligenceEnterHighlightSqueezePalette
+ _IASignalPencilVisualIntelligenceEnterHighlightUnspecified
+ _IASignalPencilVisualIntelligenceExitHighlight
+ _IASignalPencilVisualIntelligenceLassoSelection
+ _IASignalPencilVisualIntelligenceSiriRequestSent
+ _IASignalPencilVisualIntelligenceSuggestionSelected
CStrings:
+ "BEGIN TRANSACTION;DROP TABLE IF EXISTS %1$@;CREATE TABLE %1$@ (date TEXT NOT NULL, pencilVersion INTEGER NOT NULL, usageType INTEGER NOT NULL, appInfo TEXT NOT NULL, inUseDisplay INTEGER NOT NULL, devicePose INTEGER NOT NULL, activeMinutes INTEGER, activeSeconds INTEGER, lastActivityTimestamp INTEGER, PRIMARY KEY (date, pencilVersion, usageType, appInfo, inUseDisplay, devicePose));COMMIT;"
+ "Device pose changed: hingeState=%lu, outerOrientation=%lu, innerOrientation=%lu, timestamp=%f"
+ "DevicePoseChanged"
+ "Failed to load AOP daily event counter for %{private}@: %{private}@"
+ "Failed to migrate the pencil usage table to v3 with error %{private}s"
+ "Failed to reset AOP daily event counter for %{private}@: %{private}@"
+ "Migrated the pencil usage table to v3 (dropped the old table, added the devicePose column)."
+ "Not publishing pencil VI signal: %{private}@"
+ "Pencil VI signal %{private}@ carries no underlying bundle id."
+ "Pencil VI signal %{private}@ from CampoUI carries no session id."
+ "Pencil VI signal %{private}@ received outside a VI session."
+ "SuggestionCategoryEventCount"
+ "Unexpected AOP event name %@"
+ "actionType=%@"
+ "analyzer"
+ "analyzerId"
+ "analyzers"
+ "class"
+ "com.apple.inputAnalytics.pencilIntelligence"
+ "devicePose"
+ "dumpStateWithReply: %{private}@ returned a nil stateDictionary, skipping"
+ "dumpStateWithReply: JSON serialization failed: %{private}@"
+ "dumpStateWithReply: state dictionary is not JSON-serializable"
+ "hingeState"
+ "innerOrientation"
+ "linkedSessionIds"
+ "onDiskVersionForTable should be exhaustive but wasn't. Returning Unknown."
+ "outerOrientation"
+ "pccRequestType"
+ "sessionManagers"
+ "sessions"
+ "state"
+ "timestamp"
+ "v32@?0@\"NSNumber\"8@\"IASCandidateBarAnalyzer\"16^B24"
+ "v32@?0@\"NSString\"8@\"NSArray\"16^B24"
- "Failed to load AOP daily event counter: %{private}@"
- "Failed to reset AOP daily event counter: %{private}@"
```
