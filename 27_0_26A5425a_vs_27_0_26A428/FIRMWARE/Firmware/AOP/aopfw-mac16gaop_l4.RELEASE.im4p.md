## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`

```diff

   __TEXT.__text: 0xb3cec
   __TEXT.__const: 0xa878
-  __TEXT.__cstring: 0x7a38
+  __TEXT.__cstring: 0x7a54
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x14220
-  __DATA.__const: 0xef90
+  __DATA.__const: 0xefa8
   __DATA.__data: 0x72c8
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x5e0

   __CMA.__cma_log_string: 0x1259
   Functions: 2777
   Symbols:   0
-  CStrings:  2943
+  CStrings:  2945
 
Functions:
~ sub_1006028 : 528 -> 532
~ sub_10062c8 -> sub_10062cc : 152 -> 148
CStrings:
+ "13:00:56"
+ "13:06:06"
+ "13:06:07"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:34:21"
- "15:39:45"
- "15:39:46"
- "AppleSPUFirmware-2444.1.1~66"
```
