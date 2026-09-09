## SampleAnalysis

> `/System/Library/PrivateFrameworks/SampleAnalysis.framework/Versions/A/SampleAnalysis`

```diff

 439.0.0.0.0
-  __TEXT.__text: 0x11da7c
+  __TEXT.__text: 0x11d9e4
   __TEXT.__objc_methlist: 0x5e34
   __TEXT.__const: 0x328
   __TEXT.__dlopen_cstrs: 0x1ca
Functions:
~ _print_io_histograms : 968 -> 976
~ -[SASampleStore _parseKCDataTaskContainer:timestampOfSample:sampleIndex:sharedCaches:frameIterator:primaryDataIsKPerf:addStaticInfoOnly:kperfState:ktraceDataUnavailable:taskUniquePidsInThisSample:taskPidsInThisSample:importanceDonations:rPidForJetsamCoalitionId:port_label_info_array:vmrls:exclaveInfo:] : 18860 -> 18684
~ -[SAModel(Serialization) addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:] : 1568 -> 1572
~ -[SATask(Serialization) populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:] : 5304 -> 5316
```
