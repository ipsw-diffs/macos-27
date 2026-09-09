## AEBProximityHID

> `/System/Library/Extensions/AppleBluetoothRemote.kext/Contents/PlugIns/AEBProximityHID.plugin/Contents/MacOS/AEBProximityHID`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 10400.6.0.0.0
-  __TEXT.__text: 0xf34
+  __TEXT.__text: 0xebc
   __TEXT.__auth_stubs: 0x290
   __TEXT.__objc_stubs: 0x300
   __TEXT.__objc_methlist: 0x164

   __TEXT.__cstring: 0x11
   __TEXT.__objc_classname: 0x10
   __TEXT.__objc_methtype: 0x1ad
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
~ ___23-[AEBProximityHID stop]_block_invoke : 80 -> 68
~ -[AEBProximityHID propertyForKey:] : 136 -> 124
~ -[AEBProximityHID setEventCallback:withTarget:refcon:] : 88 -> 76
~ -[AEBProximityHID generateProximityEvent:] : 196 -> 184
~ -[AEBProximityHID scheduleWithRunLoop:inMode:] : 144 -> 132
~ -[AEBProximityHID unscheduleFromRunLoop:inMode:] : 164 -> 152
```
