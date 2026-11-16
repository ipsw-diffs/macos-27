## aopfw-mac15gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8aaa0
-  __TEXT.__const: 0x5640
-  __TEXT.__cstring: 0x6d90
+  __TEXT.__text: 0x8aab0
+  __TEXT.__const: 0x5620
+  __TEXT.__cstring: 0x6d85
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xb7990
-  __ETEXT.__text: 0x12d00
+  __DATA.__zerofill: 0xb79f0
+  __ETEXT.__text: 0x12e04
   __ETEXT.__StaticInit: 0x9734
   __ETEXT.__const: 0x4d0
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2254
   Symbols:   0
-  CStrings:  2059
+  CStrings:  2061
 
Functions:
~ sub_100a8c4 : 544 -> 540
~ sub_100c6a0 -> sub_100c69c : 48 -> 44
~ sub_100c6d0 -> sub_100c6c8 : 960 -> 956
~ sub_100ca90 -> sub_100ca84 : 980 -> 976
~ sub_100d748 -> sub_100d738 : 392 -> 424
~ sub_1012d70 -> sub_1012d80 : 72 -> 68
~ sub_1048614 -> sub_1048620 : 248 -> 244
~ sub_1051b58 -> sub_1051b60 : 168 -> 164
~ sub_106f138 -> sub_106f13c : 68 -> 64
~ sub_1073f1c : 208 -> 204
~ sub_1081990 -> sub_108198c : 172 -> 168
~ sub_1087248 -> sub_1087240 : 632 -> 644
~ sub_108762c -> sub_1087630 : 1344 -> 1332
~ sub_1087b6c -> sub_1087b64 : 760 -> 772
~ sub_1089080 -> sub_1089084 : 5284 -> 5296
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
