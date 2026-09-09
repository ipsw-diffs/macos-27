## MFAANetwork

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/Versions/Current/XPCServices/MFAANetwork.xpc/Contents/MacOS/MFAANetwork`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1216.0.0.0.0
-  __TEXT.__text: 0x129560
+  __TEXT.__text: 0x1290ec
   __TEXT.__auth_stubs: 0x340
   __TEXT.__objc_stubs: 0x1500
   __TEXT.__objc_methlist: 0x74c

   __TEXT.__oslogstring: 0x1a32
   __TEXT.__ustring: 0xa
   __TEXT.__gcc_except_tab: 0x150
-  __TEXT.__unwind_info: 0x4a0
+  __TEXT.__unwind_info: 0x670
   __TEXT.__eh_frame: 0x80
   __DATA_CONST.__const: 0xbcb0
   __DATA_CONST.__cfstring: 0x10a0

   __DATA.__objc_data: 0x140
   __DATA.__data: 0x790
   __DATA.__common: 0xa28
-  __DATA.__bss: 0x50
+  __DATA.__bss: 0x48
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 436
-  Symbols:   766
+  Symbols:   765
   CStrings:  637
 
Symbols:
- systemInfo_isDeveloperBuild.developerBuild
Functions:
~ _printBytes : 156 -> 144
~ _init_logging : 60 -> 48
~ +[NSError(MFAAError) MFAA_errorWithDomain:code:] : 140 -> 128
~ +[NSError(MFAAError) MFAA_errorWithDomain:code:description:] : 256 -> 244
~ +[NSError(MFAAError) MFAA_errorWithDomain:code:failureReason:] : 312 -> 300
~ _systemInfo_isDeveloperBuild : 56 -> 52
~ ___systemInfo_isDeveloperBuild_block_invoke : 16 -> 4
~ _convertNSDataToNSString : 272 -> 260
~ _trimBidirectionalUnicodeCharacters : 132 -> 120
~ _removeBidirectionalUnicodeCharacters : 164 -> 152
~ _convertNSStringToNSData : 460 -> 448
~ _NSObjectIfNotNull : 92 -> 80
~ _castNSObjectToType : 108 -> 96
~ _readJSONFile : 160 -> 148
~ _base64EncodeArray : 340 -> 328
~ _base64DecodeArray : 352 -> 340
~ _logObjectForModule : 132 -> 120
~ -[MFAANetwork certStatusCache] : 92 -> 80
~ -[MFAANetwork certStatusCacheVersion] : 152 -> 140
~ -[MFAANetwork pairingTable] : 92 -> 80
~ -[MFAANetwork pairingTableVersion] : 152 -> 140
~ -[MFAANetwork setCertStatusCache:] : 108 -> 96
~ -[MFAANetwork setCertStatusCacheVersion:] : 108 -> 96
~ -[MFAANetwork setPairingTable:] : 108 -> 96
~ -[MFAANetwork setPairingTableVersion:] : 108 -> 96
~ -[MFAANetwork _selectedFairPlaySAPServer] : 488 -> 476
~ -[MFAANetwork _selectedAPIServer] : 588 -> 576
~ -[MFAANetwork _openFairPlaySAPSession] : 528 -> 516
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[MFAANetwork _fairPlaySignatureForDataSync:timedOut:error:] : 740 -> 728
~ ___60-[MFAANetwork _fairPlaySignatureForDataSync:timedOut:error:]_block_invoke : 176 -> 164
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ ___67-[MFAANetwork _verifyFairPlaySignatureSync:forData:timedOut:error:]_block_invoke : 108 -> 96
~ -[MFAANetwork _generateTokenAuthURLRequestForEndpoint:sessionID:signature:requestUUID:] : 572 -> 560
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ __splitASN1Tokens : 1416 -> 1404
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___copy_helper_block_e8_32s40s48s56s64b : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64s : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56s64r : 96 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s64r : 88 -> 76
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ ___copy_helper_block_e8_32s40s48s56r64r : 104 -> 92
~ ___destroy_helper_block_e8_32s40s48s56r64r : 92 -> 80
~ +[MFAANetwork sharedInstance] : 160 -> 148
~ ___29+[MFAANetwork sharedInstance]_block_invoke : 64 -> 52
~ -[MFAANetwork .cxx_destruct] : 104 -> 92
~ -[MFAANetworkExported requestMetadataForToken:withUUID:requestedLocale:requestInfo:withReply:] : 228 -> 216
~ -[MFAANetworkExported requestActivationForToken:withUUID:withReply:] : 164 -> 152
~ -[MFAANetworkExported confirmActivationForToken:withUUID:withReply:] : 164 -> 152
~ -[MFAANetworkExported requestMetadataForCertSerial:issuerSeq:ppid:requestedLocale:requestInfo:withReply:] : 264 -> 252
~ -[MFAANetworkExported validateCertSerial:issuerSeq:ppid:withReply:] : 200 -> 188
~ -[MFAANetworkExported getCachedStatusForCertSerial:issuerSeq:ppid:withReply:] : 200 -> 188
~ -[MFAANetworkExported addPairingWithToken:withReply:] : 136 -> 124
~ -[MFAANetworkExported removePairingWithToken:withReply:] : 136 -> 124
~ -[MFAANetworkExported verifyPairingWithToken:withReply:] : 136 -> 124
~ _OUTLINED_FUNCTION_7 : 32 -> 20
~ _OUTLINED_FUNCTION_10 : 28 -> 16
~ _OUTLINED_FUNCTION_12 : 32 -> 20
~ _OUTLINED_FUNCTION_13 : 28 -> 16
~ _OUTLINED_FUNCTION_14 : 36 -> 24
~ _OUTLINED_FUNCTION_16 : 28 -> 16
~ _OUTLINED_FUNCTION_17 : 24 -> 12
~ _OUTLINED_FUNCTION_18 : 32 -> 20
~ _OUTLINED_FUNCTION_19 : 32 -> 20
~ _OUTLINED_FUNCTION_20 : 24 -> 12
~ -[NSLocale(Additions) languageCodeAndCountryCode] : 148 -> 136
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.20 : 120 -> 108
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.28 : 112 -> 100
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.29 : 112 -> 100
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.34 : 112 -> 100
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.36 : 112 -> 100
~ ___copy_helper_block_e8_32s40s48s56b : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56s : 76 -> 64
~ __48-[FairPlaySAPSession openWithCompletionHandler:]_block_invoke.40 : 120 -> 108
~ __57-[FairPlaySAPSession signatureForData:completionHandler:]_block_invoke.45 : 104 -> 92
~ __57-[FairPlaySAPSession signatureForData:completionHandler:]_block_invoke.46 : 104 -> 92
~ __57-[FairPlaySAPSession signatureForData:completionHandler:]_block_invoke_2.47 : 112 -> 100
~ __64-[FairPlaySAPSession verifySignature:forData:completionHandler:]_block_invoke.51 : 104 -> 92
~ __64-[FairPlaySAPSession verifySignature:forData:completionHandler:]_block_invoke.52 : 104 -> 92
~ __64-[FairPlaySAPSession verifySignature:forData:completionHandler:]_block_invoke_2.53 : 112 -> 100
~ -[FairPlaySAPSession description] : 176 -> 164
~ ___25-[FairPlaySAPSession TTL]_block_invoke : 112 -> 100
~ +[FairPlaySAPSession sessionWithDelegate:] : 92 -> 80
~ -[FairPlaySAPSession delegate] : 44 -> 32
~ -[FairPlaySAPSession .cxx_destruct] : 112 -> 100
~ +[NSError(FairPlaySAPSessionError) FPSAPS_errorWithCode:] : 116 -> 104
~ +[NSError(FairPlaySAPSessionError) FPSAPS_errorWithCode:andDescription:] : 236 -> 224
~ _DERDecodeItemPartialBufferGetLength : 488 -> 480
```
