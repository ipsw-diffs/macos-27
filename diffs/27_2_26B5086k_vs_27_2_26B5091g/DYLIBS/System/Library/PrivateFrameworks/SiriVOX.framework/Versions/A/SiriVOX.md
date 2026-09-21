## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/Versions/A/SiriVOX`

```diff

-3605.15.1.0.0
-  __TEXT.__text: 0x89ce4
-  __TEXT.__objc_methlist: 0x8b90
+3605.17.1.0.0
+  __TEXT.__text: 0x8a3b8
+  __TEXT.__objc_methlist: 0x8bc0
   __TEXT.__const: 0x12c
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x97
   __TEXT.__swift5_fieldmd: 0x38
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x1157e
+  __TEXT.__cstring: 0x116cc
   __TEXT.__swift5_capture: 0x78
   __TEXT.__swift5_reflstr: 0x16
   __TEXT.__gcc_except_tab: 0x5cc
-  __TEXT.__oslogstring: 0x8850
+  __TEXT.__oslogstring: 0x8956
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__unwind_info: 0x2c98
+  __TEXT.__unwind_info: 0x2cb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d38
+  __DATA_CONST.__objc_selrefs: 0x3d98
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x980
-  __DATA_CONST.__got: 0x768
-  __AUTH_CONST.__const: 0x2c38
-  __AUTH_CONST.__cfstring: 0x5f40
-  __AUTH_CONST.__objc_const: 0x13818
+  __DATA_CONST.__got: 0x778
+  __AUTH_CONST.__const: 0x2cc8
+  __AUTH_CONST.__cfstring: 0x5f60
+  __AUTH_CONST.__objc_const: 0x13878
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_dictobj: 0x348
   __AUTH_CONST.__auth_got: 0x570
   __AUTH.__objc_data: 0x4150
   __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0xcb4
+  __DATA.__objc_ivar: 0xcc0
   __DATA.__data: 0x2260
   __DATA.__bss: 0x248
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3202
-  Symbols:   8370
-  CStrings:  2237
+  Functions: 3208
+  Symbols:   8395
+  CStrings:  2249
 
Symbols:
+ -[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]
+ -[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]
+ -[SVXSession _electionLedger]
+ -[SVXSession _useElectionLedger:]
+ -[SVXSession _waitForLedgerDecisionForElection:usingHandler:]
+ -[SVXSession beginElectionWithIdentity:]
+ GCC_except_table2539
+ GCC_except_table2541
+ GCC_except_table2544
+ GCC_except_table2849
+ GCC_except_table3005
+ GCC_except_table3080
+ OBJC_IVAR_$_SVXSession._electionIdentity
+ OBJC_IVAR_$_SVXSession._electionLedgerOverride
+ OBJC_IVAR_$_SVXSession._ledgerDeliveryQueue
+ _OBJC_CLASS_$_SCDAElectionLedger
+ _OBJC_CLASS_$_SISchemaUEIUUFRReady
+ ___118-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]_block_invoke
+ ___61-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]_block_invoke
+ ___61-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]_block_invoke_2
+ ___block_descriptor_49_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_56_e8_32s40s48bs_e32_v20?0B8"SCDAElectionOutcome"12l
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0l
+ _objc_msgSend$_electionLedger
+ _objc_msgSend$_waitForLedgerDecisionForElection:usingHandler:
+ _objc_msgSend$beginElectionWithIdentity:
+ _objc_msgSend$decisionForElection:reason:detail:deliverOn:completion:
+ _objc_msgSend$myriadElectionIdentity
+ _objc_msgSend$setAceCommandClass:
+ _objc_msgSend$sharedLedger
+ _objc_msgSend$startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:
+ _objc_msgSend$startAdvertisingFromAlertFiringVoiceTriggerWithContext:electionIdentity:
+ _objc_msgSend$startAdvertisingFromDirectTriggerWithContext:electionIdentity:
+ _objc_msgSend$startAdvertisingFromInTaskVoiceTriggerWithContext:electionIdentity:
+ _objc_msgSend$startAdvertisingFromVoiceTriggerWithGoodnessScoreContext:withContext:electionIdentity:
- -[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]
- -[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]
- GCC_except_table2529
- GCC_except_table2533
- GCC_except_table2538
- GCC_except_table2843
- GCC_except_table2999
- GCC_except_table3074
- ___101-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]_block_invoke
- _objc_msgSend$startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:
CStrings:
+ "%s #SVXInstrumentation - Emit UUFR ready event (aceCommandClass: %@)"
+ "%s #myriad queueAdvertisementType:%lu, context=%@, goodnessScoreContext=%@, electionIdentity=%@"
+ "%s Election ledger answered identity %@ with didWin=%d."
+ "%s Request election identity %@."
+ "%s Waiting on the election ledger for identity %@."
+ "%s _electionIdentity (%@ -> %@)"
+ "-[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]"
+ "-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:electionIdentity:completion:]_block_invoke"
+ "-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]"
+ "-[SVXSession _waitForLedgerDecisionForElection:usingHandler:]_block_invoke_2"
+ "-[SVXSession beginElectionWithIdentity:]"
+ "SVXInstrumentationEmitUUFRReady"
+ "activity %@"
+ "com.apple.siri.vox.session.electionledger"
+ "v20@?0B8@\"SCDAElectionOutcome\"12"
+ "\xf0\xe1\xf0\xf0!"
- "%s #myriad queueAdvertisementType:%lu, context=%@, goodnessScoreContext=%@"
- "-[SVXMyriadDeviceManager startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]"
- "-[SVXMyriadHostDevice startAdvertising:withSCDAGoodnessScoreContext:withSCDAAudioContext:completion:]_block_invoke"
- "\xf0\xe1\xf0\xe1"
```
