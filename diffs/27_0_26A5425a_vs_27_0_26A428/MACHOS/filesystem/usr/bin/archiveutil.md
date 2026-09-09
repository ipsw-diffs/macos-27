## archiveutil

> `/usr/bin/archiveutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 183.0.0.0.0
-  __TEXT.__text: 0x4904
+  __TEXT.__text: 0x4648
   __TEXT.__auth_stubs: 0x750
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__objc_methlist: 0x104

   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x10
-  __TEXT.__unwind_info: 0x1c0
+  __TEXT.__unwind_info: 0x238
   __TEXT.__eh_frame: 0x198
   __DATA_CONST.__const: 0x1f0
   __DATA_CONST.__cfstring: 0x20
Functions:
~ sub_1000013f8 : 204 -> 192
~ sub_1000014c4 -> sub_1000014b8 : 136 -> 124
~ sub_100001710 -> sub_1000016f8 : 132 -> 120
~ sub_10000196c -> sub_100001948 : 5172 -> 5028
~ sub_100002da0 -> sub_100002cec : 304 -> 252
~ sub_100002ed0 -> sub_100002de8 : 1664 -> 1652
~ sub_100003550 -> sub_10000345c : 556 -> 544
~ sub_100003830 -> sub_100003730 : 1000 -> 960
~ sub_100003cdc -> sub_100003bb4 : 60 -> 48
~ sub_100003d18 -> sub_100003be4 : 60 -> 48
~ sub_100003d54 -> sub_100003c14 : 120 -> 108
~ sub_100003dcc -> sub_100003c80 : 152 -> 140
~ sub_100003e64 -> sub_100003d0c : 244 -> 192
~ sub_100003f7c -> sub_100003df0 : 148 -> 136
~ sub_1000043f0 -> sub_100004258 : 68 -> 56
~ sub_100004588 -> sub_1000043e4 : 192 -> 180
~ sub_100004648 -> sub_100004498 : 292 -> 240
~ sub_100004910 -> sub_10000472c : 56 -> 36
~ sub_10000499c -> sub_1000047a4 : 100 -> 80
~ sub_100004a4c -> sub_100004840 : 68 -> 48
~ sub_100004aa4 -> sub_100004884 : 112 -> 100
~ sub_100004b28 -> sub_1000048fc : 116 -> 104
~ sub_100004ecc -> sub_100004c94 : 84 -> 72
~ sub_100005090 -> sub_100004e4c : 188 -> 176
~ sub_1000054f8 -> sub_1000052a8 : 208 -> 176
~ sub_1000055c8 -> sub_100005358 : 144 -> 112
~ sub_100005674 -> sub_1000053e4 : 56 -> 44
~ sub_1000056ac -> sub_100005410 : 64 -> 52
~ sub_10000588c -> sub_1000055e4 : 68 -> 48
```
