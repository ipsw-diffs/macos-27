## com.apple.driver.DiskImages.UDIFDiskImage

> `com.apple.driver.DiskImages.UDIFDiskImage`

```diff

 704.0.0.0.0
   __TEXT.__const: 0x3058
   __TEXT.__cstring: 0x2b0
-  __TEXT_EXEC.__text: 0xb1a4
+  __TEXT_EXEC.__text: 0xb32c
   __TEXT_EXEC.__auth_stubs: 0x240
   __DATA.__data: 0xc4
   __DATA.__common: 0xd8
Functions:
~ __ZN16KDIUDIFDiskImage9MetaClassC1Ev : 72 -> 76
~ __ZN16KDIUDIFDiskImageC2EPK11OSMetaClass : 52 -> 56
~ __ZN16KDIUDIFDiskImageC1EPK11OSMetaClass : 52 -> 56
~ __ZN16KDIUDIFDiskImageD0Ev : 68 -> 72
~ __ZN16KDIUDIFDiskImage9MetaClassC2Ev : 72 -> 76
~ __ZNK16KDIUDIFDiskImage9MetaClass5allocEv : 104 -> 108
~ __ZN16KDIUDIFDiskImageC1Ev : 88 -> 92
~ __ZN16KDIUDIFDiskImageC2Ev : 88 -> 92
~ __ZN16KDIUDIFDiskImage4freeEv : 132 -> 136
~ __ZN16KDIUDIFDiskImage5probeEP9IOServicePi : 96 -> 100
~ __ZN16KDIUDIFDiskImage13_handleAttachEP9IOService : 120 -> 124
~ __ZN16KDIUDIFDiskImage12_handleStartEP9IOService : 136 -> 140
~ __ZN16KDIUDIFDiskImage11readSectorsExxPxPvb : 1588 -> 1592
~ __ZN16KDIUDIFDiskImage15readSectorChunkExPxS0_PPvb : 780 -> 784
~ __ZN16KDIUDIFDiskImage20reportStoredChecksumEP17HDIChecksumStruct : 96 -> 100
~ __ZN16KDIUDIFDiskImage11enableCacheEb : 336 -> 340
~ __ZN16KDIUDIFDiskImage20_analyzeBackingStoreEv : 584 -> 588
~ __ZN16KDIUDIFDiskImage19_generateGlobalBLKXEP14UDIFFileHeaderPP6OSDatas : 1264 -> 1268
~ _GLOBAL__sub_I_KDIUDIFDiskImage.cpp : 80 -> 84
~ __ZN18KDIUDIFCacheObject9MetaClassC1Ev : 72 -> 76
~ __ZN18KDIUDIFCacheObjectC2EPK11OSMetaClass : 52 -> 56
~ __ZN18KDIUDIFCacheObjectC1EPK11OSMetaClass : 52 -> 56
~ __ZN18KDIUDIFCacheObjectD0Ev : 68 -> 72
~ __ZN18KDIUDIFCacheObject9MetaClassC2Ev : 72 -> 76
~ __ZNK18KDIUDIFCacheObject9MetaClass5allocEv : 104 -> 108
~ __ZN18KDIUDIFCacheObjectC1Ev : 88 -> 92
~ __ZN18KDIUDIFCacheObjectC2Ev : 88 -> 92
~ __ZN18KDIUDIFCacheObject4initEi : 400 -> 404
~ __ZN18KDIUDIFCacheBufferC1Ev : 88 -> 92
~ __ZN18KDIUDIFCacheObject4freeEv : 224 -> 228
~ __ZN18KDIUDIFCacheObject14getCacheBufferEx : 196 -> 200
~ __ZN18KDIUDIFCacheObject9cacheDataExxPKv : 192 -> 196
~ __ZN18KDIUDIFCacheBuffer9setLengthEx : 124 -> 128
~ __ZN18KDIUDIFCacheObject18displayCacheStatusEv : 196 -> 200
~ __ZN18KDIUDIFCacheBuffer9MetaClassC1Ev : 72 -> 76
~ __ZN18KDIUDIFCacheBufferC2EPK11OSMetaClass : 52 -> 56
~ __ZN18KDIUDIFCacheBufferC1EPK11OSMetaClass : 52 -> 56
~ __ZN18KDIUDIFCacheBufferD0Ev : 68 -> 72
~ __ZN18KDIUDIFCacheBuffer9MetaClassC2Ev : 72 -> 76
~ __ZNK18KDIUDIFCacheBuffer9MetaClass5allocEv : 104 -> 108
~ __ZN18KDIUDIFCacheBufferC2Ev : 88 -> 92
~ __ZN18KDIUDIFCacheBuffer4initEx : 108 -> 112
~ __ZN18KDIUDIFCacheBuffer4freeEv : 96 -> 100
~ _GLOBAL__sub_I_KDIUDIFDiskImageCache.cpp : 148 -> 152
~ __GLOBAL__D_a : 56 -> 60
~ __ZN15KDIUDIFEncoding9MetaClassC1Ev : 72 -> 76
~ __ZN15KDIUDIFEncodingC2EPK11OSMetaClass : 52 -> 56
~ __ZN15KDIUDIFEncodingC1EPK11OSMetaClass : 52 -> 56
~ __ZN15KDIUDIFEncodingD0Ev : 68 -> 72
~ __ZN15KDIUDIFEncoding9MetaClassC2Ev : 72 -> 76
~ __ZNK15KDIUDIFEncoding9MetaClass5allocEv : 104 -> 108
~ __ZN15KDIUDIFEncodingC1Ev : 88 -> 92
~ __ZN15KDIUDIFEncodingC2Ev : 88 -> 92
~ __ZN15KDIUDIFEncoding4freeEv : 108 -> 112
~ __ZN15KDIUDIFEncoding5probeEP9IOServicePi : 340 -> 344
~ __ZN15KDIUDIFEncoding14readUDIFHeaderEP15KDIBackingStoreP14UDIFFileHeaderb : 348 -> 352
~ __ZN15KDIUDIFEncoding12_handleStartEP9IOService : 248 -> 252
~ __ZN15KDIUDIFEncoding9readBytesExmPmPvb : 276 -> 280
~ __ZN15KDIUDIFEncoding12loadMetaDataEv : 668 -> 672
~ __ZN15KDIUDIFEncoding15releaseMetaDataEv : 76 -> 80
~ __ZN15KDIUDIFEncoding11getMetaDataEP8OSStringPP8OSObject : 248 -> 252
~ __ZN15KDIUDIFEncoding11getResourceEjsPP6OSData : 984 -> 988
~ __ZN15KDIUDIFEncoding14countResourcesEjPs : 344 -> 348
~ _GLOBAL__sub_I_KDIUDIFEncoding.cpp : 80 -> 84
~ __ZN20KDISecondaryEncoding9MetaClassC1Ev : 72 -> 76
~ __ZN20KDISecondaryEncodingC2EPK11OSMetaClass : 52 -> 56
~ __ZN20KDISecondaryEncoding9MetaClassC2Ev : 72 -> 76
~ __ZN20KDISecondaryEncoding13_handleAttachEP9IOService : 196 -> 200
~ _GLOBAL__sub_I_KDISecondaryEncoding.cpp : 80 -> 84
~ _di_safe_uncompress : 956 -> 960
~ _my_zalloc_vector : 56 -> 60
~ _lzvnDecode : 1220 -> 1192
~ _lzbitmap_decode : 2224 -> 2228
~ _zlib_decode_buffer : 376 -> 380
~ _zlibDecodeBuffer : 1660 -> 1668
~ _zlibDecodeBufferSafe : 1904 -> 1932
~ _readHuffmanTable : 1104 -> 1132
~ _getDecoderTable : 496 -> 504
~ _lz4raw_decode_buffer : 160 -> 164
~ _lzfse_decode_buffer : 408 -> 412
~ _lzfse_decode_buffer_output_size : 448 -> 452
~ _lzfseDecodeV1 : 428 -> 436
~ _lzfse_decode_buffer_iboot : 3324 -> 3332
~ _lzfse_decode_lzvn_block_iboot : 508 -> 512
~ _LZFSEIBootBufferPushN : 244 -> 248
~ _lzfseDecode : 5428 -> 5436
~ _lzbitmap_fast_decode : 1532 -> 1536
~ _lz24_decode_buffer : 696 -> 700
~ _lz4_decode : 468 -> 472
```
