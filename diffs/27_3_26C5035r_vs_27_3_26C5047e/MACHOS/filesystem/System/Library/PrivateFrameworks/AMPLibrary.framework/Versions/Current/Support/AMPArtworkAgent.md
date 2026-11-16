## AMPArtworkAgent

> `/System/Library/PrivateFrameworks/AMPLibrary.framework/Versions/Current/Support/AMPArtworkAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1.7.3.10.0
-  __TEXT.__text: 0x1b5c24
-  __TEXT.__auth_stubs: 0x1e30
+1.7.3.21.0
+  __TEXT.__text: 0x1b60e0
+  __TEXT.__auth_stubs: 0x1e50
   __TEXT.__objc_stubs: 0x46e0
   __TEXT.__init_offsets: 0x34
   __TEXT.__objc_methlist: 0x1b9c
   __TEXT.__objc_classname: 0x375
-  __TEXT.__cstring: 0x6393
+  __TEXT.__cstring: 0x639f
   __TEXT.__objc_methname: 0x5e7d
   __TEXT.__objc_methtype: 0x11a8
-  __TEXT.__gcc_except_tab: 0xa2b8
+  __TEXT.__gcc_except_tab: 0xa33c
   __TEXT.__const: 0x2c8e8
-  __TEXT.__oslogstring: 0x4dcb
-  __TEXT.__unwind_info: 0x4fc8
+  __TEXT.__oslogstring: 0x4ecc
+  __TEXT.__unwind_info: 0x4fe8
   __TEXT.__eh_frame: 0x98
   __DATA_CONST.__const: 0x148e0
   __DATA_CONST.__cfstring: 0x1e80

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x98
-  __DATA_CONST.__auth_got: 0xf30
-  __DATA_CONST.__got: 0x4c0
+  __DATA_CONST.__auth_got: 0xf40
+  __DATA_CONST.__got: 0x4d8
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x2c48
   __DATA.__objc_selrefs: 0x16f8
   __DATA.__objc_ivar: 0x1d8
   __DATA.__objc_data: 0x870
   __DATA.__data: 0xc18
-  __DATA.__bss: 0x53e8
+  __DATA.__bss: 0x53f8
   __DATA.__common: 0x1108
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /System/Library/PrivateFrameworks/AOSAccounts.framework/Versions/A/AOSAccounts
   - /System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices
   - /System/Library/PrivateFrameworks/CrashReporterSupport.framework/Versions/A/CrashReporterSupport
+  - /System/Library/PrivateFrameworks/TCC.framework/Versions/A/TCC
   - /System/Library/PrivateFrameworks/iTunesCloud.framework/Versions/A/iTunesCloud
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3845
-  Symbols:   679
-  CStrings:  2602
+  Functions: 3850
+  Symbols:   684
+  CStrings:  2607
 
Symbols:
+ _CFDateGetTimeIntervalSinceDate
+ ___kCFBooleanFalse
+ _kTCCAccessCheckOptionPrompt
+ _kTCCServiceMediaLibrary
+ _tcc_authorization_check_audit_token
CStrings:
+ "Detected expired or expiring JWT token for client id %{public}s."
+ "Received new JWT token for client id %{public}s. Expiration %{public}@."
+ "Requesting new JWT token for client id %{public}s."
+ "ampartworkd> Refusing connection from pid %d, TCC not granted (%llu)"
+ "jwt_service"
```
