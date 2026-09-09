## smcDiagnose

> `/usr/libexec/smcDiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 162.0.7.0.0
-  __TEXT.__text: 0x4028
+  __TEXT.__text: 0x3f80
   __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x2c0
   __TEXT.__objc_methlist: 0x74

   __TEXT.__objc_methname: 0x154
   __TEXT.__objc_classname: 0xe
   __TEXT.__objc_methtype: 0x75
-  __TEXT.__unwind_info: 0x128
+  __TEXT.__unwind_info: 0x178
   __DATA_CONST.__cfstring: 0x280
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_100001184 : 32 -> 20
~ sub_100001304 -> sub_1000012f8 : 124 -> 100
~ sub_100001400 -> sub_1000013dc : 84 -> 72
~ sub_100001454 -> sub_100001424 : 84 -> 72
~ sub_1000014a8 -> sub_10000146c : 68 -> 56
~ sub_100002034 -> sub_100001fec : 200 -> 188
~ sub_1000020fc -> sub_1000020a8 : 228 -> 216
~ sub_100002244 -> sub_1000021e4 : 128 -> 116
~ sub_1000022c4 -> sub_100002258 : 272 -> 260
~ sub_1000023d4 -> sub_10000235c : 104 -> 92
~ sub_10000243c -> sub_1000023b8 : 108 -> 96
~ sub_1000024c8 -> sub_100002438 : 292 -> 280
~ sub_1000029c8 -> sub_10000292c : 732 -> 720
```
