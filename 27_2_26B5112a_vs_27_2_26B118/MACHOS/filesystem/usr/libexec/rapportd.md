## rapportd

> `/usr/libexec/rapportd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 751.200.83.0.0
-  __TEXT.__text: 0x189964
+  __TEXT.__text: 0x189a60
   __TEXT.__auth_stubs: 0x3560
   __TEXT.__objc_stubs: 0x12940
   __TEXT.__objc_methlist: 0x9d10
   __TEXT.__const: 0x66a0
-  __TEXT.__cstring: 0x36ea6
+  __TEXT.__cstring: 0x37296
   __TEXT.__objc_classname: 0x103f
   __TEXT.__objc_methtype: 0x4991
   __TEXT.__gcc_except_tab: 0x246c

   __TEXT.__unwind_info: 0x6ef8
   __TEXT.__eh_frame: 0x4bfc
   __DATA_CONST.__const: 0x8390
-  __DATA_CONST.__cfstring: 0x9cc0
+  __DATA_CONST.__cfstring: 0x9f60
   __DATA_CONST.__objc_classlist: 0x398
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x170

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 8228
   Symbols:   1366
-  CStrings:  10969
+  CStrings:  10990
 
Functions:
~ sub_10000f6bc : 1564 -> 1588
~ sub_10000fd10 -> sub_10000fd28 : 4396 -> 4624
CStrings:
+ "com.apple.SpeakerGroupSetup.calibrationConfiguration"
+ "com.apple.SpeakerGroupSetup.client.done"
+ "com.apple.SpeakerGroupSetup.client.invalidated"
+ "com.apple.SpeakerGroupSetup.done"
+ "com.apple.SpeakerGroupSetup.highlightPing"
+ "com.apple.SpeakerGroupSetup.ping"
+ "com.apple.SpeakerGroupSetup.playCelebration"
+ "com.apple.SpeakerGroupSetup.startScene"
+ "com.apple.SpeakerGroupSetup.stop"
+ "com.apple.SpeakerGroupSetup.stopScene"
+ "com.apple.audio.acousticcalibrationd.NetworkInterfaceRequest"
+ "com.apple.audio.acousticcalibrationd.StopSceneRequest"
+ "com.apple.audio.acousticcalibrationd.StopSessionRequest"
+ "com.apple.audio.acousticcalibrationd.collectCapturesRequest"
+ "com.apple.audio.acousticcalibrationd.derivedDataRequest"
+ "com.apple.audio.acousticcalibrationd.performTimeSyncRequest"
+ "com.apple.audio.acousticcalibrationd.prepareParticipantRequest"
+ "com.apple.audio.acousticcalibrationd.scheduleCalibrationRequest"
+ "com.apple.audio.acousticcalibrationd.setRolesRequest"
+ "requestSetupStateFromSurroundCompanions"
+ "synchSetupStateFromSurroundCompanions"
```
