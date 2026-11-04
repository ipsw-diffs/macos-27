## DeviceSelectionEmergencyFlow

> `/System/Library/PrivateFrameworks/DeviceSelectionEmergencyFlow.framework/Versions/A/DeviceSelectionEmergencyFlow`

```diff

-3605.25.1.0.0
-  __TEXT.__text: 0x17c94
-  __TEXT.__objc_methlist: 0x38c
+3610.8.1.0.0
+  __TEXT.__text: 0x17e38
+  __TEXT.__objc_methlist: 0x39c
   __TEXT.__dlopen_cstrs: 0x60
-  __TEXT.__const: 0x1210
+  __TEXT.__const: 0x1220
   __TEXT.__swift5_typeref: 0x5a0
   __TEXT.__swift5_fieldmd: 0x624
   __TEXT.__constg_swiftt: 0x78c

   __TEXT.__swift_as_ret: 0xb8
   __TEXT.__swift_as_cont: 0x160
   __TEXT.__gcc_except_tab: 0x38
-  __TEXT.__unwind_info: 0xc18
+  __TEXT.__unwind_info: 0xc28
   __TEXT.__eh_frame: 0x1774
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2b8
+  __DATA_CONST.__objc_selrefs: 0x2c8
   __DATA_CONST.__objc_superrefs: 0x20
-  __DATA_CONST.__got: 0x180
+  __DATA_CONST.__got: 0x190
   __AUTH_CONST.__const: 0x1568
-  __AUTH_CONST.__objc_const: 0x10a8
-  __AUTH_CONST.__auth_got: 0x590
+  __AUTH_CONST.__objc_const: 0x10d8
+  __AUTH_CONST.__auth_got: 0x598
   __AUTH.__data: 0xa0
-  __DATA.__objc_ivar: 0x3c
+  __DATA.__objc_ivar: 0x40
   __DATA.__data: 0x2a8
   __DATA.__bss: 0x12a0
   __DATA_DIRTY.__objc_data: 0x190

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 937
-  Symbols:   582
+  Functions: 940
+  Symbols:   587
   CStrings:  77
 
Symbols:
+ -[WiProxAdvertiserAdapter startAdvertisingWithPayload:additionalInfo:]
+ -[WiProxDeviceInfo initWithDeviceUUID:deviceAddress:idsDeviceID:observedAtAbsoluteTime:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:]
+ -[WiProxDeviceInfo observedAtAbsoluteTime]
+ -[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPayload:]
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_IVAR_$_WiProxDeviceInfo._observedAtAbsoluteTime
+ _WPHeySiriKeyDeviceTime
+ _WiProxMakeHeySiriPayload
+ ___65-[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPayload:]_block_invoke
+ ___70-[WiProxAdvertiserAdapter startAdvertisingWithPayload:additionalInfo:]_block_invoke
+ _objc_msgSend$doubleValue
+ _objc_msgSend$initWithDeviceUUID:deviceAddress:idsDeviceID:observedAtAbsoluteTime:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:
+ _objc_msgSend$startAdvertisingWithPayload:additionalInfo:
- -[WiProxAdvertiserAdapter startAdvertisingWithPhash:snr:random:confidence:additionalInfo:]
- -[WiProxDeviceInfo initWithDeviceUUID:deviceAddress:idsDeviceID:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:]
- -[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPhash:snr:random:confidence:]
- _MakeHeySiriPayload
- ___85-[WiProxDiscoveryAdapter startScanningAndAdvertisingWithPhash:snr:random:confidence:]_block_invoke
- ___90-[WiProxAdvertiserAdapter startAdvertisingWithPhash:snr:random:confidence:additionalInfo:]_block_invoke
- _objc_msgSend$initWithDeviceUUID:deviceAddress:idsDeviceID:heySiriPerceptualHash:heySiriSNR:heySiriConfidence:heySiriDeviceGroup:heySiriDeviceClass:heySiriRandom:heySiriProductType:
- _objc_msgSend$startAdvertisingWithPhash:snr:random:confidence:additionalInfo:
```
