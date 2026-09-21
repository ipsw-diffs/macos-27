## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/Versions/A/APTransport`

```diff

-1005.7.1.0.0
-  __TEXT.__text: 0x8c1a8
+1005.8.1.0.0
+  __TEXT.__text: 0x8cb88
   __TEXT.__objc_methlist: 0x1aa4
   __TEXT.__const: 0x64c
   __TEXT.__gcc_except_tab: 0x844
-  __TEXT.__cstring: 0x24de6
+  __TEXT.__cstring: 0x251bc
   __TEXT.__dlopen_cstrs: 0xfe
   __TEXT.__oslogstring: 0x1af
-  __TEXT.__unwind_info: 0x3640
+  __TEXT.__unwind_info: 0x3648
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1b00
+  __DATA_CONST.__const: 0x1b20
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x50

   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x360
   __AUTH_CONST.__const: 0x38b0
-  __AUTH_CONST.__cfstring: 0x5820
+  __AUTH_CONST.__cfstring: 0x5840
   __AUTH_CONST.__objc_const: 0x2128
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_intobj: 0x78

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4221
-  Symbols:   4669
-  CStrings:  3628
+  Functions: 4231
+  Symbols:   4682
+  CStrings:  3645
 
Symbols:
+ APBrowserSetAirPlayInfo
+ GCC_except_table22
+ GCC_except_table26
+ GCC_except_table32
+ GCC_except_table40
+ GCC_except_table69
+ GCC_except_table70
+ GCC_except_table79
+ _APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix
+ _APBrowserSetAirPlayInfo
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _FigCFSetContainsValue
+ _FigCFSetGetCount
+ _OUTLINED_FUNCTION_58
+ _OUTLINED_FUNCTION_59
+ _OUTLINED_FUNCTION_60
+ _OUTLINED_FUNCTION_61
+ _OUTLINED_FUNCTION_62
+ ___APBrowserSetAirPlayInfo_block_invoke
+ ___block_descriptor_72_e5_v8?0l
- GCC_except_table24
- GCC_except_table29
- GCC_except_table30
- GCC_except_table35
- GCC_except_table49
- GCC_except_table72
- GCC_except_table77
CStrings:
+ "%s external AirPlay info for device with id: %@ name: %'@ from source: [%{ptr}]"
+ "1005.8.1"
+ "APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix"
+ "APBrowserSetAirPlayInfo"
+ "APTransportDeviceForwardAirPlayInfoToBrowser"
+ "Add external source [%{ptr}] for device with id: %@. %ld registered sources"
+ "Dropping external AirPlay info for device with id: %@. Last source withdrew"
+ "Dropping external AirPlay info for device with id: %@: deviceInfo caught up"
+ "External AirPlay info for device with id: %@ is held until Discovery finds it"
+ "ExternalInfoSources"
+ "Failed to create advertiser info for %@."
+ "OSStatus browser_addOrUpdateExternalAirPlayInfo(APBrowserRef, CFNumberRef, CFNumberRef, CFStringRef, CFDataRef)"
+ "OSStatus browser_createAdvertiserInfoForDevice(APBrowserRef, CFNumberRef, CFDictionaryRef, APAdvertiserInfoRef *)"
+ "OSStatus browser_removeExternalAirPlayInfo(APBrowserRef, CFNumberRef, CFNumberRef)"
+ "Remove external source [%{ptr}] for device with id: %@. %ld registered sources"
+ "Update"
+ "browser_addOrUpdateExternalAirPlayInfo"
+ "browser_copyEffectiveAirPlayInfo"
+ "browser_removeExternalAirPlayInfo"
+ "browser_setAirPlayInfo"
+ "void browser_dropExternalAirPlayInfoIfDeviceInfoCaughtUp(APBrowserRef, CFNumberRef, CFDictionaryRef)"
- "1005.7.1"
- "Failed to create advertiser info for %@.\n"
- "OSStatus browser_createAdvertiserInfoForDevice(CFAllocatorRef, CFDictionaryRef, LogCategory *, APAdvertiserInfoRef *)"
- "_APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix"
```
