## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

 579.40.9.0.0
   __TEXT.__const: 0xc35
   __TEXT.__cstring: 0x5196
-  __TEXT.__os_log: 0x1801a
-  __TEXT_EXEC.__text: 0x84428
+  __TEXT.__os_log: 0x1807a
+  __TEXT_EXEC.__text: 0x8466c
   __TEXT_EXEC.__auth_stubs: 0x1580
   __DATA.__data: 0x12d8
   __DATA.__bss: 0x107c

   __DATA_CONST.__auth_got: 0xac0
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 798
-  Symbols:   2336
-  CStrings:  2657
+  Functions: 799
+  Symbols:   2337
+  CStrings:  2658
 
Symbols:
+ _smb_symlink_target_is_unsafe
Functions:
~ _smb_check_for_windows_symlink : 868 -> 888
~ _smbfs_smb_get_reparse_tag : 576 -> 600
~ _smbfs_smb_windows_read_symlink : 712 -> 792
~ _smbfs_smb_unix_read_symlink : 784 -> 888
+ _smb_symlink_target_is_unsafe
~ _smb2_smb_parse_get_reparse_point : 552 -> 576
CStrings:
+ "%s: %s has an unsafe symlink target, rejecting\n"
```
