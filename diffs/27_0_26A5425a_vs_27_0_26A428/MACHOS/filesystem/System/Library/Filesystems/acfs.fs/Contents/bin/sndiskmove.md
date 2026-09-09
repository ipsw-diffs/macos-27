## sndiskmove

> `/System/Library/Filesystems/acfs.fs/Contents/bin/sndiskmove`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 817.0.0.0.0
-  __TEXT.__text: 0x1faec
+  __TEXT.__text: 0x1f8fc
   __TEXT.__auth_stubs: 0x9f0
   __TEXT.__cstring: 0x77ed
   __TEXT.__const: 0x3080
-  __TEXT.__unwind_info: 0x590
+  __TEXT.__unwind_info: 0x728
   __DATA_CONST.__cfstring: 0x460
   __DATA_CONST.__auth_got: 0x4f8
   __DATA_CONST.__got: 0x78
Functions:
~ _main : 4036 -> 4028
~ _usage : 428 -> 416
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
~ _FsmPMGetDisks : 1388 -> 1384
~ _FsmGetPartitionNativeKeys : 416 -> 412
~ _FsmStartIoTest : 352 -> 344
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
~ _UtilTrackSuccess : 76 -> 64
~ _UtilTrackReport : 368 -> 356
~ _UtilTrackClose : 64 -> 52
~ _UtilTrackFailure : 64 -> 52
~ _UtilTrackHeartBeatPulse : 112 -> 100
~ _ThreadPriority : 208 -> 200
~ _RecvFromTo : 516 -> 504
~ _FormatSysError : 68 -> 56
~ _FsmSetEmbeddedCluster : 176 -> 172
~ _FsmCopyEmbedded : 148 -> 136
~ _auth_sign_data : 212 -> 204
```
