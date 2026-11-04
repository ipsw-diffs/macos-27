## adc-rheia-j70m.im4p

> `Firmware/isp_bni/adc-rheia-j70m.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x96a5d4
+  __TEXT.__text: 0x96acd0
   __TEXT.__const: 0x3146a0
-  __TEXT.__cstring: 0xf1931
+  __TEXT.__cstring: 0xf1a19
   __TEXT.text_env: 0x4f1a4
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __DATA.__zerofill: 0xd7fdf8
   Functions: 8594
   Symbols:   0
-  CStrings:  26429
+  CStrings:  26432
 
Functions:
~ sub_1c5dfc : 2516 -> 2596
~ sub_23495c -> sub_2349ac : 60112 -> 60908
~ sub_24cae4 -> sub_24ce50 : 66772 -> 67580
~ sub_40d7d0 -> sub_40de64 : 4224 -> 4084
~ sub_41dc30 -> sub_41e238 : 110988 -> 111316
~ sub_477f60 -> sub_4786b0 : 2788 -> 2792
~ sub_68e3a8 -> sub_68eafc : 9576 -> 9556
~ sub_7f2068 -> sub_7f27a8 : 5388 -> 5392
~ sub_81b9d4 -> sub_81c118 : 7840 -> 7836
~ sub_81e824 -> sub_81ef64 : 4392 -> 4376
~ sub_83cef4 -> sub_83d624 : 808 -> 812
~ sub_8446cc -> sub_844e00 : 4528 -> 4524
~ sub_867444 -> sub_867b74 : 4092 -> 4028
~ sub_8692a0 -> sub_869990 : 8048 -> 8060
CStrings:
+ "%s: SharedRawBufferPoolInfoGet: chBitMask 0x%x has no WIDE/TELE/SWIDE channel"
+ "02:03:12"
+ "AgentDesGenGP: invalid local op index %u (tot %u max %d)"
+ "Invalid LTM gamma curve 0x%08x\n"
+ "MULTICAM_MASTER_SLAVE_PARAMS_SET: totalSlaves=%u previewMasterCh=%u statsMasterCh=%u out of range (chTot=%zu)\n"
- "20:29:53"
- "pMSparams->totalSlaves < MAX_CH_PER_SYNCGROUP"
```
