## com.apple.driver.DiskImages.KernelBacked

> `com.apple.driver.DiskImages.KernelBacked`

```diff

 704.0.0.0.0
   __TEXT.__cstring: 0x725
-  __TEXT_EXEC.__text: 0x8c20
+  __TEXT_EXEC.__text: 0x8e5c
   __TEXT_EXEC.__auth_stubs: 0x3d0
   __DATA.__data: 0xc4
   __DATA.__common: 0x178
Functions:
~ __ZN37IODiskImageBlockStorageDeviceInKernel9MetaClassC1Ev : 72 -> 76
~ __ZN37IODiskImageBlockStorageDeviceInKernelC2EPK11OSMetaClass : 52 -> 56
~ __ZN37IODiskImageBlockStorageDeviceInKernelC1EPK11OSMetaClass : 52 -> 56
~ __ZN37IODiskImageBlockStorageDeviceInKernelD0Ev : 68 -> 72
~ __ZN37IODiskImageBlockStorageDeviceInKernel9MetaClassC2Ev : 72 -> 76
~ __ZNK37IODiskImageBlockStorageDeviceInKernel9MetaClass5allocEv : 104 -> 108
~ __ZN37IODiskImageBlockStorageDeviceInKernelC1Ev : 88 -> 92
~ __ZN37IODiskImageBlockStorageDeviceInKernelC2Ev : 88 -> 92
~ __ZN37IODiskImageBlockStorageDeviceInKernel6attachEP9IOService : 108 -> 112
~ _GLOBAL__sub_I_IODiskImageBlockStorageDeviceInKernel.cpp : 80 -> 84
~ __ZN21IOHDIXHDDriveInKernel9MetaClassC1Ev : 72 -> 76
~ __ZN21IOHDIXHDDriveInKernelC2EPK11OSMetaClass : 52 -> 56
~ __ZN21IOHDIXHDDriveInKernelC1EPK11OSMetaClass : 52 -> 56
~ __ZN21IOHDIXHDDriveInKernelD0Ev : 68 -> 72
~ __ZN21IOHDIXHDDriveInKernel9MetaClassC2Ev : 72 -> 76
~ __ZNK21IOHDIXHDDriveInKernel9MetaClass5allocEv : 104 -> 108
~ __ZN21IOHDIXHDDriveInKernelC1Ev : 88 -> 92
~ __ZN21IOHDIXHDDriveInKernelC2Ev : 88 -> 92
~ __ZN21IOHDIXHDDriveInKernel4initEP12OSDictionary : 132 -> 136
~ __ZN21IOHDIXHDDriveInKernel5startEP9IOService : 164 -> 168
~ __ZN21IOHDIXHDDriveInKernel12didTerminateEP9IOServicejPb : 196 -> 200
~ __ZN21IOHDIXHDDriveInKernel16checkTerminationEPbPi : 180 -> 184
~ __ZN21IOHDIXHDDriveInKernel11handleCloseEP9IOServicej : 144 -> 148
~ __ZN21IOHDIXHDDriveInKernel6attachEP9IOService : 100 -> 104
~ __ZN21IOHDIXHDDriveInKernel4freeEv : 104 -> 108
~ __ZN21IOHDIXHDDriveInKernel14instantiateNubEv : 44 -> 48
~ __ZN21IOHDIXHDDriveInKernel20makeRequestAvailableEP13IOHDIXCommandb : 304 -> 308
~ __ZN21IOHDIXHDDriveInKernel14kernelIOThreadEPv : 228 -> 232
~ __ZN21IOHDIXHDDriveInKernel26getCommandFromWaitingQueueEv : 160 -> 164
~ __ZN21IOHDIXHDDriveInKernel24finalizeProcessedCommandERK13IOHDIXCommand : 108 -> 112
~ __ZN21IOHDIXHDDriveInKernel14processCommandER13IOHDIXCommandR12BounceBuffer : 1316 -> 1320
~ __ZN21IOHDIXHDDriveInKernel19processPropertyListEv : 1448 -> 1452
~ _GLOBAL__sub_I_IOHDIXHDDriveInKernel.cpp : 80 -> 84
~ __ZN9KDIObject9MetaClassC1Ev : 72 -> 76
~ __ZN9KDIObjectC2EPK11OSMetaClass : 52 -> 56
~ __ZN9KDIObject9MetaClassC2Ev : 72 -> 76
~ __ZN9KDIObject6attachEP9IOService : 124 -> 128
~ __ZN9KDIObject5startEP9IOService : 176 -> 180
~ __ZN9KDIObject4stopEP9IOService : 120 -> 124
~ __ZN9KDIObject10handleOpenEP9IOServicejPv : 204 -> 208
~ __ZN9KDIObject11handleCloseEP9IOServicej : 136 -> 140
~ __ZN9KDIObject6detachEP9IOService : 136 -> 140
~ _GLOBAL__sub_I_KDIObject.cpp : 80 -> 84
~ __ZN15KDIBackingStore9MetaClassC1Ev : 72 -> 76
~ __ZN15KDIBackingStoreC2EPK11OSMetaClass : 52 -> 56
~ __ZN15KDIBackingStore9MetaClassC2Ev : 72 -> 76
~ __ZN15KDIBackingStore13_handleAttachEP9IOService : 100 -> 104
~ __ZN15KDIBackingStore12_handleStartEP9IOService : 344 -> 348
~ __ZN15KDIBackingStore9readBytesExmPmPvb : 40 -> 44
~ __ZN15KDIBackingStore10writeBytesExmPmPKvb : 40 -> 44
~ __ZN15KDIBackingStore14setUnmatchableEb : 104 -> 108
~ _GLOBAL__sub_I_KDIBackingStore.cpp : 80 -> 84
~ __ZN11KDIEncoding9MetaClassC1Ev : 72 -> 76
~ __ZN11KDIEncodingC2EPK11OSMetaClass : 52 -> 56
~ __ZN11KDIEncoding9MetaClassC2Ev : 72 -> 76
~ __ZN11KDIEncoding13_handleAttachEP9IOService : 72 -> 76
~ _GLOBAL__sub_I_KDIEncoding.cpp : 80 -> 84
~ __ZN15KDIDiskImageNub9MetaClassC1Ev : 72 -> 76
~ __ZN15KDIDiskImageNubC2EPK11OSMetaClass : 52 -> 56
~ __ZN15KDIDiskImageNubC1EPK11OSMetaClass : 52 -> 56
~ __ZN15KDIDiskImageNubD0Ev : 68 -> 72
~ __ZN15KDIDiskImageNub9MetaClassC2Ev : 72 -> 76
~ __ZNK15KDIDiskImageNub9MetaClass5allocEv : 104 -> 108
~ __ZN15KDIDiskImageNubC1Ev : 88 -> 92
~ __ZN15KDIDiskImageNubC2Ev : 88 -> 92
~ __ZN15KDIDiskImageNub5probeEP9IOServicePi : 120 -> 124
~ __ZN15KDIDiskImageNub4freeEv : 112 -> 116
~ __ZN15KDIDiskImageNub6attachEP9IOService : 108 -> 112
~ __ZN15KDIDiskImageNub5startEP9IOService : 812 -> 816
~ __ZN15KDIDiskImageNub16attachShadowFileEP12OSDictionary : 612 -> 616
~ __ZN15KDIDiskImageNub11handleCloseEP9IOServicej : 144 -> 148
~ _GLOBAL__sub_I_KDIDiskImageNub.cpp : 80 -> 84
~ __ZN25KDIDiskImageNubUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN25KDIDiskImageNubUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN25KDIDiskImageNubUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN25KDIDiskImageNubUserClientD0Ev : 68 -> 72
~ __ZN25KDIDiskImageNubUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK25KDIDiskImageNubUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN25KDIDiskImageNubUserClientC1Ev : 88 -> 92
~ __ZN25KDIDiskImageNubUserClientC2Ev : 88 -> 92
~ __ZN25KDIDiskImageNubUserClient6attachEP9IOService : 108 -> 112
~ __ZN25KDIDiskImageNubUserClient11clientCloseEv : 260 -> 264
~ __ZN25KDIDiskImageNubUserClient5startEP9IOService : 128 -> 132
~ __ZN25KDIDiskImageNubUserClient4stopEP9IOService : 128 -> 132
~ __ZN25KDIDiskImageNubUserClient4freeEv : 88 -> 92
~ __ZN25KDIDiskImageNubUserClient21validateImageInfoDictEP12OSDictionary : 264 -> 268
~ __ZN25KDIDiskImageNubUserClient16attachShadowFileEPKvm : 356 -> 360
~ _GLOBAL__sub_I_KDIDiskImageNubUserClient.cpp : 80 -> 84
~ __ZN12KDIDiskImage9MetaClassC1Ev : 72 -> 76
~ __ZN12KDIDiskImageC2EPK11OSMetaClass : 52 -> 56
~ __ZN12KDIDiskImage9MetaClassC2Ev : 72 -> 76
~ __ZN12KDIDiskImage13_handleAttachEP9IOService : 280 -> 284
~ __ZN12KDIDiskImage12_handleStartEP9IOService : 1476 -> 1480
~ __ZN12KDIDiskImage14setUnmatchableEb : 148 -> 152
~ __ZN12KDIDiskImage5flushEv : 136 -> 140
~ _GLOBAL__sub_I_KDIDiskImage.cpp : 80 -> 84
~ __ZN20KDIShadowedDiskImage9MetaClassC1Ev : 72 -> 76
~ __ZN20KDIShadowedDiskImageC2EPK11OSMetaClass : 52 -> 56
~ __ZN20KDIShadowedDiskImageC1EPK11OSMetaClass : 52 -> 56
~ __ZN20KDIShadowedDiskImageD0Ev : 68 -> 72
~ __ZN20KDIShadowedDiskImage9MetaClassC2Ev : 72 -> 76
~ __ZNK20KDIShadowedDiskImage9MetaClass5allocEv : 104 -> 108
~ __ZN20KDIShadowedDiskImageC1Ev : 88 -> 92
~ __ZN20KDIShadowedDiskImageC2Ev : 88 -> 92
~ __ZN20KDIShadowedDiskImage4freeEv : 316 -> 320
~ __ZN20KDIShadowedDiskImage18_flushShadowBitmapEbxx : 164 -> 168
~ __ZN20KDIShadowedDiskImage25_flushHeaderAndIndexNodesEb : 80 -> 84
~ __ZN20KDIShadowedDiskImage27_destroyHeaderAndIndexNodesEv : 84 -> 88
~ __ZN20KDIShadowedDiskImage20_destroyShadowBitmapEv : 52 -> 56
~ __ZN20KDIShadowedDiskImage19_destroyShadowTableEv : 60 -> 64
~ __ZN20KDIShadowedDiskImage5probeEP9IOServicePi : 172 -> 176
~ __ZN20KDIShadowedDiskImage13_handleAttachEP9IOService : 172 -> 176
~ __ZN20KDIShadowedDiskImage12_handleStartEP9IOService : 164 -> 168
~ __ZN20KDIShadowedDiskImage11_handleStopEP9IOService : 124 -> 128
~ __ZN20KDIShadowedDiskImage11readSectorsExxPxPvb : 812 -> 816
~ __ZN20KDIShadowedDiskImage17_pinSectorRequestExxPxPb : 288 -> 292
~ __ZN20KDIShadowedDiskImage12writeSectorsExxPxPKvb : 300 -> 304
~ __ZN20KDIShadowedDiskImage17_writeSectorsCoreExxPxPKvbb : 396 -> 400
~ __ZN20KDIShadowedDiskImage21_writeShadowedSectorsExxPxPKvb : 440 -> 444
~ __ZN20KDIShadowedDiskImage20_markShadowBitmapRunExxbb : 636 -> 640
~ __ZN20KDIShadowedDiskImage44_optimizedNewBandWithSectorUsingShadowBitmapExxPxPKcb : 452 -> 456
~ __ZN20KDIShadowedDiskImage27_optimizedNewBandWithSectorExxPxPKvb : 436 -> 440
~ __ZN20KDIShadowedDiskImage5flushEv : 136 -> 140
~ __ZN20KDIShadowedDiskImage20_analyzeBackingStoreEv : 120 -> 124
~ __ZN20KDIShadowedDiskImage18_prepareShadowFileEb : 2004 -> 2008
~ __ZN20KDIShadowedDiskImage24_loadHeaderAndIndexNodesEb : 524 -> 528
~ __ZN20KDIShadowedDiskImage28_matchHeaderAgainstBaseImageEv : 260 -> 264
~ __ZN20KDIShadowedDiskImage17_loadShadowBitmapEb : 264 -> 268
~ __ZN20KDIShadowedDiskImage20_generateShadowTableEv : 528 -> 532
~ __ZN20KDIShadowedDiskImage16_resetShadowFileEj : 500 -> 504
~ __ZN20KDIShadowedDiskImage13setLogicalEOFEx : 172 -> 176
~ __ZN20KDIShadowedDiskImage23writeHeaderNodeWithSlopEP15KDIBackingStorePK20ShadowFileHeaderNodemb : 292 -> 296
~ __ZN20KDIShadowedDiskImage14readHeaderNodeEP15KDIBackingStoreP20ShadowFileHeaderNodeb : 124 -> 128
~ __ZN20KDIShadowedDiskImage13readIndexNodeEP15KDIBackingStorexP19ShadowFileIndexNodeb : 124 -> 128
~ __ZN20KDIShadowedDiskImage17_updateHeaderNodeEb : 260 -> 264
~ __ZN20KDIShadowedDiskImage17_updateIndexNodesEb : 360 -> 364
~ __ZN20KDIShadowedDiskImage15writeHeaderNodeEP15KDIBackingStorePK20ShadowFileHeaderNodeb : 204 -> 208
~ __ZN20KDIShadowedDiskImage14writeIndexNodeEP15KDIBackingStorexPK19ShadowFileIndexNodeb : 208 -> 212
~ __ZN20KDIShadowedDiskImage13_addIndexNodeEb : 648 -> 652
~ __ZN20KDIShadowedDiskImage18_displayHeaderNodeEP20ShadowFileHeaderNode : 268 -> 272
~ __ZN20KDIShadowedDiskImage17_displayIndexNodeEP19ShadowFileIndexNode : 188 -> 192
~ __ZN20KDIShadowedDiskImage20_displayShadowBitmapEv : 184 -> 188
~ _GLOBAL__sub_I_KDIShadowedDiskImage.cpp : 80 -> 84
```
