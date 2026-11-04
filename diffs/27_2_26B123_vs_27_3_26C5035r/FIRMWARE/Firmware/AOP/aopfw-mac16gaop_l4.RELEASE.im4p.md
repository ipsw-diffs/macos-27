## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

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

-  __TEXT.__text: 0xb3dd0
-  __TEXT.__const: 0xa85c
-  __TEXT.__cstring: 0x7a55
+  __TEXT.__text: 0xb3dd4
+  __TEXT.__const: 0xa884
+  __TEXT.__cstring: 0x7a8a
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x14220
-  __DATA.__const: 0xefa8
+  __DATA.__const: 0xefd8
   __DATA.__data: 0x72c8
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x5e0

   __DATA._rtk_threads: 0x0
   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
-  __DATA.__zerofill: 0xab798
-  __ETEXT.__text: 0x13468
+  __DATA.__zerofill: 0xab7b8
+  __ETEXT.__text: 0x1347c
   __ETEXT.__StaticInit: 0x2110
   __ETEXT.__const: 0x580
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2776
   Symbols:   0
-  CStrings:  2945
+  CStrings:  2949
 
Functions:
~ sub_102a3ac : 2052 -> 2056
CStrings:
+ "21:30:33"
+ "21:35:21"
+ "21:35:22"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "AppleSPUFirmware-2444.60.10~229"
+ "Oct 28 2026"
+ "[AUD] RTKitAudioFramework v620.2 ('%s' built %s %s) ready!! {%zu nodes}"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
- "13:48:09"
- "13:53:15"
- "13:53:16"
- "AppleSPUFirmware-2444.41.1~32"
- "Oct  3 2026"
- "[AUD] RTKitAudioFramework v610.1 ('%s' built %s %s) ready!! {%zu nodes}"
```
