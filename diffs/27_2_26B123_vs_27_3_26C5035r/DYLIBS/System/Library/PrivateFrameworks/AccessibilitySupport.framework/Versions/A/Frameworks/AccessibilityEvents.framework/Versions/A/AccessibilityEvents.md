## AccessibilityEvents

> `/System/Library/PrivateFrameworks/AccessibilitySupport.framework/Versions/A/Frameworks/AccessibilityEvents.framework/Versions/A/AccessibilityEvents`

```diff

-455.1.5.0.0
-  __TEXT.__text: 0x15c2c
-  __TEXT.__objc_methlist: 0x2b64
-  __TEXT.__const: 0x1c8
-  __TEXT.__cstring: 0xbdf
-  __TEXT.__oslogstring: 0x326
-  __TEXT.__gcc_except_tab: 0x238
+455.1.10.0.0
+  __TEXT.__text: 0x17770
+  __TEXT.__objc_methlist: 0x2ecc
+  __TEXT.__const: 0x1d8
+  __TEXT.__cstring: 0xd5d
+  __TEXT.__oslogstring: 0x414
+  __TEXT.__gcc_except_tab: 0x2c0
   __TEXT.__ustring: 0x7e
-  __TEXT.__unwind_info: 0x910
+  __TEXT.__dlopen_cstrs: 0x6a
+  __TEXT.__unwind_info: 0x9c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x168
-  __DATA_CONST.__objc_classlist: 0x118
+  __DATA_CONST.__const: 0x180
+  __DATA_CONST.__objc_classlist: 0x128
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x19d8
-  __DATA_CONST.__objc_superrefs: 0xe8
+  __DATA_CONST.__objc_selrefs: 0x1bb8
+  __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0x78
-  __DATA_CONST.__got: 0x200
-  __AUTH_CONST.__const: 0x4f0
-  __AUTH_CONST.__cfstring: 0x1740
-  __AUTH_CONST.__objc_const: 0x7688
+  __DATA_CONST.__got: 0x220
+  __AUTH_CONST.__const: 0x540
+  __AUTH_CONST.__cfstring: 0x17a0
+  __AUTH_CONST.__objc_const: 0x81d8
   __AUTH_CONST.__objc_intobj: 0x12d8
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0xaf0
-  __DATA.__objc_ivar: 0x41c
+  __AUTH.__objc_data: 0xb90
+  __DATA.__objc_ivar: 0x474
   __DATA.__data: 0x480
-  __DATA.__bss: 0x180
+  __DATA.__bss: 0x1a0
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/Carbon.framework/Versions/A/Carbon
   - /System/Library/Frameworks/Cocoa.framework/Versions/A/Cocoa
+  - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/DFRFoundation.framework/Versions/A/DFRFoundation
   - /System/Library/PrivateFrameworks/HID.framework/Versions/A/HID
   - /System/Library/PrivateFrameworks/MultitouchSupport.framework/Versions/A/MultitouchSupport
+  - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 975
-  Symbols:   2498
-  CStrings:  230
+  Functions: 1056
+  Symbols:   2685
+  CStrings:  244
 
Symbols:
+ +[AXESidecarTouchEvent denormalizePoint:toScreen:]
+ +[AXESidecarTouchEvent displayIDForSenderID:]
+ +[AXESidecarTouchEvent displayIDForUUID:]
+ +[AXESidecarTouchEvent eventFromCGEvent:]
+ +[AXESidecarTouchEvent isSidecarTouchEvent:]
+ +[AXESidecarTouchEvent screenForDisplayID:]
+ +[AXESidecarTouchEvent sharedHIDSystemClient]
+ -[AXEEventTapManager registerSidecarTouchEventListener:listenOnly:]
+ -[AXEEventTapManager registerSidecarTouchEventListener:listenOnly:priority:]
+ -[AXEEventTapManager unregisterSidecarTouchEventListener:listenOnly:]
+ -[AXESidecarDevice .cxx_destruct]
+ -[AXESidecarDevice _activeTouchIdentities]
+ -[AXESidecarDevice _isNonSyntheticSidecarEvent:]
+ -[AXESidecarDevice _nsTouchPhaseFromEventAndUpdateTouchStatus:]
+ -[AXESidecarDevice _previousSidecarGestureEvent]
+ -[AXESidecarDevice _processTouchEvent:]
+ -[AXESidecarDevice _throttler]
+ -[AXESidecarDevice _waitingOnNewTouchEvent]
+ -[AXESidecarDevice dealloc]
+ -[AXESidecarDevice delegate]
+ -[AXESidecarDevice deviceType]
+ -[AXESidecarDevice eventCaptureStarted]
+ -[AXESidecarDevice eventTapManager:activelyTappedSidecarTouchEvent:cgEvent:withProxy:]
+ -[AXESidecarDevice initWithMinimumEventInterval:]
+ -[AXESidecarDevice init]
+ -[AXESidecarDevice screen]
+ -[AXESidecarDevice setDelegate:]
+ -[AXESidecarDevice setEventCaptureStarted:]
+ -[AXESidecarDevice setScreen:]
+ -[AXESidecarDevice set_activeTouchIdentities:]
+ -[AXESidecarDevice set_previousSidecarGestureEvent:]
+ -[AXESidecarDevice set_throttler:]
+ -[AXESidecarDevice set_waitingOnNewTouchEvent:]
+ -[AXESidecarDevice startEventCapture]
+ -[AXESidecarDevice stopEventCapture]
+ -[AXESidecarTouchEvent .cxx_destruct]
+ -[AXESidecarTouchEvent centroidLocation]
+ -[AXESidecarTouchEvent description]
+ -[AXESidecarTouchEvent displayFrame]
+ -[AXESidecarTouchEvent eventRepresentation]
+ -[AXESidecarTouchEvent fingerCount]
+ -[AXESidecarTouchEvent handInfo]
+ -[AXESidecarTouchEvent isBuiltIn]
+ -[AXESidecarTouchEvent isCancel]
+ -[AXESidecarTouchEvent isDisplayIntegrated]
+ -[AXESidecarTouchEvent isInRangeLift]
+ -[AXESidecarTouchEvent isInRange]
+ -[AXESidecarTouchEvent isLift]
+ -[AXESidecarTouchEvent isMove]
+ -[AXESidecarTouchEvent isTouchDown]
+ -[AXESidecarTouchEvent isTouchUp]
+ -[AXESidecarTouchEvent location]
+ -[AXESidecarTouchEvent screen]
+ -[AXESidecarTouchEvent setDisplayFrame:]
+ -[AXESidecarTouchEvent setEventRepresentation:]
+ -[AXESidecarTouchEvent setFingerCount:]
+ -[AXESidecarTouchEvent setHandInfo:]
+ -[AXESidecarTouchEvent setIsBuiltIn:]
+ -[AXESidecarTouchEvent setIsCancel:]
+ -[AXESidecarTouchEvent setIsDisplayIntegrated:]
+ -[AXESidecarTouchEvent setIsInRange:]
+ -[AXESidecarTouchEvent setIsInRangeLift:]
+ -[AXESidecarTouchEvent setIsLift:]
+ -[AXESidecarTouchEvent setIsMove:]
+ -[AXESidecarTouchEvent setIsTouchDown:]
+ -[AXESidecarTouchEvent setIsTouchUp:]
+ -[AXESidecarTouchEvent setLocation:]
+ -[AXESidecarTouchEvent setScreen:]
+ GCC_except_table0
+ _AccessibilityUtilitiesLibraryCore.frameworkLibrary
+ _CFUUIDCreateString
+ _CGDisplayCreateUUIDFromDisplayID
+ _CGGetActiveDisplayList
+ _CGPointZero
+ _IOHIDEventSystemClientActivate
+ _IOHIDEventSystemClientCopyServiceForRegistryID
+ _IOHIDEventSystemClientSetDispatchQueue
+ _NSStringFromRect
+ _OBJC_CLASS_$_AXESidecarDevice
+ _OBJC_CLASS_$_AXESidecarTouchEvent
+ _OBJC_CLASS_$_AXFScreenManager
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_IVAR_$_AXESidecarDevice.__activeTouchIdentities
+ _OBJC_IVAR_$_AXESidecarDevice.__previousSidecarGestureEvent
+ _OBJC_IVAR_$_AXESidecarDevice.__throttler
+ _OBJC_IVAR_$_AXESidecarDevice.__waitingOnNewTouchEvent
+ _OBJC_IVAR_$_AXESidecarDevice._delegate
+ _OBJC_IVAR_$_AXESidecarDevice._eventCaptureStarted
+ _OBJC_IVAR_$_AXESidecarDevice._screen
+ _OBJC_IVAR_$_AXESidecarTouchEvent._displayFrame
+ _OBJC_IVAR_$_AXESidecarTouchEvent._eventRepresentation
+ _OBJC_IVAR_$_AXESidecarTouchEvent._fingerCount
+ _OBJC_IVAR_$_AXESidecarTouchEvent._handInfo
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isBuiltIn
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isCancel
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isDisplayIntegrated
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isInRange
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isInRangeLift
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isLift
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isMove
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isTouchDown
+ _OBJC_IVAR_$_AXESidecarTouchEvent._isTouchUp
+ _OBJC_IVAR_$_AXESidecarTouchEvent._location
+ _OBJC_IVAR_$_AXESidecarTouchEvent._screen
+ _OBJC_METACLASS_$_AXESidecarDevice
+ _OBJC_METACLASS_$_AXESidecarTouchEvent
+ __OBJC_$_CLASS_METHODS_AXESidecarTouchEvent
+ __OBJC_$_INSTANCE_METHODS_AXESidecarDevice
+ __OBJC_$_INSTANCE_METHODS_AXESidecarTouchEvent
+ __OBJC_$_INSTANCE_VARIABLES_AXESidecarDevice
+ __OBJC_$_INSTANCE_VARIABLES_AXESidecarTouchEvent
+ __OBJC_$_PROP_LIST_AXESidecarDevice
+ __OBJC_$_PROP_LIST_AXESidecarTouchEvent
+ __OBJC_CLASS_PROTOCOLS_$_AXESidecarDevice
+ __OBJC_CLASS_RO_$_AXESidecarDevice
+ __OBJC_CLASS_RO_$_AXESidecarTouchEvent
+ __OBJC_METACLASS_RO_$_AXESidecarDevice
+ __OBJC_METACLASS_RO_$_AXESidecarTouchEvent
+ ___45+[AXESidecarTouchEvent sharedHIDSystemClient]_block_invoke
+ ___69-[AXEEventTapManager unregisterSidecarTouchEventListener:listenOnly:]_block_invoke
+ ___86-[AXESidecarDevice eventTapManager:activelyTappedSidecarTouchEvent:cgEvent:withProxy:]_block_invoke
+ ___AccessibilityUtilitiesLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32r_e5_v8?0l
+ ___getAXEventRepresentationClass_block_invoke
+ __sl_dlopen
+ _abort_report_np
+ _audit_stringAccessibilityUtilities
+ _getAXEventRepresentationClass.softClass
+ _objc_getClass
+ _objc_msgSend$_activeTouchIdentities
+ _objc_msgSend$_isNonSyntheticSidecarEvent:
+ _objc_msgSend$_previousSidecarGestureEvent
+ _objc_msgSend$_processTouchEvent:
+ _objc_msgSend$_waitingOnNewTouchEvent
+ _objc_msgSend$allScreens
+ _objc_msgSend$defaultCenter
+ _objc_msgSend$denormalizePoint:toScreen:
+ _objc_msgSend$displayFrame
+ _objc_msgSend$displayID
+ _objc_msgSend$displayIDForSenderID:
+ _objc_msgSend$displayIDForUUID:
+ _objc_msgSend$eventRepresentation
+ _objc_msgSend$eventTapManager:activelyTappedSidecarTouchEvent:cgEvent:withProxy:
+ _objc_msgSend$eventTapManager:passivelyTappedSidecarTouchEvent:withProxy:
+ _objc_msgSend$frame
+ _objc_msgSend$handInfo
+ _objc_msgSend$isBuiltIn
+ _objc_msgSend$isCancel
+ _objc_msgSend$isDisplayIntegrated
+ _objc_msgSend$isInRange
+ _objc_msgSend$isInRangeLift
+ _objc_msgSend$isLift
+ _objc_msgSend$isMove
+ _objc_msgSend$isSidecarTouchEvent:
+ _objc_msgSend$isTouchDown
+ _objc_msgSend$mainScreen
+ _objc_msgSend$now
+ _objc_msgSend$numberWithUnsignedInt:
+ _objc_msgSend$pathIndex
+ _objc_msgSend$pathLocation
+ _objc_msgSend$pathProximity
+ _objc_msgSend$paths
+ _objc_msgSend$registerSidecarTouchEventListener:listenOnly:
+ _objc_msgSend$removeObserver:
+ _objc_msgSend$representationWithHIDEvent:hidStreamIdentifier:
+ _objc_msgSend$screen
+ _objc_msgSend$screenForDisplayID:
+ _objc_msgSend$setDisplayFrame:
+ _objc_msgSend$setEventRepresentation:
+ _objc_msgSend$setFingerCount:
+ _objc_msgSend$setHandInfo:
+ _objc_msgSend$setIsBuiltIn:
+ _objc_msgSend$setIsCancel:
+ _objc_msgSend$setIsDisplayIntegrated:
+ _objc_msgSend$setIsInRange:
+ _objc_msgSend$setIsInRangeLift:
+ _objc_msgSend$setIsLift:
+ _objc_msgSend$setIsMove:
+ _objc_msgSend$setIsTouchDown:
+ _objc_msgSend$setIsTouchUp:
+ _objc_msgSend$setScreen:
+ _objc_msgSend$set_activeTouchIdentities:
+ _objc_msgSend$set_previousSidecarGestureEvent:
+ _objc_msgSend$set_waitingOnNewTouchEvent:
+ _objc_msgSend$sharedHIDSystemClient
+ _sharedHIDSystemClient.client
+ _sharedHIDSystemClient.onceToken
CStrings:
+ "%s"
+ "/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/Contents/MacOS/AccessibilityUtilities"
+ "AXEventRepresentation"
+ "AccessibilityEventTap"
+ "Failed to create IOHIDEventSystemClient"
+ "HIDSystemClient not available"
+ "No HIDServiceClient found for senderID: %llu"
+ "No NSScreen found for displayID: %u"
+ "No display found for UUID: %@"
+ "No displayUUID property on HIDService for senderID: %llu"
+ "Unable to find class %s"
+ "displayUUID"
+ "info: %@, location: (%@), %@ isBuiltIn: %hhd, isDisplayIntegrated: %hhd, fingerCount: %lu, isTouchDown: %hhd, isMove: %hhd, isLift: %hhd, isInRange: %hhd, isInRangeLift: %hhd, isCancel: %hhd"
+ "softlink:r:path:/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities"
```
