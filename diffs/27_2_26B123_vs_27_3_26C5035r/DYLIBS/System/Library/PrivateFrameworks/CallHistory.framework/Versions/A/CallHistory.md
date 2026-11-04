## CallHistory

> `/System/Library/PrivateFrameworks/CallHistory.framework/Versions/A/CallHistory`

```diff

-156.200.131.1.11
-  __TEXT.__text: 0x1b73c8
+156.300.51.0.0
+  __TEXT.__text: 0x1b762c
   __TEXT.__objc_methlist: 0x3a84
   __TEXT.__const: 0x1e840
-  __TEXT.__cstring: 0x42d6
-  __TEXT.__oslogstring: 0x63f9
+  __TEXT.__cstring: 0x42c6
+  __TEXT.__oslogstring: 0x64e9
   __TEXT.__gcc_except_tab: 0x7e0
   __TEXT.__dlopen_cstrs: 0xe3
   __TEXT.__constg_swiftt: 0x114f0

   __TEXT.__swift_as_cont: 0x104
   __TEXT.__swift5_capture: 0x3f0
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0xac50
+  __TEXT.__unwind_info: 0xac58
   __TEXT.__eh_frame: 0x7988
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12405
+  Functions: 12406
   Symbols:   5916
-  CStrings:  1082
+  CStrings:  1086
 
Functions:
~ -[CallHistoryDBHandle migrateAllDataFromExtensionWithApplicationID:toExtensionWithApplicationID:withCompletionHandler:] : 912 -> 960
~ -[CHRecentCall setLocationOnQueue:completion:] : 440 -> 768
~ ___46-[CHRecentCall setLocationOnQueue:completion:]_block_invoke_2 : 60 -> 240
~ -[CHRecentCall setLocationTo:] : 12 -> 232
~ -[CHRecentCall callerIdLocation] : 292 -> 76
+ -[CallHistoryDBHandle migrateAllDataFromExtensionWithApplicationID:toExtensionWithApplicationID:withCompletionHandler:].cold.1
CStrings:
+ "156.300.51"
+ "156.300.51~188"
+ "==> callerIdLocation resolved for %@ -> %{public}@"
+ "==> callerIdLocation resolved for %@ -> %{public}@ (handle is not a phone number)"
+ "==> callerIdLocation resolved for %@ -> %{public}@ (no single valid remote handle)"
+ "==> callerIdLocation set for %@ -> %{public}@"
+ "Call record query failed"
- "156.200.131.1.11"
- "156.200.131.1.11~2"
- "==> %{public}@. Current location info for %@ is %@"
```
