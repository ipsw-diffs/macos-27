## aopfw-mac15jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0xa534c
+  __TEXT.__text: 0xa535c
   __TEXT.__const: 0x5a30
-  __TEXT.__cstring: 0x67ab
+  __TEXT.__cstring: 0x67c7
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x2ff68
-  __DATA.__const: 0xa3d8
+  __DATA.__const: 0xa3f0
   __DATA.__data: 0x94b0
   __DATA._rtk_patchbay: 0x312
   __DATA._rtk_mtab: 0x638

   __CMA.__cma_log_string: 0x1259
   Functions: 3262
   Symbols:   0
-  CStrings:  2062
+  CStrings:  2064
 
Functions:
~ sub_100e020 : 528 -> 532
~ sub_100e2c0 -> sub_100e2c4 : 144 -> 156
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
