## AEBDeviceManagementHID

> `/System/Library/Extensions/AppleBluetoothRemote.kext/Contents/PlugIns/AEBDeviceManagementHID.plugin/Contents/MacOS/AEBDeviceManagementHID`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 10400.6.0.0.0
-  __TEXT.__text: 0xe24
+  __TEXT.__text: 0xdb8
   __TEXT.__auth_stubs: 0x250
   __TEXT.__objc_stubs: 0x240
   __TEXT.__objc_methlist: 0x140

   __TEXT.__cstring: 0x11
   __TEXT.__objc_classname: 0x17
   __TEXT.__objc_methtype: 0x1a2
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__const: 0x50
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __setProperty : 96 -> 84
~ __setEventCallback : 112 -> 100
~ __scheduleWithRunLoop : 96 -> 84
~ __unscheduleFromRunLoop : 96 -> 84
~ ___30-[AEBDeviceManagementHID stop]_block_invoke : 80 -> 68
~ -[AEBDeviceManagementHID propertyForKey:] : 136 -> 124
~ -[AEBDeviceManagementHID setEventCallback:withTarget:refcon:] : 88 -> 76
~ -[AEBDeviceManagementHID scheduleWithRunLoop:inMode:] : 144 -> 132
~ -[AEBDeviceManagementHID unscheduleFromRunLoop:inMode:] : 140 -> 128
```
