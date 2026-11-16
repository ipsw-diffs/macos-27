## smbutil

> `/usr/bin/smbutil`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-579.60.5.0.0
-  __TEXT.__text: 0xd5c4
-  __TEXT.__auth_stubs: 0x960
+579.60.8.0.0
+  __TEXT.__text: 0xd924
+  __TEXT.__auth_stubs: 0x980
   __TEXT.__objc_stubs: 0x180
-  __TEXT.__cstring: 0x3c17
+  __TEXT.__cstring: 0x3c47
   __TEXT.__const: 0xd4
   __TEXT.__oslogstring: 0x39e
-  __TEXT.__gcc_except_tab: 0xfc
+  __TEXT.__gcc_except_tab: 0x148
   __TEXT.__objc_methname: 0xf5
-  __TEXT.__unwind_info: 0x338
-  __DATA_CONST.__const: 0x158
+  __TEXT.__unwind_info: 0x370
+  __DATA_CONST.__const: 0x2d8
   __DATA_CONST.__cfstring: 0xb80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x4c0
-  __DATA_CONST.__got: 0xf8
+  __DATA_CONST.__auth_got: 0x4d0
+  __DATA_CONST.__got: 0xf0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_selrefs: 0x60
   __DATA.__data: 0x8558
   __DATA.__common: 0x28
-  __DATA.__bss: 0x20
+  __DATA.__bss: 0x80
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/DCERPC.framework/Versions/A/DCERPC

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 155
-  Symbols:   344
-  CStrings:  698
+  Functions: 175
+  Symbols:   374
+  CStrings:  705
 
Symbols:
+ _OUTLINED_FUNCTION_2
+ _OUTLINED_FUNCTION_3
+ __NSConcreteGlobalBlock
+ ___block_descriptor_tmp
+ ___block_literal_global
+ ___smb_log_auth_block_invoke
+ ___smb_log_dfs_block_invoke
+ ___smb_log_io_block_invoke
+ ___smb_log_mount_block_invoke
+ ___smb_log_nic_block_invoke
+ ___smb_log_rpc_block_invoke
+ _dispatch_once
+ _os_log_create
+ _smb_log_auth
+ _smb_log_auth.log
+ _smb_log_auth.once
+ _smb_log_dfs
+ _smb_log_dfs.log
+ _smb_log_dfs.once
+ _smb_log_io
+ _smb_log_io.log
+ _smb_log_io.once
+ _smb_log_mount
+ _smb_log_mount.log
+ _smb_log_mount.once
+ _smb_log_nic
+ _smb_log_nic.log
+ _smb_log_nic.once
+ _smb_log_rpc
+ _smb_log_rpc.log
+ _smb_log_rpc.once
- __os_log_default
CStrings:
+ "auth"
+ "com.apple.SMBClient"
+ "io"
+ "mount"
+ "nic"
+ "rpc"
+ "v8@?0"
```
