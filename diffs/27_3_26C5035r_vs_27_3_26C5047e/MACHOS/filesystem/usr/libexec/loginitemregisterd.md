## loginitemregisterd

> `/usr/libexec/loginitemregisterd`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

-3298.60.14.0.0
-  __TEXT.__text: 0x674
-  __TEXT.__auth_stubs: 0x210
-  __TEXT.__const: 0x68
-  __TEXT.__cstring: 0x2f7
-  __TEXT.__unwind_info: 0x88
-  __DATA_CONST.__const: 0x30
+3298.60.20.0.0
+  __TEXT.__text: 0x1448
+  __TEXT.__auth_stubs: 0x370
+  __TEXT.__const: 0x88
+  __TEXT.__cstring: 0x552
+  __TEXT.__unwind_info: 0xc8
+  __DATA_CONST.__const: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x108
-  __DATA_CONST.__got: 0x20
+  __DATA_CONST.__auth_got: 0x1b8
+  __DATA_CONST.__got: 0x28
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__data: 0x20
   __DATA.__crash_info: 0x148
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 10
-  Symbols:   39
-  CStrings:  12
+  Functions: 23
+  Symbols:   63
+  CStrings:  30
 
Symbols:
+ _CFStringGetCString
+ _CFURLCreateFileReferenceURL
+ _CFURLCreateFromFileSystemRepresentation
+ _CFURLGetString
+ _SANDBOX_CHECK_NO_REPORT
+ ___chkstk_darwin
+ _close
+ _fcntl
+ _fgetattrlist
+ _fstat
+ _fstatat
+ _fstatfs
+ _malloc_type_malloc
+ _open
+ _openat
+ _read
+ _sandbox_check_by_audit_token
+ _strchr
+ _strcmp
+ _strrchr
+ _vasprintf
+ _xpc_bundle_get_error
+ _xpc_create_from_plist
+ _xpc_release
CStrings:
+ "%s/%s"
+ "%s/Contents/Library/LoginItems"
+ "(null)"
+ ".app"
+ "@(#)VERSION:Darwin LoginItem Registration Proxy Version 1.0.0: Tue Nov 10 01:36:37 PST 2026; root:libxpc_executables-3298.60.20~43/loginitemregisterd/RELEASE_ARM64E"
+ "B24@?0r*8r*16"
+ "CFBundleExecutable"
+ "Contents"
+ "Contents/Info.plist"
+ "Contents/MacOS"
+ "Contents/MacOS/%s"
+ "Darwin LoginItem Registration Proxy Version 1.0.0: Tue Nov 10 01:36:37 PST 2026; root:libxpc_executables-3298.60.20~43/loginitemregisterd/RELEASE_ARM64E"
+ "Refusing LoginItem registration: caller bundle = %s, target = %s, error = %d"
+ "Refusing LoginItem registration: cannot open target = %s"
+ "Refusing LoginItem registration: the caller can modify the target, its Info.plist or main executable, or a directory above it: caller bundle = %s, target = %s"
+ "Refusing LoginItem registration: the target changed while it was being registered: target = %s"
+ "file-write-create"
+ "file-write-data"
+ "file-write-unlink"
+ "file:///.file/id="
- "@(#)VERSION:Darwin LoginItem Registration Proxy Version 1.0.0: Thu Oct 29 00:45:51 PDT 2026; root:libxpc_executables-3298.60.14~78/loginitemregisterd/RELEASE_ARM64E"
- "Darwin LoginItem Registration Proxy Version 1.0.0: Thu Oct 29 00:45:51 PDT 2026; root:libxpc_executables-3298.60.14~78/loginitemregisterd/RELEASE_ARM64E"
```
