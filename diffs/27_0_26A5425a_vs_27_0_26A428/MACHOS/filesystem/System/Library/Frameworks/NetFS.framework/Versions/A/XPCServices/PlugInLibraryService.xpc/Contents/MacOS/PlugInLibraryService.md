## PlugInLibraryService

> `/System/Library/Frameworks/NetFS.framework/Versions/A/XPCServices/PlugInLibraryService.xpc/Contents/MacOS/PlugInLibraryService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 71.0.0.0.0
-  __TEXT.__text: 0xc560
+  __TEXT.__text: 0xc364
   __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_stubs: 0x5e0
   __TEXT.__objc_methlist: 0x2c8

   __TEXT.__oslogstring: 0x886
   __TEXT.__cstring: 0x128d
   __TEXT.__gcc_except_tab: 0xf4
-  __TEXT.__unwind_info: 0x278
+  __TEXT.__unwind_info: 0x3b0
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__cfstring: 0x500
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ sub_1000010ec : 28 -> 16
~ sub_1000011a4 -> sub_100001198 : 108 -> 96
~ sub_100001210 -> sub_1000011f8 : 572 -> 560
~ sub_100001924 -> sub_100001900 : 236 -> 224
~ sub_100001a10 -> sub_1000019e0 : 280 -> 268
~ sub_1000020a8 -> sub_10000206c : 68 -> 56
~ _FindPluginByScheme : 88 -> 76
~ _PremountHomeDirectoryWithAuthentication : 224 -> 212
~ _NetFSGetMountInfo : 348 -> 336
~ sub_1000051dc -> sub_100005170 : 96 -> 84
~ _GetURLFromURLRemountInfo : 236 -> 224
~ sub_100005e80 -> sub_100005dfc : 148 -> 136
~ _netfs_CreateSessionRef : 96 -> 84
~ _netfs_GetServerInfo : 144 -> 132
~ _netfs_ParseURL : 128 -> 116
~ _netfs_CreateURL : 124 -> 112
~ _netfs_OpenSession : 144 -> 132
~ _netfs_EnumerateShares : 116 -> 104
~ sub_100006e8c -> sub_100006db4 : 156 -> 144
~ _netfs_Cancel : 88 -> 76
~ sub_100007314 -> sub_100007224 : 148 -> 136
~ _NetFSMountURLProbe : 1504 -> 1500
~ _NetFSSetURLApprovalState : 208 -> 196
~ _NetFSClearAllURLApprovals : 204 -> 192
~ sub_100007d08 -> sub_100007bf0 : 120 -> 108
~ sub_100008648 -> sub_100008524 : 112 -> 100
~ sub_1000087b4 -> sub_100008684 : 368 -> 356
~ sub_100008e74 -> sub_100008d38 : 144 -> 132
~ sub_100008f04 -> sub_100008dbc : 80 -> 68
~ sub_100008f54 -> sub_100008e00 : 68 -> 56
~ sub_100009468 -> sub_100009308 : 144 -> 132
~ _netfs_setXPCPlugInState : 148 -> 136
~ _piston_free_desciptor : 156 -> 144
~ _piston_set_treeconn_status : 68 -> 56
~ _piston_set_session_status : 68 -> 56
~ _piston_smb1_set_tid : 68 -> 56
~ _piston_smb1_set_uid : 68 -> 56
~ sub_10000ae98 -> sub_10000ace4 : 28 -> 16
~ _piston_negotiate_easy : 200 -> 176
~ _smb2_add_credits_granted : 76 -> 64
~ _piston_make_utf16_treestr : 212 -> 200
~ sub_10000c6dc -> sub_10000c4ec : 28 -> 16
```
