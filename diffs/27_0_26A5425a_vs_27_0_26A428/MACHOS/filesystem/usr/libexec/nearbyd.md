## nearbyd

> `/usr/libexec/nearbyd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`

```diff

 568.0.0.0.0
-  __TEXT.__text: 0x4d9acc
+  __TEXT.__text: 0x4d2268
   __TEXT.__auth_stubs: 0x27d0
-  __TEXT.__objc_stubs: 0x13500
-  __TEXT.__init_offsets: 0x2d4
-  __TEXT.__objc_methlist: 0xdd24
-  __TEXT.__gcc_except_tab: 0x4b2d0
-  __TEXT.__const: 0x3ee118
-  __TEXT.__cstring: 0x34bc3
-  __TEXT.__objc_methname: 0x1f033
-  __TEXT.__oslogstring: 0x55122
-  __TEXT.__objc_classname: 0x1aee
-  __TEXT.__objc_methtype: 0x206da
+  __TEXT.__objc_stubs: 0x13960
+  __TEXT.__init_offsets: 0x2d8
+  __TEXT.__objc_methlist: 0xdeec
+  __TEXT.__gcc_except_tab: 0x4b944
+  __TEXT.__const: 0x3ee288
+  __TEXT.__cstring: 0x34d79
+  __TEXT.__objc_methname: 0x1f463
+  __TEXT.__oslogstring: 0x55887
+  __TEXT.__objc_classname: 0x1b5e
+  __TEXT.__objc_methtype: 0x2089a
   __TEXT.__ustring: 0x60
   __TEXT.__swift5_typeref: 0x1e8
   __TEXT.__swift5_capture: 0x114

   __TEXT.__swift5_reflstr: 0x2b5
   __TEXT.__swift5_fieldmd: 0x22c
   __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x19ec8
+  __TEXT.__unwind_info: 0x1e8b0
   __TEXT.__eh_frame: 0x48
-  __DATA_CONST.__const: 0x1d620
-  __DATA_CONST.__cfstring: 0x15120
-  __DATA_CONST.__objc_classlist: 0x560
+  __DATA_CONST.__const: 0x1d8c8
+  __DATA_CONST.__cfstring: 0x15220
+  __DATA_CONST.__objc_classlist: 0x570
   __DATA_CONST.__objc_catlist: 0x20
-  __DATA_CONST.__objc_protolist: 0x270
+  __DATA_CONST.__objc_protolist: 0x288
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0x78
-  __DATA_CONST.__objc_superrefs: 0x4e8
+  __DATA_CONST.__objc_protorefs: 0x88
+  __DATA_CONST.__objc_superrefs: 0x4f0
   __DATA_CONST.__objc_arraydata: 0x438
   __DATA_CONST.__objc_arrayobj: 0x1f8
   __DATA_CONST.__objc_intobj: 0x708
   __DATA_CONST.__objc_dictobj: 0xa0
   __DATA_CONST.__auth_got: 0x1400
-  __DATA_CONST.__got: 0x930
+  __DATA_CONST.__got: 0x948
   __DATA_CONST.__auth_ptr: 0xe0
-  __DATA.__objc_const: 0x17ee8
-  __DATA.__objc_selrefs: 0x5fd0
-  __DATA.__objc_ivar: 0x1764
-  __DATA.__objc_data: 0x3a48
-  __DATA.__data: 0x34a4
-  __DATA.__bss: 0xcd38
-  __DATA.__common: 0xdf8
+  __DATA.__objc_const: 0x18248
+  __DATA.__objc_selrefs: 0x60e0
+  __DATA.__objc_ivar: 0x1790
+  __DATA.__objc_data: 0x3ae8
+  __DATA.__data: 0x35c4
+  __DATA.__bss: 0xcd68
+  __DATA.__common: 0xe08
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21247
-  Symbols:   947
-  CStrings:  17342
+  Functions: 21370
+  Symbols:   950
+  CStrings:  17450
 
Symbols:
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_CLASS_$_NSValue
CStrings:
+ "#btproximitydatabase #devicestate, OTA device-state offset read: scanner=%s advClass=%d state=%s offset=%.1fdB"
+ "#btproximitydatabase #devicestate, angle-state offset selected: scanner=%s advClass=%d state=%s offset=%.1fdB rssiThreshold %.1f -> %.1f"
+ "#dma,CMAngleManager is not available on this device"
+ "#dma,CMAngleManager started"
+ "#dma,CMAngleManager stopped"
+ "#dma,Failed to create CMAngleManager"
+ "#dma,first client added (degree), starting monitoring"
+ "#dma,first client added (state), starting monitoring"
+ "#dma,last client removed, stopping monitoring"
+ "#dma,received angle update: state=%s, mechanicalAngleDegrees=%.1f"
+ "#dma,received invalid angle update"
+ "#dma,updated angle degrees: %.4f"
+ "#dma,updated angle state: %s"
+ "#findalgs,NRBYFindingContainer::process(const common::BodyState& bodyState) unexpectedly called but not overridden"
+ "#findalgs-channelsoundingitemfinder,process(const common::BodyState &bodyState)"
+ "#findalgs-findee, process(const common::BodyState &bodyState)"
+ "#findalgs-itemfinder,process(const common::BodyState &bodyState)"
+ "#findalgs-peoplefinder,process(const common::BodyState &bodyState)"
+ "#nrby-eng,#devicestate, cached device angle state index: %u"
+ "#nrby-eng,Get update interface angle: %.4f interfaceAngle, body uuid: %@, angleDegrees: %.4f"
+ "#nrby-eng,acceptBodyStateUpdate"
+ "#roseprovider,onCMDAStateChange,index,%u"
+ "#ses-container,Debug inject UUID: %{private}@, degrees: %.1f"
+ "#ses-container,Enable the inject device state debug path"
+ "#ses-container,Session should suspend - device angle %.4f > %.4f, suspending session"
+ "#ses-container,Suspension should end - device angle %.4f < %.4f, resuming session"
+ "#ses-container,Suspension should end, resuming session"
+ "#ses-container,UWB ranging for phone auto unlock not enable yet, return"
+ "99BD6B06-60F8-4C84-87E9-DC00E52EE31B"
+ "@\"<NIBodyIdentifiable>\""
+ "@\"CMAngleManager\""
+ "@\"NIBodyToken\""
+ "Antenna state response not of expected size"
+ "B306BF46-7EBA-48D3-A730-C667BF9799C0"
+ "Body updated: %{private}@, interfaceAngle = %{public}.0f°"
+ "BtThresholdScannerModelAdvertiserClassDeviceStateOffset"
+ "D6A60FD6-4DFA-466A-8F53-0929EF56D20B"
+ "DMA"
+ "Debug inject UUID: %{private}@, angleDegrees: %{public}.1f°"
+ "DeviceAngleNotSupported"
+ "NIBodyIdentifiable"
+ "NIBodyToken"
+ "NIDebugInjectDeviceAngleState"
+ "NIDeviceAngleSuspensionEndThreshold"
+ "NIDeviceAngleSuspensionStartThreshold"
+ "NIUUIDBodyIdentifiable"
+ "NIViewBodyIdentifiable"
+ "PRDeviceAngleStateMonitor"
+ "Set originBody: %{private}p"
+ "StateA"
+ "StateB"
+ "T@\"<NIBodyIdentifiable>\",&,N"
+ "T@\"NISession\",W,N,V_session"
+ "T@\"NSUUID\",R,N"
+ "Td,R,N"
+ "_angleManager"
+ "_bodyToken"
+ "_computeDeviceAngleAndViewBodyState"
+ "_currentDeviceViewBodyAngleState"
+ "_debugInjectFakeUUID:degrees:"
+ "_degreeHandlers"
+ "_didUpdateBody is called with an unknown body"
+ "_didUpdateBody:"
+ "_didUpdateBodyInternal:"
+ "_hasRealState"
+ "_init"
+ "_interfaceAngle"
+ "_motionBodyID"
+ "_notifyDegreeHandlersWithDegrees:"
+ "_notifyStateHandlersWithIndex:"
+ "_originBody"
+ "_session"
+ "_startUpdatingBodyToken:"
+ "_stateHandlers"
+ "_stopUpdatingBodyToken:"
+ "_systemAngelDegrees"
+ "_updateDeviceAngleDegrees:"
+ "_updateInterfaceAngle:forBodyWithUUID:"
+ "acceptBodyStateUpdate:"
+ "acceptDeviceState:"
+ "addAngleDegreesHandler:forClient:queue:deliverInitialState:"
+ "addAngleStateHandler:forClient:queue:deliverInitialState:"
+ "angleStateToIndex:"
+ "com.apple.proximity.device-angle-state-monitor"
+ "iPhone19,4"
+ "initDeviceAngleStateListener"
+ "isAngleValid"
+ "isAvailable"
+ "mechanicalAngleDegrees"
+ "originBody"
+ "removeHandlersForClient:"
+ "setOriginBody:"
+ "setSession:"
+ "setUnderlyingQueue:"
+ "sharedMonitor"
+ "startAngleUpdatesToQueue:handler:"
+ "stopAngleUpdates"
+ "teardownDeviceAngleStateListener"
+ "updateInterfaceAngle:forBodyWithUUID:angleDegrees:"
+ "v12@?0f8"
+ "v16@?0@\"CMAngle\"8"
+ "v24@0:8@\"NIBodyToken\"16"
+ "v28@0:8@\"NSUUID\"16f24"
+ "v32@0:8d16@\"NSUUID\"24"
+ "v36@0:8d16@24f32"
+ "v44@0:8@?16@24@32B40"
+ "valueWithNonretainedObject:"
+ "{optional<DeviceViewBodyAngleState>=\"\"(?=\"__null_state_\"c\"__val_\"{DeviceViewBodyAngleState=\"interfaceAngle\"{optional<double>=\"\"(?=\"__null_state_\"c\"__val_\"d)\"__engaged_\"B}\"bodyUUID\"@\"NSUUID\"\"angleDegrees\"{optional<float>=\"\"(?=\"__null_state_\"c\"__val_\"f)\"__engaged_\"B}})\"__engaged_\"B}"
+ "\xf0\xf0A1"
+ "\xf0\xf0\xc4"
- "#roseprovider,CMAM is disabled"
- "\xf0\xf0d"
```
