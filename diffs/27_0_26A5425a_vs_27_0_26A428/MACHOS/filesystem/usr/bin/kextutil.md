## kextutil

> `/usr/bin/kextutil`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 784.0.0.0.0
-  __TEXT.__text: 0x9934
+  __TEXT.__text: 0x9874
   __TEXT.__auth_stubs: 0xd80
   __TEXT.__objc_stubs: 0x4c0
   __TEXT.__cstring: 0x325f

   __TEXT.__gcc_except_tab: 0x84
   __TEXT.__oslogstring: 0x2a
   __TEXT.__objc_methname: 0x334
-  __TEXT.__unwind_info: 0x188
+  __TEXT.__unwind_info: 0x1f0
   __DATA_CONST.__cfstring: 0xe60
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x78
Functions:
~ sub_100002530 : 1080 -> 1068
~ sub_100002968 -> sub_10000295c : 68 -> 56
~ sub_100004bd0 -> sub_100004bb8 : 452 -> 440
~ sub_100004eb8 -> sub_100004e94 : 320 -> 308
~ sub_100004ff8 -> sub_100004fc8 : 448 -> 436
~ sub_1000053c0 -> sub_100005384 : 120 -> 108
~ sub_100005458 -> sub_100005410 : 164 -> 152
~ sub_100005ccc -> sub_100005c78 : 104 -> 92
~ sub_100005fc0 -> sub_100005f60 : 128 -> 116
~ sub_100006040 -> sub_100005fd4 : 196 -> 184
~ sub_100006104 -> sub_10000608c : 596 -> 584
~ sub_100006d70 -> sub_100006cec : 104 -> 92
~ sub_1000076d8 -> sub_100007648 : 484 -> 460
~ sub_100009328 -> sub_100009280 : 140 -> 128
~ sub_100009b68 -> sub_100009ab4 : 128 -> 116
```
