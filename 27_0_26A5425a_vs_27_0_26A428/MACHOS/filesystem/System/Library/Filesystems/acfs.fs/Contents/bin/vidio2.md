## vidio2

> `/System/Library/Filesystems/acfs.fs/Contents/bin/vidio2`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x128c0
+  __TEXT.__text: 0x126e0
   __TEXT.__auth_stubs: 0x800
   __TEXT.__const: 0x2b8c
   __TEXT.__cstring: 0x23c8
-  __TEXT.__unwind_info: 0x4a8
+  __TEXT.__unwind_info: 0x710
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__auth_got: 0x400
   __DATA_CONST.__got: 0x50

   - /usr/lib/libedit.3.dylib
   - /usr/lib/libncurses.5.4.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 447
+  Functions: 448
   Symbols:   864
   CStrings:  390
 
Functions:
~ _io_queue_update_buffers : 196 -> 184
~ _io_stream_start : 76 -> 64
~ _qustat_reset : 312 -> 300
~ _qustat_minmax_reset : 232 -> 220
~ _qustat_grp_free : 216 -> 204
~ _qustat_grp_insert : 224 -> 212
~ _qustat_grp_remove : 224 -> 212
~ _qustat_grp_reset : 240 -> 228
~ __qustat_tbl_reset : 712 -> 700
~ _qustat_grp_minmax_reset : 240 -> 228
~ __qustat_tbl_minmax_reset : 164 -> 152
~ _qustat_minmax_tbl_reset : 224 -> 212
~ _qustat_tbl_reset : 224 -> 212
~ _qustat_tbl_free : 216 -> 204
~ __qustat_mod_free : 96 -> 84
~ _qustat_tbl_to_stat : 276 -> 272
~ __qustat_help_hash_free : 192 -> 180
~ _qustat_help_hash_destroy : 240 -> 228
~ _qustat_help_array_free : 240 -> 228
~ _qustat_help_free : 216 -> 204
~ _qustat_snprintf_end : 184 -> 172
~ __qustat_snprintf_end : 96 -> 84
+ _OUTLINED_FUNCTION_0
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ _unregister_spurious_wakeup : 160 -> 148
~ ___starter : 104 -> 92
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
~ _CloseLog : 220 -> 208
~ _GetLogFileInfo : 184 -> 172
~ _sn_hash_destroy : 128 -> 116
~ _sn_hash_info : 156 -> 148
~ _name_destroy_key : 60 -> 48
~ _uint64_destroy_key : 60 -> 48
~ _snfs_thread_sync : 112 -> 100
~ _auth_sign_data : 212 -> 204
~ _qustat_grp_time_snap_set : 232 -> 220
~ _qustat_rec_lvl : 92 -> 100
~ _qustat_rec_sum : 128 -> 136
~ _qustat_rec_time_end : 84 -> 72
```
