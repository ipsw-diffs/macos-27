## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

 764.41.11.0.0
-  __TEXT.__text: 0x41a02c
-  __TEXT.__objc_methlist: 0x2b464
+  __TEXT.__text: 0x419974
+  __TEXT.__objc_methlist: 0x2b47c
   __TEXT.__const: 0x143090
-  __TEXT.__cstring: 0x692de
+  __TEXT.__cstring: 0x690c6
   __TEXT.__oslogstring: 0x31611
   __TEXT.__gcc_except_tab: 0x1840
   __TEXT.__dlopen_cstrs: 0x23e
   __TEXT.__ustring: 0x6ea
-  __TEXT.__unwind_info: 0xddf0
+  __TEXT.__unwind_info: 0xdda8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x380
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12f88
+  __DATA_CONST.__objc_selrefs: 0x12f90
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x12a8
   __DATA_CONST.__objc_arraydata: 0x1690
   __DATA_CONST.__got: 0x67a8
-  __AUTH_CONST.__const: 0x5658
+  __AUTH_CONST.__const: 0x5688
   __AUTH_CONST.__cfstring: 0x3ea60
   __AUTH_CONST.__objc_const: 0x7a210
   __AUTH_CONST.__objc_intobj: 0x4200

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 25237
+  Functions: 25217
   Symbols:   49969
-  CStrings:  13990
+  CStrings:  13977
 
Symbols:
+ -[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]
+ -[FigCaptureSourceConfiguration initWithXPCEncoding:clientAuditToken:]
+ __71-[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]_block_invoke
+ ___71-[FigCaptureSessionConfiguration initWithXPCEncoding:clientAuditToken:]_block_invoke
+ ___block_descriptor_72_e8_32o_e36_B24?0Q8"NSObject<OS_xpc_object>"16l
+ _objc_msgSend$initWithXPCEncoding:clientAuditToken:
- FigDepthBlurEffectRenderingMaximumSimulatedAperture
- FigDepthBlurEffectRenderingMinimumSimulatedAperture
- _FigDepthBlurEffectRenderingMaximumSimulatedAperture
- _FigDepthBlurEffectRenderingMinimumSimulatedAperture
- __54-[FigCaptureSessionConfiguration initWithXPCEncoding:]_block_invoke
- ___54-[FigCaptureSessionConfiguration initWithXPCEncoding:]_block_invoke
CStrings:
+ "21:43:54"
- "*maximumSimulatedAperture > 0.0f"
- "*minimumSimulatedAperture > 0.0f"
- "0 == (effectiveVersion >> 16 )"
- "23:30:52"
- "Maximum simulated aperture invalid."
- "Minimum simulated aperture invalid."
- "Unsupported SDOFRendering parameters version"
- "Unsupported version of SDOF; cannot re-use v4 struct."
- "maximumSimulatedAperture"
- "minimumSimulatedAperture"
- "minimumSimulatedAperture is NULL"
- "renderingParametersData.bytes"
- "renderingParametersData.length == renderingParameters->header.size"
- "renderingParametersData.length >= sizeof( FigDepthBlurEffectRenderingParametersHeader )"
```
