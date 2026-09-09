## DiskSpaceDiagnosticsExtension

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/PlugIns/DiskSpaceDiagnosticsExtension.appex/Contents/MacOS/DiskSpaceDiagnosticsExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1023.0.4.0.0
-  __TEXT.__text: 0x1640
+  __TEXT.__text: 0x15d4
   __TEXT.__auth_stubs: 0x1d0
   __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x15c

   __TEXT.__objc_classname: 0x48
   __TEXT.__objc_methname: 0x5a3
   __TEXT.__objc_methtype: 0x185
-  __TEXT.__unwind_info: 0xa8
+  __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__const: 0x70
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ _shared_diagnostics_extension_log_handle : 68 -> 56
~ ___shared_diagnostics_extension_log_handle_block_invoke : 72 -> 60
~ -[DiskSpaceDiagnosticsExtension bootedDataVolumePathWithError:] : 2320 -> 2308
~ _errorForDiskManagementError : 236 -> 224
~ -[DiskSpaceDiagnosticsExtension snapshotFilesystemMetadata:progressHandler:] : 1564 -> 1552
~ ___copy_helper_block_e8_32r40r48r : 96 -> 84
~ ___destroy_helper_block_e8_32r40r48r : 80 -> 68
~ -[DiskSpaceDiagnosticsExtension observeValueForKeyPath:ofObject:change:context:] : 204 -> 192
~ -[DiskSpaceDiagnosticsExtension attachmentsForParameters:withProgressHandler:] : 324 -> 312
```
