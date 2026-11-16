## HomeDirMechanism

> `/System/Library/CoreServices/SecurityAgentPlugins/HomeDirMechanism.bundle/Contents/MacOS/HomeDirMechanism`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-110.0.2.0.0
-  __TEXT.__text: 0x5ab0
-  __TEXT.__auth_stubs: 0x4d0
+110.3.1.0.0
+  __TEXT.__text: 0x61bc
+  __TEXT.__auth_stubs: 0x540
   __TEXT.__objc_stubs: 0xe80
   __TEXT.__objc_methlist: 0x424
   __TEXT.__gcc_except_tab: 0x38
-  __TEXT.__cstring: 0x1e47
+  __TEXT.__cstring: 0x2184
   __TEXT.__objc_classname: 0x9b
   __TEXT.__objc_methname: 0xc83
   __TEXT.__objc_methtype: 0x4da
-  __TEXT.__unwind_info: 0x1f8
+  __TEXT.__unwind_info: 0x208
   __DATA_CONST.__const: 0x68
   __DATA_CONST.__cfstring: 0x1100
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x20
-  __DATA_CONST.__auth_got: 0x278
+  __DATA_CONST.__auth_got: 0x2b0
   __DATA_CONST.__got: 0x138
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x580
   __DATA.__objc_selrefs: 0x440
   __DATA.__objc_ivar: 0x38

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 99
-  Symbols:   158
-  CStrings:  417
+  Functions: 102
+  Symbols:   166
+  CStrings:  436
 
Symbols:
+ ___chkstk_darwin
+ ___memcpy_chk
+ ___memmove_chk
+ ___strlcpy_chk
+ _getattrlist
+ _readlink
+ _snprintf
+ _strchr
CStrings:
+ "%s%s"
+ "%s/%.*s"
+ "ERROR | %s | %s: %s is not a directory (%s)"
+ "ERROR | %s | %s: %s links to an unsupported target (%s)"
+ "ERROR | %s | %s: cannot look up %s (errno %d) (%s)"
+ "ERROR | %s | %s: cannot readlink %s (errno %d) (%s)"
+ "ERROR | %s | %s: cannot stat (errno %d) (%s)"
+ "ERROR | %s | %s: exists but is not a directory (%s)"
+ "ERROR | %s | %s: path contains a '.' or '..' component (%s)"
+ "ERROR | %s | %s: path is not absolute (%s)"
+ "ERROR | %s | %s: path is too long (%s)"
+ "ERROR | %s | %s: path is too long after %s (%s)"
+ "ERROR | %s | %s: too many symlinks (%s)"
+ "ERROR | %s | Refusing network home premount: path contains a '.' or '..' component (home=%s path=%s)"
+ "Refusing network home premount: derived mount point"
+ "Refusing network home premount: home path"
+ "Refusing to mount home directory"
+ "hdmHomePathIsAbsentOrDirectory"
+ "hdmStatIsAbsentOrDirectory"
```
