## aopfw-mac14jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x83c8c
-  __TEXT.__const: 0x52a8
-  __TEXT.__cstring: 0x6160
+  __TEXT.__text: 0x83c90
+  __TEXT.__const: 0x52d0
+  __TEXT.__cstring: 0x6195
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x2000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x13f68
-  __DATA.__const: 0x8c88
+  __DATA.__const: 0x8cb8
   __DATA.__data: 0x9b78
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x638

   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
   __DATA.__zerofill: 0x71700
-  __ETEXT.__text: 0x11d88
+  __ETEXT.__text: 0x11d9c
   __ETEXT.__StaticInit: 0x8734
   __ETEXT.__const: 0x47b
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2134
   Symbols:   0
-  CStrings:  1900
+  CStrings:  1904
 
Functions:
~ sub_1028168 : 2056 -> 2060
~ sub_1083b30 -> sub_1083b34 : 356 -> 348
CStrings:
+ "21:30:33"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "AppleSPUFirmware-2444.60.10~229"
+ "Oct 28 2026"
+ "[AUD] RTKitAudioFramework v620.2 ('%s' built %s %s) ready!! {%zu nodes}"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
- "13:48:09"
- "AppleSPUFirmware-2444.41.1~32"
- "Oct  3 2026"
- "[AUD] RTKitAudioFramework v610.1 ('%s' built %s %s) ready!! {%zu nodes}"
```
