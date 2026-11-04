## ScreenSharing

> `/System/Library/PrivateFrameworks/ScreenSharing.framework/Versions/A/ScreenSharing`

```diff

 786.5.0.0.0
-  __TEXT.__text: 0x120764
-  __TEXT.__objc_methlist: 0xe9e0
-  __TEXT.__cstring: 0x2d801
-  __TEXT.__const: 0x3520
-  __TEXT.__oslogstring: 0x17b3e
+  __TEXT.__text: 0x12428c
+  __TEXT.__objc_methlist: 0xec68
+  __TEXT.__cstring: 0x2df8e
+  __TEXT.__const: 0x3580
+  __TEXT.__oslogstring: 0x17e84
   __TEXT.__gcc_except_tab: 0xd38
   __TEXT.__ustring: 0x17c
-  __TEXT.__swift5_typeref: 0xca
-  __TEXT.__swift5_fieldmd: 0x54
-  __TEXT.__constg_swiftt: 0x13c
-  __TEXT.__swift5_reflstr: 0x3e
-  __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_typeref: 0x132
+  __TEXT.__constg_swiftt: 0x1f0
+  __TEXT.__swift5_reflstr: 0xbf
+  __TEXT.__swift5_fieldmd: 0xc8
+  __TEXT.__swift5_types: 0x14
+  __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x8
-  __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x3fe8
+  __TEXT.__unwind_info: 0x40d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x6a8
-  __DATA_CONST.__objc_classlist: 0x340
+  __DATA_CONST.__objc_classlist: 0x348
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8be0
+  __DATA_CONST.__objc_selrefs: 0x8cf8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x308
   __DATA_CONST.__objc_arraydata: 0x3b8
-  __DATA_CONST.__got: 0xc78
-  __AUTH_CONST.__const: 0x1638
-  __AUTH_CONST.__cfstring: 0x7c20
-  __AUTH_CONST.__objc_const: 0x12d40
+  __DATA_CONST.__got: 0xcb0
+  __AUTH_CONST.__const: 0x16b8
+  __AUTH_CONST.__cfstring: 0x7d20
+  __AUTH_CONST.__objc_const: 0x12f70
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x16a0
-  __AUTH.__objc_data: 0x20d8
-  __AUTH.__data: 0xd8
-  __DATA.__objc_ivar: 0x10ac
-  __DATA.__data: 0x18d0
+  __AUTH_CONST.__auth_got: 0x1780
+  __AUTH.__objc_data: 0x2210
+  __AUTH.__data: 0x100
+  __DATA.__objc_ivar: 0x10c4
+  __DATA.__data: 0x1938
   __DATA.__bss: 0x90c
   __DATA.__common: 0x19
   __DATA_DIRTY.__objc_data: 0x50

   - /System/Library/PrivateFrameworks/SkyLight.framework/Versions/A/SkyLight
   - /System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities
   - /System/Library/PrivateFrameworks/TimeSync.framework/Versions/A/TimeSync
+  - /System/Library/PrivateFrameworks/UniversalHID.framework/Versions/A/UniversalHID
+  - /System/Library/PrivateFrameworks/UniversalHIDKit.framework/Versions/A/UniversalHIDKit
   - /usr/lib/libDiagnosticMessagesClient.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5704
-  Symbols:   12076
-  CStrings:  5341
+  Functions: 5776
+  Symbols:   12177
+  CStrings:  5391
 
Symbols:
+ +[SSFrameBufferView directTouchCoordinateTransformForContentSize:magnification:viewerScaleAdjustment:scrollOffset:documentSize:]
+ -[SSCallScrollView gestureRecognizer:shouldCaptureEvent:]
+ -[SSCallScrollView hidEventObserver]
+ -[SSCallScrollView isPointInScrollbar:]
+ -[SSCallScrollView processTouchEvent:]
+ -[SSCallScrollView sendHIDReportToServer:]
+ -[SSCallScrollView sendHIDReportsForEvent:]
+ -[SSCallScrollView setHidEventObserver:]
+ -[SSEventSession sendHIDReport:forDisplay:]
+ -[SSEventSession stSendHIDReport:serverDisplay:]
+ -[SSEventSession stSendHIDReportWithArguments:]
+ -[SSFrameBufferView directTouchViewerScaleAdjustment]
+ -[SSFrameBufferView grTouchDrag:recognizer:]
+ -[SSFrameBufferView hidEventObserver]
+ -[SSFrameBufferView isShowingMultipleDisplaysInCombinedWindow]
+ -[SSFrameBufferView processTouchEvent:recognizer:]
+ -[SSFrameBufferView sendHIDReportToServer:]
+ -[SSFrameBufferView sendHIDReportsForEvent:]
+ -[SSFrameBufferView serverDisplayIDForTouchEvent]
+ -[SSFrameBufferView setHidEventObserver:]
+ -[SSSession sendHIDReport:forDisplay:]
+ -[SSSession stSendHIDReport:serverDisplay:]
+ -[SSSession stSendHIDReportWithArguments:]
+ -[SSSessionView hasShownOffConsoleTouchAlert]
+ -[SSSessionView isRemoteInAbsoluteControl]
+ -[SSSessionView serverSessionIsOnConsole]
+ -[SSSessionView serverSupportsTouchInput]
+ -[SSSessionView setHasShownOffConsoleTouchAlert:]
+ -[SSSessionView showTouchInputUnsupportedAlertWithMessageKey:]
+ -[SSSessionView touchInputUnsupportedByServer]
+ -[SSSessionView touchInputUnsupportedInAbsoluteControl]
+ -[SSSessionView touchInputUnsupportedInCombinedDisplay]
+ -[SSSessionView touchInputUnsupportedOffConsole]
+ -[SSSessionView uniqueIdentifierForRemoteHost]
+ GCC_except_table102
+ GCC_except_table117
+ GCC_except_table171
+ GCC_except_table181
+ GCC_except_table199
+ GCC_except_table216
+ GCC_except_table294
+ GCC_except_table313
+ GCC_except_table315
+ GCC_except_table323
+ GCC_except_table403
+ GCC_except_table423
+ GCC_except_table424
+ GCC_except_table425
+ GCC_except_table445
+ GCC_except_table67
+ GCC_except_table87
+ _OBJC_CLASS_$_NSTouch
+ _OBJC_CLASS_$_OS_os_log
+ _OBJC_CLASS_$_SSHIDEventObserver
+ _OBJC_IVAR_$_SSCallScrollView._hidEventObserver
+ _OBJC_IVAR_$_SSFrameBufferView._hidEventObserver
+ _OBJC_IVAR_$_SSFrameBufferView.mHasNotifiedDelegateAboutUnsupportedAbsoluteControlTouch
+ _OBJC_IVAR_$_SSFrameBufferView.mHasNotifiedDelegateAboutUnsupportedCombinedDisplayTouch
+ _OBJC_IVAR_$_SSFrameBufferView.mHasNotifiedDelegateAboutUnsupportedTouch
+ _OBJC_IVAR_$_SSSessionView._hasShownOffConsoleTouchAlert
+ _OBJC_METACLASS_$_SSHIDEventObserver
+ _RFBSendHIDReport
+ __DATA_SSHIDEventObserver
+ __INSTANCE_METHODS_SSHIDEventObserver
+ __IVARS_SSHIDEventObserver
+ __METACLASS_DATA_SSHIDEventObserver
+ ___62-[SSSessionView showTouchInputUnsupportedAlertWithMessageKey:]_block_invoke
+ ___swift_memcpy16_8
+ ___swift_noop_void_return
+ _objc_msgSend$arrayForKey:
+ _objc_msgSend$beginDraggingSessionWithItems:gesture:source:
+ _objc_msgSend$currentScreenInfo
+ _objc_msgSend$directTouchCoordinateTransformForContentSize:magnification:viewerScaleAdjustment:scrollOffset:documentSize:
+ _objc_msgSend$directTouchViewerScaleAdjustment
+ _objc_msgSend$gestureRecognizer:shouldCaptureEvent:
+ _objc_msgSend$grTouchDrag:recognizer:
+ _objc_msgSend$hasShownOffConsoleTouchAlert
+ _objc_msgSend$hidEventObserver
+ _objc_msgSend$isPointInScrollbar:
+ _objc_msgSend$isRemoteInAbsoluteControl
+ _objc_msgSend$isShowingMultipleDisplaysInCombinedWindow
+ _objc_msgSend$locationInView:
+ _objc_msgSend$processEvent:
+ _objc_msgSend$processTouchEvent:
+ _objc_msgSend$processTouchEvent:recognizer:
+ _objc_msgSend$sendHIDReport:forDisplay:
+ _objc_msgSend$sendHIDReportToServer:
+ _objc_msgSend$sendHIDReportsForEvent:
+ _objc_msgSend$serverDisplayIDForTouchEvent
+ _objc_msgSend$serverSessionIsOnConsole
+ _objc_msgSend$serverSupportsTouchInput
+ _objc_msgSend$setHasShownOffConsoleTouchAlert:
+ _objc_msgSend$setHidEventObserver:
+ _objc_msgSend$showTitlebarFromTouch
+ _objc_msgSend$showTouchInputUnsupportedAlertWithMessageKey:
+ _objc_msgSend$stSendHIDReport:serverDisplay:
+ _objc_msgSend$touchInputUnsupportedByServer
+ _objc_msgSend$touchInputUnsupportedInAbsoluteControl
+ _objc_msgSend$touchInputUnsupportedInCombinedDisplay
+ _objc_msgSend$touchInputUnsupportedOffConsole
+ _objc_msgSend$touchesMatchingPhase:inView:
+ _objc_msgSend$uniqueIdentifierForRemoteHost
+ _objc_msgSend$updateCoordinateTransform:
+ _objc_retainAutoreleasedReturnValue
+ _swift_dynamicCast
+ _swift_getWitnessTable
+ _swift_isaMask
+ _swift_retain
+ _symbolic So7NSTouchCSg
+ _symbolic So8NSObjectC
+ _symbolic So9OS_os_logC
+ _symbolic _____ 12CoreGraphics7CGFloatV
+ _symbolic _____ 13ScreenSharing18SSHIDEventObserverC
+ _symbolic _____ So7CGPointV
+ _symbolic _____Sg So7CGPointV
+ _symbolic _____ySo7NSEventCG 15UniversalHIDKit13EventObserverC
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _type_layout_string So7CGPointV
- GCC_except_table101
- GCC_except_table109
- GCC_except_table168
- GCC_except_table178
- GCC_except_table196
- GCC_except_table213
- GCC_except_table284
- GCC_except_table310
- GCC_except_table312
- GCC_except_table320
- GCC_except_table393
- GCC_except_table411
- GCC_except_table415
- GCC_except_table420
- GCC_except_table435
- GCC_except_table66
- GCC_except_table86
CStrings:
+ "+[SSFrameBufferView directTouchCoordinateTransformForContentSize:magnification:viewerScaleAdjustment:scrollOffset:documentSize:]"
+ "-[SSCallScrollView gestureRecognizer:shouldCaptureEvent:]"
+ "-[SSCallScrollView processTouchEvent:]"
+ "-[SSCallScrollView sendHIDReportToServer:]"
+ "-[SSCallScrollView sendHIDReportsForEvent:]"
+ "-[SSEventSession stSendHIDReport:serverDisplay:]"
+ "-[SSEventSession stSendHIDReportWithArguments:]"
+ "-[SSFrameBufferView commonInitialization]"
+ "-[SSFrameBufferView grTouchDrag:recognizer:]"
+ "-[SSFrameBufferView processTouchEvent:recognizer:]"
+ "-[SSFrameBufferView sendHIDReportsForEvent:]"
+ "-[SSSession stSendHIDReport:serverDisplay:]"
+ "-[SSSession stSendHIDReportWithArguments:]"
+ "Error sending HIDReport %d"
+ "First touch exit of window.  isBreakoutWindow: %s dynamic drag is active: %s"
+ "HIDEventObserver"
+ "HIDReport count %ld"
+ "Invalid document dimensions: %f x %f"
+ "Invalid scale factors: scaleX=%f scaleY=%f"
+ "No HID event observer available"
+ "RFBSendHIDReport"
+ "RFBSendHIDReportCore"
+ "RFBSendHIDReportCore error %d"
+ "SSHIDEventObserver deinit"
+ "SSHIDEventObserver initialized"
+ "SSHIDEventObserver update coordinate transform: [%f, %f, %f, %f, %f, %f]"
+ "SSTouchInputUnsupported"
+ "ScreenSharing-SidecarLater"
+ "Touch on scrollbar, not capturing"
+ "activeTouchCount went negative: %ld"
+ "beginDraggingSessionWithItems:gesture: dragSession=%p recognizerState=%ld"
+ "com.apple.ScreenSharing"
+ "createHIDReportForEvent"
+ "display 0x%x event info length %hu  full message size %d"
+ "effective content size is invalid (%f x %f).  Magnification is %f, viewer scale adjustment is %f"
+ "hidReport NULL"
+ "hidReportData"
+ "no HIDReport was generated"
+ "processTouchEvent"
+ "self.cursorInside NO"
+ "self.cursorInside YES"
+ "self.hidEventObserver %p"
+ "sendHIDReportToServer %p"
+ "stSendHIDReportWithArguments %s hidReportDataLength %ld"
+ "start drag"
+ "touchInputUnsupportedAbsoluteControlMessage"
+ "touchInputUnsupportedCombinedDisplayMessage"
+ "touchInputUnsupportedMessage"
+ "touchInputUnsupportedOffConsoleMessage"
+ "touchInputUnsupportedTitle"
```
