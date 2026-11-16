## SMBClient

> `/System/Library/PrivateFrameworks/SMBClient.framework/Versions/A/SMBClient`

```diff

-579.60.5.0.0
-  __TEXT.__text: 0x1e5dc
+579.60.8.0.0
+  __TEXT.__text: 0x1f848
   __TEXT.__const: 0x8c0
-  __TEXT.__cstring: 0x14e9
-  __TEXT.__oslogstring: 0x3618
-  __TEXT.__unwind_info: 0xa00
+  __TEXT.__cstring: 0x1531
+  __TEXT.__oslogstring: 0x38ef
+  __TEXT.__unwind_info: 0xa50
   __TEXT.__auth_stubs: 0x0
-  __DATA_CONST.__const: 0x70
+  __DATA_CONST.__const: 0x110
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x60
+  __AUTH_CONST.__const: 0x100
   __AUTH_CONST.__cfstring: 0xf20
-  __AUTH_CONST.__auth_got: 0x770
+  __AUTH_CONST.__auth_got: 0x780
   __DATA.__data: 0x40
-  __DATA.__bss: 0x10
+  __DATA.__bss: 0x60
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /System/Library/PrivateFrameworks/Heimdal.framework/Versions/A/Heimdal
   - /System/Library/PrivateFrameworks/KerberosHelper.framework/Versions/A/KerberosHelper
   - /usr/lib/libSystem.B.dylib
-  Functions: 635
-  Symbols:   569
-  CStrings:  657
+  Functions: 672
+  Symbols:   594
+  CStrings:  682
 
Symbols:
+ _OUTLINED_FUNCTION_16
+ _OUTLINED_FUNCTION_17
+ __NSConcreteGlobalBlock
+ ___block_literal_global
+ ___smb_log_auth_block_invoke
+ ___smb_log_dfs_block_invoke
+ ___smb_log_io_block_invoke
+ ___smb_log_mount_block_invoke
+ ___smb_log_nic_block_invoke
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
- __os_log_default
CStrings:
+ "%s: Can't parse file '%s'"
+ "%s: HiFi requested "
+ "%s: Key '%s' defined before section"
+ "%s: invalid boolean value '%s' for key '%s' in section '%s'"
+ "%s: invalid int value '%s' for key '%s' in section '%s', syserr = %s"
+ "Bonjour check dns match <%s>"
+ "DNS check dns match <%s>"
+ "already_mounted: Checking <%s> == <%s> "
+ "already_mounted: create id for <%s> "
+ "auth"
+ "com.apple.SMBClient"
+ "dfs"
+ "findMatchingSession: ss_len %d for ctx->serverName <%s> "
+ "findMatchingSession: try to match DNS name of ctx->serverName <%s> "
+ "findMatchingSession: we found a session to share for ctx->serverName <%s> "
+ "io"
+ "mount"
+ "nic"
+ "rc_getbool"
+ "rc_getint"
+ "rc_parse"
+ "smb_mount: call already_mounted for <%s>"
+ "smb_mount: create id for <%s> "
+ "smb_negotiate: ss_len %d for ctx->serverName <%s> "
+ "smb_negotiate: try to match DNS name of ctx->serverName <%s> "
```
