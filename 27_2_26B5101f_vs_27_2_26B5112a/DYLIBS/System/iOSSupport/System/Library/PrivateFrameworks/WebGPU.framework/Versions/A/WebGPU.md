## WebGPU

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebGPU.framework/Versions/A/WebGPU`

```diff

-625.2.7.1.0
-  __TEXT.__text: 0x2424d4
-  __TEXT.__objc_methlist: 0x200
+625.2.8.11.6
+  __TEXT.__text: 0x241c10
+  __TEXT.__objc_methlist: 0x654
   __TEXT.__const: 0x1e34
-  __TEXT.__gcc_except_tab: 0xa8cc
+  __TEXT.__gcc_except_tab: 0xa960
   __TEXT.__swift5_typeref: 0x7d8
-  __TEXT.__cstring: 0x400ec
+  __TEXT.__cstring: 0x4010c
   __TEXT.__constg_swiftt: 0xb7c
   __TEXT.__swift5_fieldmd: 0x400
   __TEXT.__swift5_builtin: 0xdc

   __TEXT.__swift5_types: 0x4c
   __TEXT.__swift5_protos: 0x50
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0x4750
+  __TEXT.__unwind_info: 0x47b0
   __TEXT.__eh_frame: 0xfe8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x2b38
   __DATA_CONST.__objc_classlist: 0x18
+  __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xaf8
+  __DATA_CONST.__objc_selrefs: 0xcc8
+  __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__got: 0x2a8
   __AUTH_CONST.__const: 0x4d10
   __AUTH_CONST.__cfstring: 0x3a00
-  __AUTH_CONST.__objc_const: 0x658
+  __AUTH_CONST.__objc_const: 0xc90
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__auth_got: 0x9a0
   __AUTH.__objc_data: 0xf0
   __AUTH.__data: 0x108
   __DATA.__objc_ivar: 0x60
-  __DATA.__data: 0x140
+  __DATA.__data: 0x320
   __DATA.__common: 0x90
   __DATA.__bss: 0xa50
   __DATA_DIRTY.__bss: 0x100

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 3641
-  Symbols:   4427
+  Functions: 3643
+  Symbols:   4462
   CStrings:  2754
 
Symbols:
+ GCC_except_table115
+ GCC_except_table127
+ GCC_except_table95
+ GCC_except_table98
+ __OBJC_$_PROP_LIST_MTLAllocation
+ __OBJC_$_PROP_LIST_MTLBuffer
+ __OBJC_$_PROP_LIST_MTLResource
+ __OBJC_$_PROP_LIST_MTLTexture
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLAllocation
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLBuffer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLResource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MTLTexture
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_MTLTexture
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLAllocation
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLBuffer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLResource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MTLTexture
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_REFS_MTLAllocation
+ __OBJC_$_PROTOCOL_REFS_MTLBuffer
+ __OBJC_$_PROTOCOL_REFS_MTLResource
+ __OBJC_$_PROTOCOL_REFS_MTLTexture
+ __OBJC_LABEL_PROTOCOL_$_MTLAllocation
+ __OBJC_LABEL_PROTOCOL_$_MTLBuffer
+ __OBJC_LABEL_PROTOCOL_$_MTLResource
+ __OBJC_LABEL_PROTOCOL_$_MTLTexture
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_$_MTLAllocation
+ __OBJC_PROTOCOL_$_MTLBuffer
+ __OBJC_PROTOCOL_$_MTLResource
+ __OBJC_PROTOCOL_$_MTLTexture
+ __OBJC_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_REFERENCE_$_MTLBuffer
+ __OBJC_PROTOCOL_REFERENCE_$_MTLTexture
+ __ZN3WTF6VectorIN6WebGPU5Queue23ProvisionalTextureClearELm0ENS_15CrashOnOverflowELm16ENS_10FastMallocEED1Ev
+ __ZN6WebGPU14CommandEncoder19addResidentResourceEPU22objcproto11MTLResource11objc_object
+ __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERK20WGPUImageCopyTexturemRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_objectPKS0_
+ __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERNS_7TextureEmmRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_objectPKS0_
+ _objc_msgSend$conformsToProtocol:
- GCC_except_table101
- GCC_except_table126
- GCC_except_table130
- GCC_except_table134
- GCC_except_table96
- __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERK20WGPUImageCopyTexturemRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_object
- __ZN6WebGPU14CommandEncoder20clearTextureIfNeededERNS_7TextureEmmRKNS_6DeviceEPU32objcproto21MTLBlitCommandEncoder11objc_object
CStrings:
+ "21.0.0 (clang-2100.3.34.1) [+internal-os]"
+ "static void WebGPU::CommandEncoder::clearTextureIfNeeded(Texture &, NSUInteger, NSUInteger, const Device &, __strong id<MTLBlitCommandEncoder>, const CommandEncoder * _Nullable)"
- "21.0.0 (clang-2100.4.1.1) [+internal-os]"
- "static void WebGPU::CommandEncoder::clearTextureIfNeeded(Texture &, NSUInteger, NSUInteger, const Device &, __strong id<MTLBlitCommandEncoder>)"
```
