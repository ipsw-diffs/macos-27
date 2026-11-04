## aopfw-mac15jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__OS_LOG.__string`

```diff

-  __TEXT.__text: 0xa5444
-  __TEXT.__const: 0x5a20
-  __TEXT.__cstring: 0x67c8
+  __TEXT.__text: 0xa5448
+  __TEXT.__const: 0x5a48
+  __TEXT.__cstring: 0x67fd
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x2ff68
-  __DATA.__const: 0xa3f0
+  __DATA.__const: 0xa420
   __DATA.__data: 0x94a8
   __DATA._rtk_patchbay: 0x312
   __DATA._rtk_mtab: 0x638

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xbbb78
-  __ETEXT.__text: 0x1745c
+  __DATA.__zerofill: 0xbbb98
+  __ETEXT.__text: 0x17470
   __ETEXT.__StaticInit: 0x2c0c
   __ETEXT.__const: 0xbe8
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 3261
   Symbols:   0
-  CStrings:  2064
+  CStrings:  2068
 
Functions:
~ sub_10353fc : 2056 -> 2060
~ sub_10a52e8 -> sub_10a52ec : 348 -> 356
CStrings:
+ "21:30:33"
+ "21:35:17"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "AppleSPUFirmware-2444.60.10~229"
+ "Oct 28 2026"
+ "[AUD] RTKitAudioFramework v620.2 ('%s' built %s %s) ready!! {%zu nodes}"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
- "13:48:09"
- "13:53:11"
- "AppleSPUFirmware-2444.41.1~32"
- "Oct  3 2026"
- "[AUD] RTKitAudioFramework v610.1 ('%s' built %s %s) ready!! {%zu nodes}"
```
