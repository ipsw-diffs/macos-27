## AAAFoundationUI

> `/System/Library/PrivateFrameworks/AAAFoundationUI.framework/Versions/A/AAAFoundationUI`

```diff

-117.125.3.0.0
-  __TEXT.__text: 0x1dd98
-  __TEXT.__objc_methlist: 0x1ec
+117.125.4.0.0
+  __TEXT.__text: 0x1e338
+  __TEXT.__objc_methlist: 0x294
   __TEXT.__const: 0x20a6
+  __TEXT.__cstring: 0x319
   __TEXT.__swift5_typeref: 0xc2e
   __TEXT.__swift5_capture: 0x48c
   __TEXT.__swift5_fieldmd: 0x6c4

   __TEXT.__swift_as_entry: 0xcc
   __TEXT.__swift_as_ret: 0xd8
   __TEXT.__swift_as_cont: 0x138
-  __TEXT.__cstring: 0x309
-  __TEXT.__unwind_info: 0xe08
+  __TEXT.__unwind_info: 0xe38
   __TEXT.__eh_frame: 0x1c18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1b0
-  __DATA_CONST.__objc_classlist: 0x30
+  __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x158
+  __DATA_CONST.__objc_selrefs: 0x1f0
   __DATA_CONST.__objc_protorefs: 0x18
+  __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x18d0
-  __AUTH_CONST.__objc_const: 0x950
-  __AUTH_CONST.__auth_got: 0x7e0
-  __AUTH.__objc_data: 0x118
+  __AUTH_CONST.__objc_const: 0xb90
+  __AUTH_CONST.__auth_got: 0x820
+  __AUTH.__objc_data: 0x168
   __AUTH.__data: 0x408
+  __DATA.__objc_ivar: 0x2c
   __DATA.__data: 0xee8
   __DATA.__bss: 0x2100
   __DATA.__common: 0x28
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
+  - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/ExtensionFoundation.framework/Versions/A/ExtensionFoundation
   - /System/Library/Frameworks/ExtensionKit.framework/Versions/A/ExtensionKit
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 860
-  Symbols:   510
-  CStrings:  51
+  Functions: 873
+  Symbols:   565
+  CStrings:  53
 
Symbols:
+ -[AAFInkCoverageTracker .cxx_destruct]
+ -[AAFInkCoverageTracker _checkForCover:]
+ -[AAFInkCoverageTracker dealloc]
+ -[AAFInkCoverageTracker delegate]
+ -[AAFInkCoverageTracker initWithSize:touchLifetime:recoveryEnabled:]
+ -[AAFInkCoverageTracker isUncovered]
+ -[AAFInkCoverageTracker recordTouchAtPoint:]
+ -[AAFInkCoverageTracker reset]
+ -[AAFInkCoverageTracker setDelegate:]
+ -[AAFInkCoverageTracker setSize:]
+ -[AAFInkCoverageTracker setUncovered:]
+ -[AAFInkCoverageTracker size]
+ -[AAFInkCoverageTracker touchLifetime]
+ OBJC_IVAR_$_AAFInkCoverageTracker._cellHeight
+ OBJC_IVAR_$_AAFInkCoverageTracker._cellWidth
+ OBJC_IVAR_$_AAFInkCoverageTracker._delegate
+ OBJC_IVAR_$_AAFInkCoverageTracker._expiryTimes
+ OBJC_IVAR_$_AAFInkCoverageTracker._height
+ OBJC_IVAR_$_AAFInkCoverageTracker._recoverTimer
+ OBJC_IVAR_$_AAFInkCoverageTracker._recoveryEnabled
+ OBJC_IVAR_$_AAFInkCoverageTracker._size
+ OBJC_IVAR_$_AAFInkCoverageTracker._touchLifetime
+ OBJC_IVAR_$_AAFInkCoverageTracker._uncovered
+ OBJC_IVAR_$_AAFInkCoverageTracker._width
+ _CFAbsoluteTimeGetCurrent
+ _OBJC_CLASS_$_AAFInkCoverageTracker
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSTimer
+ _OBJC_METACLASS_$_AAFInkCoverageTracker
+ __OBJC_$_INSTANCE_METHODS_AAFInkCoverageTracker
+ __OBJC_$_INSTANCE_VARIABLES_AAFInkCoverageTracker
+ __OBJC_$_PROP_LIST_AAFInkCoverageTracker
+ __OBJC_CLASS_RO_$_AAFInkCoverageTracker
+ __OBJC_METACLASS_RO_$_AAFInkCoverageTracker
+ _malloc_type_malloc
+ _objc_autoreleaseReturnValue
+ _objc_claimAutoreleasedReturnValue
+ _objc_destroyWeak
+ _objc_loadWeakRetained
+ _objc_msgSend$dateWithTimeIntervalSinceNow:
+ _objc_msgSend$delegate
+ _objc_msgSend$distantFuture
+ _objc_msgSend$distantPast
+ _objc_msgSend$inkCoverageTrackerDidRecover:
+ _objc_msgSend$inkCoverageTrackerDidUncover:
+ _objc_msgSend$isUncovered
+ _objc_msgSend$isValid
+ _objc_msgSend$reset
+ _objc_msgSend$scheduledTimerWithTimeInterval:target:selector:userInfo:repeats:
+ _objc_msgSend$setFireDate:
+ _objc_msgSend$setSize:
+ _objc_msgSend$setUncovered:
+ _objc_msgSend$timeIntervalSinceReferenceDate
+ _objc_storeStrong
+ _objc_storeWeak
CStrings:
+ "Q"
+ "q"
```
