## mscamerad-xpc

> `/System/Library/Frameworks/ImageCaptureCore.framework/Versions/A/XPCServices/mscamerad-xpc.xpc/Contents/MacOS/mscamerad-xpc`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2118.0.0.0.0
-  __TEXT.__text: 0x176b8
+  __TEXT.__text: 0x171fc
   __TEXT.__auth_stubs: 0x6c0
   __TEXT.__objc_stubs: 0x2d20
   __TEXT.__objc_methlist: 0xf94

   __TEXT.__ustring: 0x280
   __TEXT.__objc_classname: 0xec
   __TEXT.__objc_methtype: 0x574
-  __TEXT.__unwind_info: 0x3f8
+  __TEXT.__unwind_info: 0x4f0
   __DATA_CONST.__const: 0x4a0
   __DATA_CONST.__cfstring: 0x1d60
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ __diskAppearedCallback : 260 -> 248
~ __diskDisappearedCallback : 260 -> 248
~ __diskChangedCallback : 268 -> 256
~ -[MSStorageMediaProvider createStringUUIDForBSDName:diskDescription:] : 1668 -> 1656
~ __diskEjectCallback : 48 -> 36
~ -[MSStorageMediaProvider .cxx_destruct] : 92 -> 80
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ ___64-[MSCameraDevice requestDownloadObjectHandle:options:withReply:]_block_invoke : 160 -> 148
~ ___68-[MSCameraDevice requestReadDataFromObjectHandle:options:withReply:]_block_invoke : 208 -> 196
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ -[MSCameraDevice filesystemPath] : 88 -> 76
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ -[MSCameraDevice name] : 88 -> 76
~ -[MSCameraDevice reflight:error:] : 1172 -> 1160
~ -[MSCameraDevice addCameraFileToIndex:] : 96 -> 84
~ -[MSCameraDevice addCameraFolderToIndex:] : 96 -> 84
~ -[MSCameraDevice cameraFileWithObjectID:] : 96 -> 84
~ -[MSCameraDevice cameraFolderWithObjectID:] : 96 -> 84
~ -[MSCameraDevice cameraItemWithObjectID:] : 92 -> 80
~ -[MSCameraDevice removeCameraFileFromIndex:] : 132 -> 120
~ -[MSCameraDevice removeCameraFolderFromIndex:] : 128 -> 116
~ -[MSCameraDevice indexedFiles] : 88 -> 76
~ -[MSCameraDevice indexedFolders] : 88 -> 76
~ -[MSCameraDevice .cxx_destruct] : 124 -> 112
~ _OUTLINED_FUNCTION_1 : 32 -> 20
~ _ICGetDimensionsFromImageProperties : 356 -> 344
~ _ICStandardDateFromString : 128 -> 116
~ ___29-[ICBufferCache startReading]_block_invoke : 64 -> 52
~ ___26-[ICBufferCache readQueue]_block_invoke : 1140 -> 1128
~ ___45-[ICBufferCache consumeBufferAtOffset:sized:]_block_invoke : 288 -> 276
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ -[ICBufferCache .cxx_destruct] : 92 -> 80
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___copy_helper_block_e8_32s40s48r56r64r : 112 -> 100
~ ___destroy_helper_block_e8_32s40s48r56r64r : 96 -> 84
~ -[MSCameraItem name] : 80 -> 68
~ -[MSCameraItem setName:] : 96 -> 84
~ -[MSCameraItem baseName] : 80 -> 68
~ -[MSCameraItem setSize:] : 72 -> 60
~ -[MSCameraItem setObjHandle:] : 72 -> 60
~ -[MSCameraItem setParentObject:] : 72 -> 60
~ -[MSCameraItem setProtectionStatus:] : 72 -> 60
~ -[MSCameraItem setCaptureDate:] : 72 -> 60
~ -[MSCameraItem setModificationDate:] : 72 -> 60
~ -[MSCameraItem cancelSource] : 80 -> 68
~ -[MSCameraItem refreshInfo:] : 2132 -> 2120
~ ___copy_helper_block_e8_32s40s48s56s : 76 -> 64
~ -[MSCameraItem parent] : 44 -> 32
~ -[MSCameraItem device] : 44 -> 32
~ -[MSCameraItem .cxx_destruct] : 156 -> 144
~ -[MSCameraFile setHasThumbnail:] : 136 -> 124
~ -[MSCameraFile setImageHeight:] : 72 -> 60
~ -[MSCameraFile setImageWidth:] : 72 -> 60
~ -[MSCameraFile setImageOrientation:] : 72 -> 60
~ -[MSCameraFile createBufferCacheAtOffset:] : 144 -> 132
~ -[MSCameraFile destroyBufferCache] : 80 -> 68
~ -[MSCameraFile thumbnailDataUsingSidecarFiles] : 584 -> 572
~ -[MSCameraFile createThumbnailUsingOffsets:] : 1224 -> 1212
~ -[MSCameraFile metadataWithOptions:reply:] : 260 -> 248
~ -[MSCameraFile updateBasicMetadata] : 552 -> 540
~ ___32-[MSCameraFile imageIOSupported]_block_invoke : 100 -> 88
~ ___33-[MSCameraFile rawImageSupported]_block_invoke : 120 -> 108
~ -[MSCameraFile setSizeAndOrientationFromImageProperties:] : 228 -> 216
~ -[MSCameraFile rawImageValidateSubImage:error:] : 812 -> 800
~ -[MSCameraFile subImageDictForPixelWidth:] : 1348 -> 1336
~ -[MSCameraFile metadataDict] : 1424 -> 1412
~ -[MSCameraFile thumbnailDataForMaxPixelSize:rotated:] : 632 -> 620
~ -[MSCameraFile imageThumbnailDataForMaxPixelSize:rotated:] : 1264 -> 1252
~ -[MSCameraFile scaleData:maxPixelSize:] : 352 -> 340
~ -[MSCameraFile createImageDataForMaxPixelSize:] : 636 -> 624
~ -[MSCameraFile movieThumbnailDataForMaxPixelSize:] : 948 -> 936
~ ___copy_helper_block_e8_32s40s48r56r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48r56r : 84 -> 72
~ -[MSCameraFile fingerprintWithError:] : 220 -> 208
~ -[MSCameraFile .cxx_destruct] : 92 -> 80
~ _OUTLINED_FUNCTION_2 : 28 -> 16
~ -[NSURL(ImageCaptureAdditions) baseName] : 108 -> 96
~ -[NSURL(ImageCaptureAdditions) baseNameKey] : 228 -> 216
~ -[MSCameraFolder issueReflight] : 1156 -> 1144
~ __31-[MSCameraFolder issueReflight]_block_invoke.26 : 228 -> 216
~ ___51-[MSCameraFolder initWithFSURL:name:parent:device:]_block_invoke : 112 -> 100
~ ___51-[MSCameraFolder initWithFSURL:name:parent:device:]_block_invoke_2 : 44 -> 32
~ -[MSCameraFolder cancelReflight] : 104 -> 92
~ -[MSCameraFolder createAssetFromURL:notify:preflight:] : 652 -> 640
~ -[MSCameraFolder createValidAssetFromURL:attemptCount:notify:preflight:] : 1428 -> 1416
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[MSCameraFolder folderMatchingPath:] : 300 -> 288
~ -[MSCameraFolder .cxx_destruct] : 124 -> 112
~ -[MSRemoteCameraDeviceManager ejectDevice:withReply:] : 248 -> 236
~ -[MSRemoteCameraDeviceManager .cxx_destruct] : 84 -> 72
```
