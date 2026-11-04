## adc-nyx-sc7x.im4p

> `Firmware/isp_bni/adc-nyx-sc7x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8f2f50
+  __TEXT.__text: 0x8f3758
   __TEXT.__const: 0x24030c
   __TEXT.text_env: 0x8e0
-  __TEXT.__cstring: 0xe5837
+  __TEXT.__cstring: 0xe58e6
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x3b748

   __DATA.__zerofill: 0xe25af8
   Functions: 8337
   Symbols:   0
-  CStrings:  25353
+  CStrings:  25355
 
Functions:
~ sub_1ab2e8 : 2516 -> 2596
~ sub_216554 -> sub_2165a4 : 56500 -> 57452
~ sub_22d87c -> sub_22dc84 : 67092 -> 67884
~ sub_3f1b30 -> sub_3f2250 : 4224 -> 4084
~ sub_402234 -> sub_4028c8 : 112876 -> 113244
~ sub_4586b0 -> sub_458eb4 : 2504 -> 2508
~ sub_8f2e0c -> sub_8f3614 : 324 -> 332
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "02:03:04"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "20:30:09"
- "pMSparams->totalSlaves < MAX_CH_PER_SYNCGROUP"
```
