## AEBSensorsHID

> `/System/Library/Extensions/AppleBluetoothRemote.kext/Contents/PlugIns/AEBSensorsHID.plugin/Contents/MacOS/AEBSensorsHID`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 10400.6.0.0.0
-  __TEXT.__text: 0xf24
+  __TEXT.__text: 0xeac
   __TEXT.__auth_stubs: 0x290
   __TEXT.__objc_stubs: 0x2c0
   __TEXT.__objc_methlist: 0x14c

   __TEXT.__cstring: 0x11
   __TEXT.__objc_classname: 0xe
   __TEXT.__objc_methtype: 0x1b3
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__const: 0x50
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __setProperty : 96 -> 84
~ __setEventCallback : 112 -> 100
~ __scheduleWithRunLoop : 96 -> 84
~ __unscheduleFromRunLoop : 96 -> 84
~ ___21-[AEBSensorsHID stop]_block_invoke : 80 -> 68
~ -[AEBSensorsHID propertyForKey:] : 136 -> 124
~ -[AEBSensorsHID setEventCallback:withTarget:refcon:] : 88 -> 76
~ -[AEBSensorsHID generateVendorDefinedEventWithReport:reportLength:version:] : 212 -> 200
~ -[AEBSensorsHID scheduleWithRunLoop:inMode:] : 144 -> 132
~ -[AEBSensorsHID unscheduleFromRunLoop:inMode:] : 140 -> 128
```
