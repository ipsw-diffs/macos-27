## IOStreamLib

> `/System/Library/Extensions/IOStreamFamily.kext/Contents/PlugIns/IOStreamLib.plugin/Contents/MacOS/IOStreamLib`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 120.0.0.0.0
-  __TEXT.__text: 0x16f8
+  __TEXT.__text: 0x16b0
   __TEXT.__auth_stubs: 0x1f0
   __TEXT.__gcc_except_tab: 0x34
   __TEXT.__const: 0x2a
   __TEXT.__cstring: 0x9
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x140
   __DATA_CONST.__const: 0x180
   __DATA_CONST.__auth_got: 0x100
   __DATA_CONST.__got: 0x20
Functions:
~ _IOStreamLibFactory : 164 -> 152
~ __ZN16IOStreamIUnknown13factoryAddRefEv : 160 -> 148
~ __ZN16IOStreamIUnknown14factoryReleaseEv : 176 -> 164
~ __ZN20IOStreamServiceClassD2Ev : 140 -> 128
~ __ZN20IOStreamServiceClassD0Ev : 56 -> 44
~ __ZN20IOStreamServiceClass5startEPK14__CFDictionaryj : 88 -> 76
```
