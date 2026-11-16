## smb

> `/System/Library/Filesystems/NetFSPlugins/smb.bundle/Contents/MacOS/smb`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-579.60.5.0.0
-  __TEXT.__text: 0x49b0
-  __TEXT.__auth_stubs: 0x5f0
+579.60.8.0.0
+  __TEXT.__text: 0x4ca0
+  __TEXT.__auth_stubs: 0x610
   __TEXT.__const: 0x48
-  __TEXT.__oslogstring: 0x3f3
-  __TEXT.__cstring: 0x1ba
-  __TEXT.__gcc_except_tab: 0xfc
-  __TEXT.__unwind_info: 0x248
+  __TEXT.__oslogstring: 0x46f
+  __TEXT.__cstring: 0x199
+  __TEXT.__gcc_except_tab: 0x148
+  __TEXT.__unwind_info: 0x280
+  __DATA_CONST.__const: 0x180
   __DATA_CONST.__cfstring: 0x260
-  __DATA_CONST.__auth_got: 0x300
-  __DATA_CONST.__got: 0x80
+  __DATA_CONST.__auth_got: 0x310
+  __DATA_CONST.__got: 0x78
   __DATA.__data: 0x8130
-  __DATA.__bss: 0x20
+  __DATA.__bss: 0x80
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/NetFS.framework/Versions/A/NetFS
   - /System/Library/PrivateFrameworks/DCERPC.framework/Versions/A/DCERPC
   - /System/Library/PrivateFrameworks/SMBClient.framework/Versions/A/SMBClient
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 104
-  Symbols:   199
-  CStrings:  70
+  Functions: 122
+  Symbols:   229
+  CStrings:  76
 
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
+ "SMB_CreateSessionRef: creating smb handle failed, syserr = %s"
+ "SMB_EnumerateShares: - error = %d!"
+ "SMB_GetServerInfo: - error = %d!"
+ "SMB_Mount: - error = %d!"
+ "SMB_OpenSession: - error = %d!"
+ "auth"
+ "com.apple.SMBClient"
+ "dfs"
+ "io"
+ "mount"
+ "nic"
+ "rpc"
+ "v8@?0"
- "%s: - error = %d!"
- "%s: creating smb handle failed, syserr = %s"
- "SMB_CreateSessionRef"
- "SMB_EnumerateShares"
- "SMB_GetServerInfo"
- "SMB_Mount"
- "SMB_OpenSession"
```
