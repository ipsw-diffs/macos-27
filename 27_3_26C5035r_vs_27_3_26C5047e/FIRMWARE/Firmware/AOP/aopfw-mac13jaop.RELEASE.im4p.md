## aopfw-mac13jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x806b4
-  __TEXT.__const: 0x5168
-  __TEXT.__cstring: 0x1313e
+  __TEXT.__text: 0x806c8
+  __TEXT.__const: 0x5148
+  __TEXT.__cstring: 0x13133
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x2000

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x70650
-  __ETEXT.__text: 0xfaf0
+  __DATA.__zerofill: 0x706b0
+  __ETEXT.__text: 0xfc24
   __ETEXT.__StaticInit: 0x73b8
   __ETEXT.__const: 0x47b
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2040
   Symbols:   0
-  CStrings:  1856
+  CStrings:  1858
 
Functions:
~ sub_1009de4 : 636 -> 632
~ sub_100bb18 -> sub_100bb14 : 48 -> 44
~ sub_100bb48 -> sub_100bb40 : 960 -> 956
~ sub_100bf08 -> sub_100befc : 996 -> 992
~ sub_100cbd4 -> sub_100cbc4 : 392 -> 424
~ sub_1013300 -> sub_1013310 : 72 -> 68
~ sub_104f4b8 -> sub_104f4c4 : 176 -> 172
~ sub_1065934 -> sub_106593c : 68 -> 64
~ sub_106a6e0 -> sub_106a6e4 : 208 -> 204
~ sub_1077f94 : 172 -> 168
~ sub_107ccd8 -> sub_107ccd4 : 3504 -> 3492
~ sub_107da88 -> sub_107da78 : 1880 -> 1904
~ sub_107ee2c -> sub_107ee34 : 4916 -> 4928
~ sub_1080558 -> sub_108056c : 348 -> 356
CStrings:
+ "%s:%s"
+ "22:34:53"
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
- "21:30:16"
- "AppleSPUFirmware-2444.60.10~229"
- "Oct 28 2026"
```
