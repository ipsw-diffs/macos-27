## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

```diff

 1155.40.8.0.0
-  __TEXT.__text: 0xb00d8
+  __TEXT.__text: 0xb23b8
   __TEXT.__objc_methlist: 0x262c
-  __TEXT.__cstring: 0x21a53
+  __TEXT.__cstring: 0x22334
   __TEXT.__const: 0xc2c1
-  __TEXT.__gcc_except_tab: 0x3b6c
+  __TEXT.__gcc_except_tab: 0x3b94
   __TEXT.__dlopen_cstrs: 0x63
   __TEXT.__oslogstring: 0xad5
-  __TEXT.__unwind_info: 0x36b0
+  __TEXT.__unwind_info: 0x36f0
   __TEXT.__eh_frame: 0x7c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2de8
+  __DATA_CONST.__const: 0x2e30
   __DATA_CONST.__objc_classlist: 0x1f8
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__weak_got: 0x10
   __DATA_CONST.__objc_selrefs: 0xbf8
   __DATA_CONST.__got: 0x188
-  __AUTH_CONST.__const: 0x1630
-  __AUTH_CONST.__cfstring: 0xf120
+  __AUTH_CONST.__const: 0x1660
+  __AUTH_CONST.__cfstring: 0xf5c0
   __AUTH_CONST.__objc_const: 0x4908
   __AUTH_CONST.__weak_auth_got: 0x20
-  __AUTH_CONST.__auth_got: 0xda0
+  __AUTH_CONST.__auth_got: 0xdb8
   __AUTH.__objc_data: 0x13b0
   __AUTH.__data: 0x20
   __AUTH.__thread_vars: 0x18

   - /usr/lib/libz.1.dylib
   - /usr/lib/updaters/libAppleTconUARPUpdater.dylib
   - /usr/lib/updaters/libT200Updater.dylib
-  Functions: 3826
-  Symbols:   5208
-  CStrings:  4817
+  - /usr/lib/updaters/libVelozUpdater.dylib
+  Functions: 3838
+  Symbols:   5234
+  CStrings:  4885
 
Symbols:
+ _AppleTCONDPUnifiedRestoreInfoCopyFirmware
+ _AppleTCONDPUnifiedRestoreInfoCreateRequest
+ _AppleTCONDPUnifiedRestoreInfoGetTags
+ _VelozUpdaterCopyFirmwareWithLogging
+ _VelozUpdaterCreateRequestWithLogging
+ _VelozUpdaterGetTagsWithLogging
+ __ZL23GetDisplayControllerTagPK14__CFDictionaryS1_
+ __ZN20AppleTCONDPUnifiedFW14decompressGzipEPK8__CFData
+ __ZN20AppleTCONDPUnifiedFW16applyBxdiffPatchEPKhmS1_m
+ __ZN20AppleTCONDPUnifiedFWC1EPK8__CFDatajjjj
+ __ZN20AppleTCONDPUnifiedFWC2EPK8__CFDatajjjj
+ __ZN20AppleTCONDPUnifiedFWD1Ev
+ __ZN20AppleTCONDPUnifiedFWD2Ev
+ __ZZN20AppleTCONDPUnifiedFW16applyBxdiffPatchEPKhmS1_mEN11Accumulator5writeEPvPKvy
+ _dlclose
+ _kAppleTCONCommonTagDeviceDebugRegisterAccess
+ _kAppleTCONCommonTagDeviceDisplayController0Firmware
+ _kAppleTCONCommonTagDeviceDisplayController1Firmware
+ _kAppleTCONCommonTagDeviceDisplayController2Firmware
+ _kAppleTCONCommonTagDeviceDisplayController3Firmware
+ _kAppleTCONCommonTagDeviceHWCID
+ _kAppleTCONCommonTagDeviceMinorVersion
+ _kAppleTCONCommonTagDeviceVendorID
+ _kAppleTCONCommonTagMeasurementConfigDigest
+ _printf
+ _puts
CStrings:
+ "/usr/lib/libParallelCompression.dylib"
+ "Address"
+ "AppleTCONDPUnifiedFW"
+ "AppleTCONDPUnifiedFW: BXPatch5 failed (result=%d)\n"
+ "AppleTCONDPUnifiedFW: BXPatch5 symbol not found: %s\n"
+ "AppleTCONDPUnifiedFW: gzip ISIZE is zero, file may be corrupt"
+ "AppleTCONDPUnifiedFW: gzip inflate failed, status=%d msg=%s\n"
+ "AppleTCONDPUnifiedFW: gzip input too small (%ld bytes)\n"
+ "AppleTCONDPUnifiedFW: init fails."
+ "AppleTCONDPUnifiedFW: libParallelCompression unavailable: %s\n"
+ "AppleTCONDPUnifiedRestoreInfoCopyFirmware"
+ "AppleTCONDPUnifiedRestoreInfoCopyFirmware: Empty AppleTCONDPUnified firmware file"
+ "AppleTCONDPUnifiedRestoreInfoCopyFirmware: invalid FirmwareOverride type"
+ "AppleTCONDPUnifiedRestoreInfoCopyFirmware: options is NULL"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: BuildIdentity is NULL in input options"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: Cannot get DeviceInfo"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: CreateMeasurementDict fails for AppleTCONDPUnified"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: CreateRequestDictForTATSU fails."
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: kUpdaterFirmware is NULL in input options"
+ "AppleTCONDPUnifiedRestoreInfoCreateRequest: options is NULL"
+ "AppleTCONDPUnifiedRestoreInfoGetTags"
+ "AppleTCONDPUnifiedRestoreInfoGetTags: Cannot allocate memory for outputDict"
+ "AppleTCONDPUnifiedRestoreInfoGetTags: Cannot allocate memory for tagsInBI"
+ "AppleTCONDPUnifiedRestoreInfoGetTags: Cannot allocate memory for tagsInTssResponse"
+ "AppleTCONDPUnifiedRestoreInfoGetTags: options is NULL"
+ "BXPatch5"
+ "Baobab,DebugRegisterAccess"
+ "Baobab,DisplayController0"
+ "Baobab,DisplayController1"
+ "Baobab,DisplayController2"
+ "Baobab,DisplayController3"
+ "Baobab,HWCID"
+ "Baobab,MinorVersion"
+ "Baobab,VendorID"
+ "Build"
+ "ConfigDigest"
+ "ConfigSubCmd"
+ "Configs"
+ "Configurations"
+ "CreateDataFromFile: Missing display controller tag"
+ "CreateDataFromFile: Missing kAppleTCONDPUnifiedBuildIdentityPathKey"
+ "DeviceID"
+ "DirectNVMUpdatePreferred"
+ "FWConfigAPICMD"
+ "FWConfigDigest"
+ "FWConfigs"
+ "FWImg"
+ "FWImgDigest"
+ "GetFirmwareDigest"
+ "GetFirmwareImage: FW getConfigDigest failed"
+ "GetFirmwareImage: FW getImageDigest failed"
+ "HWConfig"
+ "Helsinki_Restore_Host-58.2.3.1"
+ "ImageProperties"
+ "Length"
+ "Major"
+ "Minor"
+ "Option2"
+ "PORUpdatePreferred"
+ "Patches"
+ "Payload"
+ "ProtectedRegions"
+ "Veloz"
+ "bxdiff"
+ "complete_binary"
+ "major"
+ "patches_policy"
+ "version_check_policy"
- "Helsinki_Restore_Host-58.1.4"
```
