## DeviceInterface

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__data`
- `__DATA.__data`

```diff

 294.0.0.0.0
-  __TEXT.__text: 0x8b6c4
+  __TEXT.__text: 0x8b3d4
   __TEXT.__objc_methlist: 0x6f3c
   __TEXT.__const: 0x64
   __TEXT.__cstring: 0x9b1d
   __TEXT.__gcc_except_tab: 0x470
   __TEXT.__oslogstring: 0x49
-  __TEXT.__unwind_info: 0x1250
-  __TEXT.__eh_frame: 0xd4
+  __TEXT.__unwind_info: 0x2740
+  __TEXT.__eh_frame: 0xdc
   __TEXT.__objc_stubs: 0x7d40
   __TEXT.__auth_stubs: 0x8f0
   __TEXT.__objc_classname: 0xf93
Functions:
~ -[DockChannelConnectedState stateByConnectingChannel:] : 232 -> 220
~ -[DockChannelConnectedState stateByDisconnectingChannel:] : 232 -> 220
~ -[DockChannelProbeNexus probeIDsForClient:] : 288 -> 276
~ _getFilePath : 176 -> 164
~ -[KISSnifferControllerClient createSaveFilePath:kisInterfaceID:] : 908 -> 896
~ -[RSMChannelSystemInterfaceWrapper owner] : 64 -> 52
~ +[TADFUTransportServer get_device_properties_using_client:] : 3596 -> 3584
~ _debug_usb_buffer_iousbhost_data : 100 -> 88
~ -[DockChannelProbeListenerProbeState owner] : 64 -> 52
~ +[DockChannelProbeDeviceHubState hubPortMatchingDictionaryForLocation:] : 456 -> 444
~ -[DockChannelProbeDeviceHubState owner] : 64 -> 52
~ +[DockChannelProbeDeviceHubListenerIOUSBHost captiveAppleDeviceMatchingDictionary] : 424 -> 412
~ -[DockChannelProbeDeviceHubListenerIOUSBHost hubServiceForService:hubServiceLocation:] : 552 -> 540
~ -[DockChannelProbeDeviceHubListenerIOUSBHost serviceWrapperForService:] : 240 -> 228
~ -[DockChannelProbeDeviceHubListenerIOUSBHost nameForService:hubState:] : 348 -> 336
~ +[DockChannelProbeDeviceHubListenerIOUSBHost baseNameForCustomName:probePortCount:portNumber:location:] : 316 -> 304
~ -[KISInterfaceEnablePortalState stateByRequestEnablePortal:] : 196 -> 184
~ -[KISInterfaceEnablePortalState stateByRequestDisablePortal:] : 196 -> 184
~ -[KISInterfaceEnablePortalState stateByIssuingCommand] : 104 -> 92
~ -[KISInterfaceEnablePortalState stateByCompletingCommand] : 96 -> 84
~ -[DockChannelProbeNexusController portServiceForService:] : 400 -> 388
~ -[DockChannelProbeNexusController nexusServiceForService:] : 540 -> 528
~ -[DockChannelProbeNexusController nexusStateForNexusService:] : 344 -> 332
~ -[SystemServiceWrapper createClientWithDescription:] : 84 -> 72
~ -[SystemServiceWrapper createUSBDeviceClientWithDescription:] : 84 -> 72
~ -[SystemServiceWrapper createUSBHubPortClientWithDescription:] : 84 -> 72
~ -[SystemServiceWrapper createUSBHostPortClientWithDescription:] : 84 -> 72
~ -[TADFUTransportServerService get_all_devices_from_manager] : 528 -> 516
~ _external_interface_kis_client_transport_queue : 124 -> 112
~ -[TADFUTransportClient requested_information_for_all_devices] : 816 -> 804
~ -[TADFUTransportClient request_information_for_devices_with_location_id:] : 832 -> 820
~ -[TADFUTransportClient request_information_for_device_with_vid:and_pid:] : 856 -> 844
~ +[DockChannelProbeHubState hubPortMatchingDictionaryForLocation:] : 456 -> 444
~ -[DockChannelProbeHubState owner] : 64 -> 52
~ -[DockChannelProbeHubListenerIOUSBHost serviceWrapperForService:] : 240 -> 228
~ -[DockChannelProbeHubListenerIOUSBHost nameForService:] : 248 -> 236
~ +[TADFUCallbackInfo sharedInstance] : 192 -> 180
~ _kis_interface_debug_usb_transport_queue : 124 -> 112
~ -[DockChannelProbeDeviceListenerIOUSBHost nameForService:] : 864 -> 852
~ _device_interface_client_xpc_transport_server_copy_endpoint : 140 -> 128
~ +[RSMChannelState oppositeTailOffsetFromOffsetDoorbell:bufferLength:oppositeTailOffset:] : 224 -> 220
~ -[RSMChannelState makeHostToDeviceBufferOffsetDoorbell] : 156 -> 152
~ -[DockChannelPPMState stateByInitializingPPM] : 144 -> 132
~ -[DockChannelPPMState stateByRequestEnableChannel:] : 348 -> 336
~ -[DockChannelPPMState stateByRequestDisableChannel:] : 308 -> 296
~ -[DockChannelPPMState stateByRequestEnableChannels:] : 328 -> 316
~ -[DockChannelPPMState stateByRequestDisableChannels:] : 328 -> 316
~ -[DockChannelPPMState stateByThrottlingChannel:] : 356 -> 344
~ -[DockChannelPPMState stateByUnthrottlingChannel:] : 308 -> 296
~ -[DockChannelPPMState stateByThrottlingChannels:] : 328 -> 316
~ -[DockChannelPPMState stateByUnthrottlingChannels:] : 328 -> 316
~ -[DockChannelPPMState stateByIssuingCommand] : 144 -> 132
~ -[DockChannelPPMState stateByCompletingCommand] : 228 -> 216
~ -[DockChannelPPMState newlyEnabledChannels] : 140 -> 128
~ -[DockChannelPPMState description] : 264 -> 252
~ -[DockChannelSerialInterfaceInfo owner] : 64 -> 52
~ -[DockChannelProbeNexusSerialPortController owner] : 64 -> 52
~ -[DockChannelProbeKISListenerIOUSBHost nameForService:] : 424 -> 412
~ -[DockChannelProbeKISListenerIOUSBHost getNameUsingLocationOrSerialNumber:locationID:] : 500 -> 488
~ -[DockChannelProbeKISListenerIOUSBHost truncateSerialNumberForBaseName:] : 864 -> 852
~ -[DockChannelProbeNexusProbeDevice probeIDsForClient:] : 632 -> 620
~ _debug_usb_interface_iousbhost_transport_queue : 124 -> 112
~ -[KISInterfacePendingCommandsMap validCallbackHandlersForClient:] : 160 -> 148
~ -[KISInterfacePendingCommandsMap callbackHandlerForKey:] : 204 -> 192
```
