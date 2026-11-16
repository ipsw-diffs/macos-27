## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness`

```diff

-2300.60.30.501.1
-  __TEXT.__text: 0x1773c0
-  __TEXT.__objc_methlist: 0xe1b0
-  __TEXT.__cstring: 0xd92a
-  __TEXT.__const: 0x130c8
-  __TEXT.__gcc_except_tab: 0x21b8
-  __TEXT.__oslogstring: 0x1ab5d
+2300.60.34.0.2
+  __TEXT.__text: 0x179320
+  __TEXT.__objc_methlist: 0xe2c8
+  __TEXT.__cstring: 0xda6a
+  __TEXT.__const: 0x13138
+  __TEXT.__gcc_except_tab: 0x219c
+  __TEXT.__oslogstring: 0x1adfd
   __TEXT.__dlopen_cstrs: 0x10d
   __TEXT.__swift5_typeref: 0xf36
   __TEXT.__constg_swiftt: 0xd80
-  __TEXT.__swift5_reflstr: 0xbf4
+  __TEXT.__swift5_reflstr: 0xc04
   __TEXT.__swift5_assocty: 0x288
-  __TEXT.__swift5_fieldmd: 0x1240
+  __TEXT.__swift5_fieldmd: 0x124c
   __TEXT.__swift5_builtin: 0x168
   __TEXT.__swift5_capture: 0x41c
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_proto: 0x308
   __TEXT.__swift5_types: 0x144
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x7bc0
+  __TEXT.__unwind_info: 0x7c38
   __TEXT.__eh_frame: 0xbd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1368
+  __DATA_CONST.__const: 0x13d8
   __DATA_CONST.__objc_classlist: 0x770
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x5c78
+  __DATA_CONST.__objc_selrefs: 0x5d40
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x610
   __DATA_CONST.__objc_arraydata: 0xf10
-  __DATA_CONST.__got: 0x7c0
-  __AUTH_CONST.__const: 0x6068
-  __AUTH_CONST.__cfstring: 0xf320
-  __AUTH_CONST.__objc_const: 0x3a1a0
+  __DATA_CONST.__got: 0x7c8
+  __AUTH_CONST.__const: 0x6130
+  __AUTH_CONST.__cfstring: 0xf360
+  __AUTH_CONST.__objc_const: 0x3a398
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0xd08
   __AUTH_CONST.__objc_floatobj: 0x390
   __AUTH_CONST.__objc_arrayobj: 0x618
   __AUTH_CONST.__objc_dictobj: 0x690
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x1330
+  __AUTH_CONST.__auth_got: 0x1350
   __AUTH.__objc_data: 0x2cb0
   __AUTH.__data: 0x6b0
-  __DATA.__objc_ivar: 0x19d0
+  __DATA.__objc_ivar: 0x1a04
   __DATA.__data: 0x671f8
-  __DATA.__bss: 0x6440
+  __DATA.__bss: 0x6450
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x2198
   __DATA_DIRTY.__data: 0x510

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8722
-  Symbols:   13462
-  CStrings:  4993
+  Functions: 8758
+  Symbols:   13553
+  CStrings:  5029
 
Symbols:
+ -[CBALSService orientation]
+ -[CBColorFilter frontPlacement]
+ -[CBColorFilter setSyncDisplayPolicy:]
+ -[CBColorFilter syncDisplayPolicy]
+ -[CBColorModuleShared copyTelemetrySnapshot]
+ -[CBDisplayBrightnessClient .cxx_construct]
+ -[CBDisplayBrightnessClient .cxx_destruct]
+ -[CBDisplayBrightnessClient brightnessObserver]
+ -[CBDisplayContainerSKL handleExtGenericAvailability:from:]
+ -[CBDisplayModuleExtGeneric announceAvailability:]
+ -[CBDisplayModuleExtGeneric endFirstReadSignpost:]
+ -[CBDisplayModuleExtGeneric firstReadSucceededWithCurrent:max:]
+ -[CBDisplayModuleExtGeneric handleFirstRead:linkNotReady:]
+ -[CBDisplayModuleExtGeneric performFirstRead]
+ -[CBDisplayModuleExtGeneric scheduleFirstReadAfter:]
+ -[CBIndicatorBrightnessModule canJumpToTargetIndicatorBrightness]
+ -[CBIndicatorBrightnessModule isPipelineStalled]
+ -[CBIndicatorBrightnessModule isThermalPressureCritical]
+ -[CBIndicatorBrightnessModule jumpTo:forReason:withForce:]
+ -[CBIndicatorBrightnessModule recordSwapStall:]
+ -[CBIndicatorBrightnessModule setThermalPressure:]
+ -[CBIndicatorBrightnessModule startMonitoringForSwapStalls]
+ -[CBIndicatorBrightnessModule stopMonitoringForSwapStalls]
+ GCC_except_table137
+ GCC_except_table155
+ GCC_except_table156
+ GCC_except_table37
+ GCC_except_table54
+ GCC_except_table58
+ GCC_except_table76
+ GCC_except_table83
+ _CBU_IsMultiPanelTelemetryEnabled
+ _CFXClearForceAdaptationOnNextAmbientChange
+ _CFXGetCurrentHarmonyMatrix
+ _CFXSetLogIdentity
+ _IOAVServiceGetLinkData
+ _IOAVServiceGetProtectionStatus
+ _OBJC_IVAR_$_CBALSService._orientation
+ _OBJC_IVAR_$_CBColorFilter._syncDisplayPolicy
+ _OBJC_IVAR_$_CBDisplayBrightnessClient._brightnessGranularity
+ _OBJC_IVAR_$_CBDisplayBrightnessClient._brightnessObserver
+ _OBJC_IVAR_$_CBDisplayBrightnessClient._lastBrightness
+ _OBJC_IVAR_$_CBDisplayBrightnessClient._observerLock
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._firstReadAttempts
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._firstReadGeneration
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._firstReadSignpost
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._firstReadStart
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._linkWaitExpired
+ _OBJC_IVAR_$_CBDisplayModuleExtGeneric._live
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._consecutiveSwapStalledCount
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOffRequestTimestampUs
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOnRequestTimestampUs
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._swapStallObserverToken
+ __CFXLogHandle
+ __CFXSharedLogHandle.log
+ __CFXSharedLogHandle.once
+ __OBJC_$_PROP_LIST_CBDisplayBrightnessClientProtocol
+ __OBJC_$_PROTOCOL_CLASS_METHODS_CBDisplayBrightnessClientProtocol
+ __ZL11readControlP13__IOAVServicehPU19objcproto9OS_os_log8NSObject
+ __ZL12kReadBackoff
+ __ZL16ioReturnToStringi
+ __ZN4AABC30UpdateMultiPanelTelemetryStateEP26CBMultiPanelTelemetryState
+ ___45-[CBDisplayModuleExtGeneric performFirstRead]_block_invoke
+ ___45-[CBDisplayModuleExtGeneric performFirstRead]_block_invoke_2
+ ___47-[CBIndicatorBrightnessModule recordSwapStall:]_block_invoke
+ ___52-[CBDisplayModuleExtGeneric scheduleFirstReadAfter:]_block_invoke
+ ___59-[CBDisplayContainerSKL handleExtGenericAvailability:from:]_block_invoke
+ ___59-[CBIndicatorBrightnessModule startMonitoringForSwapStalls]_block_invoke
+ ____CFXSharedLogHandle_block_invoke
+ ____ZN4AABC30UpdateMultiPanelTelemetryStateEP26CBMultiPanelTelemetryState_block_invoke
+ ___block_descriptor_40_e8_32o_e20_v40?0{?=QIBBBffff}8l
+ ___block_descriptor_40_e8_32o_e35_v24?0^{__IOHIDServiceClient=}8^v16l
+ ___block_descriptor_40_e8_32r_e20_v40?0{?=QIBBBffff}8l
+ ___block_descriptor_48_e8_32o_e20_v40?0{?=QIBBBffff}8l
+ ___block_descriptor_65_e8_32o40o_e5_v8?0l
+ ___block_descriptor_68_e8_32o_e5_v8?0l
+ _kCBDisplayBrightnessValue
+ _objc_msgSend$announceAvailability:
+ _objc_msgSend$brightnessGranularity
+ _objc_msgSend$brightnessObserver
+ _objc_msgSend$canJumpToTargetIndicatorBrightness
+ _objc_msgSend$copyTelemetrySnapshot
+ _objc_msgSend$endFirstReadSignpost:
+ _objc_msgSend$firstReadSucceededWithCurrent:max:
+ _objc_msgSend$frontPlacement
+ _objc_msgSend$handleALSEvent:alsID:
+ _objc_msgSend$handleCoexUpdate:node:
+ _objc_msgSend$handleDisplayOff
+ _objc_msgSend$handleExtGenericAvailability:from:
+ _objc_msgSend$handleFirstRead:linkNotReady:
+ _objc_msgSend$isPipelineStalled
+ _objc_msgSend$isThermalPressureCritical
+ _objc_msgSend$jumpTo:forReason:withForce:
+ _objc_msgSend$performFirstRead
+ _objc_msgSend$recordSwapStall:
+ _objc_msgSend$registerBrightnessObserver:
+ _objc_msgSend$scheduleFirstReadAfter:
+ _objc_msgSend$setLux:forALSID:
+ _objc_msgSend$setThermalPressure:
+ _objc_msgSend$setTrustedALS:
+ _objc_msgSend$startMonitoringForSwapStalls
+ _objc_msgSend$stopMonitoringForSwapStalls
+ _objc_msgSend$trigger:
+ _os_release
+ _os_variant_has_internal_content
- -[CBDisplayModuleExtGeneric readControl:currentValue:maxValue:]
- -[CBIndicatorBrightnessModule jumpTo:]
- GCC_except_table136
- GCC_except_table53
- _OBJC_IVAR_$_CBDisplayBrightnessClient._observers
- _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOffTimestampUs
- _OBJC_IVAR_$_CBIndicatorBrightnessModule._lastSILOnTimestampUs
- __CFXLogHandle.log
- __CFXLogHandle.once
- ____CFXLogHandle_block_invoke
- ___block_descriptor_40_e8_32o_e19_v40?0{?=QIBBffff}8l
- ___block_descriptor_48_e8_32o_e19_v40?0{?=QIBBffff}8l
- _objc_msgSend$jumpTo:
- _objc_msgSend$readControl:currentValue:maxValue:
CStrings:
+ "Backboardd restarted"
+ "Color filter display sync policy %s; valid services: %{public}@"
+ "ColorTelemetrySnapshot"
+ "ExtGenericAvailability"
+ "ExtGenericFirstRead"
+ "ExtGenericReadControl"
+ "ExtGenericWriteControl"
+ "Jumping to target indicator brightness: %f for reason: %s (forced=%d)"
+ "NACK"
+ "Ramp too long"
+ "ReadAttempts"
+ "Render pipeline stalled"
+ "Swap stall state changed: stalled=%d (%u consecutive)"
+ "Thermal pressure critical"
+ "[Harmony thresholds] 1.5D Harmony: deltauv=%f, uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
+ "[Harmony thresholds] Mitigation triggered -> 1D Harmony: deltauv=%f, uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
+ "[Linear Weighted] ALS services: %@"
+ "[Linear Weighted] service %p xy= %f | %f ratio=%f"
+ "[Service:0x%llX] Failed to create CBHIDEvent -> dropping event"
+ "bad reply"
+ "brightness control read failed for display %u: %{public}s (%{public}s 0x%08x) after %u attempts"
+ "colorALSMask"
+ "com.apple.CoreBrightness.ColorEffects.%d"
+ "com.apple.CoreBrightness.ExtGeneric"
+ "content protection negotiating"
+ "control=0x%02x"
+ "control=0x%02x value=%u"
+ "defer"
+ "display"
+ "display %u online — brightness %u/%u (%.2f) after %u attempt(s)"
+ "display %u: %.0f ms since start, reading without checking the link"
+ "display %u: %{public}s, deferring read for %.0f ms"
+ "display %u: brightness control %{public}s"
+ "display %u: probing brightness control, first read in %.0f ms"
+ "display %u: read control attempt %u/%u: %{public}s (%{public}s 0x%08x), retrying in %.0f ms"
+ "display %u: stop (live %d, %u read attempt(s))"
+ "display %u: write control 0x%02x failed: %{public}s 0x%08x, level %u"
+ "display=%u"
+ "display=%u available=%d"
+ "harmonyStrength"
+ "id=0x%lX location=%lu internal=%d orientation=%lu placement=%lu"
+ "link down"
+ "not read"
+ "outcome=%{public}s attempts=%u elapsed=%.0fms"
+ "read control 0x%02x: bad reply %{public}.*P"
+ "reply failed"
+ "request failed"
+ "result=%{public}s ret=0x%08x current=%u max=%u"
+ "ret=0x%08x"
+ "stale handle"
+ "stopped"
+ "unknown"
+ "v40@?0{?=QIBBBffff}8"
+ "write incomplete"
- "InternalBuild"
- "Jumping to target indicator brightness: %f"
- "The response didn't contain brightness or it had wrong type"
- "Thermal Pressure Critical! Snapping to target indicator brightness %f"
- "[Harmony thresholds] 1.5D Harmony: uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
- "[Harmony thresholds] Mitigation triggered -> 1D Harmony: uv_thr1(new_ramp)=%f, uv_thr2(interrupt)=%f Lux=%f"
- "brightness control read failed for display %u"
- "display %u online — brightness %u/%u (%.2f)"
- "id=0x%lX location=%lu internal=%d placement=%lu"
- "read control reply failed: 0x%x"
- "read control request failed: 0x%x"
- "read control: bad reply — opcode=0x%02x (expected 0x%02x) result=0x%02x (expected 0x%02x) control=0x%02x (expected 0x%02x)"
- "readControl: opcode=0x%02x (avService=%p)"
- "start: displayId=%u"
- "start: probe OK — cur=%u max=%u userBrightness=%.4f"
- "stop: displayId=%u avService=%p"
- "v40@?0{?=QIBBffff}8"
- "write control 0x%02x failed: 0x%x"
```
