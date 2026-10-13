## adc-nyx-bc6x.im4p

> `Firmware/isp_bni/adc-nyx-bc6x.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8cb5b4
-  __TEXT.__const: 0x240634
+  __TEXT.__text: 0x8cb664
+  __TEXT.__const: 0x2407b4
   __TEXT.text_env: 0x8e0
-  __TEXT.__cstring: 0xe2221
+  __TEXT.__cstring: 0xe2369
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3a448
+  __DATA.__const: 0x3a508
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xd8770
   __DATA._rtk_power: 0x3b8

   __DATA.__zerofill: 0xe50ff8
   Functions: 8033
   Symbols:   0
-  CStrings:  25000
+  CStrings:  25008
 
Functions:
~ sub_4f5978 : 856 -> 908
~ sub_4f8ffc -> sub_4f9030 : 15440 -> 15452
~ sub_4fd7e8 -> sub_4fd828 : 1668 -> 1696
~ sub_500638 -> sub_500694 : 1548 -> 1576
~ sub_5970b4 -> sub_59712c : 2828 -> 2876
~ sub_59d314 -> sub_59d3bc : 1312 -> 1320
CStrings:
+ "01:11:02"
+ "NVM header revision invalid %d - off %d\n"
+ "transition_mode019_to_mode550_revert_step0"
+ "transition_mode019_to_mode550_revert_step1"
+ "transition_mode019_to_mode550_step0"
+ "transition_mode019_to_mode550_step1"
+ "transition_mode019_to_mode650_revert_step0"
+ "transition_mode019_to_mode650_revert_step1"
+ "transition_mode019_to_mode650_step0"
+ "transition_mode019_to_mode650_step1"
- "22:03:07"
- "NVM header revision invalid\n"
```
