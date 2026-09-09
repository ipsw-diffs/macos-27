## ignition

> `/usr/lib/ignition`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__DATA.__data`

```diff

 64.0.0.0.0
-  __TEXT.__text: 0x885c
+  __TEXT.__text: 0x87e4
   __TEXT.__const: 0x188
   __TEXT.__cstring: 0x1bf1
-  __TEXT.__unwind_info: 0x440
+  __TEXT.__unwind_info: 0x490
   __DATA_CONST.__const: 0x440
   __AUTH_CONST.__const: 0x7f8
   __DATA.__data: 0x1414
Functions:
~ sub_12b0 : 108 -> 96
~ sub_2238 -> sub_222c : 152 -> 140
~ sub_2ec8 -> sub_2eb0 : 236 -> 224
~ sub_4b24 -> sub_4b00 : 92 -> 80
~ sub_6110 -> sub_60e0 : 148 -> 136
~ sub_61a4 -> sub_6168 : 780 -> 776
~ sub_7218 -> sub_71d8 : 1260 -> 1248
~ sub_7704 -> sub_76b8 : 28 -> 8
~ sub_8028 -> sub_7fc8 : 700 -> 676
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 20:40:48 PDT 2026; root:libignition-64~19252/ignition/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 20:40:48 PDT 2026; root:libignition-64~19252/ignition/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 21:44:57 PDT 2026; root:libignition-64~19270/ignition/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Tue Aug 11 21:44:57 PDT 2026; root:libignition-64~19270/ignition/RELEASE_ARM64E"
```
