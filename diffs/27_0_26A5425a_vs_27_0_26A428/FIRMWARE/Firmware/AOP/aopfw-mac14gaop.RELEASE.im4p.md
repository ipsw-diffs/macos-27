## aopfw-mac14gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14gaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x87b64
+  __TEXT.__text: 0x87b74
   __TEXT.__const: 0x5528
-  __TEXT.__cstring: 0x6a61
+  __TEXT.__cstring: 0x6a7d
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x14b68
-  __DATA.__const: 0x8c70
+  __DATA.__const: 0x8c88
   __DATA.__data: 0x96f0
   __DATA._rtk_mtab: 0x6b8
   __DATA._rtk_patchbay: 0x306

   __CMA.__cma_log_string: 0x1259
   Functions: 2176
   Symbols:   0
-  CStrings:  1981
+  CStrings:  1983
 
Functions:
~ sub_1006020 : 528 -> 532
~ sub_10062c0 -> sub_10062c4 : 144 -> 156
CStrings:
+ "13:00:56"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:34:21"
- "AppleSPUFirmware-2444.1.1~66"
```
