## osx-filevault

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/osx-filevault.appex/Contents/MacOS/osx-filevault`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 148.0.0.0.0
-  __TEXT.__text: 0x90c
+  __TEXT.__text: 0x8f4
   __TEXT.__auth_stubs: 0x90
   __TEXT.__objc_stubs: 0x3a0
   __TEXT.__objc_methlist: 0x2c
Functions:
~ -[DEFileVaultExtension attachmentsForParameters:] : 428 -> 416
~ -[DEFileVaultExtension gatherFileVaultDiagnosticsWithDestination:] : 1860 -> 1848
```
