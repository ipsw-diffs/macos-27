## sysdiagnose

> `/usr/bin/sysdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1598.0.6.0.0
-  __TEXT.__text: 0x3e84
+  __TEXT.__text: 0x3da0
   __TEXT.__auth_stubs: 0x440
   __TEXT.__objc_stubs: 0x7e0
   __TEXT.__objc_methlist: 0xbc

   __TEXT.__objc_methname: 0x5db
   __TEXT.__objc_classname: 0x12
   __TEXT.__objc_methtype: 0x5b
-  __TEXT.__unwind_info: 0x138
+  __TEXT.__unwind_info: 0x178
   __DATA_CONST.__const: 0x2f0
   __DATA_CONST.__cfstring: 0x660
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ sub_1000011ec : 120 -> 116
~ sub_1000013b0 -> sub_1000013ac : 28 -> 16
~ sub_100002a1c -> sub_100002a0c : 68 -> 56
~ sub_100002a60 -> sub_100002a44 : 788 -> 756
~ sub_100002d84 -> sub_100002d48 : 72 -> 60
~ sub_100002dcc -> sub_100002d84 : 264 -> 252
~ sub_100003394 -> sub_100003340 : 160 -> 148
~ sub_100003508 -> sub_1000034a8 : 384 -> 372
~ sub_1000038f4 -> sub_100003888 : 28 -> 16
~ sub_100003920 -> sub_1000038a8 : 36 -> 24
~ sub_100003944 -> sub_1000038c0 : 32 -> 20
~ sub_100003964 -> sub_1000038d4 : 452 -> 440
~ sub_100003b60 -> sub_100003ac4 : 68 -> 56
~ sub_100003bbc -> sub_100003b14 : 684 -> 672
~ sub_100003e68 -> sub_100003db4 : 68 -> 56
~ sub_100004324 -> sub_100004264 : 588 -> 576
~ sub_100004570 -> sub_1000044a4 : 384 -> 372
~ sub_10000470c -> sub_100004634 : 72 -> 60
```
