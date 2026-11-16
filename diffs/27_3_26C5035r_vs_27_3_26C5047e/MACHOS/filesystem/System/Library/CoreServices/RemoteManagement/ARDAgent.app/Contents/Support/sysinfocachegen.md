## sysinfocachegen

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/sysinfocachegen`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-768.2.15.1.0
-  __TEXT.__text: 0xfa80
-  __TEXT.__auth_stubs: 0xe70
+768.6.0.0.0
+  __TEXT.__text: 0x10570
+  __TEXT.__auth_stubs: 0xe90
   __TEXT.__objc_stubs: 0x7a0
   __TEXT.__objc_methlist: 0x224
-  __TEXT.__const: 0x128
-  __TEXT.__cstring: 0x48e6
-  __TEXT.__oslogstring: 0x723
+  __TEXT.__const: 0x140
+  __TEXT.__cstring: 0x4a4a
+  __TEXT.__oslogstring: 0x837
   __TEXT.__objc_methname: 0x7cf
   __TEXT.__objc_classname: 0x11
   __TEXT.__objc_methtype: 0xea
-  __TEXT.__unwind_info: 0x2b8
+  __TEXT.__unwind_info: 0x2f0
   __DATA_CONST.__const: 0x250
   __DATA_CONST.__cfstring: 0x1180
   __DATA_CONST.__objc_classlist: 0x10

   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA_CONST.__auth_got: 0x740
+  __DATA_CONST.__auth_got: 0x750
   __DATA_CONST.__got: 0x160
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x270
   __DATA.__objc_selrefs: 0x2a0
   __DATA.__objc_ivar: 0x1c

   - /System/Library/PrivateFrameworks/DiagnosticLogCollection.framework/Versions/A/DiagnosticLogCollection
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 153
-  Symbols:   283
-  CStrings:  1015
+  Functions: 167
+  Symbols:   286
+  CStrings:  1024
 
Symbols:
+ _CFDataAppendBytes
+ _CFDataCreateMutable
+ _CFPropertyListCreateWithData
+ ___chkstk_darwin
+ ___memcpy_chk
+ __exit
+ _fchmod
+ _ftruncate
+ _geteuid
+ _lseek
+ _read
+ _strlcpy
+ _strrchr
- _CFPropertyListCreateFromStream
- _CFPropertyListWriteToStream
- _CFReadStreamClose
- _CFReadStreamCreateWithFile
- _CFReadStreamOpen
- _CFStringGetSystemEncoding
- _CFWriteStreamClose
- _CFWriteStreamCreateWithFile
- _CFWriteStreamOpen
- _fclose
CStrings:
+ "%s %s exited with status %d"
+ "%s %s was killed by signal %d"
+ "/var/db/RemoteManagement/caches"
+ "/var/db/RemoteManagement/caches/asp.stage.XXXXXX"
+ "CreateStagingFile"
+ "GatherCacheInfo"
+ "No system_profiler data was collected"
+ "Refusing to stage in %s: not a private directory"
+ "Unable to pipe to %s  error %s"
+ "Unable to protect %s  error %s"
+ "Unable to unlink %s  error %s"
+ "Unable to write the %s cache  error %s"
- "/tmp/asp.cache"
- "/tmp/tigerasp.xml"
- "w"
```
