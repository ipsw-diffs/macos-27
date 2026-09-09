## com.apple.iokit.IOUserEthernet

> `com.apple.iokit.IOUserEthernet`

```diff

 79.0.0.0.0
   __TEXT.__const: 0x18
   __TEXT.__cstring: 0xc71
-  __TEXT_EXEC.__text: 0x5890
+  __TEXT_EXEC.__text: 0x5a00
   __TEXT_EXEC.__auth_stubs: 0x4e0
   __DATA.__data: 0xc8
   __DATA.__common: 0xb8
Functions:
~ __ZN32IOUserEthernetResourceUserClient9MetaClassC1Ev : 72 -> 76
~ __ZN32IOUserEthernetResourceUserClientC2EPK11OSMetaClass : 52 -> 56
~ __ZN32IOUserEthernetResourceUserClientC1EPK11OSMetaClass : 52 -> 56
~ __ZN32IOUserEthernetResourceUserClientD0Ev : 68 -> 72
~ __ZN32IOUserEthernetResourceUserClient9MetaClassC2Ev : 72 -> 76
~ __ZNK32IOUserEthernetResourceUserClient9MetaClass5allocEv : 104 -> 108
~ __ZN32IOUserEthernetResourceUserClientC1Ev : 88 -> 92
~ __ZN32IOUserEthernetResourceUserClientC2Ev : 88 -> 92
~ __ZN32IOUserEthernetResourceUserClient20_terminateControllerEPS_PvP25IOExternalMethodArguments : 28 -> 32
~ __ZN32IOUserEthernetResourceUserClient19_setIfpPowerSavingsEPS_PvP25IOExternalMethodArguments : 80 -> 84
~ __ZN32IOUserEthernetResourceUserClient12initWithTaskEP4taskPvj : 284 -> 288
~ __ZN32IOUserEthernetResourceUserClient4freeEv : 164 -> 168
~ __ZN32IOUserEthernetResourceUserClient5startEP9IOService : 272 -> 276
~ __ZN32IOUserEthernetResourceUserClient4stopEP9IOService : 184 -> 188
~ __ZN32IOUserEthernetResourceUserClient19terminateControllerEv : 208 -> 212
~ __ZN32IOUserEthernetResourceUserClient29registerNotificationPortGatedEP8ipc_port : 56 -> 60
~ __ZN32IOUserEthernetResourceUserClient24registerNotificationPortEP8ipc_portjj : 204 -> 208
~ __ZN32IOUserEthernetResourceUserClient40createMemoryDescriptorFromInputArgumentsEP25IOExternalMethodArguments : 112 -> 116
~ __ZN32IOUserEthernetResourceUserClient11clientCloseEv : 172 -> 176
~ __ZN32IOUserEthernetResourceUserClient10clientDiedEv : 176 -> 180
~ __ZN32IOUserEthernetResourceUserClient21createControllerGatedEP25IOExternalMethodArguments : 908 -> 912
~ __ZN32IOUserEthernetResourceUserClient16createControllerEP25IOExternalMethodArguments : 204 -> 208
~ __ZN32IOUserEthernetResourceUserClient18setIfpPowerSavingsEP25IOExternalMethodArguments : 80 -> 84
~ _GLOBAL__sub_I_IOUserEthernetResourceUserClient.cpp : 80 -> 84
~ __ZN22IOUserEthernetResource9MetaClassC1Ev : 72 -> 76
~ __ZN22IOUserEthernetResourceC2EPK11OSMetaClass : 52 -> 56
~ __ZN22IOUserEthernetResourceC1EPK11OSMetaClass : 52 -> 56
~ __ZN22IOUserEthernetResourceD0Ev : 68 -> 72
~ __ZN22IOUserEthernetResource9MetaClassC2Ev : 72 -> 76
~ __ZNK22IOUserEthernetResource9MetaClass5allocEv : 104 -> 108
~ __ZN22IOUserEthernetResourceC1Ev : 88 -> 92
~ __ZN22IOUserEthernetResourceC2Ev : 88 -> 92
~ __ZN22IOUserEthernetResource5startEP9IOService : 140 -> 144
~ __ZN22IOUserEthernetResource4freeEv : 108 -> 112
~ __ZN22IOUserEthernetResource13newUserClientEP4taskPvjP12OSDictionaryPP12IOUserClient : 220 -> 224
~ _GLOBAL__sub_I_IOUserEthernetResource.cpp : 80 -> 84
~ __ZN24IOUserEthernetController9MetaClassC1Ev : 72 -> 76
~ __ZN24IOUserEthernetControllerC2EPK11OSMetaClass : 52 -> 56
~ __ZN24IOUserEthernetControllerC1EPK11OSMetaClass : 52 -> 56
~ __ZN24IOUserEthernetControllerD0Ev : 68 -> 72
~ __ZN24IOUserEthernetController9MetaClassC2Ev : 72 -> 76
~ __ZNK24IOUserEthernetController9MetaClass5allocEv : 104 -> 108
~ __ZN24IOUserEthernetControllerC1Ev : 88 -> 92
~ __ZN24IOUserEthernetControllerC2Ev : 88 -> 92
~ __ZL24__client_attach_callbackP9en_clientPvm : 404 -> 408
~ __ZN24IOUserEthernetController14withPropertiesEP12OSDictionary : 220 -> 224
~ __ZN24IOUserEthernetController4freeEv : 268 -> 272
~ __ZN24IOUserEthernetController27startWithStateEventCallbackEP9IOServicePFvP8OSObjectPS_PvES3_S5_ : 1428 -> 1432
~ __ZN24IOUserEthernetController13publishMediumEv : 336 -> 340
~ __ZN24IOUserEthernetController4stopEP9IOService : 240 -> 244
~ __ZN24IOUserEthernetController18configureInterfaceEP18IONetworkInterface : 408 -> 412
~ __ZL21__mergePropertyActionP18IONetworkInterfaceP12OSDictionary : 84 -> 88
~ __ZN24IOUserEthernetController15createInterfaceEv : 140 -> 144
~ __ZN24IOUserEthernetController6enableEP18IONetworkInterface : 32 -> 36
~ __ZN24IOUserEthernetController14setEnableStateEb : 236 -> 240
~ __ZN24IOUserEthernetController7disableEP18IONetworkInterface : 32 -> 36
~ __ZN24IOUserEthernetController11outputStartEP18IONetworkInterfacej : 672 -> 676
~ __ZN24IOUserEthernetController28invalidateStateEventCallbackEv : 284 -> 288
~ __ZN24IOUserEthernetController15setRunningStateEb : 216 -> 220
~ __ZN24IOUserEthernetController12reportLinkUpEb : 280 -> 284
~ __ZN24IOUserEthernetController18handleClientAttachEP9en_client : 896 -> 900
~ __ZN24IOUserEthernetController19handleClientPacketsEP9en_clientP6__mbuf : 612 -> 616
~ __ZN24IOUserEthernetController18handleClientDetachEP9en_client : 676 -> 680
~ __ZN24IOUserEthernetController15handleBSDAttachEP18IONetworkInterface : 340 -> 344
~ __ZN24IOUserEthernetController15handleBSDDetachEP18IONetworkInterface : 328 -> 332
~ __ZN24IOUserEthernetController12setLinkStateEb : 340 -> 344
~ __ZN24IOUserEthernetController22setIfpPowerSavingsMaskEb : 396 -> 400
~ _GLOBAL__sub_I_IOUserEthernetController.cpp : 80 -> 84
~ _en_register : 336 -> 340
~ _en_ctl_send : 64 -> 68
~ _en_ctl_send_list : 64 -> 68
~ _en_packet_to_client : 80 -> 84
~ _en_packet_list_to_client : 88 -> 92
~ _en_get_enqueue_space : 56 -> 60
~ _en_set_route_cleanup : 132 -> 136
~ _virtio_mbuf_prepend_header : 716 -> 720
~ _virtio_mbuf_ingest_header : 544 -> 548
~ __ZN23IOUserEthernetInterface9MetaClassC1Ev : 72 -> 76
~ __ZN23IOUserEthernetInterfaceC2EPK11OSMetaClass : 52 -> 56
~ __ZN23IOUserEthernetInterfaceC1EPK11OSMetaClass : 52 -> 56
~ __ZN23IOUserEthernetInterfaceD0Ev : 68 -> 72
~ __ZN23IOUserEthernetInterface9MetaClassC2Ev : 72 -> 76
~ __ZNK23IOUserEthernetInterface9MetaClass5allocEv : 104 -> 108
~ __ZN23IOUserEthernetInterfaceC1Ev : 88 -> 92
~ __ZN23IOUserEthernetInterfaceC2Ev : 88 -> 92
~ __ZN23IOUserEthernetInterface4initEP19IONetworkController : 68 -> 72
~ __ZN23IOUserEthernetInterface21attachToDataLinkLayerEjPv : 284 -> 288
~ __ZN23IOUserEthernetInterface23detachFromDataLinkLayerEjPv : 380 -> 384
~ __ZN23IOUserEthernetInterface15registerServiceEj : 280 -> 284
~ __ZNK23IOUserEthernetInterface13getNamePrefixEv : 240 -> 244
~ _GLOBAL__sub_I_IOUserEthernetInterface.cpp : 80 -> 84
~ _en_ctl_connect : 108 -> 112
```
