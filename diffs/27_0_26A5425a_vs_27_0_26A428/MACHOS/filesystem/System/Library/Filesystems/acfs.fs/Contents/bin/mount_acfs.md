## mount_acfs

> `/System/Library/Filesystems/acfs.fs/Contents/bin/mount_acfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x24454
+  __TEXT.__text: 0x242a4
   __TEXT.__auth_stubs: 0x9a0
   __TEXT.__const: 0x30e8
   __TEXT.__cstring: 0x87fb
   __TEXT.__oslogstring: 0x5bd
-  __TEXT.__unwind_info: 0x5d0
+  __TEXT.__unwind_info: 0x7a0
   __DATA_CONST.__const: 0x198
   __DATA_CONST.__cfstring: 0x460
   __DATA_CONST.__auth_got: 0x4d0
Functions:
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ _MntUsage : 116 -> 104
~ _FindFsctlDev : 296 -> 292
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
~ _FsmPMFreeCoordList : 156 -> 144
~ __HexDump : 468 -> 456
~ _scan_progress : 716 -> 704
~ _CvDumpLabel : 2596 -> 2584
~ _CvFreeLabelBuffer : 68 -> 56
~ _CvCopyLabel : 80 -> 68
~ _verify_lun_readable : 736 -> 732
~ _label_config_failed : 204 -> 192
~ _CvBuildLabelEFI : 344 -> 332
~ _CvBuildLabel : 428 -> 404
~ _CvLabelWarnings : 712 -> 700
~ _CvLabelChangeEssay : 436 -> 424
~ _PlistString : 224 -> 212
~ _CvDisplayLabel : 1816 -> 1804
~ _disk_scan_finalize : 1748 -> 1744
~ _CvPrintInfo : 664 -> 652
~ _human_capacity : 200 -> 188
~ _initLibMPIOFramework : 40 -> 28
~ _find_IORegistryBSDName : 832 -> 836
~ _find_IORegistryContent : 728 -> 704
~ _find_IORegistrySerialNumber : 2248 -> 2260
~ _print_ucs2 : 108 -> 96
~ _auth_sign_data : 212 -> 204
~ _PanicCheckedWriteLog : 328 -> 304
~ _initialize_roots : 292 -> 280
~ _get_masklen : 140 -> 128
~ _ResetAddrLists : 96 -> 84
~ _save_metadata_filter : 200 -> 188
~ _BuildAddrLists : 3032 -> 3040
~ __enumerate_mac_addrs : 152 -> 140
~ __enumerate_ip_addrs : 164 -> 152
~ _enumerate_auth_ids : 112 -> 100
~ _RecvFromTo : 516 -> 504
~ _FormatSysError : 68 -> 56
~ _parse_option : 1440 -> 1444
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
```
