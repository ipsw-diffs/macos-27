## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/Versions/A/ChronoServices`

```diff

-749.3.9.0.0
-  __TEXT.__text: 0x10942c
+749.3.14.0.0
+  __TEXT.__text: 0x10a47c
   __TEXT.__objc_methlist: 0x829c
-  __TEXT.__const: 0x8080
-  __TEXT.__gcc_except_tab: 0xad2c
-  __TEXT.__cstring: 0x5885
-  __TEXT.__oslogstring: 0x570e
+  __TEXT.__const: 0x8090
+  __TEXT.__gcc_except_tab: 0xae0c
+  __TEXT.__cstring: 0x5985
+  __TEXT.__oslogstring: 0x5b3e
   __TEXT.__dlopen_cstrs: 0x5c
   __TEXT.__swift5_typeref: 0x26fc
   __TEXT.__constg_swiftt: 0x3478

   __TEXT.__swift_as_ret: 0x60
   __TEXT.__swift_as_cont: 0xdc
   __TEXT.__swift5_protos: 0x50
-  __TEXT.__unwind_info: 0x7f58
+  __TEXT.__unwind_info: 0x7fc8
   __TEXT.__eh_frame: 0x3390
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x58
   __DATA_CONST.__got: 0xb48
   __AUTH_CONST.__const: 0x7698
-  __AUTH_CONST.__cfstring: 0x4f60
+  __AUTH_CONST.__cfstring: 0x4fc0
   __AUTH_CONST.__objc_const: 0x203a8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0xa0
-  __AUTH_CONST.__auth_got: 0x15e0
+  __AUTH_CONST.__auth_got: 0x1658
   __AUTH.__objc_data: 0x30c0
   __AUTH.__data: 0x2ed8
   __DATA.__objc_ivar: 0x750

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7830
-  Symbols:   7554
-  CStrings:  1296
+  Functions: 7850
+  Symbols:   7573
+  CStrings:  1327
 
Symbols:
+ _CHSEnterSandbox
+ _CHSRegisterForPerProcessTemporaryFolder
+ _CHSRegisterForTemporaryFolder
+ _NSTemporaryDirectory
+ ___error
+ __set_user_dir_suffix
+ _asprintf
+ _close
+ _confstr
+ _exit
+ _flock
+ _getConfigPath
+ _getenv
+ _getpwuid
+ _getuid
+ _open
+ _realpath$DARWIN_EXTSN
+ _sandbox_init_with_parameters
+ _strnlen
CStrings:
+ "$HOME not set, falling back to using getpwuid"
+ "$TMPDIR is not set, so no temporary folder slot can be claimed for %{public}s"
+ "%s.%d"
+ ".lock"
+ "/private/var/db/mds/messages/%u/se_SecurityMessages"
+ "/private/var/db/mds/messages/se_SecurityMessages"
+ "All %d temporary folder slots for %{public}s are in use"
+ "Claimed temporary folder slot %{public}@ with lock file %{public}@"
+ "Cleared temporary directory (%{public}@) contents on startup."
+ "DARWIN_CACHE_DIR"
+ "DARWIN_USER_DIR"
+ "Error clearing temporary directory contents on startup: %{public}@"
+ "Error locking temporary folder lock file %{public}@: %{darwin.errno}d"
+ "Error opening temporary folder lock file %{public}@: %{darwin.errno}d"
+ "Failed to enter sandbox: %{public}s"
+ "HOME"
+ "No `INCodable` backing store found for intent of type: %@"
+ "SECURITY_MESSAGES_DIR"
+ "Sandbox parameter %{public}s is good with value %{public}s"
+ "TMPDIR"
+ "TemporaryItems"
+ "Unexpected nil value in sandbox parameters for %{public}s"
+ "Unexpected very long path in sandbox parameter for %{public}s"
+ "Unexpected zero-length path in sandbox parameter for %{public}s"
+ "_CS_DARWIN_USER_CACHE_DIR"
+ "_CS_DARWIN_USER_DIR"
+ "_CS_DARWIN_USER_TEMP_DIR"
+ "failed to compute security messages directory: %{darwin.errno}d"
+ "failed to get passwd entry for uid %u"
+ "failed to initialize sandbox %{public}s: %{darwin.errno}d"
+ "failed to resolve sandbox %{public}s: %{darwin.errno}d"
+ "failed to resolve user's home directory: %{darwin.errno}d"
- "No `INCodable` backing store found for intent of type: %@: %@"
```
