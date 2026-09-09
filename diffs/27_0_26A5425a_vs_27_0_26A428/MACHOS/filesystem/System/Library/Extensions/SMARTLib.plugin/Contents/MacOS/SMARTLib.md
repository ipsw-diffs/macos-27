## SMARTLib

> `/System/Library/Extensions/SMARTLib.plugin/Contents/MacOS/SMARTLib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 320.0.0.0.0
-  __TEXT.__text: 0xd00
+  __TEXT.__text: 0xcd0
   __TEXT.__auth_stubs: 0x130
   __TEXT.__gcc_except_tab: 0x24
   __TEXT.__cstring: 0x21
   __TEXT.__const: 0x11
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__auth_got: 0xa0
Functions:
~ _SMARTLibFactory : 156 -> 144
~ __ZN14ATASMARTClient14sFactoryAddRefEv : 152 -> 140
~ __ZN14ATASMARTClient15sFactoryReleaseEv : 176 -> 164
~ __ZN14ATASMARTClientD0Ev : 56 -> 44
```
