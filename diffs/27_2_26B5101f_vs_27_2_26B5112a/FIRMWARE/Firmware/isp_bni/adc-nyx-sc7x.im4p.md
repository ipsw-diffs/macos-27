## adc-nyx-sc7x.im4p

> `Firmware/isp_bni/adc-nyx-sc7x.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__chain_starts`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8f2ea0
-  __TEXT.__const: 0x24018c
+  __TEXT.__text: 0x8f2f50
+  __TEXT.__const: 0x24030c
   __TEXT.text_env: 0x8e0
-  __TEXT.__cstring: 0xe56ef
+  __TEXT.__cstring: 0xe5837
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x3b688
+  __DATA.__const: 0x3b748
   __DATA._rtk_heap: 0x1000
   __DATA.__data: 0xd9040
   __DATA._rtk_power: 0x3b8

   __DATA.__zerofill: 0xe25af8
   Functions: 8337
   Symbols:   0
-  CStrings:  25345
+  CStrings:  25353
 
Functions:
~ sub_4feed0 : 856 -> 908
~ sub_502554 -> sub_502588 : 15440 -> 15452
~ sub_506d40 -> sub_506d80 : 1668 -> 1696
~ sub_509b90 -> sub_509bec : 1548 -> 1576
~ sub_5a05c4 -> sub_5a063c : 2828 -> 2876
~ sub_5a54d0 -> sub_5a5578 : 1312 -> 1320
CStrings:
+ "01:11:07"
+ "NVM header revision invalid %d - off %d\n"
+ "transition_mode019_to_mode550_revert_step0"
+ "transition_mode019_to_mode550_revert_step1"
+ "transition_mode019_to_mode550_step0"
+ "transition_mode019_to_mode550_step1"
+ "transition_mode019_to_mode650_revert_step0"
+ "transition_mode019_to_mode650_revert_step1"
+ "transition_mode019_to_mode650_step0"
+ "transition_mode019_to_mode650_step1"
- "22:03:09"
- "NVM header revision invalid\n"
```
