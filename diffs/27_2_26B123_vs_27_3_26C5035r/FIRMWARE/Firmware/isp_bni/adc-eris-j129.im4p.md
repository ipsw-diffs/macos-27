## adc-eris-j129.im4p

> `Firmware/isp_bni/adc-eris-j129.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x9875d4
+  __TEXT.__text: 0x987d64
   __TEXT.__const: 0x24fd30
   __TEXT.text_env: 0xef0
-  __TEXT.__cstring: 0xf56ab
+  __TEXT.__cstring: 0xf575a
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x3b310

   __DATA.__zerofill: 0x85eef8
   Functions: 8459
   Symbols:   0
-  CStrings:  27111
+  CStrings:  27113
 
Functions:
~ sub_1b8570 : 2516 -> 2596
~ sub_2237e4 -> sub_223834 : 60816 -> 61692
~ sub_23bbf0 -> sub_23bfac : 67092 -> 67884
~ sub_4025f4 -> sub_402cc8 : 4224 -> 4084
~ sub_412cb8 -> sub_413300 : 112464 -> 112788
~ sub_46c2f0 -> sub_46ca7c : 2504 -> 2508
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "02:03:01"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "20:30:08"
- "pMSparams->totalSlaves < MAX_CH_PER_SYNCGROUP"
```
