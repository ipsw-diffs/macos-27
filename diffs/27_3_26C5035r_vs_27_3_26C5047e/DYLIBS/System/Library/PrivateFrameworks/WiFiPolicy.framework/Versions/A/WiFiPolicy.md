## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

```diff

-1080.2.0.0.0
-  __TEXT.__text: 0xdef48
+1080.4.0.0.0
+  __TEXT.__text: 0xdefe8
   __TEXT.__objc_methlist: 0x137f0
   __TEXT.__const: 0x7c0
-  __TEXT.__cstring: 0x23a7b
+  __TEXT.__cstring: 0x23aab
   __TEXT.__oslogstring: 0x4026
   __TEXT.__gcc_except_tab: 0x1754
   __TEXT.__dlopen_cstrs: 0x52

   __DATA_CONST.__objc_arraydata: 0x1548
   __DATA_CONST.__got: 0xb40
   __AUTH_CONST.__const: 0x2118
-  __AUTH_CONST.__cfstring: 0x1fd20
+  __AUTH_CONST.__cfstring: 0x1fd60
   __AUTH_CONST.__objc_const: 0x25278
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x1a58

   - /usr/lib/swift/libswiftos.dylib
   Functions: 7076
   Symbols:   15270
-  CStrings:  5067
+  CStrings:  5069
 
Symbols:
+ -[WiFiUsageMonitor appendAppleMeshFieldsToDict:isMeshEligibleNetwork:]
+ _objc_msgSend$appendAppleMeshFieldsToDict:isMeshEligibleNetwork:
- -[WiFiUsageMonitor appendAppleMeshFieldsToDict:]
- _objc_msgSend$appendAppleMeshFieldsToDict:
Functions:
~ -[WiFiUsageMonitor appendAppleMeshFieldsToDict:] -> -[WiFiUsageMonitor appendAppleMeshFieldsToDict:isMeshEligibleNetwork:] : 416 -> 544
~ -[WiFiUsageMonitor submitLqmToCA:forInterface:] : 2116 -> 2148
CStrings:
+ "foundMeshCandidate"
+ "meshCandidateCount"
```
