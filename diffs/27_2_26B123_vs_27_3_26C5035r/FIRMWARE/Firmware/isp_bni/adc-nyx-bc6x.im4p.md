## adc-nyx-bc6x.im4p

> `Firmware/isp_bni/adc-nyx-bc6x.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8cb664
+  __TEXT.__text: 0x8cbe6c
   __TEXT.__const: 0x2407b4
   __TEXT.text_env: 0x8e0
-  __TEXT.__cstring: 0xe2369
+  __TEXT.__cstring: 0xe2418
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x3a508

   __DATA.__zerofill: 0xe50ff8
   Functions: 8033
   Symbols:   0
-  CStrings:  25008
+  CStrings:  25010
 
Functions:
~ sub_1ab118 : 2516 -> 2596
~ sub_216384 -> sub_2163d4 : 56500 -> 57452
~ sub_22d6ac -> sub_22dab4 : 67092 -> 67884
~ sub_3ee168 -> sub_3ee888 : 4224 -> 4084
~ sub_3fe838 -> sub_3feecc : 112796 -> 113164
~ sub_454924 -> sub_455128 : 2504 -> 2508
~ sub_8cb520 -> sub_8cbd28 : 324 -> 332
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "02:03:00"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "20:30:08"
- "pMSparams->totalSlaves < MAX_CH_PER_SYNCGROUP"
```
