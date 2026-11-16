## aopfw-mac13gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13gaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x740e4
-  __TEXT.__const: 0x4650
-  __TEXT.__cstring: 0x14519
+  __TEXT.__text: 0x74100
+  __TEXT.__const: 0x4640
+  __TEXT.__cstring: 0x1450e
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0x5b290
-  __ETEXT.__text: 0xd7c4
+  __DATA.__zerofill: 0x5b2d0
+  __ETEXT.__text: 0xd8c0
   __ETEXT.__StaticInit: 0x8760
   __ETEXT.__const: 0x171
   __EDATA.__data: 0x1cc0

   __MISC.__apf_list: 0x90
   Functions: 1811
   Symbols:   0
-  CStrings:  1918
+  CStrings:  1920
 
Functions:
~ sub_100a404 : 960 -> 956
~ sub_100a7c4 -> sub_100a7c0 : 996 -> 992
~ sub_100b484 -> sub_100b47c : 392 -> 424
~ sub_102f958 -> sub_102f970 : 220 -> 224
~ sub_1048144 -> sub_1048160 : 176 -> 172
~ sub_1058684 -> sub_105869c : 208 -> 204
~ sub_106c244 -> sub_106c258 : 172 -> 168
~ sub_1070c04 -> sub_1070c14 : 5096 -> 5108
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
