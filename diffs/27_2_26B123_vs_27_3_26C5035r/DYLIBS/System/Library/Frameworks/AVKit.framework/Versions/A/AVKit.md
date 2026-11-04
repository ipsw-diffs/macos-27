## AVKit

> `/System/Library/Frameworks/AVKit.framework/Versions/A/AVKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1385.14.5.1.0
-  __TEXT.__text: 0xe3e44
-  __TEXT.__objc_methlist: 0xe7e0
+1395.6.2.0.0
+  __TEXT.__text: 0xe48c8
+  __TEXT.__objc_methlist: 0xe8a8
   __TEXT.__const: 0x1e48
   __TEXT.__constg_swiftt: 0x9c4
   __TEXT.__swift5_typeref: 0x310e

   __TEXT.__swift_as_cont: 0x68
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__oslogstring: 0x23b3
-  __TEXT.__gcc_except_tab: 0xe60
+  __TEXT.__gcc_except_tab: 0xe74
   __TEXT.__ustring: 0x15e
-  __TEXT.__unwind_info: 0x47c8
+  __TEXT.__unwind_info: 0x4820
   __TEXT.__eh_frame: 0xfa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x820
-  __DATA_CONST.__objc_classlist: 0x5e0
+  __DATA_CONST.__objc_classlist: 0x5e8
   __DATA_CONST.__objc_catlist: 0xa8
-  __DATA_CONST.__objc_protolist: 0x2b8
+  __DATA_CONST.__objc_protolist: 0x2b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7f40
-  __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__objc_superrefs: 0x458
+  __DATA_CONST.__objc_selrefs: 0x7fa0
+  __DATA_CONST.__objc_protorefs: 0x50
+  __DATA_CONST.__objc_superrefs: 0x460
   __DATA_CONST.__objc_arraydata: 0x1e0
   __DATA_CONST.__got: 0xf50
-  __AUTH_CONST.__const: 0x2f50
+  __AUTH_CONST.__const: 0x2fa0
   __AUTH_CONST.__cfstring: 0x7f20
-  __AUTH_CONST.__objc_const: 0x18f90
+  __AUTH_CONST.__objc_const: 0x190d8
   __AUTH_CONST.__objc_doubleobj: 0xc0
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x1e0
   __AUTH_CONST.__objc_floatobj: 0x60
   __AUTH_CONST.__auth_got: 0xd80
-  __AUTH.__objc_data: 0x3c58
+  __AUTH.__objc_data: 0x3ca8
   __AUTH.__data: 0x2b0
-  __DATA.__objc_ivar: 0x1460
-  __DATA.__data: 0x2870
+  __DATA.__objc_ivar: 0x1474
+  __DATA.__data: 0x2868
   __DATA.__bss: 0xe80
   __DATA.__common: 0xc0
   __DATA_DIRTY.__objc_data: 0xa78

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5404
-  Symbols:   12175
+  Functions: 5429
+  Symbols:   12220
   CStrings:  1515
 
Symbols:
+ -[AVCaptureView _fadeInControlsPane]
+ -[AVControlsContainerViewController _eventPassingSelfView]
+ -[AVControlsContainerViewController controlsHitTestable]
+ -[AVControlsContainerViewController setControlsHitTestable:]
+ -[AVDesktopPlayerViewContentView _handleUserInteractionObserverGestureRecognizer:]
+ -[AVDesktopPlayerViewContentView _isPlayerPaused]
+ -[AVDesktopUserInteractionObserverGestureRecognizer .cxx_destruct]
+ -[AVDesktopUserInteractionObserverGestureRecognizer _directTouchIdentitiesInEvent:matchingPhase:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer _updateStateForTrackedTouches]
+ -[AVDesktopUserInteractionObserverGestureRecognizer canBePreventedByGestureRecognizer:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer canPreventGestureRecognizer:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer initWithTarget:action:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer reset]
+ -[AVDesktopUserInteractionObserverGestureRecognizer shouldBeRequiredToFailByGestureRecognizer:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer shouldRequireFailureOfGestureRecognizer:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer touchesBeganWithEvent:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer touchesCancelledWithEvent:]
+ -[AVDesktopUserInteractionObserverGestureRecognizer touchesEndedWithEvent:]
+ -[AVEventPassthroughView hitTestable]
+ -[AVEventPassthroughView initWithFrame:]
+ -[AVEventPassthroughView setHitTestable:]
+ GCC_except_table1045
+ GCC_except_table1082
+ GCC_except_table1291
+ GCC_except_table1299
+ GCC_except_table1309
+ GCC_except_table1311
+ GCC_except_table1375
+ GCC_except_table1395
+ GCC_except_table1397
+ GCC_except_table1404
+ GCC_except_table1406
+ GCC_except_table1428
+ GCC_except_table1552
+ GCC_except_table1567
+ GCC_except_table1632
+ GCC_except_table1653
+ GCC_except_table1708
+ GCC_except_table1734
+ GCC_except_table1857
+ GCC_except_table1861
+ GCC_except_table1876
+ GCC_except_table1880
+ GCC_except_table1938
+ GCC_except_table2026
+ GCC_except_table2467
+ GCC_except_table2483
+ GCC_except_table258
+ GCC_except_table2603
+ GCC_except_table2608
+ GCC_except_table2619
+ GCC_except_table2644
+ GCC_except_table2646
+ GCC_except_table2665
+ GCC_except_table2685
+ GCC_except_table2799
+ GCC_except_table285
+ GCC_except_table2993
+ GCC_except_table3081
+ GCC_except_table3084
+ GCC_except_table3115
+ GCC_except_table3127
+ GCC_except_table3218
+ GCC_except_table3284
+ GCC_except_table3419
+ GCC_except_table3424
+ GCC_except_table3426
+ GCC_except_table3487
+ GCC_except_table3495
+ GCC_except_table3500
+ GCC_except_table3553
+ GCC_except_table3558
+ GCC_except_table3559
+ GCC_except_table3639
+ GCC_except_table3724
+ GCC_except_table3726
+ GCC_except_table3855
+ GCC_except_table3924
+ GCC_except_table3927
+ GCC_except_table3929
+ GCC_except_table3936
+ GCC_except_table3954
+ GCC_except_table3994
+ GCC_except_table4378
+ GCC_except_table549
+ GCC_except_table604
+ GCC_except_table754
+ GCC_except_table763
+ GCC_except_table817
+ GCC_except_table819
+ _OBJC_CLASS_$_AVDesktopUserInteractionObserverGestureRecognizer
+ _OBJC_CLASS_$_NSGestureRecognizer
+ _OBJC_IVAR_$_AVDesktopPlayerViewContentView._isPlayingObservationToken
+ _OBJC_IVAR_$_AVDesktopPlayerViewContentView._temporarilyVisible
+ _OBJC_IVAR_$_AVDesktopPlayerViewContentView._userInteractionCount
+ _OBJC_IVAR_$_AVDesktopPlayerViewContentView._userInteractionObserverGestureRecognizer
+ _OBJC_IVAR_$_AVDesktopUserInteractionObserverGestureRecognizer._trackedTouchIdentities
+ _OBJC_IVAR_$_AVEventPassthroughView._hitTestable
+ _OBJC_METACLASS_$_AVDesktopUserInteractionObserverGestureRecognizer
+ _OBJC_METACLASS_$_NSGestureRecognizer
+ __OBJC_$_INSTANCE_METHODS_AVDesktopUserInteractionObserverGestureRecognizer
+ __OBJC_$_INSTANCE_VARIABLES_AVDesktopUserInteractionObserverGestureRecognizer
+ __OBJC_CLASS_RO_$_AVDesktopUserInteractionObserverGestureRecognizer
+ __OBJC_METACLASS_RO_$_AVDesktopUserInteractionObserverGestureRecognizer
+ ___36-[AVCaptureView _fadeInControlsPane]_block_invoke
+ ___54-[AVDesktopPlayerViewContentView setPlayerController:]_block_invoke_2
+ ___block_descriptor_48_e8_32w40w_e5_v8?0l
+ ___copy_helper_block_e8_32w40w
+ ___destroy_helper_block_e8_32w40w
+ _objc_msgSend$_fadeInControlsPane
+ _objc_msgSend$hitTestable
+ _objc_msgSend$setAutomaticallyAdjustsContentInsets:
+ _objc_msgSend$setControlsHitTestable:
+ _objc_msgSend$setHitTestable:
+ _objc_msgSend$unionSet:
- GCC_except_table1039
- GCC_except_table1076
- GCC_except_table1285
- GCC_except_table1293
- GCC_except_table1303
- GCC_except_table1305
- GCC_except_table1369
- GCC_except_table1389
- GCC_except_table1391
- GCC_except_table1394
- GCC_except_table1398
- GCC_except_table1416
- GCC_except_table1546
- GCC_except_table1561
- GCC_except_table1626
- GCC_except_table1647
- GCC_except_table1702
- GCC_except_table1728
- GCC_except_table1851
- GCC_except_table1855
- GCC_except_table1870
- GCC_except_table1874
- GCC_except_table1932
- GCC_except_table2020
- GCC_except_table2461
- GCC_except_table2477
- GCC_except_table256
- GCC_except_table2597
- GCC_except_table2602
- GCC_except_table2613
- GCC_except_table2638
- GCC_except_table2640
- GCC_except_table2659
- GCC_except_table2679
- GCC_except_table2790
- GCC_except_table283
- GCC_except_table2984
- GCC_except_table3072
- GCC_except_table3075
- GCC_except_table3106
- GCC_except_table3118
- GCC_except_table3209
- GCC_except_table3275
- GCC_except_table3406
- GCC_except_table3410
- GCC_except_table3417
- GCC_except_table3478
- GCC_except_table3486
- GCC_except_table3491
- GCC_except_table3544
- GCC_except_table3549
- GCC_except_table3550
- GCC_except_table3630
- GCC_except_table3715
- GCC_except_table3717
- GCC_except_table3834
- GCC_except_table3903
- GCC_except_table3906
- GCC_except_table3908
- GCC_except_table3915
- GCC_except_table3933
- GCC_except_table4353
- GCC_except_table543
- GCC_except_table598
- GCC_except_table748
- GCC_except_table757
- GCC_except_table811
- GCC_except_table813
- _OBJC_IVAR_$_AVDesktopPlayerViewContentView._showControlsCount
- __OBJC_CLASS_PROTOCOLS_$__TtC5AVKit17AVGlassButtonView(AVKit)
```
