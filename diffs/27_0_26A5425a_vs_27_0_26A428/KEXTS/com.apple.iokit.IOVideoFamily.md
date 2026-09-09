## com.apple.iokit.IOVideoFamily

> `com.apple.iokit.IOVideoFamily`

```diff

 5634.0.0.0.0
   __TEXT.__cstring: 0x230
-  __TEXT_EXEC.__text: 0x45c8
+  __TEXT_EXEC.__text: 0x473c
   __TEXT_EXEC.__auth_stubs: 0x180
   __DATA.__data: 0xc8
   __DATA.__common: 0xb0
Functions:
~ __ZN13IOVideoDevice9MetaClassC1Ev : 72 -> 76
~ __ZN13IOVideoDeviceC2EPK11OSMetaClass : 52 -> 56
~ __ZN13IOVideoDeviceC1EPK11OSMetaClass : 52 -> 56
~ __ZN13IOVideoDeviceD0Ev : 68 -> 72
~ __ZN13IOVideoDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK13IOVideoDevice9MetaClass5allocEv : 104 -> 108
~ __ZN13IOVideoDeviceC1Ev : 88 -> 92
~ __ZN13IOVideoDeviceC2Ev : 88 -> 92
~ __ZN13IOVideoDevice4initEP12OSDictionary : 72 -> 76
~ __ZN13IOVideoDevice4freeEv : 152 -> 156
~ __ZN13IOVideoDevice13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 556 -> 560
~ __ZN13IOVideoDevice11startStreamEj : 160 -> 164
~ __ZN13IOVideoDevice10stopStreamEj : 160 -> 164
~ __ZN13IOVideoDevice13suspendStreamEj : 160 -> 164
~ __ZN13IOVideoDevice9addStreamEP13IOVideoStream : 236 -> 240
~ __ZN13IOVideoDevice12removeStreamEj : 304 -> 308
~ __ZN13IOVideoDevice14releaseStreamsEv : 196 -> 200
~ __ZN13IOVideoDevice24registerNotificationPortEP8ipc_portjj : 184 -> 188
~ __ZN13IOVideoDevice21sendMultiNotificationEjPK25IOVideoDeviceNotification : 288 -> 292
~ _GLOBAL__sub_I_IOVideoDevice.cpp : 80 -> 84
~ __Z28IOVideoDictionary_getBooleanPK12OSDictionaryPKc : 144 -> 148
~ __Z27IOVideoDictionary_getUInt32PK12OSDictionaryPKc : 144 -> 148
~ __Z27IOVideoDictionary_setUInt32P12OSDictionaryPKcj : 184 -> 188
~ __Z27IOVideoDictionary_getUInt64PK12OSDictionaryPKc : 144 -> 148
~ __Z27IOVideoDictionary_setUInt64P12OSDictionaryPKcy : 184 -> 188
~ __ZN24IOVideoControlDictionary6createEjjjjjbjP8OSString : 404 -> 408
~ __ZN24IOVideoControlDictionary20createBooleanControlEjjjjjbbjP8OSString : 160 -> 164
~ __ZN24IOVideoControlDictionary21createSelectorControlEjjjjjjP7OSArraybjP8OSString : 152 -> 156
~ __ZN24IOVideoControlDictionary14getControlByIDEP7OSArrayj : 232 -> 236
~ __ZN24IOVideoControlDictionary13setIsReadOnlyEP12OSDictionaryb : 152 -> 156
~ __ZN24IOVideoControlDictionary8copyNameEPK12OSDictionary : 132 -> 136
~ __ZN24IOVideoControlDictionary22setBooleanControlValueEP12OSDictionaryb : 152 -> 156
~ __ZN24IOVideoControlDictionary30copySelectorControlSelectorMapEPK12OSDictionary : 132 -> 136
~ __ZN24IOVideoControlDictionary36createSelectorControlSelectorMapItemEjPK8OSString : 136 -> 140
~ __ZN24IOVideoControlDictionary36createSelectorControlSelectorMapItemEjPK8OSStringj : 160 -> 164
~ __ZN27IOVideoDeviceUserClientInit9MetaClassC1Ev : 72 -> 76
~ __ZN27IOVideoDeviceUserClientInitC2EPK11OSMetaClass : 52 -> 56
~ __ZN27IOVideoDeviceUserClientInitC1EPK11OSMetaClass : 52 -> 56
~ __ZN27IOVideoDeviceUserClientInitD0Ev : 68 -> 72
~ __ZN27IOVideoDeviceUserClientInit9MetaClassC2Ev : 72 -> 76
~ __ZNK27IOVideoDeviceUserClientInit9MetaClass5allocEv : 104 -> 108
~ __ZN27IOVideoDeviceUserClientInitC1Ev : 88 -> 92
~ __ZN27IOVideoDeviceUserClientInitC2Ev : 88 -> 92
~ __ZN27IOVideoDeviceUserClientInit5startEP9IOService : 288 -> 292
~ __ZN27IOVideoDeviceUserClientInit27MergeDictionaryIntoProviderEP9IOServiceP12OSDictionary : 896 -> 900
~ __ZN27IOVideoDeviceUserClientInit29MergeDictionaryIntoDictionaryEP12OSDictionaryS1_ : 624 -> 628
~ _GLOBAL__sub_I_IOVideoDeviceClientInit.cpp : 80 -> 84
~ __ZN23IOVideoDeviceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN23IOVideoDeviceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IOVideoDeviceUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IOVideoDeviceUserClientD0Ev : 68 -> 72
~ __ZN23IOVideoDeviceUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK23IOVideoDeviceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN23IOVideoDeviceUserClientC1Ev : 88 -> 92
~ __ZN23IOVideoDeviceUserClientC2Ev : 88 -> 92
~ __ZN23IOVideoDeviceUserClient5startEP9IOService : 112 -> 116
~ __ZN23IOVideoDeviceUserClient8sGetModeEPS_PvP25IOExternalMethodArguments : 104 -> 108
~ __ZN23IOVideoDeviceUserClient16sSetControlValueEPS_PvP25IOExternalMethodArguments : 108 -> 112
~ __ZN23IOVideoDeviceUserClient12initWithTaskEP4taskPvj : 72 -> 76
~ __ZN23IOVideoDeviceUserClient12initWithTaskEP4taskPvjP12OSDictionary : 72 -> 76
~ __ZN23IOVideoDeviceUserClient11clientCloseEv : 60 -> 64
~ __ZN23IOVideoDeviceUserClient10clientDiedEv : 60 -> 64
~ __ZN23IOVideoDeviceUserClient4openEj : 88 -> 92
~ __ZN23IOVideoDeviceUserClient5closeEv : 256 -> 260
~ __ZN23IOVideoDeviceUserClient7getModeEjP12IOStreamMode : 136 -> 140
~ __ZN23IOVideoDeviceUserClient7setModeEj12IOStreamMode : 160 -> 164
~ __ZN23IOVideoDeviceUserClient11startStreamEj : 140 -> 144
~ __ZN23IOVideoDeviceUserClient10stopStreamEj : 140 -> 144
~ __ZN23IOVideoDeviceUserClient13suspendStreamEj : 140 -> 144
~ _GLOBAL__sub_I_IOVideoDeviceUserClient.cpp : 80 -> 84
~ __ZN13IOVideoStream9MetaClassC1Ev : 72 -> 76
~ __ZN13IOVideoStreamC2EPK11OSMetaClass : 52 -> 56
~ __ZN13IOVideoStreamC1EPK11OSMetaClass : 52 -> 56
~ __ZN13IOVideoStreamD0Ev : 68 -> 72
~ __ZN13IOVideoStream9MetaClassC2Ev : 72 -> 76
~ __ZNK13IOVideoStream9MetaClass5allocEv : 104 -> 108
~ __ZN13IOVideoStreamC1Ev : 88 -> 92
~ __ZN13IOVideoStreamC2Ev : 88 -> 92
~ __ZN13IOVideoStream11withBuffersEP7OSArray12IOStreamModejP12OSDictionary : 252 -> 256
~ __ZN13IOVideoStream15initWithBuffersEP7OSArray12IOStreamModejP12OSDictionary : 72 -> 76
~ __ZN13IOVideoStream9getDeviceEv : 84 -> 88
~ __ZN13IOVideoStream13setStreamModeE12IOStreamMode : 140 -> 144
~ __ZN13IOVideoStream11startStreamEv : 156 -> 160
~ __ZN13IOVideoStream10stopStreamEv : 156 -> 160
~ __ZN13IOVideoStream13suspendStreamEv : 156 -> 160
~ _GLOBAL__sub_I_IOVideoStream.cpp : 80 -> 84
~ __ZN23IOVideoStreamDictionary6createEjjPK12OSDictionaryP7OSArray : 248 -> 252
~ __ZN23IOVideoStreamDictionary16getCurrentFormatEPK12OSDictionaryR24IOVideoStreamDescription : 120 -> 124
~ __ZN23IOVideoStreamDictionary16setCurrentFormatEP12OSDictionaryRK24IOVideoStreamDescription : 168 -> 172
~ __ZN23IOVideoStreamDictionary27copyCurrentFormatDictionaryEPK12OSDictionary : 132 -> 136
~ __ZN23IOVideoStreamDictionary20copyAvailableFormatsEPK12OSDictionary : 132 -> 136
~ __ZN29IOVideoStreamFormatDictionary6createEjjjj : 160 -> 164
~ __ZN29IOVideoStreamFormatDictionary14getDescriptionEPK12OSDictionaryR24IOVideoStreamDescription : 116 -> 120
```
