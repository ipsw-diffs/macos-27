## fsck_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/fsck_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 331.0.0.0.0
-  __TEXT.__text: 0x10e04
+  __TEXT.__text: 0x10d00
   __TEXT.__auth_stubs: 0x420
   __TEXT.__init_offsets: 0x8
   __TEXT.__gcc_except_tab: 0x604
   __TEXT.__cstring: 0x35c9
   __TEXT.__const: 0x4f5c
-  __TEXT.__unwind_info: 0x538
+  __TEXT.__unwind_info: 0x6c8
   __DATA_CONST.__const: 0x348
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__auth_got: 0x218
Functions:
~ sub_100001b84 : 676 -> 680
~ sub_100002114 -> sub_100002118 : 192 -> 180
~ sub_100002688 -> sub_100002680 : 56 -> 44
~ sub_100002758 -> sub_100002744 : 112 -> 100
~ sub_100003600 -> sub_1000035e0 : 392 -> 380
~ sub_100003dec -> sub_100003dc0 : 96 -> 88
~ sub_100003eec -> sub_100003eb8 : 556 -> 548
~ sub_100004b3c -> sub_100004b00 : 48 -> 36
~ sub_100004b6c -> sub_100004b24 : 104 -> 96
~ sub_100004d80 -> sub_100004d30 : 96 -> 84
~ sub_100004de0 -> sub_100004d84 : 200 -> 188
~ sub_100004ea8 -> sub_100004e40 : 48 -> 36
~ sub_100004ed8 -> sub_100004e64 : 152 -> 136
~ sub_100004f70 -> sub_100004eec : 196 -> 184
~ sub_100005854 -> sub_1000057c4 : 108 -> 96
~ sub_10000590c -> sub_100005870 : 108 -> 96
~ sub_1000074c8 -> sub_100007420 : 2508 -> 2496
~ sub_100007ef0 -> sub_100007e3c : 1676 -> 1664
~ sub_100008b54 -> sub_100008a94 : 276 -> 264
~ sub_100008d64 -> sub_100008c98 : 148 -> 136
~ sub_100009834 -> sub_10000975c : 56 -> 44
~ sub_1000098f0 -> sub_10000980c : 828 -> 824
~ sub_100009c44 -> sub_100009b5c : 376 -> 372
~ sub_100009e88 -> sub_100009d9c : 56 -> 44
~ sub_10000a5b8 -> sub_10000a4c0 : 56 -> 44
~ sub_10000acd4 -> sub_10000abd0 : 132 -> 120
~ sub_10000b040 -> sub_10000af30 : 368 -> 372
~ sub_10000b2fc -> sub_10000b1f0 : 256 -> 260
~ sub_10000d94c -> sub_10000d844 : 468 -> 472
~ sub_10000db20 -> sub_10000da1c : 256 -> 260
~ sub_10000dd30 -> sub_10000dc30 : 256 -> 260
~ sub_10000dfb8 -> sub_10000debc : 172 -> 160
~ sub_10000e314 -> sub_10000e20c : 976 -> 992
~ sub_10000ec24 -> sub_10000eb2c : 1688 -> 1692
~ sub_10000f2bc -> sub_10000f1c8 : 148 -> 156
~ sub_10000ffb0 -> sub_10000fec4 : 116 -> 104
~ sub_100010d34 -> sub_100010c3c : 144 -> 132
```
