## WorkflowKit

> `/System/iOSSupport/System/Library/PrivateFrameworks/WorkflowKit.framework/Versions/A/WorkflowKit`

```diff

-5203.0.1.0.0
-  __TEXT.__text: 0x65e728
-  __TEXT.__objc_methlist: 0x2a1b4
-  __TEXT.__const: 0x23fb0
+5206.0.5.0.0
+  __TEXT.__text: 0x66bec4
+  __TEXT.__objc_methlist: 0x2a43c
+  __TEXT.__const: 0x23fd0
   __TEXT.__dlopen_cstrs: 0xc2b
-  __TEXT.__swift5_typeref: 0xc8fe
-  __TEXT.__cstring: 0x56b7b
-  __TEXT.__oslogstring: 0x22360
-  __TEXT.__constg_swiftt: 0x9968
-  __TEXT.__swift5_reflstr: 0x6318
-  __TEXT.__swift5_fieldmd: 0x7a5c
+  __TEXT.__swift5_typeref: 0xc8f8
+  __TEXT.__cstring: 0x56b63
+  __TEXT.__oslogstring: 0x225a0
+  __TEXT.__constg_swiftt: 0x988c
+  __TEXT.__swift5_reflstr: 0x6248
+  __TEXT.__swift5_fieldmd: 0x7918
   __TEXT.__swift5_builtin: 0x5a0
   __TEXT.__swift5_assocty: 0x21d0
-  __TEXT.__swift5_proto: 0x1a98
-  __TEXT.__swift5_types: 0xb48
-  __TEXT.__swift5_capture: 0x6034
-  __TEXT.__swift_as_entry: 0xaac
-  __TEXT.__swift_as_ret: 0xbd0
-  __TEXT.__swift_as_cont: 0x135c
+  __TEXT.__swift5_proto: 0x1a94
+  __TEXT.__swift5_types: 0xb3c
+  __TEXT.__swift5_capture: 0x6120
+  __TEXT.__swift_as_entry: 0xafc
+  __TEXT.__swift_as_ret: 0xc10
+  __TEXT.__swift_as_cont: 0x13d4
   __TEXT.__swift5_protos: 0x14c
   __TEXT.__swift5_mpenum: 0xa0
-  __TEXT.__gcc_except_tab: 0x488c
-  __TEXT.__ustring: 0x3c34
-  __TEXT.__unwind_info: 0x1e9b8
-  __TEXT.__eh_frame: 0x1fdec
+  __TEXT.__gcc_except_tab: 0x4708
+  __TEXT.__ustring: 0x3bfe
+  __TEXT.__unwind_info: 0x1ecb8
+  __TEXT.__eh_frame: 0x204dc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe458
-  __DATA_CONST.__objc_classlist: 0x2278
+  __DATA_CONST.__const: 0xe420
+  __DATA_CONST.__objc_classlist: 0x2290
   __DATA_CONST.__objc_catlist: 0x3d8
   __DATA_CONST.__objc_protolist: 0x630
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x121d0
-  __DATA_CONST.__objc_protorefs: 0x250
-  __DATA_CONST.__objc_superrefs: 0x1268
-  __DATA_CONST.__objc_arraydata: 0x1420
-  __DATA_CONST.__got: 0x5300
-  __AUTH_CONST.__const: 0x2a0c0
-  __AUTH_CONST.__cfstring: 0x27780
-  __AUTH_CONST.__objc_const: 0x51320
+  __DATA_CONST.__objc_selrefs: 0x122b0
+  __DATA_CONST.__objc_protorefs: 0x258
+  __DATA_CONST.__objc_superrefs: 0x1280
+  __DATA_CONST.__objc_arraydata: 0x1418
+  __DATA_CONST.__got: 0x52d8
+  __AUTH_CONST.__const: 0x2a428
+  __AUTH_CONST.__cfstring: 0x276a0
+  __AUTH_CONST.__objc_const: 0x515d8
   __AUTH_CONST.__objc_dictobj: 0x4b0
   __AUTH_CONST.__objc_intobj: 0xfa8
-  __AUTH_CONST.__objc_arrayobj: 0x810
+  __AUTH_CONST.__objc_arrayobj: 0x7f8
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0x4a88
-  __AUTH.__objc_data: 0xe2f8
-  __AUTH.__data: 0x6530
-  __DATA.__objc_ivar: 0x1fb4
-  __DATA.__data: 0xbfa0
-  __DATA.__bss: 0x2dfd8
-  __DATA.__common: 0x2cc8
-  __DATA_DIRTY.__objc_data: 0xa6f0
+  __AUTH_CONST.__auth_got: 0x4bb0
+  __AUTH.__objc_data: 0xe5d0
+  __AUTH.__data: 0x62c8
+  __DATA.__objc_ivar: 0x1ff4
+  __DATA.__data: 0xc010
+  __DATA.__bss: 0x2ded8
+  __DATA.__common: 0x2cd0
+  __DATA_DIRTY.__objc_data: 0xa6e8
   __DATA_DIRTY.__data: 0x1f20
   __DATA_DIRTY.__bss: 0x2548
   __DATA_DIRTY.__common: 0x20

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 40674
-  Symbols:   40674
-  CStrings:  11964
+  Functions: 40935
+  Symbols:   40768
+  CStrings:  11963
 
Symbols:
+ +[NSUserDefaults(Workflow) safetyGuardrailDisabled]
+ +[WFCloudKitItemProperty objectPropertyWithName:encrypted:uploadOnlyAtEncryptedSchemaVersion:]
+ +[WFMultiTaskingArrangementTrigger supportsSecureCoding]
+ +[WFPCCLimitMessaging fetchAlertForReason:completionHandler:]
+ +[WFPCCLimitMessaging fetchMessageForReason:completionHandler:]
+ +[WFPCCLimitMessaging startObserving]
+ -[WFAction cancelWithError:]
+ -[WFAction pendingCancellationError]
+ -[WFAction setPendingCancellationError:]
+ -[WFAppPickerParameter preservesUnresolvedApps]
+ -[WFBackgroundShortcutRunner beginToolStepOrReplyIfNotRunning]
+ -[WFBackgroundShortcutRunner cancelTimedOutToolStepIfStartedAction:]
+ -[WFBackgroundShortcutRunner currentToolStep]
+ -[WFBackgroundShortcutRunner endToolStepForAction:]
+ -[WFBackgroundShortcutRunner failToolStep:withError:]
+ -[WFBackgroundShortcutRunner handleTimeoutOfToolStep:]
+ -[WFBackgroundShortcutRunner performOnToolStepQueue:]
+ -[WFBackgroundShortcutRunner replyToHostWithToolStepError:]
+ -[WFBackgroundShortcutRunner setCurrentToolStep:]
+ -[WFBackgroundShortcutRunner stepWithAction:forToolStep:]
+ -[WFBackgroundShortcutRunnerStateMachine beginStepTimeoutWithDuration:handler:]
+ -[WFBackgroundShortcutRunnerStateMachine endStepTimeout]
+ -[WFBackgroundShortcutRunnerStateMachine stepTimer]
+ -[WFCloudKitItemProperty initWithType:name:itemClass:ignoredByDefault:nilValue:hasConstantValue:constantValue:fileType:encrypted:uploadOnlyAtEncryptedSchemaVersion:]
+ -[WFCloudKitItemProperty isGatedByEncryptedSchemaVersion]
+ -[WFCloudKitItemProperty uploadOnlyAtEncryptedSchemaVersion]
+ -[WFCloudKitSyncEventLogger logDesiredSyncSummary:recordType:name:recordIDsToSave:recordIDsToDelete:reasonsNotNeeded:]
+ -[WFCloudKitSyncEventLogger nameForDesiredSyncOperation:]
+ -[WFEnumerationParameter hiddenPossibleStates]
+ -[WFFPItemResolver finishWithItem:error:]
+ -[WFLinkAction cancelWithError:]
+ -[WFLinkAction currentExecutorCancellationError]
+ -[WFLinkAction currentExecutorCancelled]
+ -[WFLinkAction setCurrentExecutorCancellationError:]
+ -[WFLinkAction setCurrentExecutorCancelled:]
+ -[WFMultiTaskingArrangementTrigger encodeWithCoder:]
+ -[WFMultiTaskingArrangementTrigger initWithCoder:]
+ -[WFMultiTaskingArrangementTrigger init]
+ -[WFMultiTaskingArrangementTrigger mode]
+ -[WFMultiTaskingArrangementTrigger setMode:]
+ -[WFPCCLimitMessage .cxx_destruct]
+ -[WFPCCLimitMessage actions]
+ -[WFPCCLimitMessage body]
+ -[WFPCCLimitMessage initWithTitle:body:actions:]
+ -[WFPCCLimitMessage title]
+ -[WFPCCLimitMessageAction .cxx_destruct]
+ -[WFPCCLimitMessageAction initWithTitle:primary:cancel:performBlock:]
+ -[WFPCCLimitMessageAction isCancel]
+ -[WFPCCLimitMessageAction isPrimary]
+ -[WFPCCLimitMessageAction performBlock]
+ -[WFPCCLimitMessageAction perform]
+ -[WFPCCLimitMessageAction title]
+ -[WFRunnerToolStep .cxx_destruct]
+ -[WFRunnerToolStep action]
+ -[WFRunnerToolStep attachAction:]
+ -[WFRunnerToolStep didTimeOut]
+ -[WFRunnerToolStep end]
+ -[WFRunnerToolStep isEnded]
+ -[WFRunnerToolStep recordTimeout]
+ -[WFRunnerToolStep shouldCancelStartedAction:]
+ GCC_except_table10106
+ GCC_except_table10122
+ GCC_except_table10156
+ GCC_except_table10361
+ GCC_except_table10388
+ GCC_except_table10401
+ GCC_except_table10456
+ GCC_except_table10599
+ GCC_except_table10680
+ GCC_except_table10708
+ GCC_except_table10712
+ GCC_except_table10717
+ GCC_except_table10724
+ GCC_except_table10729
+ GCC_except_table10732
+ GCC_except_table10735
+ GCC_except_table10738
+ GCC_except_table10741
+ GCC_except_table10744
+ GCC_except_table10747
+ GCC_except_table10750
+ GCC_except_table10753
+ GCC_except_table10756
+ GCC_except_table10759
+ GCC_except_table10864
+ GCC_except_table11004
+ GCC_except_table11020
+ GCC_except_table11166
+ GCC_except_table11181
+ GCC_except_table11187
+ GCC_except_table11189
+ GCC_except_table11194
+ GCC_except_table11225
+ GCC_except_table11238
+ GCC_except_table11245
+ GCC_except_table11299
+ GCC_except_table11336
+ GCC_except_table11350
+ GCC_except_table11354
+ GCC_except_table11356
+ GCC_except_table11455
+ GCC_except_table11471
+ GCC_except_table11569
+ GCC_except_table11622
+ GCC_except_table11674
+ GCC_except_table11703
+ GCC_except_table11758
+ GCC_except_table11769
+ GCC_except_table1177
+ GCC_except_table11819
+ GCC_except_table11821
+ GCC_except_table11836
+ GCC_except_table12052
+ GCC_except_table12148
+ GCC_except_table12183
+ GCC_except_table12224
+ GCC_except_table12265
+ GCC_except_table12278
+ GCC_except_table12283
+ GCC_except_table12298
+ GCC_except_table12305
+ GCC_except_table12306
+ GCC_except_table12307
+ GCC_except_table12316
+ GCC_except_table12327
+ GCC_except_table12480
+ GCC_except_table12503
+ GCC_except_table12506
+ GCC_except_table12508
+ GCC_except_table1256
+ GCC_except_table12565
+ GCC_except_table12577
+ GCC_except_table12581
+ GCC_except_table12784
+ GCC_except_table12852
+ GCC_except_table13050
+ GCC_except_table13091
+ GCC_except_table13220
+ GCC_except_table13317
+ GCC_except_table13322
+ GCC_except_table13331
+ GCC_except_table13334
+ GCC_except_table13382
+ GCC_except_table13405
+ GCC_except_table13416
+ GCC_except_table13418
+ GCC_except_table1342
+ GCC_except_table13431
+ GCC_except_table1347
+ GCC_except_table13620
+ GCC_except_table13640
+ GCC_except_table13651
+ GCC_except_table13665
+ GCC_except_table13668
+ GCC_except_table13816
+ GCC_except_table13843
+ GCC_except_table13939
+ GCC_except_table1529
+ GCC_except_table1536
+ GCC_except_table1538
+ GCC_except_table1540
+ GCC_except_table1542
+ GCC_except_table1544
+ GCC_except_table1547
+ GCC_except_table1549
+ GCC_except_table1551
+ GCC_except_table1634
+ GCC_except_table1648
+ GCC_except_table1653
+ GCC_except_table1655
+ GCC_except_table1657
+ GCC_except_table1918
+ GCC_except_table1994
+ GCC_except_table2085
+ GCC_except_table2106
+ GCC_except_table2110
+ GCC_except_table2320
+ GCC_except_table2414
+ GCC_except_table2533
+ GCC_except_table2561
+ GCC_except_table2635
+ GCC_except_table2676
+ GCC_except_table2783
+ GCC_except_table2786
+ GCC_except_table2800
+ GCC_except_table2865
+ GCC_except_table2892
+ GCC_except_table2909
+ GCC_except_table2915
+ GCC_except_table3108
+ GCC_except_table3148
+ GCC_except_table3153
+ GCC_except_table3185
+ GCC_except_table3201
+ GCC_except_table3205
+ GCC_except_table3265
+ GCC_except_table3276
+ GCC_except_table3278
+ GCC_except_table3281
+ GCC_except_table3391
+ GCC_except_table3395
+ GCC_except_table3397
+ GCC_except_table3401
+ GCC_except_table3402
+ GCC_except_table3540
+ GCC_except_table3663
+ GCC_except_table3667
+ GCC_except_table375
+ GCC_except_table378
+ GCC_except_table4043
+ GCC_except_table4044
+ GCC_except_table4155
+ GCC_except_table4228
+ GCC_except_table4241
+ GCC_except_table4260
+ GCC_except_table4268
+ GCC_except_table4417
+ GCC_except_table4555
+ GCC_except_table4561
+ GCC_except_table4567
+ GCC_except_table4617
+ GCC_except_table4631
+ GCC_except_table4689
+ GCC_except_table4760
+ GCC_except_table4787
+ GCC_except_table4791
+ GCC_except_table4894
+ GCC_except_table4902
+ GCC_except_table4924
+ GCC_except_table4964
+ GCC_except_table5018
+ GCC_except_table5026
+ GCC_except_table5028
+ GCC_except_table5066
+ GCC_except_table5075
+ GCC_except_table5076
+ GCC_except_table5143
+ GCC_except_table5467
+ GCC_except_table556
+ GCC_except_table5606
+ GCC_except_table5639
+ GCC_except_table5713
+ GCC_except_table5725
+ GCC_except_table5838
+ GCC_except_table5922
+ GCC_except_table6086
+ GCC_except_table6136
+ GCC_except_table6157
+ GCC_except_table6508
+ GCC_except_table6521
+ GCC_except_table6541
+ GCC_except_table6542
+ GCC_except_table660
+ GCC_except_table6610
+ GCC_except_table6611
+ GCC_except_table6614
+ GCC_except_table6620
+ GCC_except_table6625
+ GCC_except_table6630
+ GCC_except_table6631
+ GCC_except_table6678
+ GCC_except_table6683
+ GCC_except_table6741
+ GCC_except_table6757
+ GCC_except_table693
+ GCC_except_table696
+ GCC_except_table698
+ GCC_except_table700
+ GCC_except_table7009
+ GCC_except_table7019
+ GCC_except_table704
+ GCC_except_table7093
+ GCC_except_table7098
+ GCC_except_table7378
+ GCC_except_table7379
+ GCC_except_table7419
+ GCC_except_table7522
+ GCC_except_table7666
+ GCC_except_table7671
+ GCC_except_table7682
+ GCC_except_table7795
+ GCC_except_table7802
+ GCC_except_table7813
+ GCC_except_table7870
+ GCC_except_table7881
+ GCC_except_table7883
+ GCC_except_table7885
+ GCC_except_table7886
+ GCC_except_table8378
+ GCC_except_table8415
+ GCC_except_table8481
+ GCC_except_table8547
+ GCC_except_table864
+ GCC_except_table8747
+ GCC_except_table8753
+ GCC_except_table8757
+ GCC_except_table8759
+ GCC_except_table8761
+ GCC_except_table8763
+ GCC_except_table8767
+ GCC_except_table8769
+ GCC_except_table8781
+ GCC_except_table8785
+ GCC_except_table8798
+ GCC_except_table8811
+ GCC_except_table8817
+ GCC_except_table8824
+ GCC_except_table8871
+ GCC_except_table8877
+ GCC_except_table8883
+ GCC_except_table9015
+ GCC_except_table9107
+ GCC_except_table9109
+ GCC_except_table9115
+ GCC_except_table9118
+ GCC_except_table9120
+ GCC_except_table9122
+ GCC_except_table9129
+ GCC_except_table9132
+ GCC_except_table9154
+ GCC_except_table9155
+ GCC_except_table9156
+ GCC_except_table9158
+ GCC_except_table9163
+ GCC_except_table9271
+ GCC_except_table938
+ GCC_except_table9440
+ GCC_except_table9446
+ GCC_except_table9465
+ GCC_except_table947
+ GCC_except_table9629
+ GCC_except_table9664
+ GCC_except_table9730
+ GCC_except_table9737
+ GCC_except_table9741
+ GCC_except_table9789
+ GCC_except_table9794
+ GCC_except_table9834
+ GCC_except_table9837
+ GCC_except_table9840
+ GCC_except_table9843
+ _CCSetErrorDomain
+ _INAppResolverOptionsRequireStrictMatchingKey
+ _LNMetadataChangedNotification
+ _NSStoreModelVersionHashesKey
+ _OBJC_CLASS_$_NSBatchDeleteResult
+ _OBJC_CLASS_$_NSExpressionDescription
+ _OBJC_CLASS_$_WFAppIntentsRemoteDeviceCoordinator
+ _OBJC_CLASS_$_WFDispatchSourceTimer
+ _OBJC_CLASS_$_WFMultiTaskingArrangementTrigger
+ _OBJC_CLASS_$_WFPCCLimitMessage
+ _OBJC_CLASS_$_WFPCCLimitMessageAction
+ _OBJC_CLASS_$_WFPCCLimitMessaging
+ _OBJC_CLASS_$_WFRemoteDevicePrewarmBridge
+ _OBJC_CLASS_$_WFRunnerToolStep
+ _OBJC_CLASS_$__TtC11WorkflowKit26WFMTACapableDeviceResource
+ _OBJC_IVAR_$_WFAction._pendingCancellationError
+ _OBJC_IVAR_$_WFAppPickerParameter._preservesUnresolvedApps
+ _OBJC_IVAR_$_WFBackgroundShortcutRunner._currentToolStep
+ _OBJC_IVAR_$_WFBackgroundShortcutRunnerStateMachine._stepTimer
+ _OBJC_IVAR_$_WFBackgroundShortcutRunnerStateMachine._stepTimerLock
+ _OBJC_IVAR_$_WFCloudKitItemProperty._uploadOnlyAtEncryptedSchemaVersionNumber
+ _OBJC_IVAR_$_WFLinkAction._currentExecutorCancellationError
+ _OBJC_IVAR_$_WFLinkAction._currentExecutorCancelled
+ _OBJC_IVAR_$_WFMultiTaskingArrangementTrigger._mode
+ _OBJC_IVAR_$_WFPCCLimitMessage._actions
+ _OBJC_IVAR_$_WFPCCLimitMessage._body
+ _OBJC_IVAR_$_WFPCCLimitMessage._title
+ _OBJC_IVAR_$_WFPCCLimitMessageAction._cancel
+ _OBJC_IVAR_$_WFPCCLimitMessageAction._performBlock
+ _OBJC_IVAR_$_WFPCCLimitMessageAction._primary
+ _OBJC_IVAR_$_WFPCCLimitMessageAction._title
+ _OBJC_IVAR_$_WFRunnerToolStep._action
+ _OBJC_IVAR_$_WFRunnerToolStep._didTimeOut
+ _OBJC_IVAR_$_WFRunnerToolStep._isEnded
+ _OBJC_METACLASS_$_WFAppIntentsRemoteDeviceCoordinator
+ _OBJC_METACLASS_$_WFMultiTaskingArrangementTrigger
+ _OBJC_METACLASS_$_WFPCCLimitMessage
+ _OBJC_METACLASS_$_WFPCCLimitMessageAction
+ _OBJC_METACLASS_$_WFPCCLimitMessaging
+ _OBJC_METACLASS_$_WFRemoteDevicePrewarmBridge
+ _OBJC_METACLASS_$_WFRunnerToolStep
+ _OBJC_METACLASS_$__TtC11WorkflowKit26WFMTACapableDeviceResource
+ _WFDebugViewExpectedEncryptedSchemaVersion
+ _WFParameterPreservesUnresolvedAppsKey
+ _WFRunnerTimedOutError
+ _WFShortcutsDisableSafetyGuardrailKey
+ __CLASS_METHODS_WFRemoteDevicePrewarmBridge
+ __CLASS_METHODS__TtC11WorkflowKit26WFMTACapableDeviceResource
+ __CLASS_PROPERTIES_WFRemoteDevicePrewarmBridge
+ __DATA_WFAppIntentsRemoteDeviceCoordinator
+ __DATA_WFRemoteDevicePrewarmBridge
+ __DATA__TtC11WorkflowKit26WFMTACapableDeviceResource
+ __DATA__TtC11WorkflowKit28AppIntentsRemoteValueQuerier
+ __INSTANCE_METHODS_WFAppIntentsRemoteDeviceCoordinator
+ __INSTANCE_METHODS_WFRemoteDevicePrewarmBridge
+ __INSTANCE_METHODS__TtC11WorkflowKit26WFMTACapableDeviceResource
+ __IVARS_WFAppIntentsRemoteDeviceCoordinator
+ __METACLASS_DATA_WFAppIntentsRemoteDeviceCoordinator
+ __METACLASS_DATA_WFRemoteDevicePrewarmBridge
+ __METACLASS_DATA__TtC11WorkflowKit26WFMTACapableDeviceResource
+ __METACLASS_DATA__TtC11WorkflowKit28AppIntentsRemoteValueQuerier
+ __OBJC_$_CLASS_METHODS_WFMultiTaskingArrangementTrigger
+ __OBJC_$_CLASS_METHODS_WFPCCLimitMessaging
+ __OBJC_$_INSTANCE_METHODS_WFMultiTaskingArrangementTrigger
+ __OBJC_$_INSTANCE_METHODS_WFPCCLimitMessage
+ __OBJC_$_INSTANCE_METHODS_WFPCCLimitMessageAction
+ __OBJC_$_INSTANCE_METHODS_WFRunnerToolStep
+ __OBJC_$_INSTANCE_VARIABLES_WFMultiTaskingArrangementTrigger
+ __OBJC_$_INSTANCE_VARIABLES_WFPCCLimitMessage
+ __OBJC_$_INSTANCE_VARIABLES_WFPCCLimitMessageAction
+ __OBJC_$_INSTANCE_VARIABLES_WFRunnerToolStep
+ __OBJC_$_PROP_LIST_WFMultiTaskingArrangementTrigger
+ __OBJC_$_PROP_LIST_WFPCCLimitMessage
+ __OBJC_$_PROP_LIST_WFPCCLimitMessageAction
+ __OBJC_$_PROP_LIST_WFRunnerToolStep
+ __OBJC_CLASS_RO_$_WFMultiTaskingArrangementTrigger
+ __OBJC_CLASS_RO_$_WFPCCLimitMessage
+ __OBJC_CLASS_RO_$_WFPCCLimitMessageAction
+ __OBJC_CLASS_RO_$_WFPCCLimitMessaging
+ __OBJC_CLASS_RO_$_WFRunnerToolStep
+ __OBJC_METACLASS_RO_$_WFMultiTaskingArrangementTrigger
+ __OBJC_METACLASS_RO_$_WFPCCLimitMessage
+ __OBJC_METACLASS_RO_$_WFPCCLimitMessageAction
+ __OBJC_METACLASS_RO_$_WFPCCLimitMessaging
+ __OBJC_METACLASS_RO_$_WFRunnerToolStep
+ __OBJC_PROTOCOL_REFERENCE_$_WFCloudKitWalrusMigrationSupporting
+ __PROPERTIES__TtC11WorkflowKit29WFScreenshotLocationParameter
+ ___51-[WFBackgroundShortcutRunner endToolStepForAction:]_block_invoke
+ ___53-[WFBackgroundShortcutRunner failToolStep:withError:]_block_invoke
+ ___57-[WFBackgroundShortcutRunner stepWithAction:forToolStep:]_block_invoke
+ ___57-[WFEnumerationParameter localizedLabelForMultipleState:]_block_invoke
+ ___57-[WFEnumerationParameter localizedLabelForMultipleState:]_block_invoke_2
+ ___59-[WFBackgroundShortcutRunner replyToHostWithToolStepError:]_block_invoke
+ ___62-[WFBackgroundShortcutRunner beginToolStepOrReplyIfNotRunning]_block_invoke
+ ___62-[WFBackgroundShortcutRunner beginToolStepOrReplyIfNotRunning]_block_invoke_2
+ ___79+[WFAction(Serialization) actionsFromSerializedRepresentations:actionRegistry:]_block_invoke_2
+ ___WFSystemShortcutEntryRowCount_block_invoke
+ ___block_descriptor_40_e8_32s_e48_v16?0"<WFOutOfProcessWorkflowControllerHost>"8ls32l8
+ ___block_descriptor_40_e8_32s_e49_B16?0"<WFEnumerationSupportingParameterState>"8ls32l8
+ ___block_descriptor_41_e8_32s_e23_B32?0"FPItem"8Q16^B24ls32l8
+ ___swift_closure_destructor.5Tm
+ _associated conformance 11WorkflowKit21RemoteValueQueryErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 11WorkflowKit21RemoteValueQueryErrorO10Foundation13CustomNSErrorAAs0F0
+ _associated conformance 11WorkflowKit21RemoteValueQueryErrorOSHAASQ
+ _associated conformance 11WorkflowKit33AppIntentsRemoteDeviceCoordinatorC04ToolB00efG0AaD0E8Hydrator
+ _associated conformance 11WorkflowKit33AppIntentsRemoteDeviceCoordinatorC17TransportDecisionVSHAASQ
+ _generic environment l
+ _get_enum_tag_for_layout_string 11WorkflowKit12PersonaErrorO
+ _objc_msgSend$attachAction:
+ _objc_msgSend$beginStepTimeoutWithDuration:handler:
+ _objc_msgSend$cancelTimedOutToolStepIfStartedAction:
+ _objc_msgSend$cancelWithError:
+ _objc_msgSend$currentExecutorCancellationError
+ _objc_msgSend$currentExecutorCancelled
+ _objc_msgSend$currentToolStep
+ _objc_msgSend$end
+ _objc_msgSend$endStepTimeout
+ _objc_msgSend$endToolStepForAction:
+ _objc_msgSend$entitiesByName
+ _objc_msgSend$expressionForFunction:arguments:
+ _objc_msgSend$expressionForKeyPath:
+ _objc_msgSend$failToolStep:withError:
+ _objc_msgSend$fetchAlertForReason:completionHandler:
+ _objc_msgSend$fetchMessageForReason:completionHandler:
+ _objc_msgSend$finishWithItem:error:
+ _objc_msgSend$handleTimeoutOfToolStep:
+ _objc_msgSend$hiddenPossibleStates
+ _objc_msgSend$initWithEntityName:
+ _objc_msgSend$initWithInterval:queue:handler:
+ _objc_msgSend$initWithName:icon:cloudKitMetadata:
+ _objc_msgSend$initWithType:name:itemClass:ignoredByDefault:nilValue:hasConstantValue:constantValue:fileType:encrypted:uploadOnlyAtEncryptedSchemaVersion:
+ _objc_msgSend$insertFolderWithName:icon:identifier:
+ _objc_msgSend$insertFolderWithName:icon:identifier:insertAt:
+ _objc_msgSend$isFoldableDevice
+ _objc_msgSend$isGatedByEncryptedSchemaVersion
+ _objc_msgSend$isNoSuchActionError:
+ _objc_msgSend$managedObjectModel
+ _objc_msgSend$nameForDesiredSyncOperation:
+ _objc_msgSend$objectPropertyWithName:encrypted:uploadOnlyAtEncryptedSchemaVersion:
+ _objc_msgSend$pause
+ _objc_msgSend$pendingCancellationError
+ _objc_msgSend$performBlock
+ _objc_msgSend$performOnToolStepQueue:
+ _objc_msgSend$preservesUnresolvedApps
+ _objc_msgSend$recordTimeout
+ _objc_msgSend$regionallyGatedActionIdentifiers
+ _objc_msgSend$replyToHostWithToolStepError:
+ _objc_msgSend$resolvedAppMatchingDescriptor:options:
+ _objc_msgSend$setCurrentExecutorCancellationError:
+ _objc_msgSend$setCurrentExecutorCancelled:
+ _objc_msgSend$setCurrentToolStep:
+ _objc_msgSend$setExpression:
+ _objc_msgSend$setExpressionResultType:
+ _objc_msgSend$setPendingCancellationError:
+ _objc_msgSend$setPropertiesToGroupBy:
+ _objc_msgSend$setResultType:
+ _objc_msgSend$shouldCancelStartedAction:
+ _objc_msgSend$stepTimer
+ _objc_msgSend$stepWithAction:
+ _objc_msgSend$totalEntryCount
+ _objc_msgSend$uploadOnlyAtEncryptedSchemaVersion
+ _symbolic $s11WorkflowKit18RemoteValueQuerierP
+ _symbolic $s11WorkflowKit28WFTriggerRegistrationStoringP
+ _symbolic SDySS_____G 7ToolKit16DeviceDescriptorV
+ _symbolic SDy_____SgSiG s5Int64V
+ _symbolic SDy_____SgSiG______pIgrzo_ s5Int64V s5ErrorP
+ _symbolic SSSbIeggy_
+ _symbolic SccySo17WFPCCLimitMessageCSg_____G s5NeverO
+ _symbolic Si6offset_x7elementt
+ _symbolic So19WFContactFieldEntryC
+ _symbolic _____ 11WorkflowKit19WFGLPResultOrderingO
+ _symbolic _____ 11WorkflowKit21RemoteValueQueryErrorO
+ _symbolic _____ 11WorkflowKit23RemoteValueQueryRequestV
+ _symbolic _____ 11WorkflowKit25RemoteDevicePrewarmBridgeC
+ _symbolic _____ 11WorkflowKit26WFMTACapableDeviceResourceC
+ _symbolic _____ 11WorkflowKit28AppIntentsRemoteValueQuerierC
+ _symbolic _____ 11WorkflowKit31PrimitiveTypesChangesetProducerV
+ _symbolic _____ 11WorkflowKit33AppIntentsRemoteDeviceCoordinatorC
+ _symbolic _____ 11WorkflowKit33AppIntentsRemoteDeviceCoordinatorC17TransportDecisionV
+ _symbolic _____ 11WorkflowKit39WFAppleIntelligenceActionsRegionalCheckV
+ _symbolic _____ 7ToolKit10TypedValueO09PrimitiveD0O03AppD0V
+ _symbolic _____ 7ToolKit16DeviceDescriptorV17InternetRelayModeO
+ _symbolic _____Sg 16GenerativeModels0aB12AvailabilityV6PolicyV
+ _symbolic _____Sg 18AppIntentsServices18SnippetEnvironmentV
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____Sg 7ToolKit16DeviceDescriptorV
+ _symbolic _____Sg 7ToolKit18RestrictionContextO
+ _symbolic _____Sg s5Int64V
+ _symbolic _____Sg_ABt 7ToolKit0A17InvocationOptionsV12UserIdentityV
+ _symbolic ______p 18AppIntentsServices23IntentParameterMetadataP
+ _symbolic ______pXmT So16WFParameterStateP
+ _symbolic _____ySDySS_____GG 15Synchronization5MutexVAARi_zrlE 7ToolKit16DeviceDescriptorV
+ _symbolic _____ySJG s10ArraySliceV
+ _symbolic _____ySJG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_____G s17_NativeDictionaryV 7ToolKit16DeviceDescriptorV
+ _symbolic _____ySiG s11_SetStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So19WFScreenshotTriggerC11WorkflowKitE8LocationO
+ _symbolic _____y_____SgSiG s17_NativeDictionaryV s5Int64V
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE s15ContinuousClockV7InstantV So16os_unfair_lock_sV
+ _symbolic _____y_____ySJGG s23_ContiguousArrayStorageC s0B5SliceV
+ _symbolic ypXp
+ _type_layout_string 11WorkflowKit12PersonaErrorO
+ _type_layout_string 11WorkflowKit23RemoteValueQueryRequestV
- +[WFAnalytics trackAutoShortcutButtonWithBundleIdentifier:]
- +[WFCloudKitFolder encryptedNameProperty]
- +[WFCloudKitFolder latestEncryptedSchemaVersion]
- +[WFCloudKitFolder nameProperty]
- +[WFCloudKitSyncSession isWalrusEnabled]
- +[WFCloudKitSyncSession isWalrusForcedEnabled]
- +[WFCloudKitSyncSession resolveWalrusStatus]
- +[WFCloudKitSyncSession setWalrusEnabled:]
- +[WFCloudKitSyncSession setWalrusForcedEnabled:]
- +[WFCloudKitWorkflow encryptedNameProperty]
- +[WFCloudKitWorkflow latestEncryptedSchemaVersion]
- +[WFCloudKitWorkflow nameProperty]
- -[WFCloudKitItemProperty initWithType:name:itemClass:ignoredByDefault:nilValue:hasConstantValue:constantValue:fileType:encrypted:]
- -[WFDatabase setWalrusStateForTesting:withError:]
- -[WFDatabase(Sync) updateWalrusStatus]
- -[WFLinkAction currentExecutorCancelledByUser]
- -[WFLinkAction setCurrentExecutorCancelledByUser:]
- -[WFWorkflowRecord lastSyncedEncryptedSchemaVersion]
- -[WFWorkflowRecord setLastSyncedEncryptedSchemaVersion:]
- -[WFWorkflowRecord setWantedEncryptedSchemaVersion:]
- -[WFWorkflowRecord wantedEncryptedSchemaVersion]
- GCC_except_table10060
- GCC_except_table10076
- GCC_except_table10110
- GCC_except_table10315
- GCC_except_table10342
- GCC_except_table10355
- GCC_except_table10410
- GCC_except_table10553
- GCC_except_table10634
- GCC_except_table10640
- GCC_except_table10643
- GCC_except_table10646
- GCC_except_table10649
- GCC_except_table10652
- GCC_except_table10655
- GCC_except_table10658
- GCC_except_table10662
- GCC_except_table10666
- GCC_except_table10671
- GCC_except_table10678
- GCC_except_table10683
- GCC_except_table10707
- GCC_except_table10710
- GCC_except_table10713
- GCC_except_table10818
- GCC_except_table10958
- GCC_except_table10974
- GCC_except_table11120
- GCC_except_table11135
- GCC_except_table11141
- GCC_except_table11143
- GCC_except_table11148
- GCC_except_table11179
- GCC_except_table11192
- GCC_except_table11199
- GCC_except_table11253
- GCC_except_table11290
- GCC_except_table11304
- GCC_except_table11308
- GCC_except_table11310
- GCC_except_table11409
- GCC_except_table11425
- GCC_except_table11523
- GCC_except_table11576
- GCC_except_table11628
- GCC_except_table11657
- GCC_except_table11712
- GCC_except_table11723
- GCC_except_table11773
- GCC_except_table11775
- GCC_except_table1178
- GCC_except_table11790
- GCC_except_table12006
- GCC_except_table12102
- GCC_except_table12137
- GCC_except_table12178
- GCC_except_table12219
- GCC_except_table12232
- GCC_except_table12237
- GCC_except_table12252
- GCC_except_table12259
- GCC_except_table12260
- GCC_except_table12261
- GCC_except_table12270
- GCC_except_table12281
- GCC_except_table12434
- GCC_except_table12457
- GCC_except_table12460
- GCC_except_table12462
- GCC_except_table12519
- GCC_except_table12531
- GCC_except_table12535
- GCC_except_table1257
- GCC_except_table12738
- GCC_except_table12806
- GCC_except_table13003
- GCC_except_table13044
- GCC_except_table13173
- GCC_except_table13270
- GCC_except_table13275
- GCC_except_table13284
- GCC_except_table13287
- GCC_except_table13335
- GCC_except_table13358
- GCC_except_table13369
- GCC_except_table13371
- GCC_except_table13384
- GCC_except_table1343
- GCC_except_table1348
- GCC_except_table13573
- GCC_except_table13593
- GCC_except_table13604
- GCC_except_table13618
- GCC_except_table13621
- GCC_except_table13769
- GCC_except_table13796
- GCC_except_table13892
- GCC_except_table1530
- GCC_except_table1537
- GCC_except_table1539
- GCC_except_table1541
- GCC_except_table1543
- GCC_except_table1545
- GCC_except_table1548
- GCC_except_table1550
- GCC_except_table1552
- GCC_except_table1633
- GCC_except_table1647
- GCC_except_table1652
- GCC_except_table1654
- GCC_except_table1656
- GCC_except_table1907
- GCC_except_table1983
- GCC_except_table2072
- GCC_except_table2082
- GCC_except_table2290
- GCC_except_table2384
- GCC_except_table2502
- GCC_except_table2530
- GCC_except_table2604
- GCC_except_table2645
- GCC_except_table2752
- GCC_except_table2755
- GCC_except_table2769
- GCC_except_table2834
- GCC_except_table2861
- GCC_except_table2878
- GCC_except_table2884
- GCC_except_table3077
- GCC_except_table3117
- GCC_except_table3122
- GCC_except_table3154
- GCC_except_table3170
- GCC_except_table3174
- GCC_except_table3234
- GCC_except_table3245
- GCC_except_table3247
- GCC_except_table3250
- GCC_except_table3360
- GCC_except_table3364
- GCC_except_table3366
- GCC_except_table3370
- GCC_except_table3371
- GCC_except_table3509
- GCC_except_table3632
- GCC_except_table3636
- GCC_except_table374
- GCC_except_table377
- GCC_except_table4012
- GCC_except_table4013
- GCC_except_table4127
- GCC_except_table4200
- GCC_except_table4213
- GCC_except_table4232
- GCC_except_table4240
- GCC_except_table4389
- GCC_except_table4527
- GCC_except_table4533
- GCC_except_table4539
- GCC_except_table4589
- GCC_except_table4603
- GCC_except_table4661
- GCC_except_table4732
- GCC_except_table4759
- GCC_except_table4763
- GCC_except_table4866
- GCC_except_table4874
- GCC_except_table4896
- GCC_except_table4936
- GCC_except_table4990
- GCC_except_table4998
- GCC_except_table5000
- GCC_except_table5038
- GCC_except_table5047
- GCC_except_table5048
- GCC_except_table5115
- GCC_except_table5439
- GCC_except_table5578
- GCC_except_table560
- GCC_except_table5611
- GCC_except_table5685
- GCC_except_table5697
- GCC_except_table5810
- GCC_except_table5892
- GCC_except_table5957
- GCC_except_table5958
- GCC_except_table5959
- GCC_except_table6060
- GCC_except_table6110
- GCC_except_table6131
- GCC_except_table6482
- GCC_except_table6495
- GCC_except_table6515
- GCC_except_table6516
- GCC_except_table6578
- GCC_except_table6579
- GCC_except_table6584
- GCC_except_table6585
- GCC_except_table6588
- GCC_except_table6594
- GCC_except_table6599
- GCC_except_table664
- GCC_except_table6651
- GCC_except_table6656
- GCC_except_table6714
- GCC_except_table6730
- GCC_except_table694
- GCC_except_table697
- GCC_except_table6982
- GCC_except_table699
- GCC_except_table6992
- GCC_except_table701
- GCC_except_table705
- GCC_except_table7066
- GCC_except_table7071
- GCC_except_table7351
- GCC_except_table7352
- GCC_except_table7392
- GCC_except_table7495
- GCC_except_table7639
- GCC_except_table7644
- GCC_except_table7655
- GCC_except_table7768
- GCC_except_table7775
- GCC_except_table7786
- GCC_except_table7843
- GCC_except_table7854
- GCC_except_table7856
- GCC_except_table7858
- GCC_except_table7859
- GCC_except_table8351
- GCC_except_table8388
- GCC_except_table8454
- GCC_except_table8505
- GCC_except_table865
- GCC_except_table8707
- GCC_except_table8713
- GCC_except_table8717
- GCC_except_table8719
- GCC_except_table8721
- GCC_except_table8723
- GCC_except_table8727
- GCC_except_table8729
- GCC_except_table8741
- GCC_except_table8745
- GCC_except_table8758
- GCC_except_table8771
- GCC_except_table8777
- GCC_except_table8784
- GCC_except_table8830
- GCC_except_table8836
- GCC_except_table8842
- GCC_except_table8971
- GCC_except_table9030
- GCC_except_table9063
- GCC_except_table9065
- GCC_except_table9071
- GCC_except_table9076
- GCC_except_table9078
- GCC_except_table9085
- GCC_except_table9088
- GCC_except_table9110
- GCC_except_table9111
- GCC_except_table9112
- GCC_except_table9114
- GCC_except_table9119
- GCC_except_table9227
- GCC_except_table939
- GCC_except_table9396
- GCC_except_table9402
- GCC_except_table9421
- GCC_except_table948
- GCC_except_table9585
- GCC_except_table9620
- GCC_except_table9686
- GCC_except_table9693
- GCC_except_table9695
- GCC_except_table9697
- GCC_except_table9744
- GCC_except_table9784
- GCC_except_table9787
- GCC_except_table9790
- GCC_except_table9793
- _LNInterfaceIdiomAirPods
- _LNInterfaceIdiomCarPlay
- _LNInterfaceIdiomEyesFree
- _LNInterfaceIdiomHomePod
- _LNInterfaceIdiomMac
- _LNInterfaceIdiomPad
- _LNInterfaceIdiomPhone
- _LNInterfaceIdiomTV
- _LNInterfaceIdiomVision
- _LNInterfaceIdiomWatch
- _OBJC_CLASS_$_CHSControlDescriptor
- _OBJC_CLASS_$_CHSControlDescriptorsPredicate
- _OBJC_CLASS_$_CHSControlIdentity
- _OBJC_CLASS_$_CHSExtensionIdentity
- _OBJC_CLASS_$_CHSWidgetExtension
- _OBJC_CLASS_$_CHSWidgetExtensionProvider
- _OBJC_CLASS_$_CHSWidgetExtensionProviderOptions
- _OBJC_IVAR_$_WFLinkAction._currentExecutorCancelledByUser
- _OBJC_IVAR_$_WFWorkflowRecord._lastSyncedEncryptedSchemaVersion
- _OBJC_IVAR_$_WFWorkflowRecord._wantedEncryptedSchemaVersion
- _OBJC_METACLASS_$__TtCC11WorkflowKit26WFDebouncerSettleSchedulerP33_5E2E360943EE47A2CBA9B8BBC9628A8D6Target
- _OUTLINED_FUNCTION_455
- _OUTLINED_FUNCTION_456
- _OUTLINED_FUNCTION_457
- _OUTLINED_FUNCTION_458
- _OUTLINED_FUNCTION_459
- _WFLastViewedAutoShortcutsAtTimeKey
- _WFShortcutSourceNotifyMeWhen
- _WFWalrusEnabledKey
- _WFWalrusForcedEnabledKey
- _WFWalrusGroundTruthEnabledKey
- __DATA__TtC11WorkflowKit20WFAppInFocusObserver
- __DATA__TtC11WorkflowKit24AppIntentsRemoteHydrator
- __DATA__TtC11WorkflowKit24WFLayoutObservationToken
- __DATA__TtC11WorkflowKit26WFDebouncerSettleScheduler
- __DATA__TtC11WorkflowKit31WFUnknownScreenPresenceProvider
- __DATA__TtCC11WorkflowKit26WFDebouncerSettleSchedulerP33_5E2E360943EE47A2CBA9B8BBC9628A8D6Target
- __INSTANCE_METHODS__TtCC11WorkflowKit26WFDebouncerSettleSchedulerP33_5E2E360943EE47A2CBA9B8BBC9628A8D6Target
- __IVARS__TtC11WorkflowKit20WFAppInFocusObserver
- __IVARS__TtC11WorkflowKit24WFLayoutObservationToken
- __IVARS__TtC11WorkflowKit26WFDebouncerSettleScheduler
- __IVARS__TtCC11WorkflowKit26WFDebouncerSettleSchedulerP33_5E2E360943EE47A2CBA9B8BBC9628A8D6Target
- __METACLASS_DATA__TtC11WorkflowKit20WFAppInFocusObserver
- __METACLASS_DATA__TtC11WorkflowKit24AppIntentsRemoteHydrator
- __METACLASS_DATA__TtC11WorkflowKit24WFLayoutObservationToken
- __METACLASS_DATA__TtC11WorkflowKit26WFDebouncerSettleScheduler
- __METACLASS_DATA__TtC11WorkflowKit31WFUnknownScreenPresenceProvider
- __METACLASS_DATA__TtCC11WorkflowKit26WFDebouncerSettleSchedulerP33_5E2E360943EE47A2CBA9B8BBC9628A8D6Target
- __OBJC_$_CLASS_PROP_LIST_WFCloudKitWalrusMigrationSupporting
- __OBJC_$_PROTOCOL_CLASS_METHODS_WFCloudKitWalrusMigrationSupporting
- ___38-[WFDatabase(Sync) updateWalrusStatus]_block_invoke
- ___38-[WFDatabase(Sync) updateWalrusStatus]_block_invoke_2
- ___47-[WFFPItemResolver determineNextItemIfPossible]_block_invoke_2
- ___49-[WFDatabase setWalrusStateForTesting:withError:]_block_invoke
- ___52-[WFLinkAction performPresentationActionWithResult:]_block_invoke_2
- ___53+[WFCloudKitItemRequest createRecordFromItem:zoneID:]_block_invoke_2
- ___59+[WFAnalytics trackAutoShortcutButtonWithBundleIdentifier:]_block_invoke
- ___block_descriptor_48_e5_v8?0l
- ___block_descriptor_48_e8_32s40s_e23_v32?0"FPItem"8Q16^B24ls32l8s40l8
- ___block_descriptor_48_e8_32s_e9_v16?0^8ls32l8
- ___block_descriptor_72_e8_32s40s48r56r_e9_v16?0^8ls32l8s40l8r48l8r56l8
- ___swift_memcpy19_8
- __os_activity_create
- __os_activity_current
- _associated conformance 11WorkflowKit11WFSettleKeyV8DecisionOSHAASQ
- _associated conformance 11WorkflowKit11WFSettleKeyVSHAASQ
- _associated conformance 11WorkflowKit12PersonaErrorOSHAASQ
- _associated conformance 11WorkflowKit19WFAppScreenPresenceOSHAASQ
- _associated conformance 11WorkflowKit37WFRemoteAppIntentExecutionActionErrorO10Foundation13CustomNSErrorAAs0H0
- _getWFWalrusLogObject
- _get_enum_tag_for_layout_string Ieg_Sg
- _objc_msgSend$actionMetadata
- _objc_msgSend$currentExecutorCancelledByUser
- _objc_msgSend$defaultIntentReference
- _objc_msgSend$encryptedNameProperty
- _objc_msgSend$entitlements
- _objc_msgSend$extensionIdentity
- _objc_msgSend$extensionPointRecord
- _objc_msgSend$extensions
- _objc_msgSend$initWithExtensionIdentity:kind:intentReference:
- _objc_msgSend$initWithName:icon:encryptedSchemaVersion:cloudKitMetadata:
- _objc_msgSend$initWithType:name:itemClass:ignoredByDefault:nilValue:hasConstantValue:constantValue:fileType:encrypted:
- _objc_msgSend$initWithWidgetsPredicate:controlsPredicate:
- _objc_msgSend$insertFolderWithName:icon:identifier:error:
- _objc_msgSend$insertFolderWithName:icon:identifier:insertAt:error:
- _objc_msgSend$isWalrusEnabled
- _objc_msgSend$isWalrusForcedEnabled
- _objc_msgSend$latestEncryptedSchemaVersion
- _objc_msgSend$nameProperty
- _objc_msgSend$objectPropertyWithName:constantValue:
- _objc_msgSend$objectPropertyWithName:constantValue:encrypted:
- _objc_msgSend$orderedControlDescriptors
- _objc_msgSend$rawIntentType
- _objc_msgSend$resolveWalrusStatus
- _objc_msgSend$setCurrentExecutorCancelledByUser:
- _objc_msgSend$setFetchBatchSize:
- _objc_msgSend$setWantedEncryptedSchemaVersion:
- _objc_msgSend$updateWalrusStatus
- _objc_msgSend$wantedEncryptedSchemaVersion
- _os_activity_scope_enter
- _os_activity_scope_leave
- _symbolic $s11WorkflowKit18WFSettleSchedulingP
- _symbolic $s11WorkflowKit28WFAppScreenPresenceProvidingP
- _symbolic Ieg_
- _symbolic SDy__________G 11WorkflowKit11WFSettleKeyV AA26WFDebouncerSettleSchedulerC5Entry33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic SaySo20CHSControlDescriptorCG
- _symbolic So10OS_voucherCSg
- _symbolic So11WFDebouncerC
- _symbolic _____ 11WorkflowKit11WFSettleKeyV
- _symbolic _____ 11WorkflowKit11WFSettleKeyV8DecisionO
- _symbolic _____ 11WorkflowKit19WFAppScreenPresenceO
- _symbolic _____ 11WorkflowKit20WFAppInFocusObserverC
- _symbolic _____ 11WorkflowKit20WFAppInFocusObserverC5State33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic _____ 11WorkflowKit23WFUseModelRegionalCheckV
- _symbolic _____ 11WorkflowKit24AppIntentsRemoteHydratorC
- _symbolic _____ 11WorkflowKit24WFLayoutObservationTokenC
- _symbolic _____ 11WorkflowKit26WFDebouncerSettleSchedulerC
- _symbolic _____ 11WorkflowKit26WFDebouncerSettleSchedulerC5Entry33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic _____ 11WorkflowKit26WFDebouncerSettleSchedulerC6Target33_5E2E360943EE47A2CBA9B8BBC9628A8DLLC
- _symbolic _____ 11WorkflowKit31WFUnknownScreenPresenceProviderC
- _symbolic _____ 11WorkflowKit37WFRemoteAppIntentExecutionActionErrorO
- _symbolic _____10invocation_t 7ToolKit0A10InvocationV
- _symbolic _____Sg 11WorkflowKit24WFLayoutObservationTokenC
- _symbolic _____SgXw 11WorkflowKit20WFAppInFocusObserverC
- _symbolic _____SgXw 11WorkflowKit26WFDebouncerSettleSchedulerC
- _symbolic _____SgXwz_Xx 11WorkflowKit20WFAppInFocusObserverC
- _symbolic _____SgXwz_Xx 11WorkflowKit26WFDebouncerSettleSchedulerC
- _symbolic ______p 11WorkflowKit18WFSettleSchedulingP
- _symbolic ______p 11WorkflowKit28WFAppScreenPresenceProvidingP
- _symbolic _____ySDy__________GG 15Synchronization5MutexVAARi_zrlE 11WorkflowKit11WFSettleKeyV AD26WFDebouncerSettleSchedulerC5Entry33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic _____ySS3key______5valuetG s23_ContiguousArrayStorageC 7ToolKit18ConcreteResolvableO
- _symbolic _____ySS_____G s17_NativeDictionaryV 11WorkflowKit19WFAppScreenPresenceO
- _symbolic _____ySo18CHSWidgetExtensionCG s11_SetStorageC
- _symbolic _____y_____G 14ChronoServices15TypedIdentifierV AA0D4TypeO6BundleO9ContainerO
- _symbolic _____y_____G 14ChronoServices15TypedIdentifierV AA0D4TypeO6BundleO9ExtensionO
- _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 11WorkflowKit20WFAppInFocusObserverC5State33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic _____y_____GSg 14ChronoServices15TypedIdentifierV AA0D4TypeO6BundleO9ContainerO
- _symbolic _____y__________G s17_NativeDictionaryV 11WorkflowKit11WFSettleKeyV AC26WFDebouncerSettleSchedulerC5Entry33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _symbolic _____y_____y__Qo_G s14PrefixSequenceV 10Foundation8CalendarV14RecurrenceRuleV11recurrences2of2inQrAC4DateV_SnyALGSgtFQO
- _symbolic _____y_____y__Qo__G s14PrefixSequenceV8IteratorV 10Foundation8CalendarV14RecurrenceRuleV11recurrences2of2inQrAE4DateV_SnyANGSgtFQO
- _symbolic ySSc
- _symbolic ytIgr_
- _symbolic yycSg
- _type_layout_string 11WorkflowKit11WFSettleKeyV
- _type_layout_string 11WorkflowKit20WFAppInFocusObserverC5State33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
- _type_layout_string 11WorkflowKit26WFDebouncerSettleSchedulerC5Entry33_5E2E360943EE47A2CBA9B8BBC9628A8DLLV
CStrings:
+ " by synced schema version"
+ "%s %{public}@ has a schema-version-gated property but doesn't provide a schema version, assuming encrypted."
+ "%s A ToolKit step arrived with no run in progress"
+ "%s Bundled model lacks SystemShortcutEntry, opening the store will drop its rows"
+ "%s Cancelling executor with error for action: %@"
+ "%s Could not find item for path component: %@"
+ "%s Destroying the Shortcuts database store, requested by %{public}@"
+ "%s Executor finished after cancellation, treating as cancelled: %{public}@"
+ "%s Falling back to an empty in-memory database in %{public}@, stored data will be invisible until the process relaunches"
+ "%s No tool for show-output action %{public}@ from %{public}@, skipping it"
+ "%s Not running action %{public}@ because its step already ended"
+ "%s Opened store in %{public}@, migrated automatically: %{public}d, SystemShortcutEntry rows: %{public}@"
+ "%s Opening store in %{public}@: store model version '%{public}@', bundled model version '%{public}@', store matches bundled model: %{public}d, store has SystemShortcutEntry: %{public}d, bundled model has SystemShortcutEntry: %{public}d"
+ "%s Second connection attempted to an existing runner"
+ "%s Step for action %{public}@ timed out"
+ "%s Step timed out before its action was created"
+ "%{public}s location trigger %{public}@: now %{public}s %{public}s, range %{public}s-%{public}s"
+ "(This automation isn’t supported on this device.)"
+ "+[WFCloudKitItemRequest createRecordFromItem:zoneID:]_block_invoke"
+ "-[WFBackgroundShortcutRunner beginToolStepOrReplyIfNotRunning]"
+ "-[WFBackgroundShortcutRunner cancelTimedOutToolStepIfStartedAction:]"
+ "-[WFBackgroundShortcutRunner handleTimeoutOfToolStep:]"
+ "-[WFBackgroundShortcutRunner stepWithAction:forToolStep:]_block_invoke"
+ "-[WFLinkAction cancelWithError:]"
+ "-[WFLinkAction performPresentationActionWithResult:]_block_invoke"
+ "Added System Shortcut Entry %{public}s"
+ "B16@?0@\"<WFEnumerationSupportingParameterState>\"8"
+ "B32@?0@\"FPItem\"8Q16^B24"
+ "Can't count by synced schema version: no entity name"
+ "Deleted %{public}ld System Shortcut Entries for app %s"
+ "Deleted %{public}ld of %{public}ld requested System Shortcut Entries"
+ "Deleting %{public}ld System Shortcut Entries by token: %{public}s"
+ "Deleting System Shortcut Entry %{public}s"
+ "Deleting trigger %{public}@"
+ "DesiredSyncSummary"
+ "DisableSafetyGuardrail"
+ "Disabled all automation triggers"
+ "Failed to count %s by synced schema version: %@"
+ "Failed to set enablement of trigger %{public}@ to %{public}s: trigger not found"
+ "Ignoring prewarm of %ld remote device(s): unsupported platform"
+ "No LaunchServices record for %s, using bundle identifier only"
+ "No System Shortcut entry for token %{public}s; database holds %{public}ld entries, ephemeral: %{bool,public}d"
+ "Not fetching iCloudQuota copy for %s: server metering is disabled"
+ "Not running location trigger %{public}@: time range is enabled but %{public}s has no value"
+ "Only value search queries can run on a remote device"
+ "Performing remote value query %s in %s"
+ "PreservesUnresolvedApps"
+ "Recreating missing System Shortcut Entry %{public}s for app %s; database held %{public}ld entries, ephemeral: %{bool,public}d"
+ "Refusing time of day trigger that recurs more often than every %{public}fs; key: %{public}@"
+ "Remote value queries aren't supported on this platform"
+ "Remote value queries aren't supported on this platform, querying the local app instead"
+ "Remote value queries can't take entity identifiers as input"
+ "Remote value query can't target a user identity, using the remote device's current user"
+ "RemoteValueQueryErrorDomain"
+ "Set enablement of trigger %{public}@: %{public}s -> %{public}s"
+ "Updating System Shortcut Entry %{public}s"
+ "Value search has no input value"
+ "Value set isn't an App Intents query with a bundle identifier"
+ "WFDebugViewExpectedEncryptedSchemaVersion"
+ "Walrus status on account has changed since last fetched status."
+ "When a screenshot is saved to the selected locations. Photos is not supported on this platform and is ignored. NOTE: For the best results use all locations unless otherwise requested by the user."
+ "WorkflowKit.WFMTACapableDeviceResource"
+ "Writing Tools actions available because additionalPolicy is unset"
+ "Writing Tools actions hidden because additionalPolicy is set"
+ "policy: App Intents metadata did not quiesce within %s, proceeding"
+ "policy: App Intents metadata quiescent, computing policy"
+ "pull: stored bookmark unusable for %s persona %s (%@); re-pulling the set from scratch"
+ "pull: user profile store unavailable (%@); skipping set enumeration"
+ "reasonsNotNeeded"
+ "recordIDsToDelete"
+ "recordIDsToSave"
+ "server copy has a newer encrypted schema version"
+ "unavailable"
+ "\xf0\xf0A"
- "%K != %lld OR %K = nil"
- "%K == NO"
- "%s Executor finished after user cancellation, treating as cancelled: %{public}@"
- "%s Looks like we want Walrus schema version %lld for %@"
- "%s Ran predicate on %@, found %ld entities: %@"
- "%s Running predicate on %@: %@"
- "%s Saving %@ to storage, but Walrus version is wrong; fixing <old: %lld, new: %lld>"
- "%s Skipping collection %@ for Walrus, as it's not a user-created one"
- "%s Unable to update wanted schema versions for Walrus: %{public}@"
- "%s Updated %lu Walrus schema versions."
- "%s Updated collection <old: wanted schema ver %lld, last synced schema ver %lld> <new: wanted schema ver %lld, last synced schema ver %lld>: %@"
- "%s Updated workflow <old: wanted schema ver %lld, sync hash %lld, last synced schema ver %lld> <new: wanted schema ver %lld, sync hash %lld, last synced schema ver %lld>: %@"
- "%s Updating Walrus status in the database - per:\n%@"
- "%s Walrus final status has changed to %d"
- "%s Walrus ground truth status has changed to %d"
- "%s Walrus status has been FORCED to %d"
- "%s does not have an implementing widget extension, unable to lookup control"
- "(%K != %K) OR (%K == NIL AND %K > 0)"
- "+[WFCloudKitSyncSession resolveWalrusStatus]"
- "+[WFCloudKitSyncSession setWalrusEnabled:]"
- "+[WFCloudKitSyncSession setWalrusForcedEnabled:]"
- "-[WFDatabase(Sync) updateWalrusStatus]"
- "-[WFDatabase(Sync) updateWalrusStatus]_block_invoke"
- "Adding new System Shortcut Entry"
- "App.InFocus: %{public}s is not on screen (%{public}s); not an open."
- "App.InFocus: %{public}s is on screen; firing open."
- "App.InFocus: %{public}s is still on screen; holding close."
- "App.InFocus: %{public}s left the display layout while covered; firing held close."
- "App.InFocus: %{public}s left the screen (presence now %{public}s); firing close."
- "App.InFocus: %{public}s lost focus while its open settled; not an open."
- "App.InFocus: %{public}s regained focus while its close settled; not a close."
- "App.InFocus: %{public}s resumed after being covered; not an open."
- "App.InFocus: %{public}s was off screen before its close resolved; firing close."
- "App.InFocus: device is locked; suppressing close of %{public}s."
- "App.InFocus: device locked while %{public}s was covered; discarding held close."
- "Automation"
- "Deleting %ld System Shortcut Entries by token"
- "Deleting System Shortcut Entries for %s"
- "Deleting System Shortcut Entry with given token"
- "Falling back to system-wide Writing Tools availability because Apple Intelligence hasn't shipped in China"
- "Looking up control matching identity: (extension: %s, container: %s"
- "Not a debug build"
- "Not running %s due to missing start/end time parameters"
- "Not running %s due to start/end time"
- "Refusing Notify Me When trigger that recurs more often than every %{public}fs; key: %{public}@"
- "Remote tool %s parameter '%s' has type(s) [%s] incompatible with target %s — should be .attributed to the target device before remote execution"
- "Shortcut Timed Out"
- "The shortcut took too long to run."
- "Updating System Shortcut Entry for %s"
- "WFLastViewedAutoShortcutsAtTimeKey"
- "WFRemoteAppIntentExecutionActionErrorDomain"
- "WFWalrusEnabled"
- "WFWalrusForcedEnabled"
- "WFWalrusGroundTruthEnabled"
- "When a screenshot is saved to the selected locations. NOTE: For the best results use all locations unless otherwise requested by the user."
- "WorkflowKit.Target"
- "clearing Walrus state for testing"
- "com.apple.chrono.effectiveContainerBundleIdentifier"
- "com.apple.shortcuts.AutoShortcutButtonEvent"
- "com.apple.shortcuts.WFAppInFocusObserver.settle"
- "com.apple.shortcuts.toolinvocation"
- "com.apple.widgetkit-extension"
- "database walrus update"
- "found control descriptors for %s: %s"
- "get remote folder ordering"
- "get remote shortcut ordering"
- "https://icq.icloud.com/?context=ZXh0ZXJuYWxBcHBfZXh0ZXJuYWxVbml2ZXJzYWxPZmZlcl9jbG91ZEZNQ2VudHJpYzFwCg==&bundleId=com.apple.shortcuts&universalLinkAction=LAUNCH_CLOUD_FM"
- "https://support.apple.com/127901?cid=mc-ols-icloud-article_127901-ios_ipados-62020270"
- "misattributed attributed<"
- "unconverted custom<"
- "updating walrus schema status for collections"
- "updating walrus schema status for shortcuts"
- "wantedEncryptedSchemaVersion"
- "“%@” took too long to run."
- "\xf0\xf01"
```
