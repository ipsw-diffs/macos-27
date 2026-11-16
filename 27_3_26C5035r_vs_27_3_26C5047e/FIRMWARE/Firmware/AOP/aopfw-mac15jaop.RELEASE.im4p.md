## aopfw-mac15jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0xa5448
-  __TEXT.__const: 0x5a48
-  __TEXT.__cstring: 0x67fd
+  __TEXT.__text: 0xa5458
+  __TEXT.__const: 0x5a28
+  __TEXT.__cstring: 0x67f2
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xbbb98
-  __ETEXT.__text: 0x17470
+  __DATA.__zerofill: 0xbbbf8
+  __ETEXT.__text: 0x1759c
   __ETEXT.__StaticInit: 0x2c0c
   __ETEXT.__const: 0xbe8
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 3261
   Symbols:   0
-  CStrings:  2068
+  CStrings:  2070
 
Functions:
~ sub_1011df4 : 636 -> 632
~ sub_1015e78 -> sub_1015e74 : 48 -> 44
~ sub_1015ea8 -> sub_1015ea0 : 960 -> 956
~ sub_1016268 -> sub_101625c : 980 -> 976
~ sub_1016f1c -> sub_1016f0c : 392 -> 424
~ sub_101e1cc -> sub_101e1dc : 72 -> 68
~ sub_1052a44 -> sub_1052a50 : 168 -> 164
~ sub_1053688 -> sub_1053690 : 244 -> 240
~ sub_1058274 -> sub_1058278 : 140 -> 144
~ sub_1058d3c -> sub_1058d44 : 140 -> 144
~ sub_1061804 -> sub_1061810 : 136 -> 140
~ sub_1078a20 -> sub_1078a30 : 68 -> 64
~ sub_107d804 -> sub_107d810 : 208 -> 204
~ sub_108b31c -> sub_108b324 : 172 -> 168
~ sub_1090d28 -> sub_1090d2c : 764 -> 776
~ sub_1091024 -> sub_1091034 : 1760 -> 1748
~ sub_1091704 -> sub_1091708 : 916 -> 928
~ sub_1092d54 -> sub_1092d64 : 5356 -> 5344
~ sub_1094240 -> sub_1094244 : 348 -> 360
CStrings:
+ "%s:%s"
+ "22:35:18"
+ "22:42:25"
+ "AppleSPUFirmware-2444.60.12~398"
+ "IOReporting.cpp"
+ "Nov  9 2026"
+ "hDr"
+ "hON"
+ "idx"
+ "lDr"
+ "lOF"
+ "lON"
+ "mnD"
+ "mxD"
+ "nAP"
+ "nON"
+ "tON"
- "%s:hDr"
- "%s:hON"
- "%s:idx"
- "%s:lDr"
- "%s:lOF"
- "%s:lON"
- "%s:mnD"
- "%s:mxD"
- "%s:nAP"
- "%s:nON"
- "%s:tON"
- "21:30:33"
- "21:35:17"
- "AppleSPUFirmware-2444.60.10~229"
- "Oct 28 2026"
```
