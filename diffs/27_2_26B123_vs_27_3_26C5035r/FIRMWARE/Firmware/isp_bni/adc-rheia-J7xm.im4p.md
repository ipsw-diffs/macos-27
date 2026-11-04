## adc-rheia-J7xm.im4p

> `Firmware/isp_bni/adc-rheia-J7xm.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x8f0130
+  __TEXT.__text: 0x8f08f4
   __TEXT.__const: 0x34898c
   __TEXT.text_env: 0x45b74
-  __TEXT.__cstring: 0xe7de8
+  __TEXT.__cstring: 0xe7e97
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __DATA.__const: 0x37140

   __DATA.__zerofill: 0x2de5f8
   Functions: 8362
   Symbols:   0
-  CStrings:  25641
+  CStrings:  25643
 
Functions:
~ sub_1b52c4 : 2516 -> 2596
~ sub_220730 -> sub_220780 : 56528 -> 57480
~ sub_23a268 -> sub_23a670 : 67092 -> 67884
~ sub_3fb6f4 -> sub_3fbe14 : 4224 -> 4084
~ sub_40bd40 -> sub_40c3d4 : 112876 -> 113244
~ sub_4641f4 -> sub_4649f8 : 2788 -> 2792
~ sub_77c74c -> sub_77cf54 : 5388 -> 5392
~ sub_7a4930 -> sub_7a513c : 7840 -> 7836
~ sub_7a7784 -> sub_7a7f8c : 4392 -> 4376
~ sub_7c5e74 -> sub_7c666c : 804 -> 808
~ sub_7cd908 -> sub_7ce104 : 4416 -> 4412
~ sub_7f0474 -> sub_7f0c6c : 4092 -> 4028
~ sub_7f22d0 -> sub_7f2a88 : 8048 -> 8060
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "02:03:12"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "20:29:52"
- "pMSparams->totalSlaves < MAX_CH_PER_SYNCGROUP"
```
