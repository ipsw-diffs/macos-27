## SharingPrefsExtension

> `/System/Library/PrivateFrameworks/AMPSharing.framework/Versions/Current/PlugIns/SharingPrefsExtension.appex/Contents/MacOS/SharingPrefsExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1.7.3.10.0
-  __TEXT.__text: 0x1b90c4
-  __TEXT.__auth_stubs: 0x1b60
-  __TEXT.__objc_stubs: 0x86e0
+1.7.3.21.0
+  __TEXT.__text: 0x1b96c4
+  __TEXT.__auth_stubs: 0x1b70
+  __TEXT.__objc_stubs: 0x86c0
   __TEXT.__init_offsets: 0x40
   __TEXT.__objc_methlist: 0x3364
-  __TEXT.__gcc_except_tab: 0x9ad4
+  __TEXT.__gcc_except_tab: 0x9b9c
   __TEXT.__const: 0x2e4c3
-  __TEXT.__cstring: 0x6edf
-  __TEXT.__oslogstring: 0x1f09
+  __TEXT.__cstring: 0x6f2a
+  __TEXT.__oslogstring: 0x1fc5
   __TEXT.__objc_classname: 0x3fc
-  __TEXT.__objc_methname: 0xb3e7
+  __TEXT.__objc_methname: 0xb3df
   __TEXT.__objc_methtype: 0x1bac
   __TEXT.__ustring: 0x3e
-  __TEXT.__unwind_info: 0x5418
+  __TEXT.__unwind_info: 0x5430
   __TEXT.__eh_frame: 0x98
   __DATA_CONST.__const: 0x157a8
   __DATA_CONST.__cfstring: 0x36a0

   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__objc_arraydata: 0x220
   __DATA_CONST.__objc_arrayobj: 0x30
-  __DATA_CONST.__auth_got: 0xdc8
+  __DATA_CONST.__auth_got: 0xdd0
   __DATA_CONST.__got: 0x5e8
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_const: 0x4aa0
-  __DATA.__objc_selrefs: 0x2e00
+  __DATA.__objc_selrefs: 0x2df8
   __DATA.__objc_ivar: 0x3d0
   __DATA.__objc_data: 0x8c0
   __DATA.__data: 0xcd0
-  __DATA.__bss: 0x5458
-  __DATA.__common: 0x10b0
+  __DATA.__bss: 0x5468
+  __DATA.__common: 0x10b8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4311
-  Symbols:   689
-  CStrings:  3636
+  Functions: 4316
+  Symbols:   690
+  CStrings:  3640
 
Symbols:
+ _CFDateGetTimeIntervalSinceDate
CStrings:
+ "Detected expired or expiring JWT token for client id %{public}s."
+ "Interactive sign-in requires a visible window to present from."
+ "Received new JWT token for client id %{public}s. Expiration %{public}@."
+ "Requesting new JWT token for client id %{public}s."
+ "jwt_service"
- "windows"
```
