## AccessibilitySharedSupport

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Versions/A/AccessibilitySharedSupport`

```diff

-591.4.5.0.0
-  __TEXT.__text: 0x181088
-  __TEXT.__objc_methlist: 0x65f0
-  __TEXT.__const: 0x20678
+591.4.12.0.0
+  __TEXT.__text: 0x189bd0
+  __TEXT.__objc_methlist: 0x6738
+  __TEXT.__const: 0x20bf0
   __TEXT.__dlopen_cstrs: 0x392
-  __TEXT.__swift5_typeref: 0x6b90
-  __TEXT.__constg_swiftt: 0x6464
-  __TEXT.__swift5_reflstr: 0x304b
-  __TEXT.__swift5_fieldmd: 0x5a90
+  __TEXT.__swift5_typeref: 0x6d48
+  __TEXT.__constg_swiftt: 0x65d8
+  __TEXT.__swift5_reflstr: 0x30bb
+  __TEXT.__swift5_fieldmd: 0x5ba4
   __TEXT.__swift5_builtin: 0x280
   __TEXT.__swift5_assocty: 0x528
-  __TEXT.__swift5_proto: 0x1e58
-  __TEXT.__swift5_types: 0x9ec
-  __TEXT.__cstring: 0x911d
-  __TEXT.__swift5_protos: 0x88
-  __TEXT.__swift_as_entry: 0x21c
-  __TEXT.__swift_as_ret: 0x42c
-  __TEXT.__swift_as_cont: 0x710
-  __TEXT.__swift5_capture: 0xd24
-  __TEXT.__oslogstring: 0x5e2c
+  __TEXT.__swift5_proto: 0x1e80
+  __TEXT.__swift5_types: 0xa18
+  __TEXT.__cstring: 0x9295
+  __TEXT.__swift5_protos: 0x84
+  __TEXT.__swift_as_entry: 0x23c
+  __TEXT.__swift_as_ret: 0x44c
+  __TEXT.__swift_as_cont: 0x748
+  __TEXT.__swift5_capture: 0xe28
+  __TEXT.__oslogstring: 0x604d
   __TEXT.__swift5_mpenum: 0xc8
   __TEXT.__gcc_except_tab: 0x12f4
   __TEXT.__ustring: 0x182
-  __TEXT.__unwind_info: 0x90c8
-  __TEXT.__eh_frame: 0x84fc
+  __TEXT.__unwind_info: 0x9370
+  __TEXT.__eh_frame: 0x88dc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd90
-  __DATA_CONST.__objc_classlist: 0x398
+  __DATA_CONST.__const: 0xdb8
+  __DATA_CONST.__objc_classlist: 0x3b0
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x41e8
+  __DATA_CONST.__objc_selrefs: 0x4300
   __DATA_CONST.__objc_protorefs: 0x88
-  __DATA_CONST.__objc_superrefs: 0x1c0
-  __DATA_CONST.__objc_arraydata: 0x488
-  __DATA_CONST.__got: 0xe48
-  __AUTH_CONST.__const: 0x19348
-  __AUTH_CONST.__cfstring: 0x4f20
-  __AUTH_CONST.__objc_const: 0xb7a0
-  __AUTH_CONST.__objc_arrayobj: 0x1c8
-  __AUTH_CONST.__objc_intobj: 0xa20
+  __DATA_CONST.__objc_superrefs: 0x1c8
+  __DATA_CONST.__objc_arraydata: 0x450
+  __DATA_CONST.__got: 0xe60
+  __AUTH_CONST.__const: 0x199b8
+  __AUTH_CONST.__cfstring: 0x4fc0
+  __AUTH_CONST.__objc_const: 0xbaf8
+  __AUTH_CONST.__objc_arrayobj: 0x1b0
+  __AUTH_CONST.__objc_intobj: 0x978
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_floatobj: 0x1c0
-  __AUTH_CONST.__auth_got: 0x1cc8
-  __AUTH.__objc_data: 0x23b0
-  __AUTH.__data: 0x1e60
-  __DATA.__objc_ivar: 0x600
-  __DATA.__data: 0x7140
-  __DATA.__bss: 0x3d100
+  __AUTH_CONST.__auth_got: 0x1ce8
+  __AUTH.__objc_data: 0x2400
+  __AUTH.__data: 0x1fa0
+  __DATA.__objc_ivar: 0x61c
+  __DATA.__data: 0x7230
+  __DATA.__bss: 0x3d600
   __DATA.__common: 0x48
   __DATA_DIRTY.__objc_data: 0x118
-  __DATA_DIRTY.__data: 0x50
+  __DATA_DIRTY.__data: 0x40
   __DATA_DIRTY.__common: 0x18
   __DATA_DIRTY.__bss: 0x38
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12490
-  Symbols:   8915
-  CStrings:  1766
+  Functions: 12687
+  Symbols:   9042
+  CStrings:  1790
 
Symbols:
+ +[AXHingePoseMonitor isAvailable]
+ +[AXHingePoseMonitor sharedMonitor]
+ -[AXHingePoseMonitor .cxx_destruct]
+ -[AXHingePoseMonitor _deliverAngle:]
+ -[AXHingePoseMonitor _deliverMagicPose:toObservers:]
+ -[AXHingePoseMonitor _init]
+ -[AXHingePoseMonitor _isMonitoringForTesting]
+ -[AXHingePoseMonitor _isObserving:]
+ -[AXHingePoseMonitor _notifyObservers:usingBlock:]
+ -[AXHingePoseMonitor _observersSnapshot]
+ -[AXHingePoseMonitor _recalculateMagicPose]
+ -[AXHingePoseMonitor _resetInitialPose]
+ -[AXHingePoseMonitor _resolveInitialPose:posture:]
+ -[AXHingePoseMonitor _startSourceUpdates]
+ -[AXHingePoseMonitor _startUpdates]
+ -[AXHingePoseMonitor _stopSourceUpdates]
+ -[AXHingePoseMonitor _stopUpdatesIfUnobserved]
+ -[AXHingePoseMonitor _stopUpdates]
+ -[AXHingePoseMonitor _updateWithAngleDegrees:]
+ -[AXHingePoseMonitor _updateWithHingePosture:tabletopPose:tabletopPoseKnown:deviceOrientationPose:]
+ -[AXHingePoseMonitor addObserver:]
+ -[AXHingePoseMonitor angleDegrees]
+ -[AXHingePoseMonitor currentMagicPose]
+ -[AXHingePoseMonitor currentPosture]
+ -[AXHingePoseMonitor isAngleValid]
+ -[AXHingePoseMonitor removeObserver:]
+ GCC_except_table1192
+ GCC_except_table1195
+ GCC_except_table1202
+ GCC_except_table1226
+ GCC_except_table1243
+ GCC_except_table1253
+ GCC_except_table1263
+ GCC_except_table1266
+ GCC_except_table1268
+ GCC_except_table1343
+ GCC_except_table1623
+ GCC_except_table1665
+ GCC_except_table1669
+ GCC_except_table1753
+ GCC_except_table1785
+ GCC_except_table1940
+ GCC_except_table1942
+ GCC_except_table1944
+ GCC_except_table1947
+ GCC_except_table1949
+ GCC_except_table1951
+ GCC_except_table1956
+ GCC_except_table1959
+ GCC_except_table1961
+ GCC_except_table1963
+ GCC_except_table1965
+ GCC_except_table1967
+ GCC_except_table1969
+ GCC_except_table1971
+ GCC_except_table1973
+ GCC_except_table1975
+ GCC_except_table1977
+ GCC_except_table2080
+ GCC_except_table2084
+ GCC_except_table2091
+ GCC_except_table2104
+ GCC_except_table2112
+ _AXHingeFoldAxisForMagicPose
+ _OBJC_CLASS_$_AXHingePoseMonitor
+ _OBJC_CLASS_$_AXMVisionAnalysisOptions
+ _OBJC_CLASS_$_AXMVoiceOverVisionEngine
+ _OBJC_IVAR_$_AXHingePoseMonitor._currentMagicPose
+ _OBJC_IVAR_$_AXHingePoseMonitor._fusionInput
+ _OBJC_IVAR_$_AXHingePoseMonitor._hasResolvedPose
+ _OBJC_IVAR_$_AXHingePoseMonitor._isMonitoring
+ _OBJC_IVAR_$_AXHingePoseMonitor._observers
+ _OBJC_IVAR_$_AXHingePoseMonitor._observersAwaitingInitialPose
+ _OBJC_IVAR_$_AXHingePoseMonitor._observersLock
+ _OBJC_METACLASS_$_AXHingePoseMonitor
+ __AXHingeFuseMagicPose
+ __DATA__TtC26AccessibilitySharedSupport21AXNamedPeopleDetector
+ __DATA__TtCC26AccessibilitySharedSupport21AXNamedPeopleDetector12PendingNames
+ __IVARS__TtC26AccessibilitySharedSupport21AXNamedPeopleDetector
+ __IVARS__TtCC26AccessibilitySharedSupport21AXNamedPeopleDetector12PendingNames
+ __METACLASS_DATA__TtC26AccessibilitySharedSupport21AXNamedPeopleDetector
+ __METACLASS_DATA__TtCC26AccessibilitySharedSupport21AXNamedPeopleDetector12PendingNames
+ __OBJC_$_CLASS_METHODS_AXHingePoseMonitor
+ __OBJC_$_CLASS_PROP_LIST_AXHingePoseMonitor
+ __OBJC_$_INSTANCE_METHODS_AXHingePoseMonitor
+ __OBJC_$_INSTANCE_VARIABLES_AXHingePoseMonitor
+ __OBJC_$_PROP_LIST_AXHingePoseMonitor
+ __OBJC_CLASS_RO_$_AXHingePoseMonitor
+ __OBJC_METACLASS_RO_$_AXHingePoseMonitor
+ ___34-[AXHingePoseMonitor addObserver:]_block_invoke
+ ___35+[AXHingePoseMonitor sharedMonitor]_block_invoke
+ ___36-[AXHingePoseMonitor _deliverAngle:]_block_invoke
+ ___37-[AXHingePoseMonitor removeObserver:]_block_invoke
+ ___50-[AXHingePoseMonitor _notifyObservers:usingBlock:]_block_invoke
+ ___52-[AXHingePoseMonitor _deliverMagicPose:toObservers:]_block_invoke
+ ___block_descriptor_48_e8_32s_e31_v16?0"<AXHingePoseObserver>"8l
+ ___swift_closure_destructor.213Tm
+ ___swift_closure_destructor.395Tm
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO015AppSwitcherLeftF0VSHAASQ
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO015AppSwitcherLeftF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO015AppSwitcherLeftF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO016AppSwitcherRightF0VSHAASQ
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO016AppSwitcherRightF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO016AppSwitcherRightF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO14BackCodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO14BackCodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 26AccessibilitySharedSupport0A12SystemActionO4BackVSHAASQ
+ _objc_msgSend$_deliverAngle:
+ _objc_msgSend$_deliverMagicPose:toObservers:
+ _objc_msgSend$_init
+ _objc_msgSend$_isObserving:
+ _objc_msgSend$_notifyObservers:usingBlock:
+ _objc_msgSend$_observersSnapshot
+ _objc_msgSend$_recalculateMagicPose
+ _objc_msgSend$_resetInitialPose
+ _objc_msgSend$_resolveInitialPose:posture:
+ _objc_msgSend$_startSourceUpdates
+ _objc_msgSend$_startUpdates
+ _objc_msgSend$_stopSourceUpdates
+ _objc_msgSend$_stopUpdates
+ _objc_msgSend$_stopUpdatesIfUnobserved
+ _objc_msgSend$addObserver:
+ _objc_msgSend$descriptionByAppendingKnownPeopleSummaryTo:locale:
+ _objc_msgSend$hingePoseMonitor:didUpdateAngle:
+ _objc_msgSend$hingePoseMonitor:didUpdateMagicPose:
+ _objc_msgSend$imageNode
+ _objc_msgSend$initWithOptions:capacity:
+ _objc_msgSend$knownPeopleOptions
+ _objc_msgSend$setShouldProcessRemotely:
+ _objc_msgSend$systemPhotoLibraryURL
+ _objc_msgSend$triggerWithImage:photoLibraryURL:options:cacheKey:resultHandler:
+ _objc_msgSend$triggerWithPixelBuffer:exifOrientation:photoLibraryURL:options:cacheKey:resultHandler:
+ _objc_msgSend$weakObjectsHashTable
+ _sharedMonitor.monitor
+ _sharedMonitor.onceToken
+ _swift_task_isCancelled
+ _swift_task_isCancelledWithFlags
+ _symbolic SDySS_____G 26AccessibilitySharedSupport0A12ShortcutInfoV
+ _symbolic ScCySo15AXMVisionResultCSg_____G s5NeverO
+ _symbolic ScTySo15AXMVisionResultCSg_____G s5NeverO
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic ShySSG
+ _symbolic So15AXMVisionResultCSg
+ _symbolic So15AXMVisionResultCSgIeAgHr_
+ _symbolic So24AXMVisionAnalysisOptionsC
+ _symbolic So24AXMVoiceOverVisionEngineC
+ _symbolic So7CIImageC
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO015AppSwitcherLeftF0V
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO015AppSwitcherLeftF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO016AppSwitcherRightF0V
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO016AppSwitcherRightF10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO14BackCodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____ 26AccessibilitySharedSupport0A12SystemActionO4BackV
+ _symbolic _____ 26AccessibilitySharedSupport0A15ShortcutChangesV
+ _symbolic _____ 26AccessibilitySharedSupport0A15ShortcutTrackerV
+ _symbolic _____ 26AccessibilitySharedSupport21AXNamedPeopleDetectorC
+ _symbolic _____ 26AccessibilitySharedSupport21AXNamedPeopleDetectorC12PendingNamesC
+ _symbolic _____ So11CVBufferRefa
+ _symbolic _____Iegn_ 26AccessibilitySharedSupport0A15ShortcutChangesV
+ _symbolic _____XDXMT 26AccessibilitySharedSupport21AXNamedPeopleDetectorC
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 26AccessibilitySharedSupport0D12ShortcutInfoV
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 26AccessibilitySharedSupport0D12SystemActionO015AppSwitcherLeftI10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 26AccessibilitySharedSupport0D12SystemActionO016AppSwitcherRightI10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 26AccessibilitySharedSupport0D12SystemActionO14BackCodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 26AccessibilitySharedSupport0D12SystemActionO015AppSwitcherLeftI10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 26AccessibilitySharedSupport0D12SystemActionO016AppSwitcherRightI10CodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 26AccessibilitySharedSupport0D12SystemActionO14BackCodingKeys33_3BD9F8F3A30BDD71BA99D49F4E197118LLO
+ _symbolic _____ytIegnr_ 26AccessibilitySharedSupport0A15ShortcutChangesV
+ _symbolic _____yy_____ScMYccSg_____G s13ManagedBufferCsRi__rlE 26AccessibilitySharedSupport0C15ShortcutChangesV So16os_unfair_lock_sV
+ _type_layout_string 26AccessibilitySharedSupport0A15ShortcutChangesV
+ _type_layout_string 26AccessibilitySharedSupport0A15ShortcutTrackerV
- GCC_except_table1193
- GCC_except_table1196
- GCC_except_table1203
- GCC_except_table1232
- GCC_except_table1245
- GCC_except_table1255
- GCC_except_table1264
- GCC_except_table1267
- GCC_except_table1269
- GCC_except_table1344
- GCC_except_table1624
- GCC_except_table1666
- GCC_except_table1670
- GCC_except_table1754
- GCC_except_table1786
- GCC_except_table1906
- GCC_except_table1908
- GCC_except_table1910
- GCC_except_table1913
- GCC_except_table1915
- GCC_except_table1917
- GCC_except_table1922
- GCC_except_table1925
- GCC_except_table1927
- GCC_except_table1929
- GCC_except_table1931
- GCC_except_table1933
- GCC_except_table1935
- GCC_except_table1937
- GCC_except_table1939
- GCC_except_table1941
- GCC_except_table1943
- GCC_except_table2038
- GCC_except_table2047
- GCC_except_table2051
- GCC_except_table2058
- GCC_except_table2079
- _AXSSArrangementGestures.arrangementGestures
- _AXSSArrangementGestures.onceToken
- ___AXSSArrangementGestures_block_invoke
- ___swift_closure_destructor.212Tm
- ___swift_closure_destructor.394Tm
- _symbolic $s26AccessibilitySharedSupport03PopA14ResolvedActionP
- _symbolic Say_____GIegg_ 26AccessibilitySharedSupport0A12ShortcutInfoV
- _symbolic Say_____GytIegnr_ 26AccessibilitySharedSupport0A12ShortcutInfoV
- _symbolic _____yySay_____GScMYccSg_____G s13ManagedBufferCsRi__rlE 26AccessibilitySharedSupport0C12ShortcutInfoV So16os_unfair_lock_sV
CStrings:
+ " recognizedTextIdle="
+ "ARRANGEMENT_APP_SWITCHER_LEFT"
+ "ARRANGEMENT_APP_SWITCHER_RIGHT"
+ "Automatic endpoint did fire. Ending transcription. %{public}s"
+ "Hinge pose changed: %{public}@ -> %{public}@ (angle %.1f, posture %ld)"
+ "Hinge pose monitoring stopped"
+ "Hinge pose observer added: %{public}@ (%lu observers)"
+ "Hinge pose observer removed (%lu observers)"
+ "Hinge pose resolved: %{public}@ (angle %.1f, posture %ld)"
+ "Named-people: detection timed out after %fs; describing without names."
+ "Named-people: detection trigger error: %@"
+ "Named-people: engine has no image node."
+ "Named-people: no photo library URL; skipping."
+ "ambiguous"
+ "appSwitcherLeftApp"
+ "appSwitcherRightApp"
+ "book.upsidedown"
+ "chevron.backward"
+ "laptop"
+ "laptop.upsidedown"
+ "rectangle.lefthalf.inset.filled.arrow.left"
+ "rectangle.righthalf.inset.filled.arrow.right"
+ "tent"
+ "v16@?0@\"<AXHingePoseObserver>\"8"
```
