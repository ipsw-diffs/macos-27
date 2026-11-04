## ScreenReader

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/ScreenReader`

```diff

-1050.3.5.0.0
-  __TEXT.__text: 0x2cddcc
-  __TEXT.__objc_methlist: 0x25e18
-  __TEXT.__dlopen_cstrs: 0x6c9
-  __TEXT.__const: 0x1470
+1050.3.12.0.0
+  __TEXT.__text: 0x2d5afc
+  __TEXT.__objc_methlist: 0x26398
+  __TEXT.__dlopen_cstrs: 0x733
+  __TEXT.__const: 0x1490
   __TEXT.__swift5_typeref: 0x664
   __TEXT.__swift5_capture: 0x4f0
   __TEXT.__constg_swiftt: 0x5d4
   __TEXT.__swift5_reflstr: 0x1d4
   __TEXT.__swift5_fieldmd: 0x258
   __TEXT.__swift5_builtin: 0x14
-  __TEXT.__cstring: 0x1e6ee
-  __TEXT.__oslogstring: 0x1475
+  __TEXT.__cstring: 0x1ec6e
+  __TEXT.__oslogstring: 0x17c1
   __TEXT.__swift5_types: 0x34
   __TEXT.__swift_as_entry: 0x7c
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0xd0
   __TEXT.__swift5_proto: 0x20
-  __TEXT.__gcc_except_tab: 0x3564
-  __TEXT.__ustring: 0x48
+  __TEXT.__gcc_except_tab: 0x3584
+  __TEXT.__ustring: 0x4c
   __TEXT.__dof_SCRMapEle: 0x47e
   __TEXT.__dof_SCRSpeech: 0x21a
-  __TEXT.__unwind_info: 0xb4c8
+  __TEXT.__unwind_info: 0xb658
   __TEXT.__eh_frame: 0x1120
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1fc0
-  __DATA_CONST.__objc_classlist: 0xd20
+  __DATA_CONST.__const: 0x1fd8
+  __DATA_CONST.__objc_classlist: 0xd38
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13f40
+  __DATA_CONST.__objc_selrefs: 0x142b0
   __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__objc_superrefs: 0x9b0
-  __DATA_CONST.__objc_arraydata: 0x8e8
-  __DATA_CONST.__got: 0x2148
-  __AUTH_CONST.__const: 0x4a08
-  __AUTH_CONST.__cfstring: 0x23ae0
-  __AUTH_CONST.__objc_const: 0x25578
-  __AUTH_CONST.__objc_arrayobj: 0x1f8
+  __DATA_CONST.__objc_superrefs: 0x9c8
+  __DATA_CONST.__objc_arraydata: 0xa00
+  __DATA_CONST.__got: 0x2180
+  __AUTH_CONST.__const: 0x4a68
+  __AUTH_CONST.__cfstring: 0x23fe0
+  __AUTH_CONST.__objc_const: 0x25a88
+  __AUTH_CONST.__objc_arrayobj: 0x210
   __AUTH_CONST.__objc_intobj: 0x15d8
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1fd8
-  __AUTH.__objc_data: 0x86a0
+  __AUTH_CONST.__auth_got: 0x2058
+  __AUTH.__objc_data: 0x8790
   __AUTH.__data: 0x560
-  __DATA.__objc_ivar: 0x1aa4
+  __DATA.__objc_ivar: 0x1aec
   __DATA.__data: 0x2290
-  __DATA.__bss: 0x1328
+  __DATA.__bss: 0x13f0
   __DATA.__common: 0x8
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox
   - /System/Library/Frameworks/Carbon.framework/Versions/A/Carbon
+  - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13797
-  Symbols:   29282
-  CStrings:  5134
+  Functions: 13922
+  Symbols:   29583
+  CStrings:  5190
 
Symbols:
+ +[SCREventUtilities _applyTouchCancelToHIDEvent:timestamp:]
+ +[SCREventUtilities _sharedHIDSystemClient]
+ +[SCREventUtilities displayIDForSenderID:]
+ +[SCREventUtilities displayIDForUUID:]
+ +[SCREventUtilities enableSidecarFactories:playSounds:]
+ +[SCREventUtilities isSidecarTouchUpEvent:]
+ +[SCREventUtilities isSyntheticTouchCancelEvent:]
+ +[SCREventUtilities postSyntheticTouchCancelFromEvent:]
+ +[SCRNavigationUtilities handleSidecarNavigationFromElement:atLocation:withRequest:]
+ +[SCROutputUtilities removeSoftHyphensFromAction:]
+ -[SCRApplication(Sidecar) _closeFocusedMenuIfNeeded]
+ -[SCRApplication(Sidecar) _findSpeakableContainerForElement:]
+ -[SCRApplication(Sidecar) _handleSidecarSelectionOnFingerLift:]
+ -[SCRApplication(Sidecar) _moveFocusToMenuBar:]
+ -[SCRApplication(Sidecar) _setSidecarFocusToSidecarUIElement:]
+ -[SCRApplication(Sidecar) _updateFocusWithSidecarInfo:]
+ -[SCRApplication(Sidecar) _updateMenuStatusForElement:info:]
+ -[SCRApplication(Sidecar) dispatchCloseFocusedMenu]
+ -[SCRApplication(Sidecar) dispatchUpdateFocusWithSidecarInfo:]
+ -[SCRApplication(Sidecar) handleApplicationSwitching:info:newTopLevelUIElement:]
+ -[SCRApplication(Sidecar) handleWindowChangeOnDoubleTap:]
+ -[SCRApplication(Sidecar) handleWindowChangeOnFingerLift:info:]
+ -[SCRApplication(Sidecar) isMenuBarItemRole:]
+ -[SCRApplication(Sidecar) menuBarItemElementForUIElement:]
+ -[SCRApplication(Sidecar) moveToFocusElement:oldDeepestChild:info:]
+ -[SCRApplication(Sidecar) setFocusedApplication]
+ -[SCRCUserDefaults(SCRCUserDefaultsCommandersConvenience) sidecarKeys]
+ -[SCRCell isSidecarContainerElement]
+ -[SCRElement isSidecarContainerElement]
+ -[SCRElement(SCRElementEventHandling) _moveToElementWithSidecarHandler:]
+ -[SCRElement(SCRElementEventHandling) _moveWindowWithSidecarHandler:]
+ -[SCRElement(SCRElementEventHandling) _resizeElementWithSidecarHandler:]
+ -[SCRElement(SCRElementEventHandling) _resizeWindowWithSidecarHandler:]
+ -[SCRElement(SCRElementInteraction) _sidecarWindowMoveEchoTimerFired:]
+ -[SCRElement(SCRElementInteraction) _sidecarWindowResizeEchoTimerFired:]
+ -[SCRElement(SCRElementInteraction) describeSidecarWindowMoveFromPosition:]
+ -[SCRElement(SCRElementInteraction) handleMoveWindowWithSidecarEvent:request:]
+ -[SCRElement(SCRElementInteraction) handleResizeElementWithSidecarEvent:request:]
+ -[SCRElement(SCRElementNavigation) handleMoveToElementWithSidecarEvent:request:]
+ -[SCREvent isSidecarEvent]
+ -[SCREventFactory screenParametersChanged:]
+ -[SCREventFactory(Gesture) _enableSidecarFromPreferences:]
+ -[SCREventFactory(Gesture) _isTrackingGestureString:]
+ -[SCREventFactory(Gesture) _shouldSwallowSidecarTouchEvent:wantsSwallow:]
+ -[SCREventFactory(Gesture) _updateSidecar]
+ -[SCREventFactory(Gesture) isSidecarSource:]
+ -[SCREventFactory(Gesture) resetSidecarTouchSequence]
+ -[SCREventFactory(Gesture) sidecarEnabledForDeviceIdentifier:]
+ -[SCRList isSidecarContainerElement]
+ -[SCRSheet isSidecarContainerElement]
+ -[SCRSidecar .cxx_destruct]
+ -[SCRSidecar _handleMoveToElementWithSidecarInfo:]
+ -[SCRSidecar _handleWindowCross:]
+ -[SCRSidecar _isUIElementPresentedRemotelyByMenuBarAgent:]
+ -[SCRSidecar alternateFocusedWindow]
+ -[SCRSidecar handleSidecarEventWithInfo:]
+ -[SCRSidecar handleSidecarMenuDismissWithInfo:]
+ -[SCRSidecar init]
+ -[SCRSidecar lastSidecarElement]
+ -[SCRSidecar lastSidecarLocation]
+ -[SCRSidecar lastSpokenContainer]
+ -[SCRSidecar menuApplication]
+ -[SCRSidecar menuDidOpenInApplication:]
+ -[SCRSidecar menuStatus]
+ -[SCRSidecar performSidecarMenuDismiss]
+ -[SCRSidecar resetMenuStatusIfOwnedByApplication:]
+ -[SCRSidecar setAlternateFocusedWindow:]
+ -[SCRSidecar setLastSidecarElement:]
+ -[SCRSidecar setLastSidecarLocation:]
+ -[SCRSidecar setLastSpokenContainer:]
+ -[SCRSidecar setMenuApplication:]
+ -[SCRSidecar setMenuStatus:]
+ -[SCRSidecar setTouchPointIsInWindow:]
+ -[SCRSidecar threadKey]
+ -[SCRSidecar touchPointIsInWindow]
+ -[SCRSidecarGestureFactory cancelIgnoredFinger]
+ -[SCRSidecarGestureFactory createGestureEventForCGEvent:]
+ -[SCRSidecarGestureFactory gestureCommander]
+ -[SCRSidecarGestureFactory gestureFocusSource]
+ -[SCRSidecarGestureFactory gestureString]
+ -[SCRSidecarGestureFactory hasIdentityMatch:]
+ -[SCRSidecarGestureFactory hasIgnoredFinger]
+ -[SCRSidecarGestureFactory init]
+ -[SCRSidecarGestureFactory screenPointFromNormalizedPoint:]
+ -[SCRSidecarGestureFactory setIgnoredFinger:fingerIdentity:]
+ -[SCRSidecarGestureFactory trackingLocation]
+ -[SCRSidecarInfo .cxx_destruct]
+ -[SCRSidecarInfo initWithLocation:isTracking:]
+ -[SCRSidecarInfo isRemoteContentPresentedByMenuBarAgent]
+ -[SCRSidecarInfo isTracking]
+ -[SCRSidecarInfo setIsRemoteContentPresentedByMenuBarAgent:]
+ -[SCRSidecarInfo setIsTracking:]
+ -[SCRSidecarInfo setTrackingLocation:]
+ -[SCRSidecarInfo setUiElement:]
+ -[SCRSidecarInfo trackingLocation]
+ -[SCRSidecarInfo uiElement]
+ -[SCRSystemUIServerApplication _liveActivityHostingRemoteUIElement:atLocation:]
+ -[SCRSystemUIServerApplication _updateFocusWithSidecarInfo:]
+ -[SCRSystemUIServerApplication dispatchUpdateFocusWithSidecarInfo:]
+ -[SCRWebAreaBookendGroup isSidecarContainerElement]
+ -[SCRWebAreaPromotableElement isSidecarContainerElement]
+ -[SCRWebDomList _excludeBookendFromBrailleIfSpeakingToRequest:]
+ -[SCRWorkspace setSidecar:]
+ -[SCRWorkspace sidecarCommanderEnabled]
+ -[SCRWorkspace sidecar]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) _warpMouseToGestureTrackingPointFromInfo:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) appExposeEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) disableSidecarCommanderEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) enableSidecarCommanderEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) launchpadEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) missionControlEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) nextSpaceEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) previousSpaceEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceEventHandler) showDesktopEventHandler:]
+ -[SCRWorkspace(SCRWorkspaceGuide) _addSidecarCommanderToCommandsGuide:mainGuide:]
+ GCC_except_table10055
+ GCC_except_table10059
+ GCC_except_table10064
+ GCC_except_table10501
+ GCC_except_table10505
+ GCC_except_table10509
+ GCC_except_table10650
+ GCC_except_table10655
+ GCC_except_table11
+ GCC_except_table11281
+ GCC_except_table11304
+ GCC_except_table11591
+ GCC_except_table11595
+ GCC_except_table1162
+ GCC_except_table11698
+ GCC_except_table1175
+ GCC_except_table118
+ GCC_except_table11920
+ GCC_except_table1209
+ GCC_except_table12157
+ GCC_except_table1217
+ GCC_except_table12204
+ GCC_except_table12273
+ GCC_except_table12275
+ GCC_except_table12402
+ GCC_except_table12481
+ GCC_except_table1253
+ GCC_except_table1257
+ GCC_except_table12579
+ GCC_except_table12583
+ GCC_except_table12584
+ GCC_except_table12591
+ GCC_except_table1260
+ GCC_except_table12811
+ GCC_except_table12900
+ GCC_except_table1474
+ GCC_except_table1659
+ GCC_except_table17
+ GCC_except_table1846
+ GCC_except_table1886
+ GCC_except_table1925
+ GCC_except_table2039
+ GCC_except_table2194
+ GCC_except_table2196
+ GCC_except_table2258
+ GCC_except_table2370
+ GCC_except_table2589
+ GCC_except_table2606
+ GCC_except_table2665
+ GCC_except_table2869
+ GCC_except_table3126
+ GCC_except_table3128
+ GCC_except_table3204
+ GCC_except_table3280
+ GCC_except_table3414
+ GCC_except_table3418
+ GCC_except_table3502
+ GCC_except_table3606
+ GCC_except_table3684
+ GCC_except_table3707
+ GCC_except_table3831
+ GCC_except_table3922
+ GCC_except_table3925
+ GCC_except_table3949
+ GCC_except_table3954
+ GCC_except_table3968
+ GCC_except_table4072
+ GCC_except_table4117
+ GCC_except_table4528
+ GCC_except_table4537
+ GCC_except_table4540
+ GCC_except_table4665
+ GCC_except_table4703
+ GCC_except_table4707
+ GCC_except_table4711
+ GCC_except_table4713
+ GCC_except_table4717
+ GCC_except_table4721
+ GCC_except_table4791
+ GCC_except_table4805
+ GCC_except_table4850
+ GCC_except_table4854
+ GCC_except_table4880
+ GCC_except_table4886
+ GCC_except_table54
+ GCC_except_table5724
+ GCC_except_table5760
+ GCC_except_table5863
+ GCC_except_table6138
+ GCC_except_table6144
+ GCC_except_table6323
+ GCC_except_table6373
+ GCC_except_table6410
+ GCC_except_table6505
+ GCC_except_table6692
+ GCC_except_table6778
+ GCC_except_table6803
+ GCC_except_table6825
+ GCC_except_table6831
+ GCC_except_table6835
+ GCC_except_table6960
+ GCC_except_table6963
+ GCC_except_table6968
+ GCC_except_table6994
+ GCC_except_table7001
+ GCC_except_table7032
+ GCC_except_table7035
+ GCC_except_table7069
+ GCC_except_table7070
+ GCC_except_table7189
+ GCC_except_table7195
+ GCC_except_table7216
+ GCC_except_table7217
+ GCC_except_table7284
+ GCC_except_table729
+ GCC_except_table7310
+ GCC_except_table7312
+ GCC_except_table7426
+ GCC_except_table7464
+ GCC_except_table7466
+ GCC_except_table7468
+ GCC_except_table7483
+ GCC_except_table7484
+ GCC_except_table7497
+ GCC_except_table7511
+ GCC_except_table7512
+ GCC_except_table7529
+ GCC_except_table7603
+ GCC_except_table7610
+ GCC_except_table7611
+ GCC_except_table7755
+ GCC_except_table790
+ GCC_except_table8048
+ GCC_except_table8070
+ GCC_except_table8246
+ GCC_except_table8335
+ GCC_except_table8341
+ GCC_except_table8342
+ GCC_except_table8343
+ GCC_except_table8344
+ GCC_except_table8348
+ GCC_except_table8349
+ GCC_except_table8470
+ GCC_except_table8481
+ GCC_except_table8485
+ GCC_except_table8548
+ GCC_except_table8653
+ GCC_except_table8799
+ GCC_except_table8805
+ GCC_except_table8900
+ GCC_except_table8974
+ GCC_except_table9
+ GCC_except_table9056
+ GCC_except_table9130
+ GCC_except_table9131
+ GCC_except_table9148
+ GCC_except_table9158
+ GCC_except_table9168
+ GCC_except_table9169
+ GCC_except_table9176
+ GCC_except_table9179
+ GCC_except_table9180
+ GCC_except_table9338
+ GCC_except_table9668
+ GCC_except_table9716
+ GCC_except_table9721
+ _AXEIsSynthesizedIgnoreEvent
+ _AXESynthesizedIgnoreEventSourceID
+ _CFUUIDCreateString
+ _CGDisplayCreateUUIDFromDisplayID
+ _IOHIDEventGetChildren
+ _IOHIDEventGetIntegerValue
+ _IOHIDEventGetPhase
+ _IOHIDEventGetSenderID
+ _IOHIDEventGetType
+ _IOHIDEventSetIntegerValue
+ _IOHIDEventSetPhase
+ _IOHIDEventSetTimeStamp
+ _IOHIDEventSystemClientActivate
+ _IOHIDEventSystemClientCopyServiceForRegistryID
+ _IOHIDEventSystemClientCreateWithType
+ _IOHIDEventSystemClientSetDispatchQueue
+ _NSApplicationDidChangeScreenParametersNotification
+ _OBJC_CLASS_$_SCRSidecar
+ _OBJC_CLASS_$_SCRSidecarGestureFactory
+ _OBJC_CLASS_$_SCRSidecarInfo
+ _OBJC_IVAR_$_SCREventFactory._lastPassedSidecarTouchEvent
+ _OBJC_IVAR_$_SCREventFactory._sidecarGestureFactories
+ _OBJC_IVAR_$_SCREventFactory._sidecarTouchSequenceOwner
+ _OBJC_IVAR_$_SCRSidecar._alternateFocusedWindow
+ _OBJC_IVAR_$_SCRSidecar._lastSidecarElement
+ _OBJC_IVAR_$_SCRSidecar._lastSidecarLocation
+ _OBJC_IVAR_$_SCRSidecar._lastSpokenContainer
+ _OBJC_IVAR_$_SCRSidecar._menuApplication
+ _OBJC_IVAR_$_SCRSidecar._menuStatus
+ _OBJC_IVAR_$_SCRSidecar._menuStatusLock
+ _OBJC_IVAR_$_SCRSidecar._threadKey
+ _OBJC_IVAR_$_SCRSidecar._touchPointIsInWindow
+ _OBJC_IVAR_$_SCRSidecarGestureFactory._ignoredFinger
+ _OBJC_IVAR_$_SCRSidecarInfo._isRemoteContentPresentedByMenuBarAgent
+ _OBJC_IVAR_$_SCRSidecarInfo._isTracking
+ _OBJC_IVAR_$_SCRSidecarInfo._trackingLocation
+ _OBJC_IVAR_$_SCRSidecarInfo._uiElement
+ _OBJC_IVAR_$_SCRWorkspace._sidecar
+ _OBJC_METACLASS_$_SCRSidecar
+ _OBJC_METACLASS_$_SCRSidecarGestureFactory
+ _OBJC_METACLASS_$_SCRSidecarInfo
+ _SCRSidecarLog
+ _SCRSidecarLog.log
+ _SCRSidecarLog.onceToken
+ __BuildGestureCommandDictionary
+ __OBJC_$_CLASS_METHODS_SCRApplication(SCRAppStoreApplication|BusyStatus|ContentChooser|RemoteGuideItems|SCRApplicationObserver|SCRApplicationUIElementCacheManager|SCRCalendarApplication|SCRControlCenterApplication|SCRMenuBarAgentApplication|SCRRecoveryApplication|SCRDFRControlStripApplication|SCRBootPickerApplication|SCRUniversalAccessControlApplication|SCRDataDetectorsApplication|SCRDictationApplication|SCRDisabledApplication|SCRDockApplication|SCRFinderApplication|SCRSpotlightApplication|SCRApplicationLanguageChooserApplication|SCRApplicationLoginWindowCategory|SCRMailApplicationCategory|Spot|SCRNotificationCenterApplication|Sidecar|SCRPagesApplication|AccessibilityVisualsAgent|SCRWindowManagerApplication|SCRSafariCategory|Search|SCRSecurityAgentApplication|SCRSetupAssistantApplication|SCRSpotlightApplication|SCRSystemApplication|SCRAccessibilityInspectorApplication|SCRSystemUIServerApplication|FocusAdditionsPrivate|SCRUITestApplication|SCRVOQuickStartApplication|SCRVOUtilityApplication|SCRInstallerProgressApplication|SCRiBooksApplication|SCRiWorkApplication)
+ __OBJC_$_INSTANCE_METHODS_SCRApplication(SCRAppStoreApplication|BusyStatus|ContentChooser|RemoteGuideItems|SCRApplicationObserver|SCRApplicationUIElementCacheManager|SCRCalendarApplication|SCRControlCenterApplication|SCRMenuBarAgentApplication|SCRRecoveryApplication|SCRDFRControlStripApplication|SCRBootPickerApplication|SCRUniversalAccessControlApplication|SCRDataDetectorsApplication|SCRDictationApplication|SCRDisabledApplication|SCRDockApplication|SCRFinderApplication|SCRSpotlightApplication|SCRApplicationLanguageChooserApplication|SCRApplicationLoginWindowCategory|SCRMailApplicationCategory|Spot|SCRNotificationCenterApplication|Sidecar|SCRPagesApplication|AccessibilityVisualsAgent|SCRWindowManagerApplication|SCRSafariCategory|Search|SCRSecurityAgentApplication|SCRSetupAssistantApplication|SCRSpotlightApplication|SCRSystemApplication|SCRAccessibilityInspectorApplication|SCRSystemUIServerApplication|FocusAdditionsPrivate|SCRUITestApplication|SCRVOQuickStartApplication|SCRVOUtilityApplication|SCRInstallerProgressApplication|SCRiBooksApplication|SCRiWorkApplication)
+ __OBJC_$_INSTANCE_METHODS_SCRSidecar
+ __OBJC_$_INSTANCE_METHODS_SCRSidecarGestureFactory
+ __OBJC_$_INSTANCE_METHODS_SCRSidecarInfo
+ __OBJC_$_INSTANCE_VARIABLES_SCRSidecar
+ __OBJC_$_INSTANCE_VARIABLES_SCRSidecarGestureFactory
+ __OBJC_$_INSTANCE_VARIABLES_SCRSidecarInfo
+ __OBJC_$_PROP_LIST_SCRSidecar
+ __OBJC_$_PROP_LIST_SCRSidecarInfo
+ __OBJC_CLASS_PROTOCOLS_$_SCRSidecarGestureFactory
+ __OBJC_CLASS_RO_$_SCRSidecar
+ __OBJC_CLASS_RO_$_SCRSidecarGestureFactory
+ __OBJC_CLASS_RO_$_SCRSidecarInfo
+ __OBJC_METACLASS_RO_$_SCRSidecar
+ __OBJC_METACLASS_RO_$_SCRSidecarGestureFactory
+ __OBJC_METACLASS_RO_$_SCRSidecarInfo
+ __SidecarCommandToGestureDictionary
+ __SidecarElementResizeEchoTimer
+ __SidecarElementResizeStartBounds
+ __SidecarWindowMoveEchoTimer
+ __SidecarWindowMoveStartPosition
+ ___39-[SCRElement isSidecarContainerElement]_block_invoke
+ ___43+[SCREventUtilities _sharedHIDSystemClient]_block_invoke
+ ___55+[SCREventUtilities postSyntheticTouchCancelFromEvent:]_block_invoke
+ ___69-[SCRWorkspace(SCRWorkspaceEventHandler) missionControlEventHandler:]_block_invoke
+ ___SCRSidecarLog_block_invoke
+ ___getAXEventRepresentationClass_block_invoke
+ __postSymbolicHotKeyEvent
+ __sharedHIDSystemClient.client
+ __sharedHIDSystemClient.onceToken
+ _getAXEventRepresentationClass.softClass
+ _isSidecarContainerElement.groupRoles
+ _isSidecarContainerElement.onceToken
+ _kSCRCConfigurationSidecarCommander
+ _kSCRCUserDefaultsDomainSidecarCommander
+ _kSCRCUserDefaultsSidecarCommanderEnabled
+ _kSCRCUserDefaultsSidecarSelectionChangeOnFingerLift
+ _kSCRCUserDefaultsSidecarSwitchWindowOnDoubleTap
+ _mach_absolute_time
+ _objc_msgSend$CGDirectDisplayID
+ _objc_msgSend$_addSidecarCommanderToCommandsGuide:mainGuide:
+ _objc_msgSend$_applyTouchCancelToHIDEvent:timestamp:
+ _objc_msgSend$_bringWindowToFront:
+ _objc_msgSend$_closeFocusedMenuIfNeeded
+ _objc_msgSend$_enableSidecarFromPreferences:
+ _objc_msgSend$_excludeBookendFromBrailleIfSpeakingToRequest:
+ _objc_msgSend$_findSpeakableContainerForElement:
+ _objc_msgSend$_handleSidecarSelectionOnFingerLift:
+ _objc_msgSend$_handleWindowCross:
+ _objc_msgSend$_isTrackingGestureString:
+ _objc_msgSend$_isUIElementPresentedRemotelyByMenuBarAgent:
+ _objc_msgSend$_liveActivityHostingRemoteUIElement:atLocation:
+ _objc_msgSend$_moveFocusToMenuBar:
+ _objc_msgSend$_setSidecarFocusToSidecarUIElement:
+ _objc_msgSend$_sharedHIDSystemClient
+ _objc_msgSend$_shouldSwallowSidecarTouchEvent:wantsSwallow:
+ _objc_msgSend$_updateMenuStatusForElement:info:
+ _objc_msgSend$_updateSidecar
+ _objc_msgSend$_warpMouseToGestureTrackingPointFromInfo:
+ _objc_msgSend$alternateFocusedWindow
+ _objc_msgSend$cancelIgnoredFinger
+ _objc_msgSend$convertPointToTopLeftOriginScreenCoordinateSpace:
+ _objc_msgSend$deltaX
+ _objc_msgSend$deltaY
+ _objc_msgSend$describeSidecarWindowMoveFromPosition:
+ _objc_msgSend$dispatchCloseFocusedMenu
+ _objc_msgSend$dispatchFocusOnMissionControlAtPoint:
+ _objc_msgSend$dispatchUpdateFocusWithSidecarInfo:
+ _objc_msgSend$displayIDForSenderID:
+ _objc_msgSend$displayIDForUUID:
+ _objc_msgSend$elementFromUIElement:candidates:
+ _objc_msgSend$enableSidecarFactories:playSounds:
+ _objc_msgSend$findClosestNavigableElementInArray:atPoint:
+ _objc_msgSend$findTopLevelLeafNodeForElement:atPoint:
+ _objc_msgSend$fingers
+ _objc_msgSend$handInfo
+ _objc_msgSend$handleApplicationSwitching:info:newTopLevelUIElement:
+ _objc_msgSend$handleMoveToElementWithSidecarEvent:request:
+ _objc_msgSend$handleMoveWindowWithSidecarEvent:request:
+ _objc_msgSend$handleResizeElementWithSidecarEvent:request:
+ _objc_msgSend$handleSidecarEventWithInfo:
+ _objc_msgSend$handleSidecarMenuDismissWithInfo:
+ _objc_msgSend$handleSidecarNavigationFromElement:atLocation:withRequest:
+ _objc_msgSend$handleWindowChangeOnDoubleTap:
+ _objc_msgSend$handleWindowChangeOnFingerLift:info:
+ _objc_msgSend$hasIgnoredFinger
+ _objc_msgSend$initWithLocation:isTracking:
+ _objc_msgSend$initWithRect:delegate:threadKey:
+ _objc_msgSend$isDisplayIntegrated
+ _objc_msgSend$isMenuBarItemRole:
+ _objc_msgSend$isRemoteContentPresentedByMenuBarAgent
+ _objc_msgSend$isShowingDesktop
+ _objc_msgSend$isSidecarContainerElement
+ _objc_msgSend$isSidecarEvent
+ _objc_msgSend$isSidecarSource:
+ _objc_msgSend$isSidecarTouchUpEvent:
+ _objc_msgSend$isSyntheticTouchCancelEvent:
+ _objc_msgSend$isTracking
+ _objc_msgSend$lastSidecarElement
+ _objc_msgSend$lastSidecarLocation
+ _objc_msgSend$lastSpokenContainer
+ _objc_msgSend$menuApplication
+ _objc_msgSend$menuBarAgentApplication
+ _objc_msgSend$menuBarItemElementForUIElement:
+ _objc_msgSend$menuDidOpenInApplication:
+ _objc_msgSend$menuStatus
+ _objc_msgSend$moveToFocusElement:oldDeepestChild:info:
+ _objc_msgSend$pathIndex
+ _objc_msgSend$pathLocation
+ _objc_msgSend$pathProximity
+ _objc_msgSend$paths
+ _objc_msgSend$performSidecarMenuDismiss
+ _objc_msgSend$postMouseDownEventAtLocation:
+ _objc_msgSend$postMouseDraggedEventAtLocation:
+ _objc_msgSend$postSyntheticTouchCancelFromEvent:
+ _objc_msgSend$primaryFingerIdentity
+ _objc_msgSend$removeSoftHyphensFromAction:
+ _objc_msgSend$representationWithHIDEvent:hidStreamIdentifier:
+ _objc_msgSend$resetMenuStatusIfOwnedByApplication:
+ _objc_msgSend$resetSidecarTouchSequence
+ _objc_msgSend$rowsForColumn:
+ _objc_msgSend$screenPointFromNormalizedPoint:
+ _objc_msgSend$setAlternateFocusedWindow:
+ _objc_msgSend$setFocusedApplication
+ _objc_msgSend$setFocusedChildAtIndex:
+ _objc_msgSend$setIgnoredFinger:fingerIdentity:
+ _objc_msgSend$setIsRemoteContentPresentedByMenuBarAgent:
+ _objc_msgSend$setIsTouchEvent:
+ _objc_msgSend$setLastSidecarElement:
+ _objc_msgSend$setLastSidecarLocation:
+ _objc_msgSend$setLastSpokenContainer:
+ _objc_msgSend$setMenuApplication:
+ _objc_msgSend$setMenuStatus:
+ _objc_msgSend$setSidecar:
+ _objc_msgSend$setTouchPointIsInWindow:
+ _objc_msgSend$sidecar
+ _objc_msgSend$sidecarCommanderEnabled
+ _objc_msgSend$sidecarKeys
+ _objc_msgSend$touchPointIsInWindow
+ _sSidecarLaunchpadOpenedByPinch
+ _sidecarKeys.SidecarKeys
- GCC_except_table10
- GCC_except_table10394
- GCC_except_table10398
- GCC_except_table10402
- GCC_except_table10543
- GCC_except_table10548
- GCC_except_table11172
- GCC_except_table11195
- GCC_except_table11481
- GCC_except_table11485
- GCC_except_table11588
- GCC_except_table116
- GCC_except_table1160
- GCC_except_table1173
- GCC_except_table11810
- GCC_except_table12044
- GCC_except_table1207
- GCC_except_table12091
- GCC_except_table1215
- GCC_except_table12160
- GCC_except_table12162
- GCC_except_table12289
- GCC_except_table12366
- GCC_except_table12455
- GCC_except_table12459
- GCC_except_table12460
- GCC_except_table12467
- GCC_except_table1251
- GCC_except_table1255
- GCC_except_table1258
- GCC_except_table12686
- GCC_except_table12775
- GCC_except_table1472
- GCC_except_table16
- GCC_except_table1656
- GCC_except_table1843
- GCC_except_table1883
- GCC_except_table1917
- GCC_except_table2035
- GCC_except_table2176
- GCC_except_table2182
- GCC_except_table2254
- GCC_except_table2362
- GCC_except_table2585
- GCC_except_table2602
- GCC_except_table2659
- GCC_except_table2863
- GCC_except_table3120
- GCC_except_table3122
- GCC_except_table3198
- GCC_except_table3274
- GCC_except_table3404
- GCC_except_table3408
- GCC_except_table3492
- GCC_except_table3596
- GCC_except_table3674
- GCC_except_table3697
- GCC_except_table3816
- GCC_except_table3907
- GCC_except_table3910
- GCC_except_table3934
- GCC_except_table3939
- GCC_except_table3953
- GCC_except_table4057
- GCC_except_table4101
- GCC_except_table4503
- GCC_except_table4512
- GCC_except_table4515
- GCC_except_table4640
- GCC_except_table4678
- GCC_except_table4682
- GCC_except_table4686
- GCC_except_table4688
- GCC_except_table4692
- GCC_except_table4696
- GCC_except_table4766
- GCC_except_table4780
- GCC_except_table4825
- GCC_except_table4829
- GCC_except_table4855
- GCC_except_table4861
- GCC_except_table52
- GCC_except_table5696
- GCC_except_table5732
- GCC_except_table5835
- GCC_except_table6110
- GCC_except_table6116
- GCC_except_table6285
- GCC_except_table6335
- GCC_except_table6372
- GCC_except_table6467
- GCC_except_table6654
- GCC_except_table6740
- GCC_except_table6755
- GCC_except_table6765
- GCC_except_table6787
- GCC_except_table6797
- GCC_except_table6906
- GCC_except_table6909
- GCC_except_table6914
- GCC_except_table6940
- GCC_except_table6947
- GCC_except_table6978
- GCC_except_table6981
- GCC_except_table7015
- GCC_except_table7016
- GCC_except_table7135
- GCC_except_table7141
- GCC_except_table7162
- GCC_except_table7163
- GCC_except_table7230
- GCC_except_table7256
- GCC_except_table7258
- GCC_except_table727
- GCC_except_table7372
- GCC_except_table7410
- GCC_except_table7412
- GCC_except_table7414
- GCC_except_table7429
- GCC_except_table7430
- GCC_except_table7443
- GCC_except_table7457
- GCC_except_table7458
- GCC_except_table7536
- GCC_except_table7543
- GCC_except_table7544
- GCC_except_table7687
- GCC_except_table788
- GCC_except_table7980
- GCC_except_table8
- GCC_except_table8002
- GCC_except_table8178
- GCC_except_table8267
- GCC_except_table8273
- GCC_except_table8274
- GCC_except_table8275
- GCC_except_table8276
- GCC_except_table8280
- GCC_except_table8281
- GCC_except_table8402
- GCC_except_table8413
- GCC_except_table8417
- GCC_except_table8445
- GCC_except_table8549
- GCC_except_table8695
- GCC_except_table8701
- GCC_except_table8796
- GCC_except_table8870
- GCC_except_table8952
- GCC_except_table9026
- GCC_except_table9027
- GCC_except_table9044
- GCC_except_table9054
- GCC_except_table9064
- GCC_except_table9065
- GCC_except_table9072
- GCC_except_table9075
- GCC_except_table9076
- GCC_except_table9231
- GCC_except_table9561
- GCC_except_table9609
- GCC_except_table9614
- GCC_except_table9948
- GCC_except_table9952
- GCC_except_table9957
- __OBJC_$_CLASS_METHODS_SCRApplication(SCRAppStoreApplication|BusyStatus|ContentChooser|RemoteGuideItems|SCRApplicationObserver|SCRApplicationUIElementCacheManager|SCRCalendarApplication|SCRControlCenterApplication|SCRMenuBarAgentApplication|SCRRecoveryApplication|SCRDFRControlStripApplication|SCRBootPickerApplication|SCRUniversalAccessControlApplication|SCRDataDetectorsApplication|SCRDictationApplication|SCRDisabledApplication|SCRDockApplication|SCRFinderApplication|SCRSpotlightApplication|SCRApplicationLanguageChooserApplication|SCRApplicationLoginWindowCategory|SCRMailApplicationCategory|Spot|SCRNotificationCenterApplication|SCRPagesApplication|AccessibilityVisualsAgent|SCRWindowManagerApplication|SCRSafariCategory|Search|SCRSecurityAgentApplication|SCRSetupAssistantApplication|SCRSpotlightApplication|SCRSystemApplication|SCRAccessibilityInspectorApplication|SCRSystemUIServerApplication|FocusAdditionsPrivate|SCRUITestApplication|SCRVOQuickStartApplication|SCRVOUtilityApplication|SCRInstallerProgressApplication|SCRiBooksApplication|SCRiWorkApplication)
- __OBJC_$_INSTANCE_METHODS_SCRApplication(SCRAppStoreApplication|BusyStatus|ContentChooser|RemoteGuideItems|SCRApplicationObserver|SCRApplicationUIElementCacheManager|SCRCalendarApplication|SCRControlCenterApplication|SCRMenuBarAgentApplication|SCRRecoveryApplication|SCRDFRControlStripApplication|SCRBootPickerApplication|SCRUniversalAccessControlApplication|SCRDataDetectorsApplication|SCRDictationApplication|SCRDisabledApplication|SCRDockApplication|SCRFinderApplication|SCRSpotlightApplication|SCRApplicationLanguageChooserApplication|SCRApplicationLoginWindowCategory|SCRMailApplicationCategory|Spot|SCRNotificationCenterApplication|SCRPagesApplication|AccessibilityVisualsAgent|SCRWindowManagerApplication|SCRSafariCategory|Search|SCRSecurityAgentApplication|SCRSetupAssistantApplication|SCRSpotlightApplication|SCRSystemApplication|SCRAccessibilityInspectorApplication|SCRSystemUIServerApplication|FocusAdditionsPrivate|SCRUITestApplication|SCRVOQuickStartApplication|SCRVOUtilityApplication|SCRInstallerProgressApplication|SCRiBooksApplication|SCRiWorkApplication)
CStrings:
+ "\n Sidecar Container: %@"
+ "AXDesktop"
+ "AXEventRepresentation"
+ "AccessibilityEventTap"
+ "Class getAXEventRepresentationClass(void)_block_invoke"
+ "Remote hit (presenter %{private}d, actual %{private}d) has no Live Activity"
+ "Remote hit (presenter %{private}d, actual %{private}d) resolved to its Live Activity"
+ "SCREventUtilities: Failed to create IOHIDEventSystemClient"
+ "SCREventUtilities: HIDSystemClient not available"
+ "SCREventUtilities: No HIDServiceClient found for senderID: %llu"
+ "SCREventUtilities: No displayUUID property on HIDService for senderID: %llu"
+ "SCRGestureCommander.moveToElementWithSidecar"
+ "SCRGesturePinchIn-4"
+ "SCRGesturePinchOut-4"
+ "SCRGestureQuadTap-1"
+ "SCRGestureSidecarTap"
+ "SCRMouse.dismissMenu"
+ "SCRSidecarCommander.disable"
+ "SCRSidecarCommander.enable"
+ "SCRSidecarCommander.gestureAnnouncement"
+ "SCRSidecarCommander.moveWindowWithSidecar"
+ "SCRSidecarCommander.resizeElementWithSidecar"
+ "SCRSidecarCommander.resizeWindowWithSidecar"
+ "SCRSidecarCommander_SCRKeyboardModifierKeyCapsLock_SCRGestureRotateClockwise"
+ "SCRSidecarCommander_SCRKeyboardModifierKeyCapsLock_SCRGestureRotateCounterclockwise"
+ "SCRSidecarCommander_SCRKeyboardNumModifierKeyControlOption_SCRGestureRotateClockwise"
+ "SCRSidecarCommander_SCRKeyboardNumModifierKeyControlOption_SCRGestureRotateCounterclockwise"
+ "SCRSidecarGestureFactory.m"
+ "SCRWorkspace-Sidecar"
+ "SCRWorkspace.appExpose"
+ "SCRWorkspace.fingerIgnored.message"
+ "SCRWorkspace.launchpad"
+ "SCRWorkspace.missionControl"
+ "SCRWorkspace.nextSpace"
+ "SCRWorkspace.previousSpace"
+ "SCRWorkspace.showDesktop"
+ "SCRWorkspace.sidecarCommander.disable.already"
+ "SCRWorkspace.sidecarCommander.disable.title"
+ "SCRWorkspace.sidecarCommander.enable.already"
+ "SCRWorkspace.sidecarCommander.enable.title"
+ "Sidecar Gestures"
+ "VO took over app-owned touch sequence"
+ "com.apple.expose.awake"
+ "com.apple.expose.front.awake"
+ "com.apple.launchpad.toggle"
+ "could not cancel app-owned touch sequence, leaving it with the app"
+ "displayUUID"
+ "passing synthetic touch cancel through"
+ "posting synthetic touch cancel, children=%{private}ld"
+ "sidecar commander toggled, enabled=%{private}d"
+ "startBounds"
+ "startPosition"
+ "updateFocus: location={%{private}.1f, %{private}.1f} tracking=%{private}d app=%{private}@ hitElement=%{private}@ sidecarElement=%{private}@"
+ "updateFocus: sidecar focus changed to %{private}@"
+ "voiceover.sidecar"
+ "\u00ad"
+ "\xf0\xf0\xf01"
+ "\xf0\xf0\xf0\xf0\xf0a"
- "\xf0\xf0\xf0!"
- "\xf0\xf0\xf0\xf0\xf01"
```
