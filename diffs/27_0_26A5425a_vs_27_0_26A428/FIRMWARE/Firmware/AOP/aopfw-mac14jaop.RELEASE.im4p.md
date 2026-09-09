## aopfw-mac14jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x83bc0
+  __TEXT.__text: 0x83bd0
   __TEXT.__const: 0x52c0
-  __TEXT.__cstring: 0x6143
+  __TEXT.__cstring: 0x615f
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x2000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x13f68
-  __DATA.__const: 0x8c70
+  __DATA.__const: 0x8c88
   __DATA.__data: 0x9b80
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x638

   __CMA.__cma_log_string: 0x1259
   Functions: 2135
   Symbols:   0
-  CStrings:  1898
+  CStrings:  1900
 
Functions:
~ sub_1006820 : 528 -> 532
~ sub_1006ac0 -> sub_1006ac4 : 144 -> 156
CStrings:
+ "13:00:56"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:34:21"
- "AppleSPUFirmware-2444.1.1~66"
```
