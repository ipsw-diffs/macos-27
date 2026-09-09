## DisplayServices

> `/System/Library/LoginPlugins/DisplayServices.loginPlugin/Contents/MacOS/DisplayServices`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 433.0.0.0.0
-  __TEXT.__text: 0xa9d4
+  __TEXT.__text: 0xa69c
   __TEXT.__auth_stubs: 0xa90
   __TEXT.__objc_stubs: 0x700
   __TEXT.__objc_methlist: 0x2cc

   __TEXT.__objc_methtype: 0x12b
   __TEXT.__const: 0xb8
   __TEXT.__oslogstring: 0x339
-  __TEXT.__unwind_info: 0x3c8
+  __TEXT.__unwind_info: 0x4b0
   __DATA_CONST.__const: 0xb0
   __DATA_CONST.__cfstring: 0xc60
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ -[O3Device saveToNVR] : 56 -> 44
~ -[O3Device enableColorCorrection:] : 56 -> 44
~ -[O3Device timingDidChange] : 56 -> 44
~ -[O3Master didStartup] : 240 -> 228
~ _TerminationNotificationCallback : 60 -> 48
~ -[O3Master deviceExistsForDisplayID:] : 60 -> 48
~ -[O3Master timerServiceForCFunctionFired:] : 204 -> 192
~ -[O3Master removeInvalidObjects] : 204 -> 192
~ -[O3Master objectInstanceForDisplayID:andType:] : 120 -> 108
~ -[O3Master setObjectInstance:forDisplayID:andType:] : 176 -> 164
~ -[O3Master removeObjectInstancesForDisplayID:] : 184 -> 172
~ -[O3Master initTemperatureMonitoring] : 136 -> 124
~ ___handleTemperatureChange_block_invoke : 240 -> 228
~ ___copy_helper_block_8_32r40r48r56r : 112 -> 100
~ ___destroy_helper_block_8_32r40r48r56r : 92 -> 80
~ _registerSleepWakeNotifications : 160 -> 148
~ _serviceSystemWakeNotification : 148 -> 136
~ _displayDidReconfigure : 156 -> 144
~ _deviceRelease : 188 -> 152
~ _deviceSetReport : 232 -> 208
~ _DSDeviceRelease : 148 -> 136
~ _serviceDisplayDidReconfigure : 272 -> 260
~ _DSDeviceGetReportBounds : 96 -> 84
~ _DSDeviceGetReportSize : 64 -> 52
~ _DSDeviceRationalReportValue : 120 -> 108
~ _DSDeviceGetReport : 140 -> 128
~ _DSDeviceGetLargeReport : 132 -> 120
~ _DSDeviceSetLargeReport : 132 -> 120
~ _DSDeviceSetReport : 132 -> 120
~ _DSDeviceSetFloatReport : 388 -> 376
~ _extractThermalDataPoint : 220 -> 208
~ _ambientTimerFire : 144 -> 132
~ _serviceInterestCallback : 160 -> 136
~ _DisplayServicesNeedsBrightnessSmoothing : 52 -> 40
~ _DisplayServicesSetBrightnessSmooth : 332 -> 324
~ _appendToGlobalIDStore : 112 -> 100
~ _DisplayServicesCreateBrightnessTable : 112 -> 100
~ _DisplayServicesEnableAmbientLightCompensation : 136 -> 124
~ _DisplayServicesAmbientLightResetChanged : 108 -> 96
~ _DisplayServicesBezelButtonsLocked : 52 -> 40
~ _DisplayServicesSetToDefaults : 60 -> 48
~ _DisplayServicesHasCommit : 60 -> 48
~ _DisplayServicesCommitSettings : 100 -> 88
~ _DisplayServicesHasOptionsAuthorization : 60 -> 48
~ _DisplayServicesSetAuthorized : 84 -> 72
~ _DisplayServicesHasPowerMode : 60 -> 48
~ _DisplayServicesSetPowerMode : 104 -> 92
~ _DisplayServicesHasTouchSwitchDisable : 60 -> 48
~ _DisplayServicesHasPowerButton : 60 -> 48
~ _DisplayServicesGetPowerSwitchMode : 80 -> 68
~ _DisplayServicesHasBrightnessButtons : 60 -> 48
~ _DisplayServicesGetDeviceID : 52 -> 40
~ ___DisplayServicesBrightnessChangeNotification_block_invoke : 268 -> 256
~ _sendChangeNotification : 224 -> 212
~ ___DisplayServicesBrightnessChangeNotificationImmediate_block_invoke : 136 -> 124
~ _notificationApplier : 76 -> 64
~ _setEDMStatus : 248 -> 236
~ _serviceInterestCallback : 208 -> 184
~ _DSIICDeviceSetReport : 228 -> 216
~ _DSIICDeviceSetToDefaults : 164 -> 152
~ _DSIICDeviceCommit : 184 -> 172
~ _bindFeature : 204 -> 192
~ _DSBrightnessExpertSetBrightness : 584 -> 572
~ _findY : 824 -> 820
~ _OSTypeFromString : 156 -> 148
```
