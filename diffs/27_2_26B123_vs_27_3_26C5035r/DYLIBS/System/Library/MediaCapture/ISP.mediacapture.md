## ISP.mediacapture

> `/System/Library/MediaCapture/ISP.mediacapture`

```diff

-20.107.1.0.0
-  __TEXT.__text: 0x1b1bdc
+20.203.1.0.0
+  __TEXT.__text: 0x1b1f38
   __TEXT.__init_offsets: 0xc
-  __TEXT.__gcc_except_tab: 0x4adc
-  __TEXT.__const: 0x27d5d
-  __TEXT.__oslogstring: 0x1ceb9
-  __TEXT.__cstring: 0x16d2e
-  __TEXT.__unwind_info: 0x57d0
+  __TEXT.__gcc_except_tab: 0x4ad0
+  __TEXT.__const: 0x27d95
+  __TEXT.__oslogstring: 0x1cfb5
+  __TEXT.__cstring: 0x16d1b
+  __TEXT.__unwind_info: 0x57d8
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_methname: 0x0
-  __DATA_CONST.__const: 0x9140
+  __DATA_CONST.__const: 0x9160
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x28
   __DATA_CONST.__objc_selrefs: 0x2b0
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x2058
-  __AUTH_CONST.__cfstring: 0x8360
+  __AUTH_CONST.__const: 0x2078
+  __AUTH_CONST.__cfstring: 0x8380
   __AUTH_CONST.__weak_auth_got: 0xb0
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1360
-  __DATA.__data: 0x5afea8
-  __DATA.__bss: 0xab0
+  __AUTH_CONST.__auth_got: 0x1370
+  __DATA.__data: 0x5b00a8
+  __DATA.__bss: 0xac0
   __DATA.__common: 0x5728
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libamsupport.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5182
-  Symbols:   6729
-  CStrings:  5988
+  Functions: 5184
+  Symbols:   6736
+  CStrings:  5993
 
Symbols:
+ GCC_except_table545
+ GCC_except_table56
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table582
+ GCC_except_table614
+ GCC_except_table637
+ GCC_except_table66
+ GCC_except_table674
+ GCC_except_table718
+ GCC_except_table719
+ GCC_except_table724
+ GCC_except_table740
+ GCC_except_table743
+ GCC_except_table746
+ GCC_except_table752
+ GCC_except_table753
+ GCC_except_table756
+ GCC_except_table757
+ GCC_except_table761
+ GCC_except_table780
+ GCC_except_table784
+ GCC_except_table808
+ GCC_except_table809
+ GCC_except_table819
+ GCC_except_table827
+ GCC_except_table840
+ __ZL19IsSecureANDKEnabledP16ISPCaptureDeviceP16ISPCaptureStream
+ __ZL25SetActiveClientAuditTokenPKvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDevice
+ __ZN3ISP26ISPFrameReceiverBufferPool12activatePoolEv
+ __ZN3ISP9ISPDevice25SetActiveClientAuditTokenEPK13audit_token_t
+ __ZZL19IsSecureANDKEnabledP16ISPCaptureDeviceP16ISPCaptureStreamE19enabledWithDefaults
+ __ZZL19IsSecureANDKEnabledP16ISPCaptureDeviceP16ISPCaptureStreamE9onceToken
+ __ZZL25SetActiveClientAuditTokenPKvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDeviceE18kInvalidAuditToken
+ ____ZL19IsSecureANDKEnabledP16ISPCaptureDeviceP16ISPCaptureStream_block_invoke
+ _audit_token_to_pid
+ _kFigCaptureDeviceProperty_ActiveClientAuditToken
+ _kFigCaptureStreamSecureFaceIDConfigurationKey_MatchOperationTrigger
+ _kFigCaptureStreamSecureFaceIDConfigurationKey_MatchSequenceType
+ _kill
+ _sandbox_check_by_audit_token
- GCC_except_table547
- GCC_except_table571
- GCC_except_table574
- GCC_except_table581
- GCC_except_table610
- GCC_except_table635
- GCC_except_table677
- GCC_except_table716
- GCC_except_table717
- GCC_except_table722
- GCC_except_table737
- GCC_except_table738
- GCC_except_table744
- GCC_except_table748
- GCC_except_table751
- GCC_except_table754
- GCC_except_table755
- GCC_except_table759
- GCC_except_table778
- GCC_except_table782
- GCC_except_table806
- GCC_except_table807
- GCC_except_table817
- GCC_except_table821
- GCC_except_table838
- _CVPixelBufferPoolScanIOSurfaces
- __ZL17SetClientIsActivePKvP16ISPCaptureStreamP15ISPCaptureGroupP16ISPCaptureDevice
- __ZN3ISP26ISPFrameReceiverBufferPool12activatePoolEb
- __ZN3ISP26ISPFrameReceiverBufferPool19PreMapClientSurfaceEj
- __ZN3ISP9ISPDevice21ISP_SetDriverPropertyEjj
- __ZN3ISP9ISPDevice23ISP_PreMapClientSurfaceEj
- __ZN3ISP9ISPDevice33ISP_ReleasePreMappedClientSurfaceEj
- __ZN3ISPL41MyCVPixelBufferPoolScanIOSurfacesCallbackEP11__IOSurfacePNS_26ISPFrameReceiverBufferPoolE
- _kFigCaptureDeviceProperty_ClientIsActive
CStrings:
+ "%s - ActiveClient audit_token cleared\n"
+ "%s - ActiveClient audit_token set: 0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x\n"
+ "%s - HueMap output does not support enable after stream has started without it\n"
+ "%s - SetActiveClientAuditToken: unexpected CFData length %ld (expected %zu)\n"
+ "%s - enabledWithDefaults %{bool}d\n"
+ "%s - procName:%s / audit_token:0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x\n"
+ "ISPCaptureDevice: ActiveClientAuditToken is INVALID_AUDIT_TOKEN_VALUE, clearing\n"
+ "ISPCaptureDevice: set kFigCaptureDeviceProperty_ActiveClientAuditToken\n"
+ "IsSecureANDKEnabled_block_invoke"
+ "SetActiveClientAuditToken"
+ "isp.EnableAndk"
- "%s - HueMap output does not support enable/disable after stream has started\n"
- "%s - ISP_PreMapClientSurface failed: 0x%08X\n"
- "%s - procNameForCIL:%s / audit_token:0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x/0x%08x\n"
- "ISPCaptureDevice: set kFigCaptureDeviceProperty_ClientIsActive, isClientActive=%d, res=0x%08X\n\n"
- "ISPFrameReceiverBufferPool::%s - ISP_PreMapClientSurface failed: 0x%08X\n"
- "PreMapClientSurface"
```
