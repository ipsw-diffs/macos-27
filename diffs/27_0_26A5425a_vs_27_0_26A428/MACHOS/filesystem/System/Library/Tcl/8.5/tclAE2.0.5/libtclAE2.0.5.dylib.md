## libtclAE2.0.5.dylib

> `/System/Library/Tcl/8.5/tclAE2.0.5/libtclAE2.0.5.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 154.0.0.0.0
-  __TEXT.__text: 0xbaa8
+  __TEXT.__text: 0xb9ec
   __TEXT.__auth_stubs: 0x7b0
   __TEXT.__cstring: 0x1285
   __TEXT.__const: 0x68
-  __TEXT.__unwind_info: 0x228
+  __TEXT.__unwind_info: 0x2b8
   __DATA_CONST.__const: 0x38
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__auth_got: 0x3d8
Functions:
~ _SetAEAddressFromAny : 1360 -> 1356
~ _AppLaunchNotificationHandler : 100 -> 88
~ _TclaeNewAEAddressObjFromCFURL : 200 -> 188
~ _dataFromAEDesc : 1404 -> 1392
~ _TclaeInitAEDescs : 108 -> 96
~ _FreeAEDescInternalRep : 92 -> 80
~ _UpdateStringOfAEDescRef : 144 -> 132
~ _TclaeRemoveCoercionHandler : 168 -> 156
~ _TclaeRemoveEventHandler : 168 -> 156
~ _TclaeInitCoercionHandlers : 352 -> 340
~ _TclaeRemoveObjectAccessor : 168 -> 156
~ _TclaeInitObjectAccessors : 220 -> 208
~ _CFStringToTclObj : 100 -> 88
~ __CFStringToTclObj : 192 -> 180
~ _TclObjToCFString : 124 -> 112
~ _bufput : 108 -> 104
~ _hexDumpDesc : 332 -> 320
```
