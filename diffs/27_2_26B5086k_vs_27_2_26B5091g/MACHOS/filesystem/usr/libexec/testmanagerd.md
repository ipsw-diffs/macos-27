## testmanagerd

> `/usr/libexec/testmanagerd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`

```diff

-25417.0.0.0.0
-  __TEXT.__text: 0x9d524
-  __TEXT.__auth_stubs: 0x2410
-  __TEXT.__objc_stubs: 0x86e0
-  __TEXT.__objc_methlist: 0x66e8
-  __TEXT.__const: 0x2398
+25424.0.0.0.0
+  __TEXT.__text: 0x9f190
+  __TEXT.__auth_stubs: 0x2450
+  __TEXT.__objc_stubs: 0x87a0
+  __TEXT.__objc_methlist: 0x67f8
+  __TEXT.__const: 0x2408
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__swift5_typeref: 0x158c
-  __TEXT.__cstring: 0x63b0
-  __TEXT.__oslogstring: 0x7b53
+  __TEXT.__swift5_typeref: 0x1658
+  __TEXT.__cstring: 0x6410
+  __TEXT.__oslogstring: 0x7bf3
   __TEXT.__ustring: 0xf4
-  __TEXT.__objc_methname: 0x105ef
-  __TEXT.__objc_classname: 0x195a
-  __TEXT.__objc_methtype: 0x5b65
+  __TEXT.__objc_methname: 0x10961
+  __TEXT.__objc_classname: 0x198a
+  __TEXT.__objc_methtype: 0x5be5
   __TEXT.__gcc_except_tab: 0x980
-  __TEXT.__constg_swiftt: 0x9dc
+  __TEXT.__constg_swiftt: 0xa18
   __TEXT.__swift5_builtin: 0x118
-  __TEXT.__swift5_reflstr: 0x9df
-  __TEXT.__swift5_fieldmd: 0x998
+  __TEXT.__swift5_reflstr: 0xa1f
+  __TEXT.__swift5_fieldmd: 0x9c0
   __TEXT.__swift5_assocty: 0x150
   __TEXT.__swift5_proto: 0xf8
-  __TEXT.__swift5_types: 0xc0
-  __TEXT.__swift5_capture: 0xedc
+  __TEXT.__swift5_types: 0xc4
+  __TEXT.__swift5_capture: 0xf60
   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__swift_as_entry: 0xf4
   __TEXT.__swift_as_ret: 0xe4
   __TEXT.__swift_as_cont: 0x1e8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x30d8
+  __TEXT.__unwind_info: 0x3158
   __TEXT.__eh_frame: 0x2e18
-  __DATA_CONST.__const: 0x4c58
-  __DATA_CONST.__cfstring: 0x4d40
-  __DATA_CONST.__objc_classlist: 0x260
+  __DATA_CONST.__const: 0x4d98
+  __DATA_CONST.__cfstring: 0x4d80
+  __DATA_CONST.__objc_classlist: 0x268
   __DATA_CONST.__objc_catlist: 0x50
-  __DATA_CONST.__objc_protolist: 0x5a0
+  __DATA_CONST.__objc_protolist: 0x5a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0x208
+  __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x180
   __DATA_CONST.__objc_intobj: 0x948
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_arraydata: 0xd0
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_arrayobj: 0x48
-  __DATA_CONST.__auth_got: 0x1218
-  __DATA_CONST.__got: 0x9f0
-  __DATA_CONST.__auth_ptr: 0x8a0
-  __DATA.__objc_const: 0x139d0
-  __DATA.__objc_selrefs: 0x3330
-  __DATA.__objc_ivar: 0x548
-  __DATA.__objc_data: 0x1cd0
-  __DATA.__data: 0x44c0
+  __DATA_CONST.__auth_got: 0x1238
+  __DATA_CONST.__got: 0xa10
+  __DATA_CONST.__auth_ptr: 0x8d8
+  __DATA.__objc_const: 0x13f98
+  __DATA.__objc_selrefs: 0x33d0
+  __DATA.__objc_ivar: 0x54c
+  __DATA.__objc_data: 0x1d98
+  __DATA.__data: 0x4530
   __DATA.__bss: 0x1fe0
   __DATA.__common: 0x170
   __CGPreLoginApp.__cgpreloginapp: 0x0

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3983
-  Symbols:   8700
-  CStrings:  4439
+  Functions: 4032
+  Symbols:   8801
+  CStrings:  4471
 
Symbols:
+ -[XCTDApplicationLauncher activationPolicyForApplicationInfo:bundleID:]
+ -[XCTDRemoteAutomationSession _XCTD_fetchRunningApplications]
+ -[XCTestSession _XCT_fetchRunningApplicationsWithReply:]
+ -[XCTestSession ensureHasInteractionClientEntitlementWithError:]
+ -[XCTestSession hasInteractionClientEntitlement]
+ GCC_except_table109
+ GCC_except_table123
+ GCC_except_table128
+ GCC_except_table134
+ GCC_except_table31
+ GCC_except_table53
+ GCC_except_table83
+ OBJC_IVAR_$_XCTestSession._hasInteractionClientEntitlement
+ _$s20XCTAutomationSupport17XCTDisplayManagerC13isMainDisplayySbSo9CADisplayCFZTj
+ _$s9XCTDaemon23XCTDisplayManagerBridgeC13isMainDisplayySbSo9CADisplayCFZ
+ _$s9XCTDaemon23XCTDisplayManagerBridgeC13isMainDisplayySbSo9CADisplayCFZTo
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC010windowInfoD033_D58AE542A6C018B192FD17AD65B6D63BLLSaySDys11AnyHashableVypGGycvpWvd
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC015applicationInfoD006windowfD0ACSaySDys11AnyHashableVypGGyc_AIyctcfCTq
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC015applicationInfoD033_D58AE542A6C018B192FD17AD65B6D63BLLSaySDys11AnyHashableVypGGycvpWvd
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC16activationPolicy33_D58AE542A6C018B192FD17AD65B6D63BLL18forApplicationInfo4typeSo024XCTApplicationActivationF0VSDys11AnyHashableVypG_SSSgtF
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC19onScreenWindowInfos33_D58AE542A6C018B192FD17AD65B6D63BLLSaySDys11AnyHashableVypGGyFZ
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC21runningUIApplicationsSaySo21XCTRunningApplicationCGyF
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC21runningUIApplicationsSaySo21XCTRunningApplicationCGyFSiycfu1_Tf2i_n
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC21runningUIApplicationsSaySo21XCTRunningApplicationCGyFSiycfu1_Tf2i_nTA
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC21runningUIApplicationsSaySo21XCTRunningApplicationCGyFSiycfu2_TA
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC21runningUIApplicationsSaySo21XCTRunningApplicationCGyFTo
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC23runningApplicationInfos33_D58AE542A6C018B192FD17AD65B6D63BLL23launchServicesFrameworkSaySDys11AnyHashableVypGGSo010XCTDLaunchrS0_p_tFZ
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderC26onScreenWindowsByProcessID33_D58AE542A6C018B192FD17AD65B6D63BLLSDys5Int32VSaySo9XCTWindowCGGyF
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCACycfc
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCACycfcSaySDys11AnyHashableVypGGycfU_TA
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCACycfcSaySDys11AnyHashableVypGGycfu_TA
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCACycfcTo
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCMF
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCMa
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCMf
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCMn
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCN
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCfD
+ _$s9XCTDaemon31XCTDRunningApplicationsProviderCfETo
+ _$sSDyq_Sgxcigs5Int32V_SaySo9XCTWindowCGTg5
+ _$sSa20_reserveCapacityImpl07minimumB013growForAppendySi_SbtFSo21XCTRunningApplicationC_Tg5
+ _$sSa5countSivgSo21XCTRunningApplicationC_Tg5
+ _$sSaySo9XCTWindowCGIgo_ACIegr_TR0128$s9XCTDaemon31XCTDRunningApplicationsProviderC26onScreenWindowsByProcessID33_D58AE542A6C018B192FD17AD65B6D63BLLSDys5Int32VSaySo9A13CGGyFAJyXEfu_Tf3npf_n
+ _$sSaySo9XCTWindowCGMR
+ _$sSaySo9XCTWindowCGMd
+ _$sSo18CGWindowListOptionVSQSCSQ2eeoiySbx_xtFZTW
+ _$sSo18CGWindowListOptionVSYSCSY8rawValue03RawE0QzvgTW
+ _$sSo18CGWindowListOptionVs0C3SetSCsACP8rawValuex03RawF0Qz_tcfCTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP10isSuperset2ofSbx_tFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP12intersectionyxxFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP16formIntersectionyyxFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP6insertySb8inserted_7ElementQz17memberAfterInserttAHnFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP8containsySb7ElementQzFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACP8isSubset2ofSbx_tFTW
+ _$sSo18CGWindowListOptionVs10SetAlgebraSCsACPxycfCTW
+ _$sSo21XCTRunningApplicationC8bundleID07processD016activationPolicy0E4Name7windowsABSS_s5Int32VSo024XCTApplicationActivationG0VSSSgSaySo9XCTWindowCGtcfcTO
+ _$sSo21XCTRunningApplicationCML
+ _$sSo21XCTRunningApplicationCMaTm
+ _$sSo9XCTWindowCML
+ _$ss10SetAlgebraPsE10isSuperset2ofSbx_tFSo18CGWindowListOptionV_Tgq5
+ _$ss10SetAlgebraPsE8isSubset2ofSbx_tFSo18CGWindowListOptionV_Tgq5
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSDys11AnyHashableVypG_Tg5
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
+ _$ss17_NativeDictionaryVys5Int32VSaySo9XCTWindowCGGMR
+ _$ss17_NativeDictionaryVys5Int32VSaySo9XCTWindowCGGMd
+ _$ss22__RawDictionaryStorageC4find_9hashValues10_HashTableV6BucketV6bucket_Sb5foundtx_SitSHRzlFs5Int32V_Tg5
+ _$ss22__RawDictionaryStorageC4findys10_HashTableV6BucketV6bucket_Sb5foundtxSHRzlFs5Int32V_Tg5
+ _$ss23_ContiguousArrayStorageCySDys11AnyHashableVypGGMR
+ _$ss23_ContiguousArrayStorageCySDys11AnyHashableVypGGMd
+ _$ss2eeoiySbx_xtSYRzSQ8RawValueRpzlFSo18CGWindowListOptionV_Tgq5
+ _$ss5Int32VSHsWP
+ _$ss6HasherV5_hash4seed5bytes5countS2i_s6UInt64VSitFZ
+ _$ss9OptionSetPs7ElementQzRszrlE8containsySbxFSo012CGWindowListA0V_Tgq5
+ _$ss9OptionSetPs7ElementQzRszs17FixedWidthInteger8RawValueRpzrlE6insertySb8inserted_x17memberAfterInserttxFSo012CGWindowListA0V_Tgq5
+ _$ss9OptionSetPsE12intersectionyxxFSo012CGWindowListA0V_Tgq5
+ _$ss9OptionSetPss17FixedWidthInteger8RawValueRpzrlE16formIntersectionyyxFSo012CGWindowListA0V_Tgq5
+ _$ss9OptionSetPss17FixedWidthInteger8RawValueRpzrlExycfCSo012CGWindowListA0V_Tgq5
+ _$sxRi_zRi0_zlySaySo9XCTWindowCGIsegr_SgWOe
+ _$sypSgWOh
+ _OBJC_CLASS_$_XCTRunningApplication
+ _OBJC_CLASS_$_XCTWindow
+ _OBJC_CLASS_$__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ _OBJC_METACLASS_$__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ _OUTLINED_FUNCTION_157
+ _OUTLINED_FUNCTION_158
+ __DATA__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ __INSTANCE_METHODS__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ __IVARS__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ __METACLASS_DATA__TtC9XCTDaemon31XCTDRunningApplicationsProvider
+ _flat unique So27XCTDLaunchServicesFramework_p
+ _kCGWindowNumber
+ _objc_msgSend$activationPolicyForApplicationInfo:bundleID:
+ _objc_msgSend$ensureHasInteractionClientEntitlementWithError:
+ _objc_msgSend$hasInteractionClientEntitlement
+ _objc_msgSend$initWithBundleID:processID:activationPolicy:processName:windows:
+ _objc_msgSend$initWithWindowID:
+ _objc_msgSend$runningUIApplications
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _symbolic SaySDy_____ypGG s11AnyHashableV
+ _symbolic SaySDy_____ypGGyc s11AnyHashableV
+ _symbolic SaySo21XCTRunningApplicationCG
+ _symbolic SaySo9XCTWindowCG
+ _symbolic _____ 9XCTDaemon31XCTDRunningApplicationsProviderC
+ _symbolic _____XDXMT 9XCTDaemon31XCTDRunningApplicationsProviderC
+ _symbolic _____XMT 9XCTDaemon31XCTDRunningApplicationsProviderC
+ _symbolic ______p So27XCTDLaunchServicesFrameworkP
+ _symbolic _____ySDy_____ypGG s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____SaySo9XCTWindowCGG s17_NativeDictionaryV s5Int32V
- GCC_except_table107
- GCC_except_table121
- GCC_except_table126
- GCC_except_table133
- GCC_except_table30
- GCC_except_table52
- GCC_except_table81
CStrings:
+ "Found %ld running UI applications out of %ld candidates"
+ "Not authorized for performing this action."
+ "Process with pid %d has entitlement '%{public}@' and can access privileged interaction APIs."
+ "Q32@0:8@16@24"
+ "TB,R,V_hasInteractionClientEntitlement"
+ "^v52@0:8r^i16I24^@28@\"OS_dispatch_queue\"36@?<v@?i@\"NSDictionary\">44"
+ "_TtC9XCTDaemon31XCTDRunningApplicationsProvider"
+ "_XCTD_fetchRunningApplications"
+ "_XCT_fetchRunningApplicationsWithReply:"
+ "_hasInteractionClientEntitlement"
+ "activationPolicyForApplicationInfo:bundleID:"
+ "applicationInfoProvider"
+ "cancel:"
+ "cancel:touchCount:"
+ "cancelAtAllActivePoints"
+ "cancelAtPoints:touchCount:"
+ "com.apple.private.dt.xctest.interaction-client"
+ "dragAndCancelWithStartPoint:endPoint:duration:"
+ "dragAndCancelWithStartPoint:endPoint:duration:radius:"
+ "dragAndCancelWithStartPoint:endPoint:duration:tapAndWait:radius:"
+ "ensureHasInteractionClientEntitlementWithError:"
+ "fetch running applications"
+ "flickAndCancelWithStartPoint:endPoint:duration:"
+ "flickAndCancelWithStartPoint:endPoint:duration:radius:"
+ "hasInteractionClientEntitlement"
+ "initWithBundleID:processID:activationPolicy:processName:windows:"
+ "initWithWindowID:"
+ "isMainDisplay:"
+ "runningUIApplications"
+ "tapAndCancel:"
+ "tapAndCancel:radius:"
+ "v24@0:8@?<v@?@\"NSArray\"@\"NSError\">16"
+ "windowInfoProvider"
- "monitor application capability"
```
