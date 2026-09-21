## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities`

```diff

-1626.200.53.0.0
-  __TEXT.__text: 0x1b2a6c
-  __TEXT.__objc_methlist: 0x1b9c0
-  __TEXT.__cstring: 0x12836
-  __TEXT.__const: 0x4acc
-  __TEXT.__oslogstring: 0x13687
+1626.200.65.0.0
+  __TEXT.__text: 0x1b33ac
+  __TEXT.__objc_methlist: 0x1ba18
+  __TEXT.__cstring: 0x12916
+  __TEXT.__const: 0x4adc
+  __TEXT.__oslogstring: 0x136a7
   __TEXT.__gcc_except_tab: 0x141c
   __TEXT.__ustring: 0xde
   __TEXT.__dlopen_cstrs: 0x4fb

   __TEXT.__swift_as_cont: 0x194
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x8f10
+  __TEXT.__unwind_info: 0x8f28
   __TEXT.__eh_frame: 0x2a70
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x420
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb660
+  __DATA_CONST.__objc_selrefs: 0xb690
   __DATA_CONST.__objc_protorefs: 0x110
   __DATA_CONST.__objc_superrefs: 0x700
   __DATA_CONST.__objc_arraydata: 0xac0
   __DATA_CONST.__got: 0x1048
-  __AUTH_CONST.__const: 0x66f0
-  __AUTH_CONST.__cfstring: 0x12500
-  __AUTH_CONST.__objc_const: 0x2b4c8
+  __AUTH_CONST.__const: 0x6780
+  __AUTH_CONST.__cfstring: 0x12580
+  __AUTH_CONST.__objc_const: 0x2b578
   __AUTH_CONST.__objc_intobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0x2e8
   __AUTH_CONST.__auth_got: 0x1378
-  __AUTH.__objc_data: 0x2920
+  __AUTH.__objc_data: 0x2510
   __AUTH.__data: 0xcf0
-  __DATA.__objc_ivar: 0x1934
+  __DATA.__objc_ivar: 0x1940
   __DATA.__data: 0x3f10
   __DATA.__bss: 0x7ae0
   __DATA.__common: 0xb0
-  __DATA_DIRTY.__objc_data: 0x3078
+  __DATA_DIRTY.__objc_data: 0x3488
   __DATA_DIRTY.__data: 0x198
   __DATA_DIRTY.__bss: 0x7c0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11732
-  Symbols:   20535
-  CStrings:  4433
+  Functions: 11743
+  Symbols:   20557
+  CStrings:  4438
 
Symbols:
+ -[TUCall relayHostCallScreeningEligibility]
+ -[TUIDSLookupManager lastForcedQueryTimestamps]
+ -[TUSimulatedIDSIDQueryController _currentCachedRemoteDevicesForDestinations:service:preferredFromID:listenerID:]
+ -[TUSimulatedIDSIDQueryController currentRemoteDevicesForDestinations:service:preferredFromID:listenerID:queue:completionBlockWithError:]
+ -[TUSimulatedParticipantUpdate isVideoEnabled]
+ -[TUSimulatedParticipantUpdate setVideoEnabled:]
+ OBJC_IVAR_$_TUCall._relayHostCallScreeningEligibility
+ OBJC_IVAR_$_TUIDSLookupManager._lastForcedQueryTimestamps
+ OBJC_IVAR_$_TUSimulatedParticipantUpdate._videoEnabled
+ ___58-[TUIDSLookupManager beginQueryWithDestination:onService:]_block_invoke_2
+ ___58-[TUIDSLookupManager beginQueryWithDestination:onService:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e33_B32?0"NSString"8"NSDate"16^B24l
+ ___block_descriptor_56_e8_32s40s48s_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_64_e8_32s40s48s56s_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72b
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ __endpointsDictionaryForDestinations
+ _objc_msgSend$_currentCachedRemoteDevicesForDestinations:service:preferredFromID:listenerID:
+ _objc_msgSend$keysOfEntriesPassingTest:
+ _objc_msgSend$lastForcedQueryTimestamps
+ _objc_msgSend$relayHostCallScreeningEligibility
+ _objc_msgSend$removeObjectsForKeys:
- ___block_descriptor_56_e8_32s40s48bs_e22_v16?0"NSDictionary"8l
CStrings:
+ " rhse=%ld"
+ "B32@?0@\"NSString\"8@\"NSDate\"16^B24"
+ "Companion Software Not Compatible"
+ "The companion device could not complete the operation because it is on an incompatible software version."
+ "isEligibleForScreening: YES because the host device reported this relay call as eligible"
+ "relayHostCallScreeningEligibility"
+ "smartHoldingAvailability=%i, callSupportsScreening=%i validRemoteParticipantCount=%i validNotConferenced=%i, validSystemProvider=%i, validNotEmergencyCall=%i, validCallStatus=%i(%i), validEndpointOnCurrentDevice=%i, validIsNotVideo=%i, validLocale=%i(%@), validCaptioningAvailable=%i, isGASRAvailable=%i, validLockdownMode=%i, qfaLocaleExpansionEnabled=%i, qfaLocaleExpansionItPtEnabled=%i"
- "isEligibleForScreening: YES because it is a relay call that can screen"
- "smartHoldingAvailability=%i, validRemoteParticipantCount=%i validNotConferenced=%i, validSystemProvider=%i, validNotEmergencyCall=%i, validCallStatus=%i(%i), validEndpointOnCurrentDevice=%i, validIsNotVideo=%i, validLocale=%i(%@), validCaptioningAvailable=%i, isGASRAvailable=%i, validLockdownMode=%i, qfaLocaleExpansionEnabled=%i, qfaLocaleExpansionItPtEnabled=%i"
```
