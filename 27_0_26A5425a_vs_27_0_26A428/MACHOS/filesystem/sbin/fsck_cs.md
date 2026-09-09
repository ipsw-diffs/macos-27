## fsck_cs

> `/sbin/fsck_cs`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 572.0.0.0.0
-  __TEXT.__text: 0x15920
+  __TEXT.__text: 0x15784
   __TEXT.__auth_stubs: 0x880
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x500
   __TEXT.__cstring: 0x2082
   __TEXT.__gcc_except_tab: 0x334
-  __TEXT.__unwind_info: 0x500
+  __TEXT.__unwind_info: 0x5c8
   __DATA_CONST.__const: 0x248
   __DATA_CONST.__cfstring: 0x100
   __DATA_CONST.__auth_got: 0x448
Functions:
~ sub_100000998 : 132 -> 120
~ sub_100000f24 -> sub_100000f18 : 208 -> 196
~ sub_100000ff4 -> sub_100000fdc : 208 -> 196
~ sub_1000017a4 -> sub_100001780 : 484 -> 472
~ sub_100001988 -> sub_100001958 : 1704 -> 1708
~ sub_1000021b4 -> sub_100002188 : 804 -> 792
~ sub_100002dbc -> sub_100002d84 : 1864 -> 1832
~ sub_10000422c -> sub_1000041d4 : 144 -> 140
~ sub_100004340 -> sub_1000042e4 : 116 -> 112
~ sub_100005c70 -> sub_100005c10 : 92 -> 80
~ sub_100005cfc -> sub_100005c90 : 120 -> 116
~ sub_100005fd4 -> sub_100005f64 : 212 -> 200
~ sub_1000060a8 -> sub_10000602c : 72 -> 60
~ sub_100006200 -> sub_100006178 : 68 -> 56
~ sub_100006588 -> sub_1000064f4 : 248 -> 236
~ sub_100006a30 -> sub_100006990 : 368 -> 364
~ sub_100007a84 -> sub_1000079e0 : 644 -> 636
~ sub_100007d08 -> sub_100007c5c : 164 -> 152
~ sub_10000852c -> sub_100008474 : 84 -> 72
~ sub_1000085a4 -> sub_1000084e0 : 64 -> 52
~ sub_1000085e4 -> sub_100008514 : 56 -> 44
~ sub_10000861c -> sub_100008540 : 56 -> 44
~ sub_100008654 -> sub_10000856c : 56 -> 44
~ sub_10000868c -> sub_100008598 : 56 -> 44
~ sub_100009cc0 -> sub_100009bc0 : 256 -> 252
~ sub_10000a56c -> sub_10000a468 : 76 -> 64
~ sub_10000a7c4 -> sub_10000a6b4 : 168 -> 156
~ sub_10000a914 -> sub_10000a7f8 : 188 -> 184
~ sub_10000ad58 -> sub_10000ac38 : 88 -> 76
~ sub_10000ae34 -> sub_10000ad08 : 160 -> 148
~ sub_10000b370 -> sub_10000b238 : 744 -> 732
~ sub_10000bfd4 -> sub_10000be90 : 472 -> 460
~ sub_10000dfac -> sub_10000de5c : 128 -> 124
~ sub_10000e31c -> sub_10000e1c8 : 2148 -> 2144
~ sub_10000ebb8 -> sub_10000ea60 : 1004 -> 1012
~ sub_10000f4d8 -> sub_10000f388 : 256 -> 244
~ sub_10000fb88 -> sub_10000fa2c : 1780 -> 1776
~ sub_10001102c -> sub_100010ecc : 2956 -> 2952
~ sub_10001214c -> sub_100011fe8 : 480 -> 476
~ sub_100014634 -> sub_1000144cc : 240 -> 236
~ sub_1000148a8 -> sub_10001473c : 644 -> 632
~ sub_100014c84 -> sub_100014b0c : 164 -> 160
~ sub_1000155b4 -> sub_100015438 : 680 -> 668
~ sub_1000158a0 -> sub_100015718 : 144 -> 140
~ sub_100015c88 -> sub_100015afc : 832 -> 816
```
