## IOUSBLib

> `/System/Library/Extensions/IOUSBHostFamily.kext/Contents/PlugIns/IOUSBLib.bundle/Contents/MacOS/IOUSBLib`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 1617.0.12.0.0
-  __TEXT.__text: 0x7f44
+  __TEXT.__text: 0x7edc
   __TEXT.__auth_stubs: 0x370
   __TEXT.__cstring: 0x21d
   __TEXT.__const: 0x74
   __TEXT.__gcc_except_tab: 0x7c
-  __TEXT.__unwind_info: 0x1d0
+  __TEXT.__unwind_info: 0x278
   __DATA_CONST.__const: 0x490
   __DATA_CONST.__cfstring: 0x320
   __DATA_CONST.__auth_got: 0x1c0
Functions:
~ _IOUSBLibFactory : 264 -> 240
~ __ZN13IOUSBIUnknown13factoryAddRefEv : 152 -> 140
~ __ZN13IOUSBIUnknown14factoryReleaseEv : 156 -> 144
~ __ZN13IOUSBIUnknown24_versionNumberFromStringEPK10__CFString : 540 -> 532
~ __ZN16IOUSBDeviceClassD2Ev : 232 -> 220
~ __ZN16IOUSBDeviceClassD0Ev : 108 -> 96
~ __ZN19IOUSBInterfaceClassD2Ev : 256 -> 244
~ __ZN19IOUSBInterfaceClassD0Ev : 108 -> 96
```
