## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/Versions/A/TVPlayback`

```diff

-635.20.5.0.0
-  __TEXT.__text: 0x1493c8
-  __TEXT.__objc_methlist: 0x5af0
+635.20.7.0.0
+  __TEXT.__text: 0x149c34
+  __TEXT.__objc_methlist: 0x5b50
   __TEXT.__const: 0x22e90
-  __TEXT.__cstring: 0x691c
-  __TEXT.__oslogstring: 0x5d1c
+  __TEXT.__cstring: 0x693e
+  __TEXT.__oslogstring: 0x5dbb
   __TEXT.__gcc_except_tab: 0x1d84
-  __TEXT.__unwind_info: 0x1ca8
+  __TEXT.__unwind_info: 0x1cc0
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3ce8
+  __DATA_CONST.__objc_selrefs: 0x3d28
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x160
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x770
-  __AUTH_CONST.__const: 0xbaf0
-  __AUTH_CONST.__cfstring: 0x67a0
-  __AUTH_CONST.__objc_const: 0x8c68
+  __AUTH_CONST.__const: 0xbb50
+  __AUTH_CONST.__cfstring: 0x67c0
+  __AUTH_CONST.__objc_const: 0x8cc8
   __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__auth_got: 0x3a8
   __AUTH.__objc_data: 0x7d0
-  __DATA.__objc_ivar: 0x6e8
+  __DATA.__objc_ivar: 0x6f0
   __DATA.__data: 0x1040
   __DATA.__bss: 0x110
   __DATA.__common: 0x9f0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2386
-  Symbols:   5476
-  CStrings:  1323
+  Functions: 2395
+  Symbols:   5495
+  CStrings:  1326
 
Symbols:
+ -[TVPPlayer _elapsedTimeAdjustedForTrailingInterstitialSnapback:]
+ -[TVPPlayer _trailingInterstitialSnapbackWorkaroundEnabled]
+ -[TVPPlayer _updatePlayedThroughTrailingInterstitial]
+ -[TVPPlayer lastSeekTargetTime]
+ -[TVPPlayer playedThroughTrailingInterstitial]
+ -[TVPPlayer setLastSeekTargetTime:]
+ -[TVPPlayer setPlayedThroughTrailingInterstitial:]
+ -[TVPPlayer waitingForAVKitSeekAfterFinishingExternalImageScanning]
+ GCC_except_table141
+ GCC_except_table150
+ GCC_except_table257
+ GCC_except_table263
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table319
+ GCC_except_table355
+ GCC_except_table373
+ GCC_except_table400
+ GCC_except_table404
+ GCC_except_table414
+ GCC_except_table425
+ GCC_except_table449
+ GCC_except_table466
+ GCC_except_table469
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table473
+ GCC_except_table479
+ GCC_except_table488
+ GCC_except_table497
+ GCC_except_table503
+ GCC_except_table505
+ GCC_except_table507
+ GCC_except_table534
+ GCC_except_table538
+ GCC_except_table541
+ GCC_except_table547
+ GCC_except_table558
+ GCC_except_table566
+ GCC_except_table570
+ GCC_except_table576
+ GCC_except_table584
+ GCC_except_table587
+ GCC_except_table601
+ GCC_except_table604
+ GCC_except_table608
+ GCC_except_table61
+ GCC_except_table70
+ _OBJC_IVAR_$_TVPPlayer._lastSeekTargetTime
+ _OBJC_IVAR_$_TVPPlayer._playedThroughTrailingInterstitial
+ ___block_descriptor_56_e8_32s_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s_e5_v8?0l
+ _objc_msgSend$_elapsedTimeAdjustedForTrailingInterstitialSnapback:
+ _objc_msgSend$_trailingInterstitialSnapbackWorkaroundEnabled
+ _objc_msgSend$_updatePlayedThroughTrailingInterstitial
+ _objc_msgSend$lastSeekTargetTime
+ _objc_msgSend$playedThroughTrailingInterstitial
+ _objc_msgSend$setLastSeekTargetTime:
+ _objc_msgSend$setPlayedThroughTrailingInterstitial:
- GCC_except_table140
- GCC_except_table148
- GCC_except_table255
- GCC_except_table261
- GCC_except_table265
- GCC_except_table268
- GCC_except_table317
- GCC_except_table350
- GCC_except_table368
- GCC_except_table395
- GCC_except_table399
- GCC_except_table409
- GCC_except_table420
- GCC_except_table444
- GCC_except_table451
- GCC_except_table452
- GCC_except_table464
- GCC_except_table465
- GCC_except_table468
- GCC_except_table474
- GCC_except_table478
- GCC_except_table487
- GCC_except_table498
- GCC_except_table500
- GCC_except_table502
- GCC_except_table529
- GCC_except_table531
- GCC_except_table533
- GCC_except_table542
- GCC_except_table551
- GCC_except_table553
- GCC_except_table565
- GCC_except_table571
- GCC_except_table579
- GCC_except_table582
- GCC_except_table59
- GCC_except_table594
- GCC_except_table596
- GCC_except_table603
- GCC_except_table68
CStrings:
+ "DisablePostRollSnapbackWorkaround"
+ "Playing trailing interstitial of an item with external interstitials"
+ "Reporting duration %@ as elapsed time instead of %@ due to trailing interstitial snapback"
```
