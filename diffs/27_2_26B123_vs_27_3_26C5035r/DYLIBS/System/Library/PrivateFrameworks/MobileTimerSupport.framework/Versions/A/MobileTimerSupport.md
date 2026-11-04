## MobileTimerSupport

> `/System/Library/PrivateFrameworks/MobileTimerSupport.framework/Versions/A/MobileTimerSupport`

```diff

-2333.2.6.0.0
-  __TEXT.__text: 0x73220
-  __TEXT.__objc_methlist: 0xf64
-  __TEXT.__const: 0x5e38
-  __TEXT.__cstring: 0x1f6b
-  __TEXT.__oslogstring: 0x663
-  __TEXT.__constg_swiftt: 0x1f94
-  __TEXT.__swift5_typeref: 0x2a48
-  __TEXT.__swift5_reflstr: 0x1502
-  __TEXT.__swift5_fieldmd: 0x1320
-  __TEXT.__swift5_builtin: 0x28
-  __TEXT.__swift5_types: 0x134
-  __TEXT.__swift5_assocty: 0x610
-  __TEXT.__swift5_proto: 0x354
-  __TEXT.__swift_as_entry: 0x228
-  __TEXT.__swift_as_ret: 0x184
-  __TEXT.__swift_as_cont: 0x364
-  __TEXT.__swift5_capture: 0x11c8
-  __TEXT.__swift5_protos: 0x28
-  __TEXT.__unwind_info: 0x2458
-  __TEXT.__eh_frame: 0x2b34
+2333.3.4.0.0
+  __TEXT.__text: 0x90bd0
+  __TEXT.__objc_methlist: 0x131c
+  __TEXT.__const: 0x7598
+  __TEXT.__cstring: 0x24cb
+  __TEXT.__oslogstring: 0xa03
+  __TEXT.__constg_swiftt: 0x2870
+  __TEXT.__swift5_typeref: 0x3050
+  __TEXT.__swift5_reflstr: 0x16f2
+  __TEXT.__swift5_fieldmd: 0x17dc
+  __TEXT.__swift5_builtin: 0x50
+  __TEXT.__swift5_types: 0x18c
+  __TEXT.__swift5_assocty: 0x708
+  __TEXT.__swift5_proto: 0x478
+  __TEXT.__swift_as_entry: 0x28c
+  __TEXT.__swift_as_ret: 0x1b0
+  __TEXT.__swift_as_cont: 0x488
+  __TEXT.__swift5_capture: 0x177c
+  __TEXT.__swift5_protos: 0x34
+  __TEXT.__unwind_info: 0x2fe8
+  __TEXT.__eh_frame: 0x4094
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1d0
-  __DATA_CONST.__objc_classlist: 0xf8
+  __DATA_CONST.__const: 0x308
+  __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x8
-  __DATA_CONST.__objc_protolist: 0xe0
+  __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x940
-  __DATA_CONST.__objc_protorefs: 0x70
-  __DATA_CONST.__objc_superrefs: 0x28
-  __DATA_CONST.__got: 0x668
-  __AUTH_CONST.__const: 0x4061
+  __DATA_CONST.__objc_selrefs: 0xaa0
+  __DATA_CONST.__objc_protorefs: 0x78
+  __DATA_CONST.__objc_superrefs: 0x30
+  __DATA_CONST.__got: 0x6d8
+  __AUTH_CONST.__const: 0x5021
   __AUTH_CONST.__cfstring: 0xe0
-  __AUTH_CONST.__objc_const: 0x3f60
-  __AUTH_CONST.__auth_got: 0xef0
-  __AUTH.__objc_data: 0x278
-  __AUTH.__data: 0x778
-  __DATA.__objc_ivar: 0x2c
-  __DATA.__data: 0x14d0
-  __DATA.__bss: 0x5df8
+  __AUTH_CONST.__objc_const: 0x4b68
+  __AUTH_CONST.__auth_got: 0x1028
+  __AUTH.__objc_data: 0x350
+  __AUTH.__data: 0xa10
+  __DATA.__objc_ivar: 0x34
+  __DATA.__data: 0x1620
+  __DATA.__bss: 0x6a98
   __DATA.__common: 0x80
-  __DATA_DIRTY.__objc_data: 0x9f0
-  __DATA_DIRTY.__data: 0x1598
-  __DATA_DIRTY.__bss: 0xc10
-  __DATA_DIRTY.__common: 0x88
+  __DATA_DIRTY.__objc_data: 0xfd0
+  __DATA_DIRTY.__data: 0x1de8
+  __DATA_DIRTY.__bss: 0x2310
+  __DATA_DIRTY.__common: 0xf0
+  - /System/Library/Frameworks/ActivityKit.framework/Versions/A/ActivityKit
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib
   - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreAudio.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftCoreMIDI.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
   - /usr/lib/swift/libswiftIntents.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2764
-  Symbols:   1704
-  CStrings:  275
+  Functions: 3647
+  Symbols:   1977
+  CStrings:  336
 
Symbols:
+ -[MTActivitiesManager .cxx_destruct]
+ -[MTActivitiesManager alarmActivities:]
+ -[MTActivitiesManager alarmAlertingActivities:]
+ -[MTActivitiesManager alarmCountdownActivities:]
+ -[MTActivitiesManager alarmProxy]
+ -[MTActivitiesManager alertActivityWithAlarm:playSound:completion:]
+ -[MTActivitiesManager alertActivityWithTimer:completion:]
+ -[MTActivitiesManager contextForAlarm:]
+ -[MTActivitiesManager contextForTimer:]
+ -[MTActivitiesManager createActivityWithAlarm:completion:]
+ -[MTActivitiesManager createActivityWithTimer:completion:]
+ -[MTActivitiesManager endActivityWithAlarmID:completion:]
+ -[MTActivitiesManager endActivityWithTimerID:completion:]
+ -[MTActivitiesManager init]
+ -[MTActivitiesManager localSetup]
+ -[MTActivitiesManager restoreActivityWithAlarm:completion:]
+ -[MTActivitiesManager restoreActivityWithTimer:completion:]
+ -[MTActivitiesManager sessionStateForTimer:]
+ -[MTActivitiesManager setAlarmProxy:]
+ -[MTActivitiesManager setTimerProxy:]
+ -[MTActivitiesManager timerActivities:]
+ -[MTActivitiesManager timerAlertingActivities:]
+ -[MTActivitiesManager timerCountdownActivities:]
+ -[MTActivitiesManager timerProxy]
+ -[MTActivitiesManager updateActivityWithAlarm:completion:]
+ -[MTActivitiesManager updateActivityWithTimer:completion:]
+ _OBJC_CLASS_$_MTActivitiesManager
+ _OBJC_CLASS_$_MTFeatures
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$__TtC18MobileTimerSupport12AlarmContext
+ _OBJC_CLASS_$__TtC18MobileTimerSupport12TimerContext
+ _OBJC_CLASS_$__TtC18MobileTimerSupport15MTActivityError
+ _OBJC_CLASS_$__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ _OBJC_CLASS_$__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ _OBJC_IVAR_$_MTActivitiesManager._alarmProxy
+ _OBJC_IVAR_$_MTActivitiesManager._timerProxy
+ _OBJC_METACLASS_$_MTActivitiesManager
+ _OBJC_METACLASS_$_NSError
+ _OBJC_METACLASS_$__TtC18MobileTimerSupport12AlarmContext
+ _OBJC_METACLASS_$__TtC18MobileTimerSupport12TimerContext
+ _OBJC_METACLASS_$__TtC18MobileTimerSupport15MTActivityError
+ _OBJC_METACLASS_$__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ _OBJC_METACLASS_$__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ __CLASS_METHODS__TtC18MobileTimerSupport15MTActivityError
+ __DATA__TtC18MobileTimerSupport12AlarmContext
+ __DATA__TtC18MobileTimerSupport12TimerContext
+ __DATA__TtC18MobileTimerSupport15MTActivityError
+ __DATA__TtC18MobileTimerSupport19MTActivitiesUpdater
+ __DATA__TtC18MobileTimerSupport21AlarmActivityProvider
+ __DATA__TtC18MobileTimerSupport21TimerActivityProvider
+ __DATA__TtC18MobileTimerSupport25StopwatchSessionsProvider
+ __DATA__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ __DATA__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ __DATA__TtC18MobileTimerSupport27StopwatchActivityAttributes
+ __INSTANCE_METHODS__TtC18MobileTimerSupport12AlarmContext
+ __INSTANCE_METHODS__TtC18MobileTimerSupport12TimerContext
+ __INSTANCE_METHODS__TtC18MobileTimerSupport15MTActivityError
+ __INSTANCE_METHODS__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ __INSTANCE_METHODS__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ __IVARS__TtC18MobileTimerSupport12AlarmContext
+ __IVARS__TtC18MobileTimerSupport12TimerContext
+ __IVARS__TtC18MobileTimerSupport15MTActivityError
+ __IVARS__TtC18MobileTimerSupport21AlarmActivityProvider
+ __IVARS__TtC18MobileTimerSupport21TimerActivityProvider
+ __IVARS__TtC18MobileTimerSupport25StopwatchSessionsProvider
+ __IVARS__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ __IVARS__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ __IVARS__TtC18MobileTimerSupport27StopwatchActivityAttributes
+ __METACLASS_DATA__TtC18MobileTimerSupport12AlarmContext
+ __METACLASS_DATA__TtC18MobileTimerSupport12TimerContext
+ __METACLASS_DATA__TtC18MobileTimerSupport15MTActivityError
+ __METACLASS_DATA__TtC18MobileTimerSupport19MTActivitiesUpdater
+ __METACLASS_DATA__TtC18MobileTimerSupport21AlarmActivityProvider
+ __METACLASS_DATA__TtC18MobileTimerSupport21TimerActivityProvider
+ __METACLASS_DATA__TtC18MobileTimerSupport25StopwatchSessionsProvider
+ __METACLASS_DATA__TtC18MobileTimerSupport26AlarmActivityProviderProxy
+ __METACLASS_DATA__TtC18MobileTimerSupport26TimerActivityProviderProxy
+ __METACLASS_DATA__TtC18MobileTimerSupport27StopwatchActivityAttributes
+ __OBJC_$_INSTANCE_METHODS_MTActivitiesManager
+ __OBJC_$_INSTANCE_METHODS__TtC18MobileTimerSupport25StopwatchSessionsProvider(MobileTimerSupport)
+ __OBJC_$_INSTANCE_VARIABLES_MTActivitiesManager
+ __OBJC_$_PROP_LIST_MTActivitiesManager
+ __OBJC_CLASS_PROTOCOLS_$__TtC18MobileTimerSupport25StopwatchSessionsProvider(MobileTimerSupport)
+ __OBJC_CLASS_RO_$_MTActivitiesManager
+ __OBJC_METACLASS_RO_$_MTActivitiesManager
+ __PROPERTIES__TtC18MobileTimerSupport12AlarmContext
+ __PROPERTIES__TtC18MobileTimerSupport12TimerContext
+ __PROTOCOLS__TtC18MobileTimerSupport12AlarmContext
+ __PROTOCOLS__TtC18MobileTimerSupport12TimerContext
+ __PROTOCOL_INSTANCE_METHODS__TtP18MobileTimerSupport15StyleRequesting_
+ __PROTOCOL_METHOD_TYPES__TtP18MobileTimerSupport15StyleRequesting_
+ __PROTOCOL_PROPERTIES__TtP18MobileTimerSupport15StyleRequesting_
+ __PROTOCOL__TtP18MobileTimerSupport15StyleRequesting_
+ ___swift_closure_destructor.25Tm
+ ___swift_closure_destructor.34Tm
+ ___swift_closure_destructor.419Tm
+ ___swift_closure_destructor.429Tm
+ ___swift_get_extra_inhabitant_indexTm
+ ___swift_store_extra_inhabitant_indexTm
+ ___unnamed_4
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_MobileTimerSupport
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_MobileTimerSupport
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA10AttributesAaDP_0D3Kit0dG0
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA10AttributesAaDP_AA8Priority
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA7ContextAaDP_AA18StringIdentifiable
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA7ContextAaDP_SE
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA7ContextAaDP_SH
+ _associated conformance 18MobileTimerSupport0B16ActivityProviderCAA0D9ProvidingAA7ContextAaDP_Se
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_SE
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_SH
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV0D3Kit0dE0AA12ContentStateAdEP_Se
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV0D3Kit0dE0AASE
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV0D3Kit0dE0AASe
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOSHAASQ
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport0B18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18MobileTimerSupport0B5StateOSHAASQ
+ _associated conformance 18MobileTimerSupport0B7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOSHAASQ
+ _associated conformance 18MobileTimerSupport0B7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport0B7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18MobileTimerSupport0B7ContextCs12IdentifiableAA2IDsADP_SH
+ _associated conformance 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOSHAASQ
+ _associated conformance 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18MobileTimerSupport12AlarmContextCs12IdentifiableAA2IDsADP_SH
+ _associated conformance 18MobileTimerSupport14RequestedStyleOSHAASQ
+ _associated conformance 18MobileTimerSupport14RequestedStyleOSLAASQ
+ _associated conformance 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOSHAASQ
+ _associated conformance 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18MobileTimerSupport16StopwatchContextVSHAASQ
+ _associated conformance 18MobileTimerSupport17DeleteAlarmIntentV10AppIntents0dF0AA6TargetAdEP_AD0G21EntityCollectionValue
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA10AttributesAaDP_0E3Kit0eH0
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA10AttributesAaDP_AA8Priority
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA7ContextAaDP_AA18StringIdentifiable
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA7ContextAaDP_SE
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA7ContextAaDP_SH
+ _associated conformance 18MobileTimerSupport21AlarmActivityProviderCAA0E9ProvidingAA7ContextAaDP_Se
+ _associated conformance 18MobileTimerSupport21StopwatchSessionErrorOSHAASQ
+ _associated conformance 18MobileTimerSupport22RemoveWorldClockIntentV10AppIntents06DeleteG0AA6TargetAdEP_AD0H21EntityCollectionValue
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV0E3Kit0eF0AA12ContentStateAdEP_SE
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV0E3Kit0eF0AA12ContentStateAdEP_SH
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV0E3Kit0eF0AA12ContentStateAdEP_Se
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV0E3Kit0eF0AASE
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV0E3Kit0eF0AASe
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOSHAASQ
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC0E3Kit0eF0AA12ContentStateAdEP_SE
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC0E3Kit0eF0AA12ContentStateAdEP_SH
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC0E3Kit0eF0AA12ContentStateAdEP_Se
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC0E3Kit0eF0AASE
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC0E3Kit0eF0AASe
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOSHAASQ
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _get_witness_table 11ActivityKit0A10AttributesRzl18MobileTimerSupport05AlarmaC0VAaBHPyHC
+ _get_witness_table 11ActivityKit0A10AttributesRzl18MobileTimerSupport0eaC0VAaBHPyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport0B7ContextCSEHPyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport0B7ContextCSHHpyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport0B7ContextCSeHPyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport12AlarmContextCSEHPyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport12AlarmContextCSHHpyHC
+ _get_witness_table SeRzSERzSHRzl18MobileTimerSupport12AlarmContextCSeHPyHC
+ _keypath_get.141Tm
+ _keypath_get.143Tm
+ _keypath_get.147Tm
+ _keypath_getTm
+ _keypath_set.144Tm
+ _keypath_setTm
+ _objc_msgSend$activitiesWithAlert:completion:
+ _objc_msgSend$activitiesWithCompletion:
+ _objc_msgSend$alarmProxy
+ _objc_msgSend$alertActivityWithContext:tlConfig:completion:
+ _objc_msgSend$contextForAlarm:
+ _objc_msgSend$contextForTimer:
+ _objc_msgSend$createActivityWithContext:completion:
+ _objc_msgSend$endActivityWithId:completion:
+ _objc_msgSend$initWithCoder:
+ _objc_msgSend$initWithDomain:code:userInfo:
+ _objc_msgSend$initWithState:timerId:duration:remainingTime:firing:fireDate:title:
+ _objc_msgSend$initWithTitle:alarmId:hour:min:isSnoozed:snoozeFireDate:isFiring:
+ _objc_msgSend$isFiring
+ _objc_msgSend$isSnoozed
+ _objc_msgSend$nextTrigger
+ _objc_msgSend$sessionStateForTimer:
+ _objc_msgSend$setAlarmProxy:
+ _objc_msgSend$setRequestedStyle:
+ _objc_msgSend$setTimerProxy:
+ _objc_msgSend$snoozeFireDate
+ _objc_msgSend$supportsLiveActivitiesQFA
+ _objc_msgSend$timerProxy
+ _objc_msgSend$title
+ _objc_msgSend$tlAlertConfigurationForCategory:
+ _objc_msgSend$triggerDate
+ _objc_msgSend$updateActivityWithContext:completion:
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_deallocPartialClassInstance
+ _swift_getErrorValue
+ _symbolic $s11ActivityKit0A10AttributesP
+ _symbolic $s18MobileTimerSupport15StyleRequestingP
+ _symbolic $s18MobileTimerSupport17ActivityProvidingP
+ _symbolic $s18MobileTimerSupport18StringIdentifiableP
+ _symbolic $s18MobileTimerSupport8PriorityP
+ _symbolic 10Attributes_____Qz 18MobileTimerSupport17ActivityProvidingP
+ _symbolic 7Context_____Qz 18MobileTimerSupport17ActivityProvidingP
+ _symbolic SDySS_____y_____GG 11ActivityKit0A0C 18MobileTimerSupport09StopwatchA10AttributesC
+ _symbolic SSSgSo7NSErrorCSgIeghgg_
+ _symbolic SS_ypt
+ _symbolic SaySSGSgIeghg_
+ _symbolic So20TLAlertConfigurationC
+ _symbolic So7NSArrayCSgIeyBhy_
+ _symbolic So7NSErrorC
+ _symbolic So7NSErrorCSgIeghg_
+ _symbolic So7NSErrorCSgIeyBhy_
+ _symbolic So8NSStringCSgSo7NSErrorCSgIeyBhyy_
+ _symbolic _____ 18MobileTimerSupport0B16ActivityProviderC
+ _symbolic _____ 18MobileTimerSupport0B18ActivityAttributesV
+ _symbolic _____ 18MobileTimerSupport0B18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____ 18MobileTimerSupport0B21ActivityProviderProxyC
+ _symbolic _____ 18MobileTimerSupport0B5StateO
+ _symbolic _____ 18MobileTimerSupport0B7ContextC
+ _symbolic _____ 18MobileTimerSupport0B7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____ 18MobileTimerSupport12AlarmContextC
+ _symbolic _____ 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____ 18MobileTimerSupport14RequestedStyleO
+ _symbolic _____ 18MobileTimerSupport15MTActivityErrorC
+ _symbolic _____ 18MobileTimerSupport16StopwatchContextV
+ _symbolic _____ 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____ 18MobileTimerSupport19MTActivitiesUpdaterC
+ _symbolic _____ 18MobileTimerSupport21AlarmActivityProviderC
+ _symbolic _____ 18MobileTimerSupport21StopwatchSessionErrorO
+ _symbolic _____ 18MobileTimerSupport23AlarmActivityAttributesV
+ _symbolic _____ 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____ 18MobileTimerSupport25StopwatchSessionsProviderC
+ _symbolic _____ 18MobileTimerSupport26AlarmActivityProviderProxyC
+ _symbolic _____ 18MobileTimerSupport27StopwatchActivityAttributesC
+ _symbolic _____ 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____Sg 11ActivityKit18AlertConfigurationV
+ _symbolic ___________t 11ActivityKit0A19PresentationOptionsV0aC11DestinationO AA11SceneTargetO7RequestO
+ _symbolic _____ySSSgG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____y_____GG s18_DictionaryStorageC 11ActivityKit0C0C 18MobileTimerSupport09StopwatchC10AttributesC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
+ _symbolic _____y_____G 11ActivityKit0A0C 18MobileTimerSupport05AlarmA10AttributesV
+ _symbolic _____y_____G 11ActivityKit0A0C 18MobileTimerSupport09StopwatchA10AttributesC
+ _symbolic _____y_____G 11ActivityKit0A0C 18MobileTimerSupport0dA10AttributesV
+ _symbolic _____y_____G 11ActivityKit0A7ContentV 18MobileTimerSupport0E7ContextC
+ _symbolic _____y_____G 11ActivityKit0A7ContentV 18MobileTimerSupport12AlarmContextC
+ _symbolic _____y_____G 11ActivityKit0A7ContentV 18MobileTimerSupport16StopwatchContextV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport0E18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport0E7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport0E18ActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport0E7ContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport12AlarmContextC10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport16StopwatchContextV10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport23AlarmActivityAttributesV10CodingKeys33_86B46DA7E23651236057BD5334CA6B68LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 18MobileTimerSupport27StopwatchActivityAttributesC10CodingKeys33_3C7AB23F72EF4EBE0D82D1E3F09C518FLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11ActivityKit0D13ContentSourceO7RequestO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11ActivityKit0D19PresentationOptionsV0dF11DestinationO
+ _symbolic _____y_____GSg 11ActivityKit0A7ContentV 18MobileTimerSupport0E7ContextC
+ _symbolic _____y_____GSg 11ActivityKit0A7ContentV 18MobileTimerSupport12AlarmContextC
+ _symbolic _____y_____GSg 11ActivityKit0A7ContentV 18MobileTimerSupport16StopwatchContextV
+ _symbolic _____y______G 11ActivityKit0A0C7RequestV 18MobileTimerSupport05AlarmA10AttributesV
+ _symbolic _____y______G 11ActivityKit0A0C7RequestV 18MobileTimerSupport0eA10AttributesV
+ _symbolic _____y__________G s18_DictionaryStorageC 11ActivityKit0C19PresentationOptionsV0cE11DestinationO AC11SceneTargetO7RequestO
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 11ActivityKit0D19PresentationOptionsV0dF11DestinationO AC11SceneTargetO7RequestO
+ _type_layout_string 18MobileTimerSupport16StopwatchContextV
- ___swift_closure_destructor.124Tm
- ___unnamed_3
CStrings:
+ " activity already exists for id: "
+ " activity for id: "
+ " for context id: "
+ " for snoozed alarm "
+ " for stopwatch id: "
+ " for stopwatch with id: "
+ " restored stopwatch sessions "
+ " update error could not find activity for "
+ "%@ clearig out old stopwatch session %s)"
+ "%@ got active stopwatches %s)"
+ "%@ got restored stopwatch sessions %s)"
+ "%{public}@ alarmActivities"
+ "%{public}@ alarmAlertingActivities"
+ "%{public}@ alarmCountdownActivities"
+ "%{public}@ alerting session for alarm: %{public}@, play sound: %i"
+ "%{public}@ alerting session for timer: %{public}@"
+ "%{public}@ created TLAlertConfiguration: %{public}@"
+ "%{public}@ created alarm context: %{public}@"
+ "%{public}@ created timer context: %{public}@ "
+ "%{public}@ creating new alarm session"
+ "%{public}@ creating new timer session"
+ "%{public}@ ending session for alarm: %{public}@"
+ "%{public}@ ending session for timer: %{public}@"
+ "%{public}@ restoring alarm session"
+ "%{public}@ restoring timer session"
+ "%{public}@ timerActivities"
+ "%{public}@ timerAlertingActivities"
+ "%{public}@ timerCountdownActivities"
+ "%{public}@ updating session for alarm: %{public}@"
+ "%{public}@ updating session for timer: %{public}@"
+ ", dismissedDate:"
+ ", remainingTime:"
+ ", requestedStyle: "
+ ", snoozeFireDate: "
+ "Created session with id: "
+ "Creating session for stopwatch id: "
+ "Duplicate values for key: '"
+ "Error creating session: "
+ "Error finishing session: "
+ "ErrorDescription"
+ "Fatal error"
+ "Finishing session with id: "
+ "Live activities flag disabled, skipping session for stopwatch: "
+ "MobileTimerSupport.AlarmContext"
+ "MobileTimerSupport.TimerContext"
+ "No stopwatch session to restore found"
+ "Session already exists for stopwatch id: "
+ "Swift/NativeDictionary.swift"
+ "[Alarm Context] alarmId:"
+ "[Timer Context] timerId:"
+ "com.apple.ClockAngel"
+ "com.apple.mobiletimerd"
+ "created AlertConfiguration: "
+ "ending all activities of type: "
+ "estimatedEndDate"
+ "finishing session for stopwatch id: "
+ "generated relative score of "
+ "generated relevance score of "
+ "generated relevance score of: "
+ "requestAlarmStyle for alarm "
+ "requestTimerStyle for timer "
```
