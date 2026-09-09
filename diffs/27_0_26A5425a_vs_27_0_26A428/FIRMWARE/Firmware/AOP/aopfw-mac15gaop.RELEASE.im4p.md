## aopfw-mac15gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`

```diff

-  __TEXT.__text: 0x8a9d4
+  __TEXT.__text: 0x8a9e4
   __TEXT.__const: 0x5628
-  __TEXT.__cstring: 0x6d3e
+  __TEXT.__cstring: 0x6d5a
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x12f68
-  __DATA.__const: 0x99c8
+  __DATA.__const: 0x99e0
   __DATA.__data: 0x9dd8
   __DATA._rtk_mtab: 0x6c0
   __DATA._rtk_patchbay: 0x306

   __CMA.__cma_log_string: 0x1259
   Functions: 2255
   Symbols:   0
-  CStrings:  2053
+  CStrings:  2055
 
Functions:
~ sub_1006820 : 528 -> 532
~ sub_1006ac0 -> sub_1006ac4 : 144 -> 156
CStrings:
+ "13:00:56"
+ "13:06:01"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:34:21"
- "15:39:41"
- "AppleSPUFirmware-2444.1.1~66"
```
