## MTLCompilerService

> `/System/Library/Frameworks/Metal.framework/Versions/A/XPCServices/MTLCompilerService.xpc/Contents/MacOS/MTLCompilerService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`

```diff

-384.5.0.0.0
-  __TEXT.__text: 0x4ff4
-  __TEXT.__auth_stubs: 0x760
+384.7.0.0.0
+  __TEXT.__text: 0x6340
+  __TEXT.__auth_stubs: 0x770
   __TEXT.__gcc_except_tab: 0x38c
   __TEXT.__const: 0xb0
-  __TEXT.__oslogstring: 0x569
-  __TEXT.__cstring: 0x660
-  __TEXT.__unwind_info: 0x388
+  __TEXT.__oslogstring: 0x567
+  __TEXT.__cstring: 0xb10
+  __TEXT.__unwind_info: 0x410
   __DATA_CONST.__const: 0x1a0
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x3b8
+  __DATA_CONST.__auth_got: 0x3c0
   __DATA_CONST.__got: 0xb8
   __DATA.__data: 0x560
   __DATA.__bss: 0x68

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 137
-  Symbols:   330
-  CStrings:  94
+  Functions: 173
+  Symbols:   337
+  CStrings:  149
 
Symbols:
+ GCC_except_table40
+ GCC_except_table47
+ GCC_except_table50
+ GCC_except_table53
+ GCC_except_table58
+ GCC_except_table62
+ GCC_except_table68
+ GCC_except_table69
+ GCC_except_table73
+ GCC_except_table74
+ _OUTLINED_FUNCTION_3
+ _OUTLINED_FUNCTION_4
+ _OUTLINED_FUNCTION_5
+ _OUTLINED_FUNCTION_6
+ __ZL13MTLBlobRejectPKc
+ __ZNK18MTLRequestBlobView12checkCStringEyy
+ _memchr
- GCC_except_table38
- GCC_except_table43
- GCC_except_table48
- GCC_except_table49
- GCC_except_table56
- GCC_except_table60
- GCC_except_table64
- GCC_except_table67
- GCC_except_table71
- GCC_except_table72
CStrings:
+ "Invalid request data"
+ "Request blob validation failed: %{public}s"
+ "airScript"
+ "archiveID"
+ "archiveID header does not fit requestSize"
+ "archiveID.archiverBasePath"
+ "archiverBasePath"
+ "binaryArchiveID"
+ "binaryRequest.bitCode"
+ "binaryRequest.functionName"
+ "binaryRequest.pluginData"
+ "buildBinaries header does not fit requestSize"
+ "buildLibraryFromSource header does not fit requestSize"
+ "builtin header does not fit requestSize"
+ "builtinScript"
+ "cispi header does not fit requestSize"
+ "cispi.funcInfo"
+ "cispi.funcInfo.arguments"
+ "cispi.funcInfo.moduleIndex"
+ "cispi.funcNames"
+ "cispi.module.bitCode"
+ "cispi.moduleInfo"
+ "dylibInstallName"
+ "entries array exceeds requestSize"
+ "entry.airScript"
+ "entry.binary"
+ "entry.bitCode"
+ "entry.bitcodeHashList"
+ "entry.hashes"
+ "entry.reflectionBlock"
+ "entry.tools"
+ "gpuCompilerSPIOptions"
+ "hashes"
+ "header does not fit requestSize"
+ "libFromSource.align overflow"
+ "libFromSource.linkedAir"
+ "libFromSource.linkedAir blobSize"
+ "libFromSource.linkedAir size prefix"
+ "libFromSource.options"
+ "libFromSource.options cstring"
+ "libFromSource.source"
+ "libFromSource.source cstring"
+ "libFromSource.unaligned blob"
+ "linkData"
+ "mtlScript"
+ "overrideTriple"
+ "pipelineArchUnitId"
+ "pipelineData"
+ "pipelineList"
+ "privateVisibleFunctionRequests"
+ "requestData"
+ "sandboxExt"
+ "specializedName"
+ "tools"
+ "uniqueBitcodeList"
+ "visibleFunctionGroup"
+ "visibleFunctionRequests"
- "Invalid request data size"
- "Request data size insufficient for operation"
```
