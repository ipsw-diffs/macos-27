## Audio

> `/System/Library/Spotlight/Audio.mdimporter/Contents/MacOS/Audio`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

 830.0.0.0.0
-  __TEXT.__text: 0x19f8
+  __TEXT.__text: 0x19cc
   __TEXT.__auth_stubs: 0x2c0
   __TEXT.__gcc_except_tab: 0x80
   __TEXT.__cstring: 0x15f
-  __TEXT.__unwind_info: 0xc8
+  __TEXT.__unwind_info: 0xd8
   __DATA_CONST.__const: 0xc0
   __DATA_CONST.__cfstring: 0x560
   __DATA_CONST.__auth_got: 0x168
Functions:
~ sub_6d8 : 460 -> 452
~ sub_e20 -> sub_e18 : 260 -> 248
~ sub_10a8 -> sub_1094 : 136 -> 124
~ _DeallocAudioPluginType : 92 -> 80
```
