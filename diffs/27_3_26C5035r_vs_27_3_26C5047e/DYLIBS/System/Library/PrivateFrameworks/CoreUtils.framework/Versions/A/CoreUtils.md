## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils`

```diff

-920.3.0.0.0
-  __TEXT.__text: 0x11d934
-  __TEXT.__objc_methlist: 0xa418
-  __TEXT.__cstring: 0x1e6c4
+920.6.0.0.0
+  __TEXT.__text: 0x11df60
+  __TEXT.__objc_methlist: 0xa448
+  __TEXT.__cstring: 0x1e79c
   __TEXT.__const: 0x22dc
   __TEXT.__gcc_except_tab: 0x1af4
   __TEXT.__oslogstring: 0x4978
-  __TEXT.__unwind_info: 0x49a0
+  __TEXT.__unwind_info: 0x49c0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x158
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5428
+  __DATA_CONST.__objc_selrefs: 0x5448
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x240
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x680
-  __AUTH_CONST.__const: 0x4198
+  __AUTH_CONST.__const: 0x41c8
   __AUTH_CONST.__cfstring: 0x40a0
-  __AUTH_CONST.__objc_const: 0x13f48
+  __AUTH_CONST.__objc_const: 0x13f80
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x15d8
   __AUTH.__objc_data: 0x1e28
   __AUTH.__data: 0xa18
-  __DATA.__objc_ivar: 0x1548
+  __DATA.__objc_ivar: 0x154c
   __DATA.__data: 0x2f50
-  __DATA.__bss: 0x11d0
+  __DATA.__bss: 0x11f0
   __DATA.__common: 0x2a
   __DATA_DIRTY.__objc_data: 0x2f8
   __DATA_DIRTY.__data: 0xa8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5863
-  Symbols:   11567
-  CStrings:  4903
+  Functions: 5873
+  Symbols:   11579
+  CStrings:  4911
 
Symbols:
+ -[CUUserNotificationSession _addRequestWithResultBlock:error:]
+ -[CUUserNotificationSession mockPostCount]
+ -[CUUserNotificationSession repost]
+ GCC_except_table4367
+ GCC_except_table4375
+ GCC_except_table4383
+ GCC_except_table4498
+ GCC_except_table4525
+ GCC_except_table4526
+ GCC_except_table4590
+ GCC_except_table4594
+ GCC_except_table4596
+ GCC_except_table4598
+ GCC_except_table4621
+ GCC_except_table4696
+ GCC_except_table4698
+ GCC_except_table4700
+ GCC_except_table4702
+ GCC_except_table4704
+ GCC_except_table4706
+ GCC_except_table4710
+ GCC_except_table4712
+ GCC_except_table4737
+ GCC_except_table4741
+ GCC_except_table4742
+ GCC_except_table4743
+ GCC_except_table4745
+ GCC_except_table4746
+ GCC_except_table4747
+ GCC_except_table4755
+ GCC_except_table4777
+ GCC_except_table4781
+ GCC_except_table4783
+ GCC_except_table4785
+ GCC_except_table4786
+ GCC_except_table4787
+ GCC_except_table4789
+ GCC_except_table5341
+ GCC_except_table5354
+ GCC_except_table5423
+ GCC_except_table5427
+ GCC_except_table5432
+ GCC_except_table5452
+ GCC_except_table5463
+ GCC_except_table5712
+ GCC_except_table5713
+ GCC_except_table5726
+ _OBJC_IVAR_$_CUUserNotificationSession._mockPostCount
+ __PairingResetThrottleBucket
+ __PairingThrottleDelayLocked
+ __SetupServerSetupCodeVerified
+ ___35-[CUUserNotificationSession repost]_block_invoke
+ ___35-[CUUserNotificationSession repost]_block_invoke_2
+ ___35-[CUUserNotificationSession repost]_block_invoke_3
+ ___49-[CUUserNotificationSession _runRequestAddStart:]_block_invoke_3
+ ___62-[CUUserNotificationSession _addRequestWithResultBlock:error:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8l
+ _gPairingThrottle
+ _objc_msgSend$_addRequestWithResultBlock:error:
- GCC_except_table4360
- GCC_except_table4368
- GCC_except_table4376
- GCC_except_table4491
- GCC_except_table4518
- GCC_except_table4519
- GCC_except_table4583
- GCC_except_table4587
- GCC_except_table4589
- GCC_except_table4591
- GCC_except_table4614
- GCC_except_table4688
- GCC_except_table4689
- GCC_except_table4690
- GCC_except_table4691
- GCC_except_table4693
- GCC_except_table4699
- GCC_except_table4703
- GCC_except_table4705
- GCC_except_table4717
- GCC_except_table4726
- GCC_except_table4727
- GCC_except_table4729
- GCC_except_table4730
- GCC_except_table4735
- GCC_except_table4739
- GCC_except_table4748
- GCC_except_table4750
- GCC_except_table4751
- GCC_except_table4754
- GCC_except_table4759
- GCC_except_table4760
- GCC_except_table4762
- GCC_except_table4770
- GCC_except_table5334
- GCC_except_table5347
- GCC_except_table5416
- GCC_except_table5420
- GCC_except_table5425
- GCC_except_table5444
- GCC_except_table5453
- GCC_except_table5702
- GCC_except_table5703
- GCC_except_table5716
- _gPairingThrottleCounter
- _gPairingThrottleNextTicks
- _gPairingTries
CStrings:
+ "### Repost failed: %{error}\n"
+ "-[CUUserNotificationSession _addRequestWithResultBlock:error:]"
+ "-[CUUserNotificationSession repost]_block_invoke"
+ "-[CUUserNotificationSession repost]_block_invoke_3"
+ "Failed"
+ "Repost ignored: %s\n"
+ "Repost: %@\n"
+ "Reposted: %@, %{error}\n"
+ "Succeeded"
- "-[CUUserNotificationSession _runRequestAddStart:]"
```
