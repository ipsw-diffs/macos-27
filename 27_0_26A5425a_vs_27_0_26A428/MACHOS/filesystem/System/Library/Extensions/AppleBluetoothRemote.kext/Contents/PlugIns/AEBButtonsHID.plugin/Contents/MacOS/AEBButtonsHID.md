## AEBButtonsHID

> `/System/Library/Extensions/AppleBluetoothRemote.kext/Contents/PlugIns/AEBButtonsHID.plugin/Contents/MacOS/AEBButtonsHID`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 10400.6.0.0.0
-  __TEXT.__text: 0x132c
+  __TEXT.__text: 0x12c0
   __TEXT.__auth_stubs: 0x2a0
   __TEXT.__objc_stubs: 0x340
   __TEXT.__objc_methlist: 0x188

   __TEXT.__oslogstring: 0x3f
   __TEXT.__objc_classname: 0xe
   __TEXT.__objc_methtype: 0x1a2
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xf8
   __DATA_CONST.__const: 0x50
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ __setProperty : 96 -> 84
~ __setEventCallback : 112 -> 100
~ __scheduleWithRunLoop : 96 -> 84
~ __unscheduleFromRunLoop : 96 -> 84
~ ___21-[AEBButtonsHID stop]_block_invoke : 80 -> 68
~ -[AEBButtonsHID propertyForKey:] : 136 -> 124
~ -[AEBButtonsHID setEventCallback:withTarget:refcon:] : 88 -> 76
~ -[AEBButtonsHID scheduleWithRunLoop:inMode:] : 144 -> 132
~ -[AEBButtonsHID unscheduleFromRunLoop:inMode:] : 192 -> 180
```
