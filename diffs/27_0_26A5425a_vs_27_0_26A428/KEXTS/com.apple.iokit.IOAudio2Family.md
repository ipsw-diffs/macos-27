## com.apple.iokit.IOAudio2Family

> `com.apple.iokit.IOAudio2Family`

```diff

 550.1.0.0.0
   __TEXT.__cstring: 0x3af
   __TEXT.__const: 0x18
-  __TEXT_EXEC.__text: 0x65b8
+  __TEXT_EXEC.__text: 0x674c
   __TEXT_EXEC.__auth_stubs: 0x220
   __DATA.__data: 0xc8
   __DATA.__common: 0x60
Functions:
~ __Z29IOAudio2Dictionary_getBooleanP12OSDictionaryPKc : 228 -> 232
~ __Z29IOAudio2Dictionary_setBooleanP12OSDictionaryPKcb : 324 -> 328
~ __Z28IOAudio2Dictionary_getUInt32P12OSDictionaryPKc : 144 -> 148
~ __Z28IOAudio2Dictionary_setUInt32P12OSDictionaryPKcj : 324 -> 328
~ __Z28IOAudio2Dictionary_getUInt64P12OSDictionaryPKc : 144 -> 148
~ __Z28IOAudio2Dictionary_setUInt64P12OSDictionaryPKcy : 324 -> 328
~ __ZN25IOAudio2ControlDictionary6createEjjjjjbjP8OSString : 308 -> 312
~ __ZN25IOAudio2ControlDictionary19createSliderControlEjjjjjjjjbjP8OSString : 136 -> 140
~ __ZN25IOAudio2ControlDictionary29createLevelControlSimpleRangeEjjjjjjjxjxjbjP8OSString : 336 -> 340
~ __ZN25IOAudio2ControlDictionary30createLevelControlRangeMapItemEjxjx : 160 -> 164
~ __ZN25IOAudio2ControlDictionary18createLevelControlEjjjjjjP7OSArrayjbjP8OSString : 172 -> 176
~ __ZN25IOAudio2ControlDictionary20createBooleanControlEjjjjjbbjP8OSString : 84 -> 88
~ __ZN25IOAudio2ControlDictionary21createSelectorControlEjjjjjjP7OSArraybjP8OSString : 152 -> 156
~ __ZN25IOAudio2ControlDictionary26createMultiSelectorControlEjjjjjP7OSArrayS1_bjP8OSString : 208 -> 212
~ __ZN25IOAudio2ControlDictionary22createStereoPanControlEjjjjjjjjjjjbjP8OSString : 220 -> 224
~ __ZN25IOAudio2ControlDictionary18createBlockControlEjjjjjjP12OSDictionarybjP8OSString : 152 -> 156
~ __ZN25IOAudio2ControlDictionary14getControlByIDEP7OSArrayj : 232 -> 236
~ __ZN25IOAudio2ControlDictionary8copyNameEP12OSDictionary : 132 -> 136
~ __ZN25IOAudio2ControlDictionary21getSliderControlRangeEP12OSDictionaryRjS2_ : 84 -> 88
~ __ZN25IOAudio2ControlDictionary21setSliderControlRangeEP12OSDictionaryjj : 84 -> 88
~ __ZN25IOAudio2ControlDictionary33setSliderControlPropertySelectorsEP12OSDictionaryjj : 380 -> 384
~ __ZN25IOAudio2ControlDictionary26getLevelControlSimpleRangeEP12OSDictionaryRjRxS2_S3_ : 172 -> 176
~ __ZN25IOAudio2ControlDictionary24copyLevelControlRangeMapEP12OSDictionary : 132 -> 136
~ __ZN25IOAudio2ControlDictionary27getLevelControlRangeByIndexEP7OSArrayjRjRxS2_S3_ : 196 -> 200
~ __ZN25IOAudio2ControlDictionary26setLevelControlSimpleRangeEP12OSDictionaryjxjx : 300 -> 304
~ __ZN25IOAudio2ControlDictionary32setLevelControlPropertySelectorsEP12OSDictionaryjjjjjj : 804 -> 808
~ __ZN25IOAudio2ControlDictionary34setBooleanControlPropertySelectorsEP12OSDictionaryj : 280 -> 284
~ __ZN25IOAudio2ControlDictionary33copyMultiSelectorControlValueListEP12OSDictionary : 132 -> 136
~ __ZN25IOAudio2ControlDictionary30copySelectorControlSelectorMapEP12OSDictionary : 132 -> 136
~ __ZN25IOAudio2ControlDictionary35setSelectorControlPropertySelectorsEP12OSDictionaryjjj : 492 -> 496
~ __ZN25IOAudio2ControlDictionary36createSelectorControlSelectorMapItemEjP8OSString : 136 -> 140
~ __ZN25IOAudio2ControlDictionary36createSelectorControlSelectorMapItemEjP8OSStringj : 160 -> 164
~ __ZN25IOAudio2ControlDictionary36setStereoPanControlPropertySelectorsEP12OSDictionaryjj : 380 -> 384
~ __ZN25IOAudio2ControlDictionary26copyBlockControlDescriptorEP12OSDictionary : 132 -> 136
~ __ZN25IOAudio2ControlDictionary32setBlockControlPropertySelectorsEP12OSDictionaryjj : 380 -> 384
~ __ZN14IOAudio2Device9MetaClassC1Ev : 72 -> 76
~ __ZN14IOAudio2DeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN14IOAudio2DeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN14IOAudio2DeviceD0Ev : 68 -> 72
~ __ZN14IOAudio2Device9MetaClassC2Ev : 72 -> 76
~ __ZNK14IOAudio2Device9MetaClass5allocEv : 104 -> 108
~ __ZN14IOAudio2DeviceC1Ev : 88 -> 92
~ __ZN14IOAudio2DeviceC2Ev : 88 -> 92
~ __ZN14IOAudio2Device4freeEv : 152 -> 156
~ __ZN14IOAudio2Device18destroyIOReportersEv : 72 -> 76
~ __ZN14IOAudio2Device5startEP9IOService : 284 -> 288
~ __ZN14IOAudio2Device17createIOReportersEv : 476 -> 480
~ __ZN14IOAudio2Device4stopEP9IOService : 120 -> 124
~ __ZN14IOAudio2Device13setPropertiesEP8OSObject : 248 -> 252
~ __ZN14IOAudio2Device13startIOEngineEv : 308 -> 312
~ __ZN14IOAudio2Device12stopIOEngineEv : 304 -> 308
~ __ZN14IOAudio2Device22startIOEngineWithFlagsEjPy : 96 -> 100
~ __ZN14IOAudio2Device21stopIOEngineWithFlagsEjPy : 96 -> 100
~ __ZN14IOAudio2Device13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 688 -> 692
~ __ZN14IOAudio2Device15clientWasClosedEP24IOAudio2DeviceUserClient : 188 -> 192
~ __ZN14IOAudio2Device21sendMultiNotificationEjPK20IOAudio2Notification : 244 -> 248
~ __ZN14IOAudio2Device19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 384 -> 388
~ __ZN14IOAudio2Device19requestConfigChangeEjjyy : 288 -> 292
~ __ZN14IOAudio2Device18handleConfigChangeEP20IOAudio2Notificationy : 232 -> 236
~ __ZN14IOAudio2Device12updateReportEP19IOReportChannelListjPvS2_ : 324 -> 328
~ _GLOBAL__sub_I_IOAudio2Device.cpp : 80 -> 84
~ __ZN24IOAudio2DeviceUserClient4doIOEbjjjjj : 216 -> 220
~ __ZN24IOAudio2DeviceUserClient12doIsolatedIOEjyjjyy : 216 -> 220
~ __ZN24IOAudio2DeviceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN24IOAudio2DeviceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN24IOAudio2DeviceUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN24IOAudio2DeviceUserClientD0Ev : 68 -> 72
~ __ZN24IOAudio2DeviceUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK24IOAudio2DeviceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN24IOAudio2DeviceUserClientC1Ev : 88 -> 92
~ __ZN24IOAudio2DeviceUserClientC2Ev : 88 -> 92
~ __ZN24IOAudio2DeviceUserClient12initWithTaskEP4taskPvjP12OSDictionary : 124 -> 128
~ __ZN24IOAudio2DeviceUserClient4freeEv : 112 -> 116
~ __ZN24IOAudio2DeviceUserClient5startEP9IOService : 400 -> 404
~ __ZN24IOAudio2DeviceUserClient4stopEP9IOService : 224 -> 228
~ __ZN24IOAudio2DeviceUserClient12didTerminateEP9IOServicejPb : 112 -> 116
~ __ZN24IOAudio2DeviceUserClient13clientCleanupEv : 152 -> 156
~ __ZN24IOAudio2DeviceUserClient11clientCloseEv : 172 -> 176
~ __ZN24IOAudio2DeviceUserClient12_clientCloseEP8OSObjectPvS2_S2_S2_ : 132 -> 136
~ __ZN24IOAudio2DeviceUserClient24registerNotificationPortEP8ipc_portjj : 164 -> 168
~ __ZN24IOAudio2DeviceUserClient25_registerNotificationPortEP8OSObjectPvS2_S2_S2_ : 204 -> 208
~ __ZN24IOAudio2DeviceUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 212 -> 216
~ __ZN24IOAudio2DeviceUserClient15_externalMethodEP8OSObjectPvS2_S2_S2_ : 168 -> 172
~ __ZN24IOAudio2DeviceUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 180 -> 184
~ __ZN24IOAudio2DeviceUserClient20_clientMemoryForTypeEP8OSObjectPvS2_S2_S2_ : 204 -> 208
~ _GLOBAL__sub_I_IOAudio2DeviceUserClient.cpp : 80 -> 84
~ __ZN24IOAudio2StreamDictionary6createEjjP12OSDictionaryP7OSArray : 248 -> 252
~ __ZN24IOAudio2StreamDictionary6createEjjjP12OSDictionaryP7OSArray : 272 -> 276
~ __ZN24IOAudio2StreamDictionary6createEjjjbP12OSDictionaryP7OSArray : 76 -> 80
~ __ZN24IOAudio2StreamDictionary16getCurrentFormatEP12OSDictionaryR30IOAudio2StreamBasicDescription : 120 -> 124
~ __ZN24IOAudio2StreamDictionary16setCurrentFormatEP12OSDictionaryRK30IOAudio2StreamBasicDescription : 168 -> 172
~ __ZN24IOAudio2StreamDictionary27copyCurrentFormatDictionaryEP12OSDictionary : 132 -> 136
~ __ZN24IOAudio2StreamDictionary20copyAvailableFormatsEP12OSDictionary : 132 -> 136
~ __ZN30IOAudio2StreamFormatDictionary6createExjjjjjjj : 272 -> 276
~ __ZN30IOAudio2StreamFormatDictionary12createRangedExxjjjjjjj : 296 -> 300
~ __ZN30IOAudio2StreamFormatDictionary27createRangedWithDescriptionERK31IOAudio2StreamRangedDescription : 60 -> 64
~ __ZN30IOAudio2StreamFormatDictionary31createRangedWithSimpleLinearPCMExxjjjb : 100 -> 104
~ __ZN30IOAudio2StreamFormatDictionary30createRangedWithSimple60958AC3Exxb : 80 -> 84
~ __ZN30IOAudio2StreamFormatDictionary14getDescriptionEP12OSDictionaryR30IOAudio2StreamBasicDescription : 192 -> 196
~ __ZN30IOAudio2StreamFormatDictionary20getRangedDescriptionEP12OSDictionaryR31IOAudio2StreamRangedDescription : 228 -> 232
~ __ZN35IOAudio2DataExchangeBlockDictionary6createEj : 72 -> 76
```
