## mount_smbfs

> `/sbin/mount_smbfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-579.60.5.0.0
-  __TEXT.__text: 0x33ac
-  __TEXT.__auth_stubs: 0x590
-  __TEXT.__cstring: 0x56b
+579.60.8.0.0
+  __TEXT.__text: 0x36b0
+  __TEXT.__auth_stubs: 0x5b0
+  __TEXT.__cstring: 0x59f
   __TEXT.__const: 0x28
   __TEXT.__oslogstring: 0x27b
-  __TEXT.__gcc_except_tab: 0x88
-  __TEXT.__unwind_info: 0x1f0
+  __TEXT.__gcc_except_tab: 0xbc
+  __TEXT.__unwind_info: 0x220
+  __DATA_CONST.__const: 0x180
   __DATA_CONST.__cfstring: 0x1e0
-  __DATA_CONST.__auth_got: 0x2d0
-  __DATA_CONST.__got: 0xa0
+  __DATA_CONST.__auth_got: 0x2e0
+  __DATA_CONST.__got: 0x98
   __DATA.__data: 0x34c8
-  __DATA.__bss: 0x10
+  __DATA.__bss: 0x70
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/PrivateFrameworks/DCERPC.framework/Versions/A/DCERPC
   - /System/Library/PrivateFrameworks/SMBClient.framework/Versions/A/SMBClient
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libutil.dylib
-  Functions: 81
-  Symbols:   169
-  CStrings:  104
+  Functions: 100
+  Symbols:   199
+  CStrings:  112
 
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
+ "dfs"
+ "io"
+ "mount"
+ "nic"
+ "rpc"
+ "v8@?0"
```
