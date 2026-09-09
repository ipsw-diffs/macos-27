## aopfw-mac13gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13gaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x74008
+  __TEXT.__text: 0x74018
   __TEXT.__const: 0x4638
-  __TEXT.__cstring: 0x144c8
+  __TEXT.__cstring: 0x144e4
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x2c
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_exc_stack: 0x1000
   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0xe368
-  __DATA.__const: 0x7838
+  __DATA.__const: 0x7850
   __DATA.__data: 0x8650
   __DATA._rtk_patchbay: 0x333
   __DATA._rtk_mtab: 0x610

   __MISC.__apf_list: 0x90
   Functions: 1811
   Symbols:   0
-  CStrings:  1912
+  CStrings:  1914
 
Functions:
~ sub_1005a10 : 528 -> 532
~ sub_1005c20 -> sub_1005c24 : 144 -> 156
CStrings:
+ "13:00:42"
+ "AOP2IMU2"
+ "AppleSPUFirmware-2444.1.1~64"
+ "aop2.imu_1_100aop2"
- "15:33:57"
- "AppleSPUFirmware-2444.1.1~66"
```
