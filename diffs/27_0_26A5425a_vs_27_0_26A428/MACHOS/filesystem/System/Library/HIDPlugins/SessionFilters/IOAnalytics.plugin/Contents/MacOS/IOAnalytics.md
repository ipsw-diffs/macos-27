## IOAnalytics

> `/System/Library/HIDPlugins/SessionFilters/IOAnalytics.plugin/Contents/MacOS/IOAnalytics`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x16534
+  __TEXT.__text: 0x16004
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__objc_stubs: 0xfe0
   __TEXT.__objc_methlist: 0xef4

   __TEXT.__objc_methtype: 0x50d
   __TEXT.__gcc_except_tab: 0x11c
   __TEXT.__ustring: 0xa
-  __TEXT.__unwind_info: 0x460
+  __TEXT.__unwind_info: 0x5f8
   __DATA_CONST.__const: 0xb18
   __DATA_CONST.__cfstring: 0x2c60
   __DATA_CONST.__objc_classlist: 0x70
Functions:
~ ___23-[AUVDMAnalytics start]_block_invoke : 136 -> 124
~ ___22-[AUVDMAnalytics stop]_block_invoke : 136 -> 124
~ -[AUVDMAnalytics _startEventMonitoring] : 552 -> 540
~ -[AUVDMAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ _OUTLINED_FUNCTION_7 : 24 -> 12
~ _OUTLINED_FUNCTION_8 : 28 -> 16
~ _OUTLINED_FUNCTION_9 : 24 -> 12
~ _OUTLINED_FUNCTION_10 : 24 -> 12
~ _OUTLINED_FUNCTION_11 : 32 -> 20
~ ___26-[ApplePCIeAnalytics stop]_block_invoke : 116 -> 104
~ +[ApplePCIeAnalytics _getProp:fromReg:withType:] : 116 -> 104
~ _convertNSDataToHexString : 96 -> 84
~ -[ApplePCIeAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_2 : 32 -> 20
~ _OUTLINED_FUNCTION_3 : 32 -> 20
~ ___21-[CIOAnalytics start]_block_invoke : 136 -> 124
~ ___20-[CIOAnalytics stop]_block_invoke : 136 -> 124
~ -[CIOAnalytics _startEventMonitoring] : 540 -> 528
~ -[CIOAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _OUTLINED_FUNCTION_8 : 24 -> 12
~ _OUTLINED_FUNCTION_9 : 24 -> 12
~ _OUTLINED_FUNCTION_11 : 24 -> 12
~ _get_kCAEvent_Thunderbolt_Daily : 68 -> 56
~ ___25-[PowerInAnalytics start]_block_invoke : 136 -> 124
~ ___24-[PowerInAnalytics stop]_block_invoke : 136 -> 124
~ -[PowerInAnalytics _startEventMonitoring] : 572 -> 560
~ _copyIORegistryEntryProperties : 112 -> 88
~ -[PowerInAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ _OUTLINED_FUNCTION_6 : 28 -> 16
~ ___21-[USBAnalytics start]_block_invoke : 136 -> 124
~ ___20-[USBAnalytics stop]_block_invoke : 136 -> 124
~ -[USBAnalytics _startEventMonitoring] : 488 -> 476
~ -[USBAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_4 : 32 -> 20
~ _OUTLINED_FUNCTION_6 : 24 -> 12
~ +[CAField fieldWithName:ioProperty:valueType:] : 136 -> 124
~ -[CAField .cxx_destruct] : 80 -> 68
~ _foreachIOObject : 144 -> 132
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ ___43-[AppleUSBCLightningAdapterAnalytics start]_block_invoke : 136 -> 124
~ ___42-[AppleUSBCLightningAdapterAnalytics stop]_block_invoke : 136 -> 124
~ -[AppleUSBCLightningAdapterAnalytics _startEventMonitoring] : 488 -> 476
~ -[AppleUSBCLightningAdapterAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_0 : 28 -> 16
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_4 : 24 -> 12
~ -[CacheEntry .cxx_destruct] : 68 -> 56
~ -[IOAnalytics setupAnalyticsConfigObserver] : 120 -> 108
~ -[IOAnalytics registerMatchingNotifications] : 260 -> 248
~ ___34-[IOAnalytics setupDailyHeartbeat]_block_invoke : 64 -> 52
~ __44-[IOAnalytics removedService:withClassName:]_block_invoke.91 : 408 -> 400
~ -[IOAnalytics sendDailyEventForService:withClassName:] : 452 -> 440
~ -[IOAnalytics payloadForService:withClassName:] : 1184 -> 1172
~ -[IOAnalytics decodeUSBHostConnectionSpeed:] : 100 -> 88
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[IOAnalytics createMetadataFromIOUSBHostDevice:properties:] : 720 -> 708
~ -[IOAnalytics createMetadataFromIOUSBHostInterface:properties:] : 836 -> 824
~ -[IOAnalytics createMetadataFromIOThunderboltSwitch:properties:] : 1036 -> 1024
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[IOAnalytics .cxx_destruct] : 92 -> 80
~ _OUTLINED_FUNCTION_8 : 32 -> 20
~ -[IOAnalyticsHIDSessionFilter .cxx_destruct] : 164 -> 152
~ ___30-[AppleFireWireAnalytics stop]_block_invoke : 116 -> 104
~ _getPropFromReg : 68 -> 56
~ -[AppleFireWireAnalytics .cxx_destruct] : 68 -> 56
~ _get_kCAEvent_USBFW : 68 -> 56
~ _get_kCAEvent_ThunderboltCounters : 68 -> 56
~ ___23-[USBPDAnalytics start]_block_invoke : 136 -> 124
~ ___22-[USBPDAnalytics stop]_block_invoke : 136 -> 124
~ -[USBPDAnalytics _startEventMonitoring] : 572 -> 560
~ -[USBPDAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_5 : 28 -> 16
~ _OUTLINED_FUNCTION_8 : 24 -> 12
~ +[CAEvent eventWithName:fields:] : 128 -> 116
~ -[CAEvent createPayloadFromDictionary:] : 48 -> 36
~ -[CAEvent .cxx_destruct] : 68 -> 56
~ _get_kCAEvent_USB_Device_Daily : 68 -> 56
~ _get_USBFields : 276 -> 264
~ _get_kCAEvent_USB_Interface_Daily : 68 -> 56
~ _convertNSDataToNSString : 272 -> 260
~ _trimBidirectionalUnicodeCharacters : 132 -> 120
~ _removeBidirectionalUnicodeCharacters : 164 -> 152
~ _convertNSStringToNSData : 460 -> 448
~ _NSObjectIfNotNull : 92 -> 80
~ _castNSObjectToType : 108 -> 96
~ _readJSONFile : 160 -> 148
~ _base64EncodeArray : 340 -> 328
~ _base64DecodeArray : 352 -> 340
~ ___20-[DPAnalytics start]_block_invoke : 136 -> 124
~ ___19-[DPAnalytics stop]_block_invoke : 136 -> 124
~ -[DPAnalytics _startEventMonitoring] : 596 -> 584
~ -[DPAnalytics .cxx_destruct] : 68 -> 56
~ _OUTLINED_FUNCTION_5 : 32 -> 20
~ _OUTLINED_FUNCTION_13 : 32 -> 20
~ _OUTLINED_FUNCTION_14 : 24 -> 12
~ _OUTLINED_FUNCTION_16 : 24 -> 12
~ _OUTLINED_FUNCTION_17 : 24 -> 12
~ _OUTLINED_FUNCTION_18 : 24 -> 12
~ _OUTLINED_FUNCTION_19 : 24 -> 12
~ _OUTLINED_FUNCTION_20 : 24 -> 12
~ _OUTLINED_FUNCTION_21 : 24 -> 12
~ _OUTLINED_FUNCTION_25 : 32 -> 20
~ _OUTLINED_FUNCTION_26 : 24 -> 12
~ _OUTLINED_FUNCTION_27 : 24 -> 12
```
