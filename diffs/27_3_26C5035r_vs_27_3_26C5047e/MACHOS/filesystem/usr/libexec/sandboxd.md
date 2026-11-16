## sandboxd

> `/usr/libexec/sandboxd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_assocty`
- `__TEXT.__dof_sandboxd`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3051.60.20.0.0
-  __TEXT.__text: 0x3336c
-  __TEXT.__auth_stubs: 0x15f0
+3051.60.23.0.1
+  __TEXT.__text: 0x33948
+  __TEXT.__auth_stubs: 0x1610
   __TEXT.__objc_stubs: 0x27a0
   __TEXT.__objc_methlist: 0x10c4
   __TEXT.__const: 0x83b0
-  __TEXT.__cstring: 0x20286
-  __TEXT.__oslogstring: 0x2512
+  __TEXT.__cstring: 0x20306
+  __TEXT.__oslogstring: 0x25a2
   __TEXT.__objc_classname: 0x233
   __TEXT.__objc_methname: 0x2b60
   __TEXT.__objc_methtype: 0x67e
-  __TEXT.__gcc_except_tab: 0x294
+  __TEXT.__gcc_except_tab: 0x2a0
   __TEXT.__swift5_typeref: 0x189
   __TEXT.__constg_swiftt: 0x190
   __TEXT.__swift5_fieldmd: 0x1e4

   __TEXT.__swift5_types: 0x1c
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__dof_sandboxd: 0x2f5
-  __TEXT.__unwind_info: 0xde8
+  __TEXT.__unwind_info: 0xdf0
   __TEXT.__eh_frame: 0x370
   __DATA_CONST.__const: 0x27f0
-  __DATA_CONST.__cfstring: 0x84c0
+  __DATA_CONST.__cfstring: 0x84e0
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x80
-  __DATA_CONST.__objc_intobj: 0x1068
+  __DATA_CONST.__objc_intobj: 0x1080
   __DATA_CONST.__objc_arraydata: 0x1388
   __DATA_CONST.__objc_arrayobj: 0xd20
-  __DATA_CONST.__auth_got: 0xb08
+  __DATA_CONST.__auth_got: 0xb18
   __DATA_CONST.__got: 0x328
-  __DATA_CONST.__auth_ptr: 0x188
+  __DATA_CONST.__auth_ptr: 0x198
   __DATA.__objc_const: 0x2298
   __DATA.__objc_selrefs: 0xc10
   __DATA.__objc_ivar: 0x144

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 992
-  Symbols:   522
-  CStrings:  6035
+  Functions: 994
+  Symbols:   524
+  CStrings:  6043
 
Symbols:
+ __os_feature_enabled_impl
+ _tcc_indirect_object_create_with_private_folder_path
CStrings:
+ "FDA_WARNING"
+ "Nov 10 2026"
+ "TCC"
+ "enabling private folder support"
+ "failed to set private_folders_enabled sysctl: %{darwin.errno}d"
+ "kTCCServiceSystemPolicyPrivateFolders"
+ "no private folder root path for %{public}s"
+ "private-folder-root-path"
+ "security.mac.sandbox.private_folders_enabled"
- "Oct 30 2026"
```
