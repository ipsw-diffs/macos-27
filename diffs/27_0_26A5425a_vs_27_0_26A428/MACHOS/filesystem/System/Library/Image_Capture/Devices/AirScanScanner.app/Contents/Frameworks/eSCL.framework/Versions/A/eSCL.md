## eSCL

> `/System/Library/Image Capture/Devices/AirScanScanner.app/Contents/Frameworks/eSCL.framework/Versions/A/eSCL`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 66.0.0.0.0
-  __TEXT.__text: 0xe76c
+  __TEXT.__text: 0xe0b8
   __TEXT.__auth_stubs: 0x3f0
   __TEXT.__objc_stubs: 0x2a40
   __TEXT.__objc_methlist: 0x1b58

   __TEXT.__objc_methname: 0x41db
   __TEXT.__objc_methtype: 0xc4b
   __TEXT.__gcc_except_tab: 0xac
-  __TEXT.__unwind_info: 0x468
+  __TEXT.__unwind_info: 0x580
   __DATA_CONST.__const: 0x660
   __DATA_CONST.__cfstring: 0x22c0
   __DATA_CONST.__objc_classlist: 0xc0
Functions:
~ _AirScanShouldSaveBandData : 68 -> 56
~ __get_queue : 68 -> 56
~ _AirScanLogConditionalVA : 108 -> 96
~ ____get_queue_block_invoke : 68 -> 56
~ _string_for_integer : 92 -> 80
~ _file_extension_for_UTI : 96 -> 84
~ _eSCLBonjourServiceTypes : 132 -> 120
~ +[eSCL validScannerIntents] : 68 -> 56
~ ___27+[eSCL validScannerIntents]_block_invoke : 76 -> 64
~ +[eSCL validColorModes] : 68 -> 56
~ ___23+[eSCL validColorModes]_block_invoke : 76 -> 64
~ +[eSCL validColorModesForTXTColorSpace:] : 208 -> 196
~ +[eSCL validEdgeDetectionEdges] : 68 -> 56
~ ___31+[eSCL validEdgeDetectionEdges]_block_invoke : 76 -> 64
~ +[eSCL validImageCorrectionFeatures] : 68 -> 56
~ ___36+[eSCL validImageCorrectionFeatures]_block_invoke : 76 -> 64
~ +[eSCL namespaceURIForESCLKey:] : 148 -> 136
~ -[NSXMLElement(eSCL) childForESCLKey:] : 204 -> 192
~ -[NSXMLElement(eSCL) elementsForESCLKey:] : 168 -> 156
~ -[NSXMLElement(eSCL) attributeForESCLKey:] : 168 -> 156
~ -[eSCLURLSessionTaskCallbacks didReceiveData:] : 232 -> 220
~ -[eSCLURLSessionTaskCallbacks didWriteNumBytes:totalBytesWritten:totalBytesExpectedToWrite:] : 160 -> 148
~ -[eSCLURLSessionTaskCallbacks didFinishDownloadingToURL:] : 136 -> 124
~ -[eSCLURLSessionTaskCallbacks didCompleteWithResponse:error:] : 164 -> 152
~ -[eSCLURLSessionTaskCallbacks .cxx_destruct] : 104 -> 92
~ +[NSXMLElement(ExtraTypes) elementWithName:unsignedInteger:] : 160 -> 148
~ -[NSXMLElement(ExtraTypes) childWithName:namespace:] : 248 -> 236
~ +[ScannerCapabilities scannerCapabilitiesWithXMLData:error:] : 216 -> 204
~ ___43-[ScannerCapabilities initWithXMLDocument:]_block_invoke_2 : 120 -> 108
~ -[ScannerCapabilities description] : 1228 -> 1216
~ -[ScannerCapabilities settingProfileForName:] : 308 -> 296
~ -[ScannerCapabilities .cxx_destruct] : 224 -> 212
~ +[ScannerStatus scannerStatusWithXMLData:error:] : 216 -> 204
~ ___37-[ScannerStatus initWithXMLDocument:]_block_invoke_2 : 96 -> 84
~ -[ScannerStatus description] : 592 -> 580
~ -[ScannerStatus setState:] : 116 -> 104
~ -[ScannerStatus jobInfoForURI:] : 356 -> 344
~ ___31-[ScannerStatus jobInfoForURI:]_block_invoke : 184 -> 172
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ -[ScannerStatus jobInfoForUUID:] : 336 -> 324
~ ___32-[ScannerStatus jobInfoForUUID:]_block_invoke : 164 -> 152
~ -[ScannerStatus acceptingJobs] : 88 -> 76
~ -[ScannerStatus .cxx_destruct] : 104 -> 92
~ -[JobInfo description] : 696 -> 684
~ -[JobInfo setJobState:] : 140 -> 128
~ -[JobInfo pageReady] : 76 -> 64
~ -[JobInfo jobDone] : 88 -> 76
~ -[JobInfo .cxx_destruct] : 92 -> 80
~ ___26-[ADFOptions initWithXML:]_block_invoke : 168 -> 156
~ _DNSSDResolveCallbackUsingBlock : 248 -> 236
~ +[NSDictionary(DNSSDUtilities) dictionaryWithTXTRecordData:length:] : 444 -> 432
~ -[DNSSDResolveCallbackData description] : 808 -> 796
~ -[DNSSDResolveCallbackData .cxx_destruct] : 80 -> 68
~ +[SettingProfile settingProfileWithXML:] : 376 -> 364
~ ___40+[SettingProfile settingProfileWithXML:]_block_invoke : 64 -> 52
~ __childrenOfElementMatchingKey : 468 -> 456
~ -[SettingProfile description] : 320 -> 308
~ -[SettingProfile .cxx_destruct] : 140 -> 128
~ -[SupportedFeatureList objectInSettingsAtIndex:] : 112 -> 100
~ -[SupportedFeatureList .cxx_destruct] : 68 -> 56
~ -[RangeAndStep nearestInRange:] : 196 -> 172
~ -[RangeAndStep arrayRepresentation] : 196 -> 184
~ +[Resolution resolutionWithX:andY:] : 68 -> 56
~ +[Resolution resolutionWithResolution:] : 108 -> 96
~ -[Resolution initWithXML:] : 168 -> 156
~ -[Resolution copyWithZone:] : 104 -> 92
~ -[RangeSupportedResolutions description] : 220 -> 208
~ -[RangeSupportedResolutions maxResolution] : 132 -> 120
~ -[RangeSupportedResolutions nearestResolution:] : 184 -> 172
~ -[RangeSupportedResolutions .cxx_destruct] : 68 -> 56
~ ___44-[DiscreteSupportedResolutions initWithXML:]_block_invoke : 96 -> 84
~ -[DiscreteSupportedResolutions description] : 140 -> 128
~ -[DiscreteSupportedResolutions maxResolution] : 112 -> 100
~ -[DiscreteSupportedResolutions nearestResolution:] : 392 -> 380
~ ___50-[DiscreteSupportedResolutions nearestResolution:]_block_invoke : 204 -> 192
~ ___copy_helper_block_e8_32s40r48r : 88 -> 76
~ ___destroy_helper_block_e8_32s40r48r : 76 -> 64
~ -[InputSourceCapabilities description] : 1172 -> 1160
~ -[InputSourceCapabilities supportsGrayscale] : 92 -> 80
~ -[InputSourceCapabilities supportsColor] : 92 -> 80
~ -[InputSourceCapabilities supportedDocumentFormats] : 348 -> 336
~ -[InputSourceCapabilities supportedUTIs] : 88 -> 76
~ ___40-[InputSourceCapabilities supportedUTIs]_block_invoke : 56 -> 44
~ -[InputSourceCapabilities preferredOutputUTI] : 128 -> 116
~ -[InputSourceCapabilities maximumResolution] : 92 -> 80
~ -[InputSourceCapabilities .cxx_destruct] : 80 -> 68
~ -[InputSourceCapabilities(TXTRecordHelpers) TXTRecordColorSpaces] : 180 -> 168
~ -[ScanRegion initWithXML:] : 264 -> 252
~ -[ScanRegion XMLRepresentation] : 412 -> 400
~ +[DefaultESCLAuthenticationDelegate sharedInstance] : 68 -> 56
~ ___51+[DefaultESCLAuthenticationDelegate sharedInstance]_block_invoke : 64 -> 52
~ -[DefaultESCLAuthenticationDelegate scanner:didReceiveAuthenticationChallenge:forRequest:completionHandler:] : 312 -> 300
~ ___32-[eSCLScanSettings initWithXML:]_block_invoke : 96 -> 84
~ -[eSCLScanSettings description] : 676 -> 664
~ -[eSCLScanSettings XMLData] : 2612 -> 2600
~ -[eSCLScanSettings .cxx_destruct] : 200 -> 188
~ +[NSMutableURLRequest(Utilities) requestWithURL:verb:headers:] : 160 -> 148
~ -[eSCLScanner session] : 244 -> 232
~ -[eSCLScanner _URLOnScannerWithESCLRootRelativeResource:] : 140 -> 128
~ -[eSCLScanner _doRequestWithURL:verb:completion:] : 192 -> 180
~ ___61-[eSCLScanner fetchScannerCapabilitiesUsingCache:completion:]_block_invoke : 312 -> 300
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ ___52-[eSCLScanner createScanJobWithSettings:completion:]_block_invoke_2 : 300 -> 288
~ -[eSCLScanner _doNextDocumentRequestWithJobURL:callbacks:useDownloadTask:] : 348 -> 336
~ ___82-[eSCLScanner fetchNextDocumentToMemoryForJobWithURL:progressCallback:completion:]_block_invoke : 200 -> 188
~ ___copy_helper_block_e8_32b40w : 76 -> 64
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ -[eSCLScanner URLSession:task:didReceiveChallenge:completionHandler:] : 312 -> 300
~ -[eSCLScanner URLSession:task:willPerformHTTPRedirection:newRequest:completionHandler:] : 836 -> 824
~ -[eSCLScanner URLSession:task:didCompleteWithError:] : 228 -> 216
~ -[eSCLScanner URLSession:dataTask:didReceiveData:] : 160 -> 148
~ -[eSCLScanner URLSession:dataTask:willCacheResponse:completionHandler:] : 96 -> 84
~ -[eSCLScanner URLSession:downloadTask:didFinishDownloadingToURL:] : 160 -> 148
~ -[eSCLScanner URLSession:downloadTask:didWriteData:totalBytesWritten:totalBytesExpectedToWrite:] : 164 -> 152
~ -[eSCLScanner authenticationDelegate] : 44 -> 32
~ -[eSCLScanner .cxx_destruct] : 112 -> 100
~ __extractHostZoneID : 172 -> 160
~ +[ScanBufferInfo scanBufferInfoWithXMLData:error:] : 216 -> 204
~ -[Justification description] : 152 -> 140
~ -[Justification .cxx_destruct] : 68 -> 56
~ -[NSArray(Extensions) airscan_map:] : 412 -> 400
~ -[eSCLSimpleScannerInfoSource _deviceURLComponents] : 184 -> 172
~ -[eSCLSimpleScannerInfoSource scannerURL] : 80 -> 68
~ -[eSCLSimpleScannerInfoSource eSCLRootURLOnScanner] : 124 -> 112
~ -[eSCLSimpleScannerInfoSource URLOnScannerForResourceAtPath:] : 120 -> 108
~ -[eSCLSimpleScannerInfoSource URLOnScannerForResourceAtURL:] : 424 -> 412
~ -[eSCLSimpleScannerInfoSource iconURLOnScanner] : 168 -> 156
~ -[eSCLSimpleScannerInfoSource .cxx_destruct] : 164 -> 152
~ +[NSDictionary(Extensions) dictionaryOfNSNullForKeys:] : 388 -> 376
~ -[NSDictionary(Extensions) airscan_map:] : 272 -> 260
~ ___40-[NSDictionary(Extensions) airscan_map:]_block_invoke : 172 -> 160
~ ___49-[NSDictionary(Extensions) leftKeySetDifference:]_block_invoke : 92 -> 80
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___41-[NSDictionary(Extensions) airscan_diff:]_block_invoke : 180 -> 168
~ -[NSDictionary(Extensions) sortedDescriptionUsingBlock:] : 536 -> 524
~ -[NSMutableDictionary(Extensions) copyValueForKey:fromDict:] : 124 -> 112
~ -[NSMutableDictionary(KeychainExtensions) setUsesModernKeychain:] : 96 -> 84
```
