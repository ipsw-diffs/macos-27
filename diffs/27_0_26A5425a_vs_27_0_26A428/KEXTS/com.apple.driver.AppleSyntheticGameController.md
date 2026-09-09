## com.apple.driver.AppleSyntheticGameController

> `com.apple.driver.AppleSyntheticGameController`

```diff

   __TEXT.__const: 0x8
   __TEXT.__cstring: 0x420
   __TEXT.__os_log: 0x693
-  __TEXT_EXEC.__text: 0x50a8
+  __TEXT_EXEC.__text: 0x51fc
   __TEXT_EXEC.__auth_stubs: 0x280
   __DATA.__data: 0xd0
   __DATA.__common: 0xe0
Functions:
~ __ZN31AppleGCResourceDeviceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN31AppleGCResourceDeviceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN31AppleGCResourceDeviceUserClientD0Ev : 68 -> 72
~ __ZNK31AppleGCResourceDeviceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN31AppleGCResourceDeviceUserClientC1Ev : 88 -> 92
~ __ZN31AppleGCResourceDeviceUserClient12initWithTaskEP4taskPvj : 100 -> 104
~ __ZN31AppleGCResourceDeviceUserClient4freeEv : 112 -> 116
~ __ZN31AppleGCResourceDeviceUserClient5startEP9IOService : 564 -> 568
~ __ZN31AppleGCResourceDeviceUserClient12didTerminateEP9IOServicejPb : 160 -> 164
~ __ZN31AppleGCResourceDeviceUserClient11clientCloseEv : 64 -> 68
~ __ZN31AppleGCResourceDeviceUserClient40createMemoryDescriptorFromInputArgumentsEP25IOExternalMethodArguments : 420 -> 424
~ __ZN31AppleGCResourceDeviceUserClient14externalMethodEjP31IOExternalMethodArgumentsOpaque : 120 -> 124
~ _GLOBAL__sub_I_AppleGCResourceDeviceUserClient.cpp : 80 -> 84
~ __ZN22AppleGCSyntheticDevice9MetaClassC1Ev : 72 -> 76
~ __ZN22AppleGCSyntheticDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN22AppleGCSyntheticDeviceD0Ev : 68 -> 72
~ __ZNK22AppleGCSyntheticDevice9MetaClass5allocEv : 104 -> 108
~ __ZN22AppleGCSyntheticDeviceC1Ev : 88 -> 92
~ __ZN22AppleGCSyntheticDevice14withPropertiesEP12OSDictionaryy : 232 -> 236
~ __ZN22AppleGCSyntheticDevice4freeEv : 112 -> 116
~ __ZN22AppleGCSyntheticDevice11setPropertyEPK8OSSymbolP8OSObject : 536 -> 540
~ __ZNK22AppleGCSyntheticDevice19newReportDescriptorEPP18IOMemoryDescriptor : 236 -> 240
~ __ZNK22AppleGCSyntheticDevice18newTransportStringEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice21newManufacturerStringEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice16newProductStringEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice17newVendorIDNumberEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice18newProductIDNumberEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice16newVersionNumberEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice21newSerialNumberStringEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice23newVendorIDSourceNumberEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice20newCountryCodeNumberEv : 136 -> 140
~ __ZNK22AppleGCSyntheticDevice19newLocationIDNumberEv : 136 -> 140
~ __ZN22AppleGCSyntheticDevice18matchPropertyTableEP12OSDictionaryPi : 216 -> 220
~ __ZN22AppleGCSyntheticDevice13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 284 -> 288
~ _GLOBAL__sub_I_AppleGCSyntheticDevice.cpp : 80 -> 84
~ __ZN32AppleGCSyntheticDeviceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN32AppleGCSyntheticDeviceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN32AppleGCSyntheticDeviceUserClientD0Ev : 68 -> 72
~ __ZNK32AppleGCSyntheticDeviceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN32AppleGCSyntheticDeviceUserClientC1Ev : 88 -> 92
~ __ZN32AppleGCSyntheticDeviceUserClient12initWithTaskEP4taskPvj : 96 -> 100
~ __ZN32AppleGCSyntheticDeviceUserClient4freeEv : 112 -> 116
~ __ZN32AppleGCSyntheticDeviceUserClient5startEP9IOService : 1008 -> 1012
~ __ZN32AppleGCSyntheticDeviceUserClient11clientCloseEv : 64 -> 68
~ _GLOBAL__sub_I_AppleGCSyntheticDeviceUserClient.cpp : 200 -> 204
~ __ZN15AppleGCResource9MetaClassC1Ev : 72 -> 76
~ __ZN15AppleGCResourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN15AppleGCResourceD0Ev : 68 -> 72
~ __ZNK15AppleGCResource9MetaClass5allocEv : 104 -> 108
~ __ZN15AppleGCResourceC1Ev : 88 -> 92
~ __Z9DeviceLogv : 64 -> 68
~ __ZN15AppleGCResource4freeEv : 260 -> 264
~ __ZN15AppleGCResource5startEP9IOService : 276 -> 280
~ __ZN15AppleGCResource37syntheticDeviceTerminatedNotificationEPvP9IOServiceP10IONotifier : 112 -> 116
~ __ZN15AppleGCResource4stopEP9IOService : 172 -> 176
~ __ZN15AppleGCResource10handleOpenEP9IOServicejPv : 624 -> 628
~ __ZN15AppleGCResource11handleCloseEP9IOServicej : 76 -> 80
~ __ZN15AppleGCResource43createAndStartSyntheticDeviceWithPropertiesEP12OSDictionaryPP22AppleGCSyntheticDevice : 952 -> 956
~ _GLOBAL__sub_I_AppleGCResource.cpp : 80 -> 84
~ __ZN31AppleGCResourceDeviceUserClient5_openEPS_PvP25IOExternalMethodArguments : 188 -> 192
~ __ZN31AppleGCResourceDeviceUserClient6_closeEPS_PvP25IOExternalMethodArguments : 100 -> 104
~ __ZN31AppleGCResourceDeviceUserClient13_createDeviceEPS_PvP25IOExternalMethodArguments : 856 -> 860
~ __ZN31AppleGCResourceDeviceUserClient16_terminateDeviceEPS_PvP25IOExternalMethodArguments : 600 -> 604
~ __ZN31AppleGCResourceDeviceUserClient20_terminateAllDevicesEPS_PvP25IOExternalMethodArguments : 180 -> 184
~ __ZN31AppleGCResourceDeviceUserClient4stopEP9IOService : 204 -> 208
~ __ZN31AppleGCResourceDeviceUserClient19externalMethodGatedEPNS_28ExternalMethodGatedArgumentsE : 112 -> 116
~ __ZN31AppleGCResourceDeviceUserClient15checkCompatibleEP22AppleGCSyntheticDeviceP32AppleGCSyntheticDeviceUserClientPj : 872 -> 876
~ _ZN31AppleGCResourceDeviceUserClient12initWithTaskEP4taskPvj.cold.1 : 44 -> 48
~ _ZN31AppleGCResourceDeviceUserClient5startEP9IOService.cold.1 : 136 -> 140
~ __ZN22AppleGCSyntheticDevice16newAppUserClientEP4taskPvP12OSDictionaryPP12IOUserClient : 420 -> 424
~ __ZN32AppleGCSyntheticDeviceUserClient16_checkCompatibleEPS_PvP25IOExternalMethodArguments : 236 -> 240
~ __ZN32AppleGCSyntheticDeviceUserClient4stopEP9IOService : 192 -> 196
~ __ZN32AppleGCSyntheticDeviceUserClient13setPropertiesEP8OSObject : 208 -> 212
~ __ZN32AppleGCSyntheticDeviceUserClient25_setClientAttributesGatedEP12OSDictionary : 112 -> 116
~ __ZN32AppleGCSyntheticDeviceUserClient14externalMethodEjP31IOExternalMethodArgumentsOpaque : 148 -> 152
~ __ZN32AppleGCSyntheticDeviceUserClient19externalMethodGatedEPNS_28ExternalMethodGatedArgumentsE : 112 -> 116
~ _ZN32AppleGCSyntheticDeviceUserClient12initWithTaskEP4taskPvj.cold.1 : 44 -> 48
~ _ZN32AppleGCSyntheticDeviceUserClient5startEP9IOService.cold.1 : 136 -> 140
~ __ZN15AppleGCResource42syntheticDeviceTerminatedNotificationGatedEPvP9IOServiceP10IONotifier : 488 -> 492
~ __ZN15AppleGCResource29createSyntheticDeviceIteratorEPP10OSIterator : 76 -> 80
~ __ZN15AppleGCResource32getSyntheticDeviceWithIdentifierEP8OSStringPP22AppleGCSyntheticDevice : 600 -> 604
~ __ZN15AppleGCResource52createOrReplaceAndStartSyntheticDeviceWithPropertiesEP12OSDictionaryyPbPP22AppleGCSyntheticDevice : 1272 -> 1276
~ __ZN15AppleGCResource38terminateSyntheticDeviceWithIdentifierEP8OSString : 552 -> 556
~ __ZN15AppleGCResource44terminateAllSyntheticDevicesBeforeGenerationEy : 760 -> 764
~ _ZN15AppleGCResource5startEP9IOService.cold.1 : 156 -> 160
```
