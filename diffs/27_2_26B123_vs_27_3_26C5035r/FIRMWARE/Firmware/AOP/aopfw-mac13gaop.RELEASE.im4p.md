## aopfw-mac13gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`

```diff

   __TEXT.__text: 0x740e4
-  __TEXT.__const: 0x4648
-  __TEXT.__cstring: 0x144e4
+  __TEXT.__const: 0x4650
+  __TEXT.__cstring: 0x14519
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0xe368
-  __DATA.__const: 0x7850
+  __DATA.__const: 0x7880
   __DATA.__data: 0x8648
   __DATA._rtk_patchbay: 0x333
   __DATA._rtk_mtab: 0x610

   __MISC.__apf_list: 0x90
   Functions: 1811
   Symbols:   0
-  CStrings:  1914
+  CStrings:  1918
 
CStrings:
+ "21:30:16"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "AppleSPUFirmware-2444.60.10~229"
+ "Oct 28 2026"
+ "RTKitAudioFramework v620.2 ('%s' built %s %s) ready!! {%zu nodes}"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
- "13:47:50"
- "AppleSPUFirmware-2444.41.1~32"
- "Oct  3 2026"
- "RTKitAudioFramework v610.1 ('%s' built %s %s) ready!! {%zu nodes}"
```
