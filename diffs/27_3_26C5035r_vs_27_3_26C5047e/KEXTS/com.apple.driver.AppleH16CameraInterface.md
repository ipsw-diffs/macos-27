## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

```diff

-6.201.0.0.0
+6.203.0.0.0
   __TEXT.__const: 0x3f8
-  __TEXT.__cstring: 0x1589f
-  __TEXT.__os_log: 0x11628
-  __TEXT_EXEC.__text: 0x7f9dc
+  __TEXT.__cstring: 0x158d9
+  __TEXT.__os_log: 0x11678
+  __TEXT_EXEC.__text: 0x7fb08
   __TEXT_EXEC.__auth_stubs: 0xdc0
   __DATA.__data: 0x1d0
   __DATA.__common: 0x448

   __DATA_CONST.__got: 0x120
   __DATA_CONST.__auth_ptr: 0x10
   Functions: 1487
-  Symbols:   3479
-  CStrings:  1866
+  Symbols:   3480
+  CStrings:  1869
 
Symbols:
+ __ZZL10ffw_callocmmE22kalloc_type_view_25451
+ __ZZL8ffw_freePvE22kalloc_type_view_25456
+ __ZZN13AppleH16CamIn22SendBCARDataToFirmwareEjE22kalloc_type_view_25566
+ __ZZN13AppleH16CamIn22SendBCARDataToFirmwareEjE22kalloc_type_view_25576
+ __ZZN13AppleH16CamIn22SendBCTRDataToFirmwareEjE22kalloc_type_view_25540
+ __ZZN13AppleH16CamIn26SendPhyEfuseDataToFirmwareEjE22kalloc_type_view_25625
+ __ZZN13AppleH16CamIn26SendPhyEfuseDataToFirmwareEjE22kalloc_type_view_25643
+ __ZZN13AppleH16CamIn27SendStrobeCalDataToFirmwareEjE22kalloc_type_view_25495
+ __ZZN13AppleH16CamIn27SendStrobeCalDataToFirmwareEjE22kalloc_type_view_25505
+ __ZZN13AppleH16CamIn39SendSphereExtendedStrokeRangeToFirmwareEjE22kalloc_type_view_25677
+ __ZZN13AppleH16CamIn39SendSphereExtendedStrokeRangeToFirmwareEjE22kalloc_type_view_25685
+ __ZZN23AppleH16CamInUserClient15ISP_LoadSetfileEPvjjE11_os_log_fmt
+ __ZZN30H16ISPMultiCameraSessionStructdlEPvmE21kalloc_type_view_6146
+ __ZZN30H16ISPMultiCameraSessionStructnwEmE21kalloc_type_view_6146
- __ZZL10ffw_callocmmE22kalloc_type_view_25442
- __ZZL8ffw_freePvE22kalloc_type_view_25447
- __ZZN13AppleH16CamIn22SendBCARDataToFirmwareEjE22kalloc_type_view_25557
- __ZZN13AppleH16CamIn22SendBCARDataToFirmwareEjE22kalloc_type_view_25567
- __ZZN13AppleH16CamIn22SendBCTRDataToFirmwareEjE22kalloc_type_view_25522
- __ZZN13AppleH16CamIn26SendPhyEfuseDataToFirmwareEjE22kalloc_type_view_25616
- __ZZN13AppleH16CamIn26SendPhyEfuseDataToFirmwareEjE22kalloc_type_view_25634
- __ZZN13AppleH16CamIn27SendStrobeCalDataToFirmwareEjE22kalloc_type_view_25486
- __ZZN13AppleH16CamIn27SendStrobeCalDataToFirmwareEjE22kalloc_type_view_25496
- __ZZN13AppleH16CamIn39SendSphereExtendedStrokeRangeToFirmwareEjE22kalloc_type_view_25668
- __ZZN13AppleH16CamIn39SendSphereExtendedStrokeRangeToFirmwareEjE22kalloc_type_view_25676
- __ZZN30H16ISPMultiCameraSessionStructdlEPvmE21kalloc_type_view_6145
- __ZZN30H16ISPMultiCameraSessionStructnwEmE21kalloc_type_view_6145
Functions:
~ __ZN13AppleH16CamIn26ISP_InitialSensorDetectionEv : 10996 -> 11060
~ __ZN23AppleH16CamInUserClient16_ISP_LoadSetfileEPS_PvP25IOExternalMethodArguments : 36 -> 24
~ __ZN23AppleH16CamInUserClient4initEP4taskP12OSDictionary : 1152 -> 1232
~ __ZN23AppleH16CamInUserClient15ISP_LoadSetfileEPvjj : 24 -> 192
CStrings:
+ "AppleH16CamInUserClient:%s - Process %s (pid %d) not permitted to load setfile\n"
+ "ISP_LoadSetfile"
+ "com.apple.private.camera.isp-setfile-load"
```
