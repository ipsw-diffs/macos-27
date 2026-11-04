## com.apple.filesystems.acfs

> `com.apple.filesystems.acfs`

```diff

-817.40.2.0.0
-  __TEXT.__cstring: 0x37eb7
+817.60.3.0.0
+  __TEXT.__cstring: 0x381f6
   __TEXT.__const: 0x3672
-  __TEXT_EXEC.__text: 0xcf7d0
-  __TEXT_EXEC.__auth_stubs: 0x1030
+  __TEXT_EXEC.__text: 0xcfcf8
+  __TEXT_EXEC.__auth_stubs: 0x1040
   __DATA.__data: 0x12498
   __DATA.__common: 0x60e4
   __DATA.__bss: 0x10934
   __DATA_CONST.__const: 0x3c8
   __DATA_CONST.__kalloc_type: 0x780
-  __DATA_CONST.__auth_got: 0x818
+  __DATA_CONST.__auth_got: 0x820
   __DATA_CONST.__got: 0x40
-  Functions: 4087
-  Symbols:   2253
-  CStrings:  5164
+  Functions: 4090
+  Symbols:   2255
+  CStrings:  5178
 
Symbols:
+ _get_msgbuf_alloclen
+ _memchr
Functions:
~ _dmig_path_to_handle : 1388 -> 1396
~ _FsmDataToken : 1608 -> 1648
~ _FsmGetExtentList : 520 -> 560
~ _FsmStatVfs : 1160 -> 1256
~ _FsmLookup : 684 -> 856
~ _FsmGetFullPath : 628 -> 716
~ _FsmGetNTSecurityDescriptor : 328 -> 412
~ _FsmSetNTSecurityDescriptor : 344 -> 424
~ _InitFsmReply : 104 -> 124
+ _get_msgbuf_alloclen
~ _snbt_scan : 1336 -> 1492
~ _ReadDirBlk3 : 2152 -> 2196
~ _LookupCvp : 1672 -> 1676
~ _cvrtqos_freeBucket : 444 -> 448
~ _cvrtqos_stopProcessing : 288 -> 292
~ _cvRtQos_createBucketFromReply : 636 -> 668
~ _cvfs_ioctl : 1448 -> 1524
~ _cvfs_searchfs : 3520 -> 3776
~ _xsanfs_getsecurity : 3152 -> 3104
+ _FsmDataToken.cold.3
+ _FsmGetExtentList.cold.4
CStrings:
+ "FsmDataToken: rejecting malformed extent count %d cookie 0x%llx"
+ "FsmGetExtentList: rejecting malformed extent count %d cookie 0x%llx"
+ "FsmGetFullPath: path truncated to fit target buffer"
+ "FsmGetNTSecurityDescriptor: bad nt_sd_key 0x%llx, rejecting"
+ "FsmLookup: rejecting malformed VopLkUpNmOffset 0x%x (maxNmOffset %u)"
+ "FsmLookup: server name truncated to fit %u byte buffer"
+ "FsmSetNTSecurityDescriptor: bad nt_sd_key 0x%llx, rejecting"
+ "FsmStatVfs: rejecting malformed domain sid off %d len %d"
+ "cvfs_searchfs: match data ran past reply buffer"
+ "cvfs_searchfs: rejecting bogus match length %u from FSM"
+ "cvfs_searchfs: rejecting bogus nummatches %d from FSM"
+ "snbt_scan bad entry idx/%d offs/%d len/%d, rejecting block"
+ "xan_spotlight_rpc: FSM claimed replyLen %u but only sent %u"
+ "xsanfs_getsecurity: cvp %p nt_sd_key 0x%llx bad SD length, rejecting"
```
