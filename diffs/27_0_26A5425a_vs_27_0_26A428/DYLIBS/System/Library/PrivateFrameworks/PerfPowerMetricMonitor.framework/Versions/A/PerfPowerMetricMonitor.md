## PerfPowerMetricMonitor

> `/System/Library/PrivateFrameworks/PerfPowerMetricMonitor.framework/Versions/A/PerfPowerMetricMonitor`

```diff

 3486.1.2.0.0
-  __TEXT.__text: 0x19238
-  __TEXT.__objc_methlist: 0x1844
+  __TEXT.__text: 0x19c98
+  __TEXT.__objc_methlist: 0x191c
   __TEXT.__const: 0xc8
-  __TEXT.__gcc_except_tab: 0x988
-  __TEXT.__cstring: 0x11ea
+  __TEXT.__gcc_except_tab: 0x998
+  __TEXT.__cstring: 0x1326
   __TEXT.__oslogstring: 0x1129
   __TEXT.__ustring: 0x77e
   __TEXT.__unwind_info: 0x4f8

   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xea0
+  __DATA_CONST.__objc_selrefs: 0xf20
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x50
-  __DATA_CONST.__objc_arraydata: 0x2e8
+  __DATA_CONST.__objc_arraydata: 0x328
   __DATA_CONST.__got: 0xf8
   __AUTH_CONST.__const: 0x790
-  __AUTH_CONST.__cfstring: 0x1420
-  __AUTH_CONST.__objc_const: 0x2898
+  __AUTH_CONST.__cfstring: 0x1520
+  __AUTH_CONST.__objc_const: 0x2a48
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__auth_got: 0x248
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x280
+  __DATA.__objc_ivar: 0x2a4
   __DATA.__data: 0x300
   __DATA.__bss: 0x50
   __DATA_DIRTY.__objc_data: 0x2d0

   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 677
-  Symbols:   1490
-  CStrings:  293
+  Functions: 696
+  Symbols:   1533
+  CStrings:  301
 
Symbols:
+ -[PPSMetricCollection brightnessX]
+ -[PPSMetricCollection displayAPLX]
+ -[PPSMetricCollection displayCostX]
+ -[PPSMetricCollection displayEnergyX]
+ -[PPSMetricCollection displayFPSX]
+ -[PPSMetricCollection displayPowerX]
+ -[PPSMetricCollection scanoutFPSX]
+ -[PPSMetricCollection setBrightnessX:]
+ -[PPSMetricCollection setDisplayAPLX:]
+ -[PPSMetricCollection setDisplayCostX:]
+ -[PPSMetricCollection setDisplayEnergyX:]
+ -[PPSMetricCollection setDisplayFPSX:]
+ -[PPSMetricCollection setDisplayPowerX:]
+ -[PPSMetricCollection setScanoutFPSX:]
+ -[PPSProcessMetricCollection displayPowerX]
+ -[PPSProcessMetricCollection setDisplayPowerX:]
+ -[PPSProcessMetricCollection setWeightOnScreenX:]
+ -[PPSProcessMetricCollection weightOnScreenX]
+ OBJC_IVAR_$_PPSMetricCollection._brightnessX
+ OBJC_IVAR_$_PPSMetricCollection._displayAPLX
+ OBJC_IVAR_$_PPSMetricCollection._displayCostX
+ OBJC_IVAR_$_PPSMetricCollection._displayEnergyX
+ OBJC_IVAR_$_PPSMetricCollection._displayFPSX
+ OBJC_IVAR_$_PPSMetricCollection._displayPowerX
+ OBJC_IVAR_$_PPSMetricCollection._scanoutFPSX
+ OBJC_IVAR_$_PPSProcessMetricCollection._displayPowerX
+ OBJC_IVAR_$_PPSProcessMetricCollection._weightOnScreenX
+ _objc_msgSend$brightnessX
+ _objc_msgSend$displayAPLX
+ _objc_msgSend$displayCostX
+ _objc_msgSend$displayEnergyX
+ _objc_msgSend$displayFPSX
+ _objc_msgSend$displayPowerX
+ _objc_msgSend$scanoutFPSX
+ _objc_msgSend$setBrightnessX:
+ _objc_msgSend$setDisplayAPLX:
+ _objc_msgSend$setDisplayCostX:
+ _objc_msgSend$setDisplayEnergyX:
+ _objc_msgSend$setDisplayFPSX:
+ _objc_msgSend$setDisplayPowerX:
+ _objc_msgSend$setScanoutFPSX:
+ _objc_msgSend$setWeightOnScreenX:
+ _objc_msgSend$weightOnScreenX
CStrings:
+ "\nDisplay X Power    %8.3f W   %@\nDisplay X APL      %8.3f     %@\nDisplay X Cost     %8.3f     %@\nDisplay X Avg FPS  %8.3f     %@\nScanout X Avg FPS  %8.3f     %@\nDisplay X Energy   %8.3f J   %@\nBrightness X       %8.3f nits %@"
+ "brightnessX"
+ "displayAPLX"
+ "displayCostX"
+ "displayEnergyX"
+ "displayFPSX"
+ "displayPowerX"
+ "scanoutFPSX"
```
