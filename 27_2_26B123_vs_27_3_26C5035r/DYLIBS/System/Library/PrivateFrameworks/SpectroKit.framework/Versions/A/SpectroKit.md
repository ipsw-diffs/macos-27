## SpectroKit

> `/System/Library/PrivateFrameworks/SpectroKit.framework/Versions/A/SpectroKit`

```diff

-11.11.7.0.0
-  __TEXT.__text: 0x1e678
-  __TEXT.__objc_methlist: 0x1f68
+11.11.8.0.0
+  __TEXT.__text: 0x1f994
+  __TEXT.__objc_methlist: 0x1fb0
   __TEXT.__const: 0x104
-  __TEXT.__oslogstring: 0x470
-  __TEXT.__cstring: 0x2520
-  __TEXT.__gcc_except_tab: 0xf08
+  __TEXT.__oslogstring: 0x4c1
+  __TEXT.__cstring: 0x262f
+  __TEXT.__gcc_except_tab: 0xf58
   __TEXT.__ustring: 0xb2
-  __TEXT.__unwind_info: 0x8c0
+  __TEXT.__unwind_info: 0x8d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__const: 0x28
   __DATA_CONST.__objc_classlist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1450
+  __DATA_CONST.__objc_selrefs: 0x14b0
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x250
   __AUTH_CONST.__const: 0x1d0
-  __AUTH_CONST.__cfstring: 0x3660
+  __AUTH_CONST.__cfstring: 0x3900
   __AUTH_CONST.__objc_const: 0x3148
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0x898

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 703
-  Symbols:   1768
-  CStrings:  521
+  Functions: 709
+  Symbols:   1787
+  CStrings:  545
 
Symbols:
+ -[Spectro commandCS3000:wait:]
+ -[Spectro cs3000ExtractEmbeddedPhase2:]
+ -[Spectro cs3000SetResultForErrorCode:]
+ -[Spectro processCS3000SpectrumData:]
+ -[Spectro resetCS3000]
+ -[Spectro setupCS3000]
+ _objc_msgSend$commandCS3000:wait:
+ _objc_msgSend$cs3000ExtractEmbeddedPhase2:
+ _objc_msgSend$cs3000SetResultForErrorCode:
+ _objc_msgSend$hasPrefix:
+ _objc_msgSend$isClosing
+ _objc_msgSend$lock
+ _objc_msgSend$newlineCharacterSet
+ _objc_msgSend$processCS3000SpectrumData:
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$serialLock
+ _objc_msgSend$setupCS3000
+ _objc_msgSend$substringToIndex:
+ _objc_msgSend$unlock
CStrings:
+ "-[Spectro commandCS3000:wait:]"
+ "CS3000 MEAS phase2 (already received): %{public}@"
+ "CS3000 MEAS phase2: %{public}@"
+ "CSMS,0"
+ "ER"
+ "IDDR"
+ "INIT,2"
+ "LUUS,1"
+ "MEAS,1"
+ "MEDR,1,0,0"
+ "MEDR,2,0,2"
+ "Measurement cancelled: device is closing"
+ "OBSS,0"
+ "OK"
+ "RMTS,0"
+ "RMTS,1"
+ "RMTS,2"
+ "Reset cancelled: device is closing"
+ "SCMS,1,6000"
+ "SPMS,0,2"
+ "STSS,0"
+ "Setup cancelled: device is closing"
+ "UCCS,0"
+ "VERR"
```
