## SystemMigrationNetwork

> `/System/Library/PrivateFrameworks/SystemMigrationNetwork.framework/Versions/A/SystemMigrationNetwork`

```diff

-1441.41.1.0.0
-  __TEXT.__text: 0x3cf94
-  __TEXT.__objc_methlist: 0x4618
-  __TEXT.__const: 0x130
-  __TEXT.__cstring: 0x98fd
-  __TEXT.__gcc_except_tab: 0xed0
-  __TEXT.__ustring: 0x2cf8
+1446.60.1.0.0
+  __TEXT.__text: 0x3dfd4
+  __TEXT.__objc_methlist: 0x4698
+  __TEXT.__const: 0x140
+  __TEXT.__cstring: 0x9aa9
+  __TEXT.__gcc_except_tab: 0xf38
+  __TEXT.__ustring: 0x2f56
   __TEXT.__oslogstring: 0xb
-  __TEXT.__unwind_info: 0x10a0
+  __TEXT.__unwind_info: 0x10e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x328
-  __DATA_CONST.__objc_classlist: 0x1d8
+  __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2a20
+  __DATA_CONST.__objc_selrefs: 0x2a70
   __DATA_CONST.__objc_superrefs: 0x138
   __DATA_CONST.__objc_arraydata: 0xf0
   __DATA_CONST.__got: 0x5c0
   __AUTH_CONST.__const: 0x810
-  __AUTH_CONST.__cfstring: 0x9940
-  __AUTH_CONST.__objc_const: 0x6938
+  __AUTH_CONST.__cfstring: 0x9ac0
+  __AUTH_CONST.__objc_const: 0x6a68
   __AUTH_CONST.__objc_intobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1248
-  __DATA.__objc_ivar: 0x538
+  __AUTH.__objc_data: 0x1298
+  __DATA.__objc_ivar: 0x544
   __DATA.__data: 0x318
   __DATA.__bss: 0x108
   __DATA.__common: 0x18

   - /usr/lib/libParallelCompression.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1550
-  Symbols:   4091
-  CStrings:  1289
+  Functions: 1564
+  Symbols:   4132
+  CStrings:  1301
 
Symbols:
+ -[SMNNetworkSession addressesWithThunderboltBridgeFirst:]
+ -[SMNNetworkSession candidateIsInUseOrBlacklisted:justAddressData:humanReadableAddress:]
+ -[SMNNetworkSession connectToThunderboltBridgeFromRemoteAddressMap]
+ -[SMNNetworkSession setThunderboltBridgeDialStates:]
+ -[SMNNetworkSession thunderboltBridgeDialStates]
+ -[SMNNetworkSession thunderboltBridgeLinkMayHaveChanged]
+ -[SMNThunderboltBridgeDialState attemptCount]
+ -[SMNThunderboltBridgeDialState nextAttemptNanoseconds]
+ -[SMNThunderboltBridgeDialState setAttemptCount:]
+ -[SMNThunderboltBridgeDialState setNextAttemptNanoseconds:]
+ GCC_except_table102
+ GCC_except_table107
+ GCC_except_table203
+ GCC_except_table204
+ GCC_except_table21
+ GCC_except_table226
+ GCC_except_table228
+ GCC_except_table23
+ GCC_except_table35
+ GCC_except_table44
+ GCC_except_table53
+ GCC_except_table58
+ GCC_except_table63
+ GCC_except_table64
+ GCC_except_table66
+ GCC_except_table70
+ GCC_except_table79
+ GCC_except_table87
+ GCC_except_table94
+ GCC_except_table99
+ _OBJC_CLASS_$_SMNThunderboltBridgeDialState
+ _OBJC_IVAR_$_SMNNetworkSession._thunderboltBridgeDialStates
+ _OBJC_IVAR_$_SMNThunderboltBridgeDialState._attemptCount
+ _OBJC_IVAR_$_SMNThunderboltBridgeDialState._nextAttemptNanoseconds
+ _OBJC_METACLASS_$_SMNThunderboltBridgeDialState
+ _SMNCandidateMatchesPath
+ _SMNIsAWDLInterfaceIndex
+ _SMNScopeIDForSocketAddress
+ __OBJC_$_INSTANCE_METHODS_SMNThunderboltBridgeDialState
+ __OBJC_$_INSTANCE_VARIABLES_SMNThunderboltBridgeDialState
+ __OBJC_$_PROP_LIST_SMNThunderboltBridgeDialState
+ __OBJC_CLASS_RO_$_SMNThunderboltBridgeDialState
+ __OBJC_METACLASS_RO_$_SMNThunderboltBridgeDialState
+ ___56-[SMNNetworkSession thunderboltBridgeLinkMayHaveChanged]_block_invoke
+ _clock_gettime_nsec_np
+ _if_indextoname
+ _if_nametoindex
+ _objc_msgSend$addressesWithThunderboltBridgeFirst:
+ _objc_msgSend$attemptCount
+ _objc_msgSend$candidateIsInUseOrBlacklisted:justAddressData:humanReadableAddress:
+ _objc_msgSend$connectToThunderboltBridgeFromRemoteAddressMap
+ _objc_msgSend$nextAttemptNanoseconds
+ _objc_msgSend$setAttemptCount:
+ _objc_msgSend$setNextAttemptNanoseconds:
+ _objc_msgSend$setThunderboltBridgeDialStates:
+ _objc_msgSend$thunderboltBridgeDialStates
+ _objc_msgSend$thunderboltBridgeLinkMayHaveChanged
- GCC_except_table17
- GCC_except_table190
- GCC_except_table191
- GCC_except_table213
- GCC_except_table215
- GCC_except_table31
- GCC_except_table40
- GCC_except_table41
- GCC_except_table50
- GCC_except_table55
- GCC_except_table68
- GCC_except_table72
- GCC_except_table76
- GCC_except_table88
- GCC_except_table91
- GCC_except_table96
CStrings:
+ "(unknown)"
+ "State:/Network/Interface/bridge"
+ "[SMNNetworkSession] Dialing %lu Thunderbolt Bridge (%@) candidate(s) first"
+ "[TBBridge] No Thunderbolt connection; dialing source %@ address %@ from its address map (attempt %lu of %lu)"
+ "[TBBridge] Not dialing %@: %lu attempts failed (waiting for a Thunderbolt Bridge link change)"
+ "[TBBridge] Thunderbolt Bridge link changed; checking the source address map"
+ "[TBBridge] ✅ Connected over the Thunderbolt Bridge from the source address map: %@"
+ "[TBBridge] ❌ Dial to %@ failed (attempt %lu of %lu); next try after %0.0fs or on a Thunderbolt Bridge link change"
+ "[TBBridge] ❌ Dial to %@ failed (attempt %lu of %lu); no more tries until a Thunderbolt Bridge link change"
+ "awdl"
+ "bridge"
+ "remoteSocketAddress"
```
