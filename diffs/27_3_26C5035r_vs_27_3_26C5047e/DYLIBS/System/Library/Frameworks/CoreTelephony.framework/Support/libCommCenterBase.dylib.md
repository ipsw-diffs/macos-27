## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

```diff

-13504.1.0.0.0
-  __TEXT.__text: 0xd0c68
+13508.0.0.0.0
+  __TEXT.__text: 0xd0a10
   __TEXT.__init_offsets: 0x20
   __TEXT.__objc_methlist: 0x110
-  __TEXT.__const: 0xce80
-  __TEXT.__cstring: 0x134b8
-  __TEXT.__gcc_except_tab: 0x13e3c
-  __TEXT.__oslogstring: 0x2849
-  __TEXT.__unwind_info: 0x5498
+  __TEXT.__const: 0xceb0
+  __TEXT.__cstring: 0x13321
+  __TEXT.__gcc_except_tab: 0x13e60
+  __TEXT.__oslogstring: 0x26f1
+  __TEXT.__unwind_info: 0x54a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x75f8
+  __DATA_CONST.__const: 0x7608
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_selrefs: 0x188
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__got: 0x208
-  __AUTH_CONST.__const: 0x14488
-  __AUTH_CONST.__cfstring: 0x2cc0
+  __AUTH_CONST.__const: 0x144f8
+  __AUTH_CONST.__cfstring: 0x2d00
   __AUTH_CONST.__objc_const: 0x200
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__auth_got: 0xbc8
+  __AUTH_CONST.__auth_got: 0xbc0
   __DATA.__objc_ivar: 0x8
   __DATA.__data: 0x70
   __DATA.__bss: 0x1

   - /usr/lib/libTelephonyUtilDynamic.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5752
-  Symbols:   9458
-  CStrings:  4463
+  Functions: 5763
+  Symbols:   9471
+  CStrings:  4454
 
Symbols:
+ __ZN28LazuliHealthMonitorInterface14addPushArrivalERK13PersonalityIDi
+ __ZN28LazuliHealthMonitorInterface17addMessageOutcomeERK13PersonalityIDRK17MessageHealthInfo
+ __ZN28LazuliHealthMonitorInterface21addProvisioningResultERK13PersonalityIDRK22ProvisioningHealthInfo
+ __ZN28LazuliHealthMonitorInterface22addPcscfConnectFailureERK13PersonalityID
+ __ZN28LazuliHealthMonitorInterface27addMessageEncryptionFailureERK13PersonalityID
+ __ZN2sd17getImsPhoneNumberERKNSt3__110shared_ptrIK8RegistryEERK13PersonalityIDb15QuickSwitchRoleRKNS1_I14CSIPhoneNumberEE
+ __ZN2sd30IMSConnectivityHelperInterface22restartPcscfResolutionEv
+ __ZNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEED1Ev
+ __ZTINSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEEE
+ __ZTSNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEEE
+ __ZTVNSt3__120__shared_ptr_emplaceI14CSIPhoneNumberNS_9allocatorIS1_EEEE
+ ___TUAssertTrigger
- __ZNK3xpc6object9to_stringEv
- __os_log_debug_impl
CStrings:
+ "AltPhoneNumber"
+ "kMessagesAppNotInstalled"
+ "kMlsControl"
+ "phonebook"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreTelephony/CSI/Source/Common/SmsPduEncoder.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreTelephony/CommCenter/CommCenterCommandDrivers/Sim/SubscriberDefinitions.cpp"
- "Assertion failure: ( %s ), in file %s, line: %d"
- "DisplayStatus [isOn=%{bool}d, isLocked=%{bool}d, isCoversheetActive=%{bool}d, isPasscodeSet=%{bool}d, isEffectivelyLocked=%{bool}d]"
- "Getting main bundle"
- "Input(%s) = %f"
- "Parsed %zu lines successfully"
- "Personality Info: %s - %s"
- "Sending OTASP success dialogue to UI"
- "ThumperID: %s, info: %p"
- "[conn %p] Connection closed."
- "[conn %p] Got REST message: %s"
- "not active"
```
