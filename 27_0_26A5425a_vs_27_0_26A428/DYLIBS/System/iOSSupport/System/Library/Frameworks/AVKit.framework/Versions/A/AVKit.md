## AVKit

> `/System/iOSSupport/System/Library/Frameworks/AVKit.framework/Versions/A/AVKit`

```diff

 1360.75.5.3.0
-  __TEXT.__text: 0x15fe28
-  __TEXT.__objc_methlist: 0x19310
+  __TEXT.__text: 0x160fc0
+  __TEXT.__objc_methlist: 0x193e0
   __TEXT.__dlopen_cstrs: 0x58
   __TEXT.__const: 0x2270
   __TEXT.__constg_swiftt: 0x9d0

   __TEXT.__swift5_assocty: 0x138
   __TEXT.__swift5_proto: 0x88
   __TEXT.__swift5_types: 0x70
-  __TEXT.__cstring: 0xc2cc
+  __TEXT.__cstring: 0xc354
   __TEXT.__swift5_capture: 0x448
   __TEXT.__swift_as_entry: 0x38
   __TEXT.__swift_as_cont: 0x50
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift5_protos: 0x20
-  __TEXT.__gcc_except_tab: 0x3678
-  __TEXT.__oslogstring: 0x4d7c
+  __TEXT.__gcc_except_tab: 0x3690
+  __TEXT.__oslogstring: 0x4dba
   __TEXT.__ustring: 0x3c
-  __TEXT.__unwind_info: 0x5cd8
+  __TEXT.__unwind_info: 0x5d18
   __TEXT.__eh_frame: 0xc28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x2670
-  __DATA_CONST.__objc_classlist: 0x868
+  __DATA_CONST.__objc_classlist: 0x878
   __DATA_CONST.__objc_catlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x460
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa870
+  __DATA_CONST.__objc_selrefs: 0xa8d8
   __DATA_CONST.__objc_protorefs: 0x78
-  __DATA_CONST.__objc_superrefs: 0x688
+  __DATA_CONST.__objc_superrefs: 0x698
   __DATA_CONST.__objc_arraydata: 0x168
-  __DATA_CONST.__got: 0xff8
+  __DATA_CONST.__got: 0x1060
   __AUTH_CONST.__const: 0x3050
-  __AUTH_CONST.__cfstring: 0x59a0
-  __AUTH_CONST.__objc_const: 0x2dfc0
+  __AUTH_CONST.__cfstring: 0x5a00
+  __AUTH_CONST.__objc_const: 0x2e298
   __AUTH_CONST.__objc_intobj: 0x4f8
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x210
-  __AUTH_CONST.__auth_got: 0xf30
-  __AUTH.__objc_data: 0x4af0
+  __AUTH_CONST.__auth_got: 0xf48
+  __AUTH.__objc_data: 0x4b90
   __AUTH.__data: 0x3e8
-  __DATA.__objc_ivar: 0x28b8
-  __DATA.__data: 0x3a30
+  __DATA.__objc_ivar: 0x28e8
+  __DATA.__data: 0x3a40
   __DATA.__bss: 0x14c8
   __DATA.__common: 0xe8
   __DATA_DIRTY.__objc_data: 0x1128

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9509
-  Symbols:   20111
-  CStrings:  1674
+  Functions: 9526
+  Symbols:   20181
+  CStrings:  1679
 
Symbols:
+ +[AVCaptureDeviceStates stateWithStateADeviceIDs:stateBDeviceIDs:]
+ -[AVCaptureDeviceStateCoordinator .cxx_destruct]
+ -[AVCaptureDeviceStateCoordinator _updateCurrentState:]
+ -[AVCaptureDeviceStateCoordinator dealloc]
+ -[AVCaptureDeviceStateCoordinator deviceState]
+ -[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]
+ -[AVCaptureDeviceStateCoordinator observeValueForKeyPath:ofObject:change:context:]
+ -[AVCaptureDeviceStates .cxx_destruct]
+ -[AVCaptureDeviceStates _initWithStateADeviceIDs:stateBDeviceIDs:]
+ -[AVCaptureDeviceStates debugDescription]
+ -[AVCaptureDeviceStates description]
+ -[AVCaptureDeviceStates hash]
+ -[AVCaptureDeviceStates isEqual:]
+ -[AVCaptureDeviceStates stateADeviceIDs]
+ -[AVCaptureDeviceStates stateBDeviceIDs]
+ GCC_except_table7460
+ GCC_except_table7479
+ GCC_except_table7554
+ GCC_except_table7686
+ GCC_except_table7688
+ GCC_except_table7702
+ GCC_except_table7937
+ GCC_except_table7943
+ GCC_except_table8082
+ GCC_except_table8104
+ GCC_except_table8232
+ GCC_except_table8239
+ GCC_except_table8253
+ GCC_except_table8453
+ GCC_except_table8454
+ GCC_except_table8458
+ GCC_except_table8466
+ GCC_except_table8502
+ GCC_except_table8524
+ GCC_except_table8578
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._bostonDevices
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._currentState
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._handler
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._isRenoSuspended
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._lock
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._otherDevices
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._queue
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._renoCamera
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._renoDevices
+ OBJC_IVAR_$_AVCaptureDeviceStateCoordinator._types
+ OBJC_IVAR_$_AVCaptureDeviceStates._stateADeviceIDs
+ OBJC_IVAR_$_AVCaptureDeviceStates._stateBDeviceIDs
+ _AVCaptureDeviceStateCoordinatorChangedContext
+ _AVCaptureDeviceTypeBuiltInBostonUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInDualCamera
+ _AVCaptureDeviceTypeBuiltInDualWideCamera
+ _AVCaptureDeviceTypeBuiltInLiDARDepthCamera
+ _AVCaptureDeviceTypeBuiltInRenoUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInTelephotoCamera
+ _AVCaptureDeviceTypeBuiltInTripleCamera
+ _AVCaptureDeviceTypeBuiltInTrueDepthCamera
+ _AVCaptureDeviceTypeBuiltInUltraWideCamera
+ _AVCaptureDeviceTypeBuiltInWideAngleCamera
+ _NSKeyValueChangeNewKey
+ _OBJC_CLASS_$_AVCaptureDeviceDiscoverySession
+ _OBJC_CLASS_$_AVCaptureDeviceStateCoordinator
+ _OBJC_CLASS_$_AVCaptureDeviceStates
+ _OBJC_METACLASS_$_AVCaptureDeviceStateCoordinator
+ _OBJC_METACLASS_$_AVCaptureDeviceStates
+ __OBJC_$_CLASS_METHODS_AVCaptureDeviceStates
+ __OBJC_$_INSTANCE_METHODS_AVCaptureDeviceStateCoordinator
+ __OBJC_$_INSTANCE_METHODS_AVCaptureDeviceStates
+ __OBJC_$_INSTANCE_VARIABLES_AVCaptureDeviceStateCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_AVCaptureDeviceStates
+ __OBJC_$_PROP_LIST_AVCaptureDeviceStates
+ __OBJC_CLASS_RO_$_AVCaptureDeviceStateCoordinator
+ __OBJC_CLASS_RO_$_AVCaptureDeviceStates
+ __OBJC_METACLASS_RO_$_AVCaptureDeviceStateCoordinator
+ __OBJC_METACLASS_RO_$_AVCaptureDeviceStates
+ ___68-[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]_block_invoke
+ ___82-[AVCaptureDeviceStateCoordinator observeValueForKeyPath:ofObject:change:context:]_block_invoke
+ _dispatch_assert_queue$V2
+ _objc_msgSend$_initWithStateADeviceIDs:stateBDeviceIDs:
+ _objc_msgSend$_updateCurrentState:
+ _objc_msgSend$addObserver:forKeyPath:options:context:
+ _objc_msgSend$devices
+ _objc_msgSend$discoverySessionWithDeviceTypes:mediaType:position:
+ _objc_msgSend$removeObserver:forKeyPath:
+ _objc_msgSend$stateADeviceIDs
+ _objc_msgSend$stateBDeviceIDs
+ _objc_msgSend$stateWithStateADeviceIDs:stateBDeviceIDs:
+ _objc_msgSend$uniqueID
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- GCC_except_table7462
- GCC_except_table7537
- GCC_except_table7669
- GCC_except_table7671
- GCC_except_table7685
- GCC_except_table7920
- GCC_except_table7926
- GCC_except_table8065
- GCC_except_table8087
- GCC_except_table8215
- GCC_except_table8222
- GCC_except_table8236
- GCC_except_table8420
- GCC_except_table8436
- GCC_except_table8441
- GCC_except_table8449
- GCC_except_table8485
- GCC_except_table8507
- GCC_except_table8561
CStrings:
+ "%s Initialized AVCaptureDeviceStateCoordinator for UIView: %@"
+ "-[AVCaptureDeviceStateCoordinator initWithView:types:queue:handler:]"
+ "<%@: %p %@>"
+ "stateADeviceIDs: %@, stateBDeviceIDs: %@"
+ "suspended"
```
