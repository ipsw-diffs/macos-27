## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 913.43.1.0.0
-  __TEXT.__text: 0x879d4
+  __TEXT.__text: 0x8787c
   __TEXT.__auth_stubs: 0xd70
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4

   __TEXT.__const: 0x229f8
   __TEXT.__gcc_except_tab: 0x628
   __TEXT.__objc_methname: 0xb
-  __TEXT.__unwind_info: 0x670
+  __TEXT.__unwind_info: 0xba0
   __DATA_CONST.__const: 0x5430
   __DATA_CONST.__cfstring: 0x980
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ sub_e384 : 6988 -> 6996
~ sub_1016c -> sub_10174 : 124 -> 112
~ sub_11a5c -> sub_11a58 : 6956 -> 6960
~ sub_13674 : 240 -> 232
~ sub_25c5c -> sub_25c54 : 328 -> 324
~ sub_280a4 -> sub_28098 : 600 -> 596
~ sub_282fc -> sub_282ec : 580 -> 576
~ sub_2b9dc -> sub_2b9c8 : 1064 -> 1060
~ sub_35518 -> sub_35500 : 500 -> 528
~ sub_3bb60 -> sub_3bb64 : 540 -> 504
~ sub_3bd7c -> sub_3bd5c : 7396 -> 7384
~ sub_3df30 -> sub_3df04 : 116 -> 104
~ sub_3f56c -> sub_3f534 : 29240 -> 29224
~ sub_49724 -> sub_496dc : 140 -> 128
~ sub_49b44 -> sub_49af0 : 172 -> 160
~ sub_4af90 -> sub_4af30 : 172 -> 160
~ sub_4f988 -> sub_4f91c : 2108 -> 2096
~ sub_53b48 -> sub_53ad0 : 428 -> 404
~ sub_56d1c -> sub_56c8c : 96 -> 92
~ sub_56e88 -> sub_56df4 : 616 -> 608
~ sub_5b5bc -> sub_5b520 : 460 -> 412
~ sub_611d8 -> sub_6110c : 292 -> 288
~ sub_62114 -> sub_62044 : 780 -> 744
~ sub_660b4 -> sub_65fc0 : 68 -> 64
~ sub_6612c -> sub_66034 : 48 -> 44
~ sub_676b8 -> sub_675bc : 1028 -> 1016
~ sub_68c3c -> sub_68b34 : 1096 -> 1080
~ sub_69720 -> sub_69608 : 244 -> 232
~ sub_69eb4 -> sub_69d90 : 468 -> 472
~ sub_6a088 -> sub_69f68 : 256 -> 260
~ sub_6a298 -> sub_6a17c : 256 -> 260
~ sub_6a580 -> sub_6a468 : 196 -> 192
~ sub_6a808 -> sub_6a6ec : 196 -> 192
~ sub_6a914 -> sub_6a7f4 : 2116 -> 2080
~ sub_6baac -> sub_6b968 : 2100 -> 2052
~ sub_74860 -> sub_746ec : 244 -> 240
~ sub_74b98 -> sub_74a20 : 120 -> 108
~ sub_76b08 -> sub_76984 : 1204 -> 1212
~ sub_83ec4 -> sub_83d48 : 544 -> 536
~ sub_840e4 -> sub_83f60 : 204 -> 208
~ sub_841b0 -> sub_84030 : 204 -> 208
~ sub_8427c -> sub_84100 : 276 -> 264
~ sub_84390 -> sub_84208 : 276 -> 264
~ sub_851d4 -> sub_85040 : 4004 -> 4096
~ sub_869d4 -> sub_8689c : 224 -> 220
~ sub_870b4 -> sub_86f78 : 1868 -> 1900
~ sub_87800 -> sub_876e4 : 304 -> 312
~ sub_87930 -> sub_8781c : 212 -> 204
~ sub_87bbc -> sub_87aa0 : 44 -> 32
~ sub_87be8 -> sub_87ac0 : 44 -> 32
~ sub_87c14 -> sub_87ae0 : 44 -> 32
~ sub_87c40 -> sub_87b00 : 44 -> 32
~ sub_87c6c -> sub_87b20 : 44 -> 32
CStrings:
+ "20:49:05"
- "21:53:05"
```
