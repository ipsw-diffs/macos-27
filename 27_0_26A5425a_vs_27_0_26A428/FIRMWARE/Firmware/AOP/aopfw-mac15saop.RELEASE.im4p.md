## aopfw-mac15saop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15saop.RELEASE.im4p`

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

```diff

-  __TEXT.__text: 0x95318
+  __TEXT.__text: 0x95328
   __TEXT.__const: 0x5a60
-  __TEXT.__cstring: 0x6769
+  __TEXT.__cstring: 0x6785
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x2ff68
-  __DATA.__const: 0xa3e0
+  __DATA.__const: 0xa3f8
   __DATA.__data: 0x95f8
   __DATA._rtk_patchbay: 0x312
   __DATA._rtk_mtab: 0x638

   __CMA.__cma_log_string: 0x1259
   Functions: 2528
   Symbols:   0
-  CStrings:  2059
+  CStrings:  2061
 
Functions:
~ sub_1006020 : 528 -> 532
~ sub_10062c0 -> sub_10062c4 : 144 -> 156
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
