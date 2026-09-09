## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/Versions/A/PowerlogHelperdOperators`

```diff

 3486.1.2.0.0
-  __TEXT.__text: 0x112c6c
-  __TEXT.__objc_methlist: 0xa6a0
+  __TEXT.__text: 0x113354
+  __TEXT.__objc_methlist: 0xa718
   __TEXT.__const: 0x4b0
-  __TEXT.__cstring: 0x1679c
-  __TEXT.__oslogstring: 0xafe7
-  __TEXT.__gcc_except_tab: 0x1cf4
+  __TEXT.__cstring: 0x167e3
+  __TEXT.__oslogstring: 0xb06e
+  __TEXT.__gcc_except_tab: 0x1cf0
   __TEXT.__unwind_info: 0x2580
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2238
+  __DATA_CONST.__const: 0x2260
   __DATA_CONST.__objc_classlist: 0x230
   __DATA_CONST.__objc_nlclslist: 0xb0
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7288
+  __DATA_CONST.__objc_selrefs: 0x72f0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1d0
   __DATA_CONST.__objc_arraydata: 0x2af8
   __DATA_CONST.__got: 0xac0
   __AUTH_CONST.__const: 0x2bc8
-  __AUTH_CONST.__cfstring: 0x207a0
-  __AUTH_CONST.__objc_const: 0xd4b8
+  __AUTH_CONST.__cfstring: 0x20840
+  __AUTH_CONST.__objc_const: 0xd578
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_doubleobj: 0x640
   __AUTH_CONST.__objc_intobj: 0x1428

   __AUTH_CONST.__objc_arrayobj: 0xc90
   __AUTH_CONST.__auth_got: 0xb78
   __AUTH.__objc_data: 0x9b0
-  __DATA.__objc_ivar: 0xd84
+  __DATA.__objc_ivar: 0xd94
   __DATA.__data: 0x3a0
   __DATA.__bss: 0xe50
   __DATA.__common: 0x74

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5290
-  Symbols:   10632
-  CStrings:  5461
+  Functions: 5303
+  Symbols:   10662
+  CStrings:  5470
 
Symbols:
+ -[PLBatteryAgent serialNumber2]
+ -[PLBatteryAgent setSerialNumber2:]
+ -[PLPowerMetricMonitorService _parseDisplayAPLXMetricsFromEntry:cacheMetrics:]
+ -[PLPowerMetricMonitorService dcpDisplayStatsX]
+ -[PLPowerMetricMonitorService dcpScanoutStatsX]
+ -[PLPowerMetricMonitorService dcpSwapStatsX]
+ -[PLPowerMetricMonitorService isV68]
+ -[PLPowerMetricMonitorService setDcpDisplayStatsX:]
+ -[PLPowerMetricMonitorService setDcpScanoutStatsX:]
+ -[PLPowerMetricMonitorService setDcpSwapStatsX:]
+ GCC_except_table154
+ OBJC_IVAR_$_PLBatteryAgent._serialNumber2
+ OBJC_IVAR_$_PLPowerMetricMonitorService._dcpDisplayStatsX
+ OBJC_IVAR_$_PLPowerMetricMonitorService._dcpScanoutStatsX
+ OBJC_IVAR_$_PLPowerMetricMonitorService._dcpSwapStatsX
+ _kPLBB25
+ _kPLBatteryAgentEventPointNameBatteryShutdownPack1
+ _kPLBatteryAgentStringLastShutdownSystemTimestamp1
+ _kPLDisplayAgentEventForwardNameDisplayX
+ _objc_msgSend$dcpDisplayStatsX
+ _objc_msgSend$dcpScanoutStatsX
+ _objc_msgSend$dcpSwapStatsX
+ _objc_msgSend$isV68
+ _objc_msgSend$serialNumber2
+ _objc_msgSend$setDcpDisplayStatsX:
+ _objc_msgSend$setDcpScanoutStatsX:
+ _objc_msgSend$setDcpSwapStatsX:
+ _objc_msgSend$setDisplayEnergyX:
+ _objc_msgSend$setDisplayFPSX:
+ _objc_msgSend$setScanoutFPSX:
+ _objc_msgSend$setSerialNumber2:
- GCC_except_table153
CStrings:
+ "BatteryShutdownPack1"
+ "DCPSEC"
+ "DisplayX"
+ "Failed to subscribe to IOReport DCP display stats"
+ "Failed to subscribe to IOReport DCP scanout"
+ "Failed to subscribe to IOReport DCP swap"
+ "LastShutdownSystemTimestamp1"
+ "bb25"
+ "\x8f\v\""
```
