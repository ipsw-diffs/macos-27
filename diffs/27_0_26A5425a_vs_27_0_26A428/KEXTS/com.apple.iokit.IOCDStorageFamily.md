## com.apple.iokit.IOCDStorageFamily

> `com.apple.iokit.IOCDStorageFamily`

```diff

 62.0.0.0.0
   __TEXT.__cstring: 0x26d
   __TEXT.__const: 0x90
-  __TEXT_EXEC.__text: 0x606c
+  __TEXT_EXEC.__text: 0x61d0
   __TEXT_EXEC.__auth_stubs: 0x2f0
   __DATA.__data: 0xc8
   __DATA.__common: 0xd8
Functions:
~ __ZN22IOCDBlockStorageDevice9MetaClassC1Ev : 72 -> 76
~ __ZN22IOCDBlockStorageDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOCDBlockStorageDevice9MetaClassC2Ev : 72 -> 76
~ __ZN22IOCDBlockStorageDevice4initEP12OSDictionary : 128 -> 132
~ _GLOBAL__sub_I_IOCDBlockStorageDevice.cpp : 80 -> 84
~ __ZN22IOCDBlockStorageDriver9MetaClassC1Ev : 72 -> 76
~ __ZN22IOCDBlockStorageDriverC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOCDBlockStorageDriverC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOCDBlockStorageDriverD0Ev : 68 -> 72
~ __ZN22IOCDBlockStorageDriver9MetaClassC2Ev : 72 -> 76
~ __ZNK22IOCDBlockStorageDriver9MetaClass5allocEv : 104 -> 108
~ __ZN22IOCDBlockStorageDriverC1Ev : 88 -> 92
~ __ZN22IOCDBlockStorageDriverC2Ev : 88 -> 92
~ __ZN22IOCDBlockStorageDriver14acceptNewMediaEv : 1036 -> 1040
~ __ZN22IOCDBlockStorageDriver14reportDiscInfoEP10CDDiscInfo : 304 -> 308
~ __ZN22IOCDBlockStorageDriver15reportTrackInfoEtP11CDTrackInfo : 324 -> 328
~ __ZN22IOCDBlockStorageDriver12cacheTocInfoEv : 680 -> 684
~ __ZN22IOCDBlockStorageDriver17decommissionMediaEb : 104 -> 108
~ __ZN22IOCDBlockStorageDriver14executeRequestEyP18IOMemoryDescriptorP19IOStorageAttributesP19IOStorageCompletionPN20IOBlockStorageDriver7ContextE : 612 -> 616
~ __ZN22IOCDBlockStorageDriver4freeEv : 96 -> 100
~ __ZN22IOCDBlockStorageDriver4initEP12OSDictionary : 100 -> 104
~ __ZN22IOCDBlockStorageDriver29instantiateDesiredMediaObjectEv : 44 -> 48
~ __ZN22IOCDBlockStorageDriver22instantiateMediaObjectEyyjPc : 680 -> 684
~ __ZN22IOCDBlockStorageDriver14prepareRequestEyP18IOMemoryDescriptor12CDSectorArea12CDSectorTypeP19IOStorageAttributesP19IOStorageCompletion : 624 -> 628
~ __ZN22IOCDBlockStorageDriver8readISRCEhPc : 140 -> 144
~ __ZN22IOCDBlockStorageDriver7readMCNEPc : 132 -> 136
~ __ZN22IOCDBlockStorageDriver21recordMediaParametersEv : 152 -> 156
~ __ZN22IOCDBlockStorageDriver8getSpeedEPt : 132 -> 136
~ __ZN22IOCDBlockStorageDriver8setSpeedEt : 132 -> 136
~ __ZN22IOCDBlockStorageDriver7readTOCEP18IOMemoryDescriptorhhhPt : 180 -> 184
~ __ZN22IOCDBlockStorageDriver12readDiscInfoEP18IOMemoryDescriptorPt : 140 -> 144
~ __ZN22IOCDBlockStorageDriver13readTrackInfoEP18IOMemoryDescriptorjhPt : 164 -> 168
~ _GLOBAL__sub_I_IOCDBlockStorageDriver.cpp : 80 -> 84
~ __ZN9IOCDMedia9MetaClassC1Ev : 72 -> 76
~ __ZN9IOCDMediaC2EPK11OSMetaClass : 52 -> 56
~ __ZN9IOCDMediaC1EPK11OSMetaClass : 52 -> 56
~ __ZN9IOCDMediaD0Ev : 68 -> 72
~ __ZN9IOCDMedia9MetaClassC2Ev : 72 -> 76
~ __ZNK9IOCDMedia9MetaClass5allocEv : 104 -> 108
~ __ZN9IOCDMediaC1Ev : 88 -> 92
~ __ZN9IOCDMediaC2Ev : 88 -> 92
~ __ZN9IOCDMedia18matchPropertyTableEP12OSDictionaryPi : 216 -> 220
~ __ZN9IOCDMedia4readEP9IOServiceyP18IOMemoryDescriptorP19IOStorageAttributesP19IOStorageCompletion : 452 -> 456
~ __ZN9IOCDMedia5writeEP9IOServiceyP18IOMemoryDescriptorP19IOStorageAttributesP19IOStorageCompletion : 500 -> 504
~ __ZN9IOCDMedia6readCDEP9IOServiceyP18IOMemoryDescriptor12CDSectorArea12CDSectorTypeP19IOStorageAttributesPy : 104 -> 108
~ __ZL17storageCompletionPvS_iy : 100 -> 104
~ __ZN15IOStorageSyncer4waitEv : 84 -> 88
~ __ZN9IOCDMedia6readCDEP9IOServiceyP18IOMemoryDescriptor12CDSectorArea12CDSectorTypeP19IOStorageAttributesP19IOStorageCompletion : 364 -> 368
~ __ZN9IOCDMedia8readISRCEhPc : 188 -> 192
~ __ZN9IOCDMedia7readMCNEPc : 168 -> 172
~ __ZN9IOCDMedia6getTOCEv : 156 -> 160
~ __ZN9IOCDMedia8getSpeedEPt : 168 -> 172
~ __ZN9IOCDMedia8setSpeedEt : 168 -> 172
~ __ZN9IOCDMedia7readTOCEP18IOMemoryDescriptorhhhPt : 256 -> 260
~ __ZN9IOCDMedia12readDiscInfoEP18IOMemoryDescriptorPt : 220 -> 224
~ __ZN9IOCDMedia13readTrackInfoEP18IOMemoryDescriptorjhPt : 248 -> 252
~ __ZN9IOCDMedia7writeCDEP9IOServiceyP18IOMemoryDescriptor12CDSectorArea12CDSectorTypeP19IOStorageAttributesP19IOStorageCompletion : 416 -> 420
~ __ZN9IOCDMedia7writeCDEP9IOServiceyP18IOMemoryDescriptor12CDSectorArea12CDSectorTypeP19IOStorageAttributesPy : 104 -> 108
~ _GLOBAL__sub_I_IOCDMedia.cpp : 92 -> 96
~ __ZN18IOCDMediaBSDClient9MetaClassC1Ev : 72 -> 76
~ __ZN18IOCDMediaBSDClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN18IOCDMediaBSDClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN18IOCDMediaBSDClientD0Ev : 68 -> 72
~ __ZN18IOCDMediaBSDClient9MetaClassC2Ev : 72 -> 76
~ __ZNK18IOCDMediaBSDClient9MetaClass5allocEv : 104 -> 108
~ __ZN18IOCDMediaBSDClientC1Ev : 88 -> 92
~ __ZN18IOCDMediaBSDClientC2Ev : 88 -> 92
~ __ZN18IOCDMediaBSDClient5ioctlEimPciP4proc : 2960 -> 2964
~ __ZL20DKIOC_PREPARE_BUFFERyjjP4proc : 204 -> 208
~ _GLOBAL__sub_I_IOCDMediaBSDClient.cpp : 80 -> 84
~ __ZN19IOCDPartitionScheme9MetaClassC1Ev : 72 -> 76
~ __ZN19IOCDPartitionSchemeC2EPK11OSMetaClass : 52 -> 56
~ __ZN19IOCDPartitionSchemeC1EPK11OSMetaClass : 52 -> 56
~ __ZN19IOCDPartitionSchemeD0Ev : 68 -> 72
~ __ZN19IOCDPartitionScheme9MetaClassC2Ev : 72 -> 76
~ __ZNK19IOCDPartitionScheme9MetaClass5allocEv : 104 -> 108
~ __ZN19IOCDPartitionSchemeC1Ev : 88 -> 92
~ __ZN19IOCDPartitionSchemeC2Ev : 88 -> 92
~ __ZN19IOCDPartitionScheme4initEP12OSDictionary : 68 -> 72
~ __ZN19IOCDPartitionScheme4freeEv : 108 -> 112
~ __ZN19IOCDPartitionScheme5probeEP9IOServicePi : 128 -> 132
~ __ZN19IOCDPartitionScheme5startEP9IOService : 300 -> 304
~ __ZN19IOCDPartitionScheme4scanEPi : 3480 -> 3484
~ __ZN19IOCDPartitionScheme18isPartitionInvalidEP15CDTOCDescriptoryj12CDSectorTypeP5CDTOC : 256 -> 260
~ __ZN19IOCDPartitionScheme22instantiateMediaObjectEP15CDTOCDescriptoryj12CDSectorTypeP5CDTOC : 1160 -> 1164
~ __ZN19IOCDPartitionScheme29instantiateDesiredMediaObjectEP15CDTOCDescriptoryj12CDSectorTypeP5CDTOC : 44 -> 48
~ __ZN19IOCDPartitionScheme4readEP9IOServiceyP18IOMemoryDescriptorP19IOStorageAttributesP19IOStorageCompletion : 188 -> 192
~ __ZN19IOCDPartitionScheme5writeEP9IOServiceyP18IOMemoryDescriptorP19IOStorageAttributesP19IOStorageCompletion : 188 -> 192
~ _GLOBAL__sub_I_IOCDPartitionScheme.cpp : 80 -> 84
```
