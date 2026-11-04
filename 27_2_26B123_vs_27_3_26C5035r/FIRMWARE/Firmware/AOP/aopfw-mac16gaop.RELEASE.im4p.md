## aopfw-mac16gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__OS_LOG.__string`

```diff

-  __TEXT.__text: 0xb37f8
-  __TEXT.__const: 0xa874
-  __TEXT.__cstring: 0x5add
+  __TEXT.__text: 0xb37fc
+  __TEXT.__const: 0xa8b4
+  __TEXT.__cstring: 0x5b12
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x14240
-  __DATA.__const: 0xefa8
-  __DATA.__data: 0x72c0
+  __DATA.__const: 0xefd8
+  __DATA.__data: 0x72c8
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x5e0
   __DATA.__version: 0x8

   __DATA._spu_exts: 0x0
   __DATA.__constructor: 0x0
   __DATA.__zerofill: 0xab7b8
-  __ETEXT.__text: 0x1346c
+  __ETEXT.__text: 0x13480
   __ETEXT.__StaticInit: 0x2110
   __ETEXT.__const: 0x580
   __EDATA.__data: 0x1cc0

   __CMA.__cma_log_string: 0x1259
   Functions: 2775
   Symbols:   0
-  CStrings:  2942
+  CStrings:  2946
 
Functions:
~ sub_1088e6c : 1988 -> 1992
CStrings:
+ "21:31:14"
+ "21:35:21"
+ "21:35:22"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "AppleSPUFirmware-2444.60.10~229"
+ "Oct 28 2026"
+ "[AUD] RTKitAudioFramework v620.2 ('%s' built %s %s) ready!! {%zu nodes}"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
- "13:48:46"
- "13:53:15"
- "13:53:16"
- "AppleSPUFirmware-2444.41.1~32"
- "Oct  3 2026"
- "[AUD] RTKitAudioFramework v610.1 ('%s' built %s %s) ready!! {%zu nodes}"
```
