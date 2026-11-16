## aopfw-mac15saop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15saop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x95414
+  __TEXT.__text: 0x95424
   __TEXT.__const: 0x5a58
-  __TEXT.__cstring: 0x67bb
+  __TEXT.__cstring: 0x67b0
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xbb298
-  __ETEXT.__text: 0x174a0
+  __DATA.__zerofill: 0xbb2f8
+  __ETEXT.__text: 0x175cc
   __ETEXT.__StaticInit: 0x2a90
   __ETEXT.__const: 0xbe8
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2527
   Symbols:   0
-  CStrings:  2065
+  CStrings:  2067
 
Functions:
~ sub_1009df4 : 636 -> 632
~ sub_100de78 -> sub_100de74 : 48 -> 44
~ sub_100dea8 -> sub_100dea0 : 984 -> 980
~ sub_100e280 -> sub_100e274 : 980 -> 976
~ sub_100ef34 -> sub_100ef24 : 392 -> 424
~ sub_10161f0 -> sub_1016200 : 72 -> 68
~ sub_104a280 -> sub_104a28c : 252 -> 248
~ sub_104b124 -> sub_104b12c : 140 -> 144
~ sub_104c91c -> sub_104c928 : 164 -> 160
~ sub_106145c -> sub_1061464 : 140 -> 144
~ sub_1061f90 -> sub_1061f9c : 136 -> 140
~ sub_10791ac -> sub_10791bc : 68 -> 64
~ sub_107df94 -> sub_107dfa0 : 208 -> 204
~ sub_108ba04 -> sub_108ba0c : 172 -> 168
~ sub_109160c -> sub_1091610 : 1084 -> 1096
~ sub_1091a48 -> sub_1091a58 : 1724 -> 1712
~ sub_1092104 -> sub_1092108 : 868 -> 880
~ sub_10937ac -> sub_10937bc : 5520 -> 5508
~ sub_1094d3c -> sub_1094d40 : 348 -> 360
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
