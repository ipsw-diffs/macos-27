## AMPDevicesAgent

> `/System/Library/PrivateFrameworks/AMPDevices.framework/Versions/Current/Support/AMPDevicesAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1.7.3.10.0
-  __TEXT.__text: 0x6639ac
-  __TEXT.__auth_stubs: 0x58b0
+1.7.3.21.0
+  __TEXT.__text: 0x664264
+  __TEXT.__auth_stubs: 0x58c0
   __TEXT.__objc_stubs: 0x8300
   __TEXT.__init_offsets: 0x90
   __TEXT.__objc_methlist: 0x1f34
   __TEXT.__const: 0x85c24
-  __TEXT.__gcc_except_tab: 0x2b12c
-  __TEXT.__cstring: 0x60607
-  __TEXT.__oslogstring: 0x1c6f1
+  __TEXT.__gcc_except_tab: 0x2b164
+  __TEXT.__cstring: 0x60665
+  __TEXT.__oslogstring: 0x1c7f4
   __TEXT.__objc_methname: 0x8e3d
   __TEXT.__objc_classname: 0x374
   __TEXT.__objc_methtype: 0x28fd
-  __TEXT.__unwind_info: 0x15fa0
+  __TEXT.__unwind_info: 0x15fc0
   __TEXT.__eh_frame: 0x1c0
-  __DATA_CONST.__const: 0x54070
+  __DATA_CONST.__const: 0x54080
   __DATA_CONST.__cfstring: 0x13ea0
   __DATA_CONST.__objc_classlist: 0x90
   __DATA_CONST.__objc_catlist: 0x48

   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x70
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x2c70
+  __DATA_CONST.__auth_got: 0x2c78
   __DATA_CONST.__got: 0xec0
   __DATA_CONST.__auth_ptr: 0x198
   __DATA.__objc_const: 0x2268

   __DATA.__objc_data: 0x5a0
   __DATA.__data: 0x1ab8
   __DATA.__common: 0x3b08
-  __DATA.__bss: 0x33768
+  __DATA.__bss: 0x33798
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 17933
-  Symbols:   1932
-  CStrings:  19830
+  Functions: 17939
+  Symbols:   1933
+  CStrings:  19839
 
Symbols:
+ _CFDateGetTimeIntervalSinceDate
CStrings:
+ "(outChangeDataVar->mValidFields & kAMPLPlaylistChangeDataValidField_Var_CloudArtworkVariantsInfo) != kAMPLPlaylistChangeDataValidFields_Var_None"
+ "1.7.3.21"
+ "13.7.3.21"
+ "@24@0:8r^{IPodDeviceInfo=Q{IPodVersionInfo={NumVersion=CCCC}I{NumVersion=CCCC}S[32c][32c][32c][32c][32c][32c]ISIIIICC}[256c][64c]I[64S]CCC[16c][16c]CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCSCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCSSS[16c][16c]IIIQ[20C]ISSSIIIIISCICCCCiI[8c]QQIS{DeviceAudioCodecList=I[20{DeviceAudioCodecInfo=ICCCCCffIIII}]}{DeviceVideoCodecList=I[30{DeviceVideoCodecInfo=ICCCCCCfCCCIIIIIIIIIifICCC{DeviceAudioCodecList=I[20{DeviceAudioCodecInfo=ICCCCCffIIII}]}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}QIIIIIQII[16c][8c][32c][32c][32c][32c][32c][32c][32c][32c][32c][34c][256c]CCCCCCC{VoiceMemoCodecList=I[25{VoiceMemoCodecInfo=SffII}]}IIIIIIIIIICCCCCCCCCIIIIIISSfCC}16"
+ "AMPDevicesAgent: 1.7.3.21"
+ "CalculatedArtworkVariantsInfo"
+ "CloudArtworkVariantsInfo"
+ "Detected expired or expiring JWT token for client id %{public}s."
+ "Received new JWT token for client id %{public}s. Expiration %{public}@."
+ "Requesting new JWT token for client id %{public}s."
+ "cloudArtworkVariantsInfo"
+ "codecList->numCodecs < 30"
+ "genius> callback for %16.llu  m %u"
+ "genius> callback for %16.llu  s %lu"
+ "jwt_service"
+ "log-genius"
- "(outChangeDataVar->mValidFields & kAMPLPlaylistChangeDataValidField_Var_ArtworkVariantsInfo) != kAMPLPlaylistChangeDataValidFields_Var_None"
- "1.7.3.10"
- "13.7.3.10"
- "@24@0:8r^{IPodDeviceInfo=Q{IPodVersionInfo={NumVersion=CCCC}I{NumVersion=CCCC}S[32c][32c][32c][32c][32c][32c]ISIIIICC}[256c][64c]I[64S]CCC[16c][16c]CCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCSCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCCSSS[16c][16c]IIIQ[20C]ISSSIIIIISCICCCCiI[8c]QQIS{DeviceAudioCodecList=I[20{DeviceAudioCodecInfo=ICCCCCffIIII}]}{DeviceVideoCodecList=I[20{DeviceVideoCodecInfo=ICCCCCCfCCCIIIIIIIIIifICCC{DeviceAudioCodecList=I[20{DeviceAudioCodecInfo=ICCCCCffIIII}]}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}{ITImageFormatList=iIIBBI[20{ITImageFormatDescription=IIIC{ThumbnailFormat=IISSSSSSS{RGBColor=SSS}CCCCCCCCCIIC{Rect=ssss}I{RGBColor=SSS}CiCIf^vSSSS}}]}QIIIIIQII[16c][8c][32c][32c][32c][32c][32c][32c][32c][32c][32c][34c][256c]CCCCCCC{VoiceMemoCodecList=I[25{VoiceMemoCodecInfo=SffII}]}IIIIIIIIIICCCCCCCCCIIIIIISSfCC}16"
- "AMPDevicesAgent: 1.7.3.10"
- "ArtworkVariantsInfo"
- "artworkVariantsInfo"
```
