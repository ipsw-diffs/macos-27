## aopfw-mac13jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x805e8
+  __TEXT.__text: 0x805f8
   __TEXT.__const: 0x5150
-  __TEXT.__cstring: 0x130ed
+  __TEXT.__cstring: 0x13109
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x2000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x12768
-  __DATA.__const: 0x8498
+  __DATA.__const: 0x84b0
   __DATA.__data: 0x8c70
   __DATA._rtk_patchbay: 0x31e
   __DATA._rtk_mtab: 0x628

   __CMA.__cma_log_string: 0x1259
   Functions: 2041
   Symbols:   0
-  CStrings:  1850
+  CStrings:  1852
 
Functions:
~ sub_1006020 : 528 -> 532
~ sub_10062c0 -> sub_10062c4 : 144 -> 156
CStrings:
+ "13:00:42"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:33:57"
- "AppleSPUFirmware-2444.1.1~66"
```
