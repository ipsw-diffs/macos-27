## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

```diff

-2775.20.120.0.0
-  __TEXT.__text: 0x128c25c
-  __TEXT.__objc_methlist: 0xe81c0
-  __TEXT.__const: 0x38240
-  __TEXT.__dlopen_cstrs: 0x1962
-  __TEXT.__cstring: 0xcee88
-  __TEXT.__swift5_typeref: 0x14b80
-  __TEXT.__constg_swiftt: 0x16628
+2775.20.129.0.0
+  __TEXT.__text: 0x1297c54
+  __TEXT.__objc_methlist: 0xe8858
+  __TEXT.__const: 0x38270
+  __TEXT.__dlopen_cstrs: 0x19e1
+  __TEXT.__cstring: 0xcf443
+  __TEXT.__swift5_typeref: 0x14b70
+  __TEXT.__constg_swiftt: 0x16600
   __TEXT.__swift5_builtin: 0xc58
   __TEXT.__swift5_reflstr: 0xd498
   __TEXT.__swift5_fieldmd: 0xf26c
-  __TEXT.__swift5_assocty: 0x39f0
-  __TEXT.__swift5_proto: 0x200c
+  __TEXT.__swift5_assocty: 0x3a08
+  __TEXT.__swift5_proto: 0x2014
   __TEXT.__swift5_types: 0x1370
   __TEXT.__swift5_capture: 0x5360
   __TEXT.__swift5_mpenum: 0x90
-  __TEXT.__oslogstring: 0x273bf
-  __TEXT.__gcc_except_tab: 0xd29d0
+  __TEXT.__oslogstring: 0x276a6
+  __TEXT.__gcc_except_tab: 0xd36b0
   __TEXT.__swift5_protos: 0x1c8
   __TEXT.__swift_as_entry: 0x154
   __TEXT.__swift_as_cont: 0x224

   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x74de0
+  __TEXT.__unwind_info: 0x75230
   __TEXT.__eh_frame: 0x8a1c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xbc00
-  __DATA_CONST.__objc_classlist: 0x5688
+  __DATA_CONST.__const: 0xbc88
+  __DATA_CONST.__objc_classlist: 0x56a8
   __DATA_CONST.__objc_nlclslist: 0x20
   __DATA_CONST.__objc_catlist: 0x228
   __DATA_CONST.__objc_protolist: 0x15d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x560d8
+  __DATA_CONST.__objc_selrefs: 0x56410
   __DATA_CONST.__objc_protorefs: 0x8a8
-  __DATA_CONST.__objc_superrefs: 0x4108
+  __DATA_CONST.__objc_superrefs: 0x4120
   __DATA_CONST.__objc_arraydata: 0x52f8
-  __DATA_CONST.__got: 0x6b18
-  __AUTH_CONST.__const: 0x51600
-  __AUTH_CONST.__cfstring: 0xa0b40
-  __AUTH_CONST.__objc_const: 0x122af0
+  __DATA_CONST.__got: 0x6b50
+  __AUTH_CONST.__const: 0x51688
+  __AUTH_CONST.__cfstring: 0xa0f00
+  __AUTH_CONST.__objc_const: 0x123380
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x1e78
   __AUTH_CONST.__objc_intobj: 0x2e98
   __AUTH_CONST.__objc_dictobj: 0x820
   __AUTH_CONST.__objc_doubleobj: 0x470
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0xa308
-  __AUTH.__objc_data: 0x3aaa8
-  __AUTH.__data: 0x9c50
-  __DATA.__objc_ivar: 0x83b0
-  __DATA.__data: 0x1fd38
+  __AUTH_CONST.__auth_got: 0xa320
+  __AUTH.__objc_data: 0x3aba0
+  __AUTH.__data: 0x9cf0
+  __AUTH.__thread_vars: 0x18
+  __AUTH.__thread_bss: 0x8
+  __DATA.__objc_ivar: 0x83fc
+  __DATA.__data: 0x1fdc8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x3d188
+  __DATA.__bss: 0x3d358
   __DATA.__common: 0x1673
-  __DATA_DIRTY.__objc_ivar: 0x48c0
+  __DATA_DIRTY.__objc_ivar: 0x48f8
   __DATA_DIRTY.__objc_data: 0xb680
-  __DATA_DIRTY.__data: 0x3848
-  __DATA_DIRTY.__bss: 0x8420
+  __DATA_DIRTY.__data: 0x3858
+  __DATA_DIRTY.__bss: 0x83e0
   __DATA_DIRTY.__common: 0x1c8
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accessibility.framework/Versions/A/Accessibility

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 109021
-  Symbols:   167602
-  CStrings:  27823
+  Functions: 109221
+  Symbols:   167930
+  CStrings:  27865
 
Symbols:
+ +[NSPanGestureRecognizer _mouseTranslationBeginsPan:]
+ +[NSPanGestureRecognizer _touchTranslationBeginsPan:]
+ +[NSPopover(NSPopoverBackgroundTouchTesting) _setBackgroundTouchInstallerForTesting:uninstaller:]
+ +[NSSheetEffectDimmingView dimmingViewForWindow:]
+ -[NSCell _controlCancelTracking:at:inView:]
+ -[NSCell _showsMenuOnPressAtPoint:inRect:ofView:isDirectTouch:]
+ -[NSClipView _regionForOpaqueDescendants:forMove:forUnderTitlebar:]
+ -[NSCollectionView _indexPathsBeingDragged]
+ -[NSCollectionView _isTouchItemDragRecognizer:]
+ -[NSCollectionView(NSGestureRecognizerDelegatePrivate) _isDragRecognizer:forPoint:viewFromTouch:canDragItems:]
+ -[NSColorPickerMatrixView _dragOverColorsWithGestureState:location:commitsOnBegin:]
+ -[NSColorPopoverController _isTrackableLocation:]
+ -[NSColorPopoverController _trackDragToLocation:gestureState:]
+ -[NSColorPopoverController _trackDragWithGestureState:locationInMatrixView:]
+ -[NSControl _cancelTrackingFromPoint:endingAtPoint:]
+ -[NSControl _controlCancelTracking:at:inView:]
+ -[NSControl(_NSTracking) _showsMenuOnPressAtPoint:isDirectTouch:]
+ -[NSCoreDragManager _beginDraggingSessionWithItems:fromWindow:windowLocation:clipRect:source:isDirectTouch:modifierFlags:dragType:]
+ -[NSCoreDragManager beginTouchDraggingSessionWithItems:fromWindow:windowLocation:clipRect:source:modifierFlags:]
+ -[NSDocumentDragButton _beginDeferredDraggingSessionWithGestureRecognizer:event:pasteboard:]
+ -[NSDocumentDragButton _beginDragSessionWithGestureRecognizer:pasteboard:]
+ -[NSDocumentDragButton _handleIconDragGesture:]
+ -[NSDocumentDragButton _handleWindowMoveGesture:]
+ -[NSDocumentDragButton _prepareDragSessionWithGesture:]
+ -[NSDocumentDragButton _windowDragAllowed]
+ -[NSDocumentDragButtonIconDragGestureRecognizer .cxx_destruct]
+ -[NSDocumentDragButtonIconDragGestureRecognizer isMouse]
+ -[NSDocumentDragButtonIconDragGestureRecognizer latestDraggingEvent]
+ -[NSDocumentDragButtonIconDragGestureRecognizer mouseDown:]
+ -[NSDocumentDragButtonIconDragGestureRecognizer mouseDragged:]
+ -[NSDocumentDragButtonIconDragGestureRecognizer requestDeferredDragForDragButton:preparedPasteboard:]
+ -[NSDocumentDragButtonIconDragGestureRecognizer reset]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer .cxx_destruct]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer isMouse]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer latestDraggingEvent]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer mouseDown:]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer mouseDragged:]
+ -[NSDocumentDragButtonWindowMoveGestureRecognizer reset]
+ -[NSDragContextMenuController _canDragIntoMenu]
+ -[NSDragContextMenuController _cancelDragToTrackMenu]
+ -[NSDragContextMenuController _endIfGestureRecognizerIsGone]
+ -[NSDragContextMenuController _screenLocationFromWindowLocation:]
+ -[NSDragContextMenuController _startMenuTracking]
+ -[NSDragContextMenuController _trackedGestureRecognizerChanged:]
+ -[NSDragContextMenuController canDragIntoMenu]
+ -[NSDragContextMenuController delegate]
+ -[NSDragContextMenuController draggingSession]
+ -[NSDragContextMenuController forwardEventToApp:]
+ -[NSDragContextMenuController isPresentingMenu]
+ -[NSDragContextMenuController mainMenu]
+ -[NSDragContextMenuController menuReplaysTouchesAfterAutoDismissal]
+ -[NSDragContextMenuController menuTrackingSessionDidTerminateDrag:]
+ -[NSDragContextMenuController setCanDragIntoMenu:]
+ -[NSDragContextMenuController setDelegate:]
+ -[NSDragContextMenuController setMenuReplaysTouchesAfterAutoDismissal:]
+ -[NSDragContextMenuController trackGestureRecognizer:]
+ -[NSDragContextMenuController trackingEndedAtLocation:]
+ -[NSDragContextMenuController trackingMovedToLocation:]
+ -[NSDragContextMenuController trackingSessionCanForwardEvent:toCustomMenuItem:]
+ -[NSDragContextMenuController trackingSessionDidEnd:]
+ -[NSDragContextMenuController trackingSessionDidLoseFocus]
+ -[NSDragContextMenuController trackingSessionDidStart]
+ -[NSDragContextMenuController trackingSessionWillDismissAnimated]
+ -[NSDragContextMenuController trackingWillBeginAtLocation:]
+ -[NSDraggingSession _setTrackingEndedHandler:]
+ -[NSLegacyScrollerImp _beginTouchExpansion]
+ -[NSLegacyScrollerImp _endTouchExpansion]
+ -[NSMenuTrackingSession _isTrackingContextMenu]
+ -[NSMenuTrackingSession replaysTouchesForDragAndDrop]
+ -[NSMenuTrackingSession setReplaysTouchesForDragAndDrop:]
+ -[NSPageController _handlePanGesture:]
+ -[NSPageController _panProgressForTranslation:]
+ -[NSPageController _settlePanTransitionCommitting:]
+ -[NSPageController _startPanWithTranslation:]
+ -[NSPageController _updatePanTransitionWithProgress:]
+ -[NSPanGestureRecognizer _continueAfterTrackedTouchesInPhase:withEvent:]
+ -[NSPanGestureRecognizer _fullDeltaForRecognition]
+ -[NSPanGestureRecognizer _locationOfTouches:excludingEnded:event:]
+ -[NSPanGestureRecognizer _moveLocationFromTouches:toTouches:event:]
+ -[NSPanGestureRecognizer _tracksChangesInTouchCount]
+ -[NSPopover _observeContextsOfWindows:]
+ -[NSPopover _popoverDismissalRecognizerAction:]
+ -[NSPopover _popoverGestureRecognizer:shouldBeRequiredToFailByGestureRecognizer:]
+ -[NSPopover _popoverGestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[NSPopover _uninstallBackgroundTouchMonitor]
+ -[NSPopover(NSPopoverBackgroundTouchMonitoring) _removeBackgroundTouchMonitor]
+ -[NSPopover(NSPopoverBackgroundTouchMonitoring) _updateBackgroundTouchMonitor]
+ -[NSPopoverFrame gestureRecognizer:shouldRequireFailureOfGestureRecognizer:]
+ -[NSScrollView _touchCaughtDecelerationHoldsGestureRecognizer:]
+ -[NSScrollingAnimator _reanchorMomentumCalculatorTo:]
+ -[NSScrollingAnimator catchAnimationForPossibleGesture]
+ -[NSScrollingBehavior scrollView:panGestureRecognizerCaughtTapEnded:]
+ -[NSScrollingBehaviorSingleThreadedVBL scrollView:panGestureRecognizerCaughtTapEnded:]
+ -[NSSegmentedCell _showsMenuOnPressAtPoint:inRect:ofView:isDirectTouch:]
+ -[NSSliderCell _noteTracking:at:inView:phase:canValidateValue:]
+ -[NSSliderCell cancelTrackingAt:inView:]
+ -[NSStatusItem _popUpMenuForExpandedInterfaceSession:]
+ -[NSStepper _cancelTrackingFromPoint:endingAtPoint:]
+ -[NSStepperCell cancelTrackingAt:inView:]
+ -[NSTableView _canSnapshotRowForDrag:]
+ -[NSTableView _initializeRowSnapshotDragItem:atRow:]
+ -[NSTableView _rowSnapshotBackgroundColorForRowView:]
+ -[NSTableView _safeSendDelegateCanInvokeDoubleActionForClickedRow:]
+ -[NSTableView _showContextMenuForTouchPressThatCannotDrag:]
+ -[NSTableView _tableViewGestureRecognizer:acceptsFirstTouch:event:]
+ -[NSTextAttachmentCell _sendClickInRect:ofView:atCharacterIndex:]
+ -[NSTextAttachmentCell _sendDoubleClickInRect:ofView:atCharacterIndex:]
+ -[NSTextSelectionManager _setPressGesturesReplayKeyEvents:]
+ -[NSTextView _beginDragOfTextAttachmentView:atCharacterIndex:withGesture:]
+ -[NSTextView _draggableTextAttachmentViewProviderAtPoint:characterIndex:]
+ -[NSTextView(NSPrivate) _attachmentCellRequiresMouseFallback:]
+ -[NSTitlebarView _regionForOpaqueDescendants:forMove:forUnderTitlebar:]
+ -[NSTitlebarView _touchIsInStoplightInteractionRegion:]
+ -[NSToolbarFullScreenContentView _handleRevealGestureRecognizer:]
+ -[NSToolbarFullScreenContentView gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
+ -[NSTouchDevice _lastDeliveredTimestampForTouchIdentity:targetId:]
+ -[NSTouchDevice _noteDeliveredTouchIdentities:timestamp:forTargetId:]
+ -[NSTouchDeviceTouchMap setTouchesToTimestampMap:]
+ -[NSTouchDeviceTouchMap touchesToTimestampMap]
+ -[NSView(NSDrag) beginTouchDraggingSessionWithItems:source:locationInView:modifierFlags:]
+ -[NSWindow __touchAtPointShouldDragWindow:]
+ -[NSWindow _shouldInterruptFrameAnimationsWhenParentMoves]
+ -[NSWindow _validateWindowControlActionForButtonType:sender:]
+ -[NSWindow _windowForOrdering]
+ -[NSWindow(MacCatalystDragging) _touchAtPointShouldDragWindow:]
+ -[NSWindow(NSForSwiftUI) _resizeAnchorContentLayerContextID]
+ -[NSWindow(NSForSwiftUI) _resizeAnchorContentLayerRenderID]
+ -[NSWindow(NSForSwiftUI) _resizeAnchorContentView]
+ -[NSWindow(NSForSwiftUI) _setResizeAnchorContentLayerContextID:renderID:]
+ -[NSWindow(NSForSwiftUI) _setResizeAnchorContentView:]
+ -[NSWindowAuxiliary setWindowManagerResizeAnimationIsSizeOnly:]
+ -[NSWindowAuxiliary windowManagerResizeAnimationIsSizeOnly]
+ -[_NSCollectionViewRubberband rounded]
+ -[_NSCollectionViewRubberband setRounded:]
+ -[_NSDragManager beginTouchDraggingSessionWithItems:fromWindow:windowLocation:clipRect:source:modifierFlags:]
+ -[_NSGestureRecognizerDelegateHandler _gestureRecognizer:acceptsFirstTouch:event:]
+ -[_NSHitTestResult participation]
+ -[_NSHitTestResult setParticipation:]
+ -[_NSHitTestResultBox scope]
+ -[_NSHitTestResultBox setScope:]
+ -[_NSHitTestState hasStrictHitView]
+ -[_NSHitTestState initWithPoint:rootView:]
+ -[_NSHitTestState isPointCoveredByStackingRegion]
+ -[_NSHitTestState noteReachedResult:participation:]
+ -[_NSHitTestState rootView]
+ -[_NSHitTestState setStrictHitView:]
+ -[_NSHitTestState strictHitView]
+ -[_NSPopoverDismissalGestureRecognizer _acceptsBeingFailureDependentOnGestureRecognizer:]
+ -[_NSPopoverDismissalGestureRecognizer blocksPositioningView]
+ -[_NSPopoverDismissalGestureRecognizer reset]
+ -[_NSPopoverDismissalGestureRecognizer setBlocksPositioningView:]
+ -[_NSPopoverWindow addChildWindow:ordered:]
+ -[_NSPopoverWindow removeChildWindow:]
+ -[_NSSplitViewDividerPanGestureRecognizer _shouldRecognizeForDelta:]
+ -[_NSWindowActivationGestureRecognizer _acceptsBeingFailureDependentOnGestureRecognizer:]
+ -[_NSWindowActivationGestureRecognizer acceptsFirstTouch:event:]
+ GCC_except_table1012
+ GCC_except_table1028
+ GCC_except_table1029
+ GCC_except_table1039
+ GCC_except_table1044
+ GCC_except_table1047
+ GCC_except_table1051
+ GCC_except_table1056
+ GCC_except_table1063
+ GCC_except_table1066
+ GCC_except_table1078
+ GCC_except_table1081
+ GCC_except_table1082
+ GCC_except_table1083
+ GCC_except_table1084
+ GCC_except_table1085
+ GCC_except_table1086
+ GCC_except_table1089
+ GCC_except_table1097
+ GCC_except_table1104
+ GCC_except_table1105
+ GCC_except_table1107
+ GCC_except_table1117
+ GCC_except_table1120
+ GCC_except_table1123
+ GCC_except_table1124
+ GCC_except_table1127
+ GCC_except_table1128
+ GCC_except_table1134
+ GCC_except_table1135
+ GCC_except_table1138
+ GCC_except_table1140
+ GCC_except_table1148
+ GCC_except_table1152
+ GCC_except_table1161
+ GCC_except_table1163
+ GCC_except_table1165
+ GCC_except_table1169
+ GCC_except_table1171
+ GCC_except_table1173
+ GCC_except_table1183
+ GCC_except_table1184
+ GCC_except_table1187
+ GCC_except_table1188
+ GCC_except_table1189
+ GCC_except_table1194
+ GCC_except_table1200
+ GCC_except_table1207
+ GCC_except_table1208
+ GCC_except_table1211
+ GCC_except_table1224
+ GCC_except_table1226
+ GCC_except_table1230
+ GCC_except_table1231
+ GCC_except_table1232
+ GCC_except_table1233
+ GCC_except_table1235
+ GCC_except_table1239
+ GCC_except_table1244
+ GCC_except_table1246
+ GCC_except_table1247
+ GCC_except_table1248
+ GCC_except_table1266
+ GCC_except_table1267
+ GCC_except_table1270
+ GCC_except_table1275
+ GCC_except_table1296
+ GCC_except_table1297
+ GCC_except_table1417
+ GCC_except_table1469
+ GCC_except_table1639
+ GCC_except_table1647
+ GCC_except_table1677
+ GCC_except_table1681
+ GCC_except_table1689
+ GCC_except_table569
+ GCC_except_table570
+ GCC_except_table622
+ GCC_except_table653
+ GCC_except_table697
+ GCC_except_table704
+ GCC_except_table716
+ GCC_except_table721
+ GCC_except_table737
+ GCC_except_table738
+ GCC_except_table808
+ GCC_except_table819
+ GCC_except_table824
+ GCC_except_table846
+ GCC_except_table854
+ GCC_except_table857
+ GCC_except_table871
+ GCC_except_table893
+ GCC_except_table904
+ GCC_except_table912
+ GCC_except_table918
+ GCC_except_table934
+ GCC_except_table956
+ GCC_except_table975
+ GCC_except_table999
+ HIServicesLibraryCore.frameworkLibrary
+ OBJC_IVAR_$_NSDocumentDragButton._dragSessionBegan
+ OBJC_IVAR_$_NSDragContextMenuController._canDragIntoMenu
+ OBJC_IVAR_$_NSDragContextMenuController._delegate
+ OBJC_IVAR_$_NSDragContextMenuController._dragCancellationToken
+ OBJC_IVAR_$_NSDragContextMenuController._gestureRecognizer
+ OBJC_IVAR_$_NSDragContextMenuController._menuReplaysTouchesAfterAutoDismissal
+ OBJC_IVAR_$_NSDragContextMenuController._tracksGestureRecognizer
+ OBJC_IVAR_$_NSDraggingSession._trackingEndedHandler
+ OBJC_IVAR_$_NSMenuTrackingSession._hasTouchesToReplayForDragAndDrop
+ OBJC_IVAR_$_NSMenuTrackingSession._replaysTouchesForDragAndDrop
+ OBJC_IVAR_$_NSPopover._backgroundTouchExcludedContextIDs
+ OBJC_IVAR_$_NSPopover._backgroundTouchMonitor
+ OBJC_IVAR_$_NSPopover._observedWindows
+ OBJC_IVAR_$_NSTouchDeviceTouchMap._touchesToTimestampMap
+ OBJC_IVAR_$_NSWindowAuxiliary._windowManagerResizeAnimationIsSizeOnly
+ OBJC_IVAR_$__NSHitTestResult._participation
+ OBJC_IVAR_$__NSHitTestResultBox._scope
+ OBJC_IVAR_$__NSHitTestState._hasStrictHitView
+ OBJC_IVAR_$__NSHitTestState._rootView
+ OBJC_IVAR_$__NSHitTestState._strictHitView
+ OBJC_IVAR_$__NSPageControllerPrivateData._panState
+ OBJC_IVAR_$__NSPopoverDismissalGestureRecognizer._blocksPositioningView
+ _GetApplicationIsDaemon
+ _HIServicesLibraryCore
+ _NSTextInsertionIndicatorDisableReducedFrameRateDefaultValueFunction
+ _NSToolbarViewIsSafariToolbarDefaultValueFunction
+ _OBJC_CLASS_$_NSDocumentDragButtonIconDragGestureRecognizer
+ _OBJC_CLASS_$_NSDocumentDragButtonWindowMoveGestureRecognizer
+ _OBJC_CLASS_$__NSPopoverDismissalGestureRecognizer
+ _OBJC_CLASS_$__NSSplitViewDividerPanGestureRecognizer
+ _OBJC_CLASS_$__WMCornerRadii
+ _OBJC_METACLASS_$_NSDocumentDragButtonIconDragGestureRecognizer
+ _OBJC_METACLASS_$_NSDocumentDragButtonWindowMoveGestureRecognizer
+ _OBJC_METACLASS_$__NSPopoverDismissalGestureRecognizer
+ _OBJC_METACLASS_$__NSSplitViewDividerPanGestureRecognizer
+ __44-[NSDragContextMenuController _presentMenu:]_block_invoke
+ __45-[NSPageController _startPanWithTranslation:]_block_invoke
+ __52-[NSTableView _initializeRowSnapshotDragItem:atRow:]_block_invoke
+ __63-[NSSliderCell _noteTracking:at:inView:phase:canValidateValue:]_block_invoke
+ __DATA__TtC6AppKit39WindowDragPreventionContentPathObserver
+ __IVARS__TtC6AppKit39WindowDragPreventionContentPathObserver
+ __METACLASS_DATA__TtC6AppKit39WindowDragPreventionContentPathObserver
+ __NSActivateWindowForTouch
+ __NSDraggingSessionTrackingEndedProc
+ __NSHitTestResultReportingScope
+ __NSMenuDefaultActionFlashingInDelay
+ __NSMenuDefaultActionFlashingOutDelay
+ __NSMenuThemeCloseAnimationLength
+ __NSPerformWithoutHitTestResultReporting
+ __NSPopoverCollectWindows
+ __NSPopoverUpdateExcludedContextsForWindow
+ __NSPopoverWindowLayerContextObservationContext
+ __NSViewPerformWithHitTestResultBox
+ __OBJC_$_CLASS_METHODS_NSPopover(AppKit|NSMenuItemForceReactiveTarget|NSPopoverPositioningPrivate|NSPopoverBackgroundTouchMonitoring|NSPopoverBackgroundTouchTesting|NSTransientUIElement|NSPopoverAccessibility)
+ __OBJC_$_CLASS_METHODS_NSSheetEffectDimmingView
+ __OBJC_$_CLASS_METHODS_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|MacCatalystDragging|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
+ __OBJC_$_INSTANCE_METHODS_NSDocumentDragButtonIconDragGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS_NSDocumentDragButtonWindowMoveGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS_NSPopover(AppKit|NSMenuItemForceReactiveTarget|NSPopoverPositioningPrivate|NSPopoverBackgroundTouchMonitoring|NSPopoverBackgroundTouchTesting|NSTransientUIElement|NSPopoverAccessibility)
+ __OBJC_$_INSTANCE_METHODS_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|MacCatalystDragging|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
+ __OBJC_$_INSTANCE_METHODS__NSPopoverDismissalGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS__NSSplitViewDividerPanGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES_NSDocumentDragButtonIconDragGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES_NSDocumentDragButtonWindowMoveGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES__NSPopoverDismissalGestureRecognizer
+ __OBJC_$_PROP_LIST_NSDocumentDragButtonIconDragGestureRecognizer
+ __OBJC_$_PROP_LIST_NSDocumentDragButtonWindowMoveGestureRecognizer
+ __OBJC_$_PROP_LIST__NSCollectionViewRubberband
+ __OBJC_$_PROP_LIST__NSPopoverDismissalGestureRecognizer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSMenuTrackingSessionDelegate
+ __OBJC_CLASS_PROTOCOLS_$_NSDragContextMenuController
+ __OBJC_CLASS_PROTOCOLS_$_NSPopover(AppKit|NSMenuItemForceReactiveTarget|NSPopoverPositioningPrivate|NSPopoverBackgroundTouchMonitoring|NSPopoverBackgroundTouchTesting|NSTransientUIElement|NSPopoverAccessibility)
+ __OBJC_CLASS_PROTOCOLS_$_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|MacCatalystDragging|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
+ __OBJC_CLASS_RO_$_NSDocumentDragButtonIconDragGestureRecognizer
+ __OBJC_CLASS_RO_$_NSDocumentDragButtonWindowMoveGestureRecognizer
+ __OBJC_CLASS_RO_$__NSPopoverDismissalGestureRecognizer
+ __OBJC_CLASS_RO_$__NSSplitViewDividerPanGestureRecognizer
+ __OBJC_METACLASS_RO_$_NSDocumentDragButtonIconDragGestureRecognizer
+ __OBJC_METACLASS_RO_$_NSDocumentDragButtonWindowMoveGestureRecognizer
+ __OBJC_METACLASS_RO_$__NSPopoverDismissalGestureRecognizer
+ __OBJC_METACLASS_RO_$__NSSplitViewDividerPanGestureRecognizer
+ ___38-[NSWindow _startWindowMoveWithEvent:]_block_invoke
+ ___45-[NSPageController _startPanWithTranslation:]_block_invoke
+ ___45-[NSPageController _startPanWithTranslation:]_block_invoke_2
+ ___47-[NSStatusItem _beginExpandedInterfaceSession:]_block_invoke
+ ___50-[NSStepperCell stopTracking:at:inView:mouseIsUp:]_block_invoke
+ ___51-[NSPageController _settlePanTransitionCommitting:]_block_invoke
+ ___51-[NSPageController _settlePanTransitionCommitting:]_block_invoke_2
+ ___52-[NSDragContextMenuController _rescheduleDwellTimer]_block_invoke
+ ___52-[NSStepper _cancelTrackingFromPoint:endingAtPoint:]_block_invoke
+ ___52-[NSTableView _initializeRowSnapshotDragItem:atRow:]_block_invoke
+ ___52-[NSTableView _initializeRowSnapshotDragItem:atRow:]_block_invoke_2
+ ___53-[NSTableView _rowSnapshotBackgroundColorForRowView:]_block_invoke
+ ___62-[NSColorPopoverController _trackDragToLocation:gestureState:]_block_invoke
+ ___62-[NSTextView(NSDragging) _dragSelectionWithGesture:slideBack:]_block_invoke
+ ___63-[NSSliderCell _noteTracking:at:inView:phase:canValidateValue:]_block_invoke
+ ___67-[NSColorPopoverController trackDragToScreenLocation:gestureState:]_block_invoke
+ ___74-[NSDocumentDragButton _beginDragSessionWithGestureRecognizer:pasteboard:]_block_invoke
+ ___78-[NSPopover(NSPopoverBackgroundTouchMonitoring) _updateBackgroundTouchMonitor]_block_invoke
+ ___89-[NSView(NSDrag) beginTouchDraggingSessionWithItems:source:locationInView:modifierFlags:]_block_invoke
+ ___HIServicesLibraryCore_block_invoke
+ ____NSCanTouchDragIntoMenuOverride_block_invoke
+ ____NSViewHitTestResultUsingBox_block_invoke
+ ____NSViewStrictHitViewForHitTest_block_invoke
+ ___block_descriptor_114_e8_32o40b48r56r64w_e14_v20?0f8B12B16l
+ ___block_descriptor_128_e28_v16?0"NSAnimationContext"8l
+ ___block_descriptor_48_e44_{CGPoint=dd}16?0"NSColorPickerMatrixView"8l
+ ___block_descriptor_56_e8_32o40o_e17_v16?0"NSImage"8l
+ ___block_descriptor_56_ea8_32s_e44_{CGPoint=dd}16?0"NSColorPickerMatrixView"8l
+ ___block_descriptor_64_e8_32o40o_e17_v16?0"NSImage"8l
+ ___block_descriptor_80_ea8_32s_e14_"NSArray"8?0l
+ ___block_descriptor_96_ea8_32s40r48r_e39_B40?0{CGRect={CGPoint=dd}{CGSize=dd}}8l
+ ___block_descriptor_97_e8_32o40o48o56o64o_e5_v8?0l
+ ___copy_helper_block_e8_32o40b48r56r64w
+ ___destroy_helper_block_e8_32o40b48r56r64w
+ ___getCoreDragSetTrackingEndedProcSymbolLoc_block_invoke
+ __tlv_bootstrap
+ _associated conformance 6AppKit39WindowDragPreventionContentPathObserverC7SwiftUI07TrivialfgH0AaD0fgH0
+ _audit_stringHIServices
+ _getCoreDragSetTrackingEndedProcSymbolLoc
+ _objc_msgSend$_attachmentCellRequiresMouseFallback:
+ _objc_msgSend$_beginDeferredDraggingSessionWithGestureRecognizer:event:pasteboard:
+ _objc_msgSend$_beginDragOfTextAttachmentView:atCharacterIndex:withGesture:
+ _objc_msgSend$_beginDragSessionWithGestureRecognizer:pasteboard:
+ _objc_msgSend$_beginDraggingSessionWithItems:fromWindow:windowLocation:clipRect:source:isDirectTouch:modifierFlags:dragType:
+ _objc_msgSend$_canDragIntoMenu
+ _objc_msgSend$_canSnapshotRowForDrag:
+ _objc_msgSend$_cancelDragToTrackMenu
+ _objc_msgSend$_cancelTrackingFromPoint:endingAtPoint:
+ _objc_msgSend$_continueAfterTrackedTouchesInPhase:withEvent:
+ _objc_msgSend$_controlCancelTracking:at:inView:
+ _objc_msgSend$_dragOverColorsWithGestureState:location:commitsOnBegin:
+ _objc_msgSend$_draggableTextAttachmentViewProviderAtPoint:characterIndex:
+ _objc_msgSend$_endIfGestureRecognizerIsGone
+ _objc_msgSend$_endsOnSingleTouch
+ _objc_msgSend$_fullDeltaForRecognition
+ _objc_msgSend$_handleIconDragGesture:
+ _objc_msgSend$_indexPathsBeingDragged
+ _objc_msgSend$_initializeRowSnapshotDragItem:atRow:
+ _objc_msgSend$_isDragRecognizer:forPoint:viewFromTouch:canDragItems:
+ _objc_msgSend$_isTouchItemDragRecognizer:
+ _objc_msgSend$_isTrackingContextMenu
+ _objc_msgSend$_lastDeliveredTimestampForTouchIdentity:targetId:
+ _objc_msgSend$_locationOfTouches:excludingEnded:event:
+ _objc_msgSend$_mouseTranslationBeginsPan:
+ _objc_msgSend$_moveLocationFromTouches:toTouches:event:
+ _objc_msgSend$_noteDeliveredTouchIdentities:timestamp:forTargetId:
+ _objc_msgSend$_noteTracking:at:inView:phase:canValidateValue:
+ _objc_msgSend$_panProgressForTranslation:
+ _objc_msgSend$_popUpMenuForExpandedInterfaceSession:
+ _objc_msgSend$_prepareDragSessionWithGesture:
+ _objc_msgSend$_reanchorMomentumCalculatorTo:
+ _objc_msgSend$_removeBackgroundTouchMonitor
+ _objc_msgSend$_resizeAnchorContentLayerContextID
+ _objc_msgSend$_resizeAnchorContentLayerRenderID
+ _objc_msgSend$_resizeAnchorContentView
+ _objc_msgSend$_rowSnapshotBackgroundColorForRowView:
+ _objc_msgSend$_safeSendDelegateCanInvokeDoubleActionForClickedRow:
+ _objc_msgSend$_screenLocationFromWindowLocation:
+ _objc_msgSend$_sendClickInRect:ofView:atCharacterIndex:
+ _objc_msgSend$_sendDoubleClickInRect:ofView:atCharacterIndex:
+ _objc_msgSend$_setTrackingEndedHandler:
+ _objc_msgSend$_settlePanTransitionCommitting:
+ _objc_msgSend$_shouldInterruptFrameAnimationsWhenParentMoves
+ _objc_msgSend$_showContextMenuForTouchPressThatCannotDrag:
+ _objc_msgSend$_showsMenuOnPressAtPoint:inRect:ofView:isDirectTouch:
+ _objc_msgSend$_showsMenuOnPressAtPoint:isDirectTouch:
+ _objc_msgSend$_startMenuTracking
+ _objc_msgSend$_startPanWithTranslation:
+ _objc_msgSend$_touchCaughtDecelerationHoldsGestureRecognizer:
+ _objc_msgSend$_touchIsInStoplightInteractionRegion:
+ _objc_msgSend$_touchTranslationBeginsPan:
+ _objc_msgSend$_trackDragWithGestureState:locationInMatrixView:
+ _objc_msgSend$_tracksChangesInTouchCount
+ _objc_msgSend$_updateBackgroundTouchMonitor
+ _objc_msgSend$_updatePanTransitionWithProgress:
+ _objc_msgSend$_validateWindowControlActionForButtonType:sender:
+ _objc_msgSend$_windowDragAllowed
+ _objc_msgSend$_windowForOrdering
+ _objc_msgSend$beginTouchDraggingSessionWithItems:fromWindow:windowLocation:clipRect:source:modifierFlags:
+ _objc_msgSend$blocksPositioningView
+ _objc_msgSend$catchAnimationForPossibleGesture
+ _objc_msgSend$dimmingViewForWindow:
+ _objc_msgSend$dragContextMenuController:didDismissContextMenuAutoDismissed:
+ _objc_msgSend$dragContextMenuControllerDidDisplayContextMenu:
+ _objc_msgSend$dragContextMenuControllerWillDisplayContextMenu:
+ _objc_msgSend$handoffTrackingToContextMenu:
+ _objc_msgSend$hasStrictHitView
+ _objc_msgSend$initWithMinXMinY:maxXMinY:minXMaxY:maxXMaxY:
+ _objc_msgSend$initWithPoint:rootView:
+ _objc_msgSend$initWithUniformRadius:
+ _objc_msgSend$isDismissing
+ _objc_msgSend$isHorizontal
+ _objc_msgSend$isPointCoveredByStackingRegion
+ _objc_msgSend$menuReplaysTouchesAfterAutoDismissal
+ _objc_msgSend$menuTrackingSessionDidTerminateDrag:
+ _objc_msgSend$noteReachedResult:participation:
+ _objc_msgSend$outlineView:canInvokeDoubleActionForClickedItem:
+ _objc_msgSend$participation
+ _objc_msgSend$preciseLocationX
+ _objc_msgSend$preciseLocationY
+ _objc_msgSend$requestDeferredDragForDragButton:preparedPasteboard:
+ _objc_msgSend$resizeAnchorContentDidChange
+ _objc_msgSend$scrollView:panGestureRecognizerCaughtTapEnded:
+ _objc_msgSend$setBlocksPositioningView:
+ _objc_msgSend$setParticipation:
+ _objc_msgSend$setReplaysTouchesForDragAndDrop:
+ _objc_msgSend$setRounded:
+ _objc_msgSend$setScope:
+ _objc_msgSend$setStrictHitView:
+ _objc_msgSend$setWindowManagerResizeAnimationIsSizeOnly:
+ _objc_msgSend$strictHitView
+ _objc_msgSend$tableView:canInvokeDoubleActionForClickedRow:
+ _objc_msgSend$touchesToTimestampMap
+ _objc_msgSend$trackGestureRecognizer:
+ _objc_msgSend$trackingEndedAtLocation:
+ _objc_msgSend$trackingMovedToLocation:
+ _objc_msgSend$trackingWillBeginAtLocation:
+ _objc_msgSend$windowManagerResizeAnimationIsSizeOnly
+ _sNSClampTrailingEdgeComputedValue
+ _sNSTableViewDragsRowSnapshotsComputedValue
+ _sNSTextInsertionIndicatorDisableReducedFrameRateComputedValue
+ _sNSToolbarViewIsSafariToolbarComputedValue
+ _symbolic _____ 6AppKit39WindowDragPreventionContentPathObserverC
+ _symbolic _____Sg 6AppKit39WindowDragPreventionContentPathObserverC
+ getCoreDragSetTrackingEndedProcSymbolLoc.ptr
- -[NSCollectionView _isTouchDragRecognizer:]
- -[NSDocumentDragButton _beginDragSessionWithGesture:]
- -[NSDocumentDragButton _dragBegan:]
- -[NSDocumentDragButton _handleDocumentDragButtonDelayedPressGesture:]
- -[NSDocumentDragButton _handleDocumentDragButtonGesture:]
- -[NSDocumentDragButton gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
- -[NSDocumentDragButton gestureRecognizerIsOurs:]
- -[NSDocumentDragButton interactionState]
- -[NSDocumentDragButton setInteractionState:]
- -[NSDocumentDragButtonGestureRecognizer .cxx_destruct]
- -[NSDocumentDragButtonGestureRecognizer isMouse]
- -[NSDocumentDragButtonGestureRecognizer latestDraggingEvent]
- -[NSDocumentDragButtonGestureRecognizer mouseDragged:]
- -[NSDragContextMenuController _startTrackingSession:forImpl:]
- -[NSPopover _popoverDismissalRecognizerNeverCalled:]
- -[NSSliderCell _noteTracking:at:inView:startEvent:endEvent:]
- -[NSSliderCell _noteTracking:at:inView:startEvent:endEvent:canValidateValue:]
- -[NSThemeDocumentButton gestureRecognizerIsOurs:]
- -[NSToolbarFullScreenContentView _handleTapGestureRecognizer:]
- -[NSView _setHitTestResultBox:]
- -[NSWindow _validateWindowControlActionForButtonType:]
- -[_NSHitTestResult canClaimTouch]
- -[_NSHitTestResult setCanClaimTouch:]
- -[_NSHitTestState initWithPoint:]
- -[_NSHitTestState noteReachedResult:canClaimTouch:]
- GCC_except_table1015
- GCC_except_table1018
- GCC_except_table1037
- GCC_except_table1046
- GCC_except_table1052
- GCC_except_table1060
- GCC_except_table1061
- GCC_except_table1067
- GCC_except_table1068
- GCC_except_table1092
- GCC_except_table1093
- GCC_except_table1096
- GCC_except_table1098
- GCC_except_table1099
- GCC_except_table1100
- GCC_except_table1113
- GCC_except_table1114
- GCC_except_table1115
- GCC_except_table1118
- GCC_except_table1125
- GCC_except_table1126
- GCC_except_table1129
- GCC_except_table1139
- GCC_except_table1143
- GCC_except_table1146
- GCC_except_table1150
- GCC_except_table1151
- GCC_except_table1153
- GCC_except_table1154
- GCC_except_table1156
- GCC_except_table1157
- GCC_except_table1168
- GCC_except_table1174
- GCC_except_table1176
- GCC_except_table1178
- GCC_except_table1179
- GCC_except_table1180
- GCC_except_table1191
- GCC_except_table1196
- GCC_except_table1198
- GCC_except_table1203
- GCC_except_table1205
- GCC_except_table1206
- GCC_except_table1209
- GCC_except_table1213
- GCC_except_table1216
- GCC_except_table1217
- GCC_except_table1219
- GCC_except_table1220
- GCC_except_table1234
- GCC_except_table1236
- GCC_except_table1255
- GCC_except_table1260
- GCC_except_table1263
- GCC_except_table1264
- GCC_except_table1290
- GCC_except_table1294
- GCC_except_table1414
- GCC_except_table1466
- GCC_except_table1636
- GCC_except_table1644
- GCC_except_table1674
- GCC_except_table1678
- GCC_except_table1686
- GCC_except_table616
- GCC_except_table654
- GCC_except_table687
- GCC_except_table688
- GCC_except_table698
- GCC_except_table705
- GCC_except_table706
- GCC_except_table718
- GCC_except_table728
- GCC_except_table731
- GCC_except_table746
- GCC_except_table752
- GCC_except_table772
- GCC_except_table776
- GCC_except_table826
- GCC_except_table896
- GCC_except_table909
- GCC_except_table936
- GCC_except_table958
- GCC_except_table967
- GCC_except_table968
- GCC_except_table972
- GCC_except_table981
- GCC_except_table982
- GCC_except_table997
- OBJC_IVAR_$_NSDocumentDragButtonGestureRecognizer._latestDraggingEvent
- OBJC_IVAR_$_NSMenuTrackingSession._replayTouchesForDnd
- OBJC_IVAR_$__NSHitTestResult._canClaimTouch
- _OBJC_CLASS_$_NSDocumentDragButtonGestureRecognizer
- _OBJC_METACLASS_$_NSDocumentDragButtonGestureRecognizer
- __IVARS__TtCC6AppKit18_NSCoreHostingViewP33_BA32A240C00B8297E9917CB393308F8439WindowDragPreventionContentPathObserver
- __OBJC_$_CLASS_METHODS_NSPopover
- __OBJC_$_CLASS_METHODS_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
- __OBJC_$_INSTANCE_METHODS_NSDocumentDragButtonGestureRecognizer
- __OBJC_$_INSTANCE_METHODS_NSPopover(AppKit|NSMenuItemForceReactiveTarget|NSPopoverPositioningPrivate|NSTransientUIElement|NSPopoverAccessibility)
- __OBJC_$_INSTANCE_METHODS_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
- __OBJC_$_INSTANCE_VARIABLES_NSDocumentDragButtonGestureRecognizer
- __OBJC_$_PROP_LIST_NSDocumentDragButtonGestureRecognizer
- __OBJC_CLASS_PROTOCOLS_$_NSPopover(AppKit|NSMenuItemForceReactiveTarget|NSPopoverPositioningPrivate|NSTransientUIElement|NSPopoverAccessibility)
- __OBJC_CLASS_PROTOCOLS_$_NSWindow(NSSwiftImplementation|ScrollPocketAppearanceCoordinator|NSWindow_Performance|NSWindowTabbing_Private|NSTrackingAreas|NSCursorRects|NSDrawers|NSDrawerSupportPrivate|SnapshotAnimation|Assertions|NSIPTA|NSTouchBarFinder|_NSResponderDebugging|NSWindowARC|NSSheets|NSSplitViewPreferredThicknessReset|Regions|NSStatusItemInternal|NSResponderDebug|GlassWindow|NSDisplayCycle|MotionCompatibility|NSScreenLayout|TrustedRendering|NSCarbonExtensions|NSWindow_Theme|NSWindow_Carbon|NSWindow_Scale|NSTimeMachineSupport|NSInspectorBarSupport|NSTitleRenamingSupport|NSSavelessDocumentSupport|NSWindowSharedFirstResponder|NSWindowContentsHostedInLayerSurface|NSWMWindowManagement|For_Sidecar|TelemetryAnalytics|NSPopoverClosing|NSWindowAccessibility|NSScripting|NSForSwiftUI|NSDrag|NSWindowsMenu|NSWindow_CarbonEventHandlers|NSEventRouting|NSEventRouting_Deprecated|NSGestureRecognizer_Routing|SwiftUI|NSWindow_NonARC|NSViewRoot|_NSSegmentedCellToolbarAdditions|NSUIActivityProvider|_NSWindowAnimator|NSSidecarMenu|NSFunctionRow|NSDisplayLinkInternal|NSDisplayLinkPrivate|NSDisplayLink|NSVBOpenAndSavePanels|NSPersistentUISupport|NSUserInterfaceRestoration|ScrollPockets|NSLayoutConstraintVisualization|NSRemoteWindowAccessibility|NSWindowResizing|NSSharingServicePickerToolbarItem|NSFocusEngine_Private|NSFocusEngine_Internal|NSConstraintBasedLayoutPrivate|NSConstraintBasedLayoutInternal|NSAppearanceCustomizationInternal|NSFullScreen|NSQuietSafeQuit)
- __OBJC_CLASS_RO_$_NSDocumentDragButtonGestureRecognizer
- __OBJC_METACLASS_RO_$_NSDocumentDragButtonGestureRecognizer
- ___46-[NSPopupMenuWindow closeAnimated:completion:]_block_invoke_2
- ___53-[NSDocumentDragButton _beginDragSessionWithGesture:]_block_invoke
- ___61-[NSDragContextMenuController _startTrackingSession:forImpl:]_block_invoke
- ___77-[NSSliderCell _noteTracking:at:inView:startEvent:endEvent:canValidateValue:]_block_invoke
- ___block_descriptor_128_e8_32o40b48w_e14_v20?0f8B12B16l
- _associated conformance 6AppKit18_NSCoreHostingViewC39WindowDragPreventionContentPathObserver33_BA32A240C00B8297E9917CB393308F84LLCyx_G7SwiftUI07TrivialijK0AaH0ijK0
- _objc_msgSend$_beginDragSessionWithGesture:
- _objc_msgSend$_dragBegan:
- _objc_msgSend$_handleDocumentDragButtonGesture:
- _objc_msgSend$_isTouchDragRecognizer:
- _objc_msgSend$_noteTracking:at:inView:startEvent:endEvent:
- _objc_msgSend$_noteTracking:at:inView:startEvent:endEvent:canValidateValue:
- _objc_msgSend$_startTrackingSession:forImpl:
- _objc_msgSend$_validateWindowControlActionForButtonType:
- _objc_msgSend$canClaimTouch
- _objc_msgSend$gestureRecognizerIsOurs:
- _objc_msgSend$initWithPoint:
- _objc_msgSend$noteReachedResult:canClaimTouch:
- _objc_msgSend$setCanClaimTouch:
- _objc_msgSend$setResizeAnchorContentLayer:
- _sNSCanTouchDragIntoMenuComputedValue
- _sNSMenuAllowAsyncFadeOutAnimationComputedValue
- _symbolic _____ 6AppKit18_NSCoreHostingViewC39WindowDragPreventionContentPathObserver33_BA32A240C00B8297E9917CB393308F84LLC
- _symbolic _____yx_GSg 6AppKit18_NSCoreHostingViewC39WindowDragPreventionContentPathObserver33_BA32A240C00B8297E9917CB393308F84LLC
CStrings:
+ "%x not showing deferred expanded interface menu"
+ "%{public}s Drag/gesture event, cancel touch tracking moved out of menu, current point %@, touch-began %@"
+ "%{public}s Drag/gesture event, cancel touch tracking moving away from menu, current point %@, touch-began %@, towardMenuRect = [%@, %@]"
+ "%{public}s ignoring triggerActionForItemID %@ because tracking session is dismissing"
+ "*** Ignoring exception raised while dispatching an event during a dragging session. Exception: %{private}@"
+ "*** Ignoring exception raised while receiving events during a dragging session. Exception: %{private}@"
+ ", covering"
+ "/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/Contents/MacOS/HIServices"
+ "A\x91"
+ "Cancelling touch idx:%ld tid:%ld on target 0x%lx: not delivered for %.0fms (missing from frame %ld, multiplexedMore:%{public}s)"
+ "CoreDragSetTrackingEndedProc"
+ "Disparity detected between floating group row index %@ and floating group row view %@."
+ "GestureRecognizer:acceptsFirstTouch:event:"
+ "NSClampTrailingEdge"
+ "NSCollectionView.immediateDragRecognizer"
+ "NSCollectionView.sectionScrollTouchRecognizer"
+ "NSCollectionView.touchBandSelectRecognizer"
+ "NSCollectionView.touchItemDragRecognizer"
+ "NSCollectionView.twoFingerSelectRecognizer"
+ "NSCollectionViewScalesLiftedDragImage"
+ "NSDocumentDragButton.iconDragGestureRecognizer"
+ "NSDocumentDragButton.windowMoveGestureRecognizer"
+ "NSDragContextMenuController.m"
+ "NSDraggingSession.m"
+ "NSPageControllerPanAxisLockDistance"
+ "NSPageControllerPanMinProgressForSuccessfulSwipe"
+ "NSPageControllerPanMinVelocityForSuccessfulSwipe"
+ "NSPageControllerPanTwitchAvoidanceProgress"
+ "NSTableViewDragsRowSnapshots"
+ "NSTextInsertionIndicatorDisableReducedFrameRate"
+ "NSThemeDocumentButton.modifierLeftPressGestureRecognizer"
+ "NSThemeDocumentButton.rightPressGestureRecognizer"
+ "NSToolbarFullScreenContentView.pressGestureRecognizer"
+ "NSToolbarTitleView.dragDocumentIconGestureRecognizer"
+ "NSToolbarTitleView.longPressGestureRecognizer"
+ "NSToolbarTitleView.tapToToggleExpandedStateGestureRecognizer"
+ "NSToolbarViewIsSafariToolbar"
+ "OSStatus _soft_CoreDragSetTrackingEndedProc(CoreDragRef, void *, void *)"
+ "PXMPro.PhotoEditViewPageControlsView"
+ "Tracking driven by the -tracking... methods needs a delegate to hand off tracking to the presented context menu."
+ "UnifiedField"
+ "UnifiedTabBar"
+ "Where a hit-test would land without forgiveness, to tell which containers cover it"
+ "_NSMenuDefaultActionFlashingInDelay"
+ "_NSMenuDefaultActionFlashingOutDelay"
+ "_NSMenuThemeCloseAnimationLength"
+ "com.pixelmatorteam.pixelmator.touch.x.photo"
+ "com.roblox.RobloxPlayer"
+ "identity"
+ "slider tracking cancelled"
+ "softlink:r:path:/System/Library/Frameworks/ApplicationServices.framework/Versions/A/Frameworks/HIServices.framework/HIServices"
+ "stepper tracking cancelled"
+ "touch (resumed)"
+ "void *HIServicesLibrary(void)"
+ "{CGPoint=dd}16@?0@\"NSColorPickerMatrixView\"8"
- "%f Missing Touches."
- "%{public}s Drag/gesture event, cancel touch tracking moving away from menu, current point %@, touch-began %@"
- "-[NSEvent _initDigitizerTouchesFromIOHidEvent:window:windowIsViewBridged:contextID:]"
- "A\x81"
- "NSCollectionView pan drag"
- "NSCollectionView press drag"
- "NSCollectionView section scroll"
- "NSCollectionView touch drag"
- "NSCollectionView touch select"
- "NSToolbarFullScreenContentView.tapGestureRecognizer"
- "Popover dismissal gesture recognizer action should never be called"
- "R6"
- "\xf0Q"
```
