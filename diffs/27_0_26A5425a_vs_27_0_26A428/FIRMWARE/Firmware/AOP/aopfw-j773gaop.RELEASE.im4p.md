## aopfw-j773gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-j773gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._spu_service`
- `__DATA._rtk_power`

```diff

   __TEXT.__text: 0x8be00
   __TEXT.__const: 0x84f0
-  __TEXT.__cstring: 0x4c63
+  __TEXT.__cstring: 0x4c7f
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x28
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0xca20
-  __DATA.__const: 0xaab0
+  __DATA.__const: 0xaac8
   __DATA.__data: 0x6b30
   __DATA._rtk_patchbay: 0x306
   __DATA._rtk_mtab: 0x5f8

   __MISC.__apf_list: 0x30
   Functions: 2147
   Symbols:   0
-  CStrings:  2559
+  CStrings:  2561
 
Functions:
~ sub_1005578 : 528 -> 532
~ sub_1005788 -> sub_100578c : 152 -> 148
CStrings:
+ "13:01:27"
+ "13:06:01"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:35:12"
- "15:39:41"
- "AppleSPUFirmware-2444.1.1~66"
```
