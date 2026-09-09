## mpioutil

> `/sbin/mpioutil`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 565.0.1.0.0
-  __TEXT.__text: 0x5948
+  __TEXT.__text: 0x57e0
   __TEXT.__auth_stubs: 0x4d0
   __TEXT.__objc_stubs: 0x820
   __TEXT.__init_offsets: 0x10

   __TEXT.__objc_classname: 0x24
   __TEXT.__objc_methtype: 0x156
   __TEXT.__gcc_except_tab: 0x18
-  __TEXT.__unwind_info: 0x188
+  __TEXT.__unwind_info: 0x1e8
   __DATA_CONST.__const: 0x240
   __DATA_CONST.__cfstring: 0x9c0
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ sub_1000015fc : 284 -> 272
~ sub_1000019f0 -> sub_1000019e4 : 28 -> 16
~ sub_100001a18 -> sub_100001a00 : 24 -> 12
~ sub_100001a30 -> sub_100001a0c : 28 -> 16
~ sub_100001a6c -> sub_100001a3c : 24 -> 12
~ sub_100001a84 -> sub_100001a48 : 24 -> 12
~ sub_100001a9c -> sub_100001a54 : 24 -> 12
~ sub_100001e1c -> sub_100001dc8 : 24 -> 12
~ sub_100001fb4 -> sub_100001f54 : 356 -> 344
~ sub_100002d74 -> sub_100002d08 : 52 -> 40
~ sub_100002da8 -> sub_100002d30 : 36 -> 24
~ sub_100002dcc -> sub_100002d48 : 40 -> 28
~ sub_100002df4 -> sub_100002d64 : 228 -> 216
~ sub_100002f3c -> sub_100002ea0 : 224 -> 212
~ sub_10000301c -> sub_100002f74 : 236 -> 224
~ sub_1000035e4 -> sub_100003530 : 44 -> 32
~ sub_10000365c -> sub_10000359c : 28 -> 16
~ sub_100003678 -> sub_1000035ac : 28 -> 16
~ sub_100003760 -> sub_100003688 : 24 -> 12
~ sub_100003778 -> sub_100003694 : 24 -> 12
~ sub_100003790 -> sub_1000036a0 : 24 -> 12
~ sub_100003b34 -> sub_100003a38 : 344 -> 332
~ sub_100003e20 -> sub_100003d18 : 252 -> 240
~ sub_100003f1c -> sub_100003e08 : 136 -> 124
~ sub_100003fa4 -> sub_100003e84 : 136 -> 124
~ sub_100004ea4 -> sub_100004d78 : 172 -> 160
~ sub_100004f50 -> sub_100004e18 : 136 -> 124
~ sub_100006454 -> sub_100006310 : 192 -> 180
~ sub_100006514 -> sub_1000063c4 : 252 -> 228
```
