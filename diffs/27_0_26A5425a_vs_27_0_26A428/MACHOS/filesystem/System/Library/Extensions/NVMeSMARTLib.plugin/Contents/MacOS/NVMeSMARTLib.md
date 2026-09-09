## NVMeSMARTLib

> `/System/Library/Extensions/NVMeSMARTLib.plugin/Contents/MacOS/NVMeSMARTLib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 877.0.7.0.0
-  __TEXT.__text: 0x211c
+  __TEXT.__text: 0x20d4
   __TEXT.__auth_stubs: 0x1c0
   __TEXT.__gcc_except_tab: 0x24
   __TEXT.__cstring: 0x440
   __TEXT.__const: 0x12
-  __TEXT.__unwind_info: 0x110
+  __TEXT.__unwind_info: 0x180
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x340
   __DATA_CONST.__auth_got: 0xe8
Functions:
~ _SMARTLibFactory : 156 -> 144
~ __ZN15NVMeSMARTClient14sFactoryAddRefEv : 152 -> 140
~ __ZN15NVMeSMARTClient15sFactoryReleaseEv : 156 -> 144
~ __ZN15NVMeSMARTClientD0Ev : 56 -> 44
~ __ZN15NVMeSMARTClient21SetNumberValueForTypeEP14__CFDictionaryPK10__CFStringPKv12CFNumberType : 128 -> 116
~ sub_1b3c -> sub_1b00 : 24 -> 12
```
