## com.apple.iokit.IOUSBHostFamily

> `com.apple.iokit.IOUSBHostFamily`

```diff

   __TEXT.__cstring: 0xa4be
   __TEXT.__os_log: 0x873b
   __TEXT.__const: 0x2018
-  __TEXT_EXEC.__text: 0x934fc
+  __TEXT_EXEC.__text: 0x935bc
   __TEXT_EXEC.__auth_stubs: 0xd50
   __DATA.__data: 0x1f0
   __DATA.__common: 0x980
Functions:
~ __ZN15IOUSBHostDevice21_GetDescriptor_InvokeE5IORPCP15OSMetaClassBasePFiS2_hhthhP18IOMemoryDescriptorPtE : 252 -> 256
~ __ZN15IOUSBHostDevice11Open_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicejmE : 236 -> 240
~ __ZN15IOUSBHostDevice12Close_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicejE : 232 -> 236
~ __ZN15IOUSBHostDevice21CreateIOBuffer_InvokeE5IORPCP15OSMetaClassBasePFiS2_jyPP24IOBufferMemoryDescriptorE : 192 -> 196
~ __ZN15IOUSBHostDevice25AsyncDeviceRequest_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicehhtttP18IOMemoryDescriptorP8OSActionjE : 368 -> 372
~ __ZN15IOUSBHostDevice20DeviceRequest_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicehhtttP18IOMemoryDescriptorPtjE : 316 -> 320
~ __ZN15IOUSBHostDevice26AbortDeviceRequests_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicejiE : 232 -> 236
~ __ZN15IOUSBHostDevice23SetConfiguration_InvokeE5IORPCP15OSMetaClassBasePFiS2_hbE : 176 -> 180
~ __ZN15IOUSBHostDevice17GetAddress_InvokeE5IORPCP15OSMetaClassBasePFiS2_PhE : 164 -> 168
~ __ZN15IOUSBHostDevice15GetSpeed_InvokeE5IORPCP15OSMetaClassBasePFiS2_PhE : 164 -> 168
~ __ZN15IOUSBHostDevice21GetFrameNumber_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN15IOUSBHostDevice24CurrentMicroframe_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN15IOUSBHostDevice26ReferenceMicroframe_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN15IOUSBHostDevice20GetPortStatus_InvokeE5IORPCP15OSMetaClassBasePFiS2_PjE : 164 -> 168
~ __ZN15IOUSBHostDevice12Reset_InvokeE5IORPCP15OSMetaClassBasePFiS2_E : 156 -> 160
~ __ZN15IOUSBHostDevice30CreateInterfaceIterator_InvokeE5IORPCP15OSMetaClassBasePFiS2_PmE : 164 -> 168
~ __ZN15IOUSBHostDevice31DestroyInterfaceIterator_InvokeE5IORPCP15OSMetaClassBasePFiS2_mE : 164 -> 168
~ __ZN15IOUSBHostDevice20CopyInterface_InvokeE5IORPCP15OSMetaClassBasePFiS2_mPP18IOUSBHostInterfaceE : 188 -> 192
~ __ZN15IOUSBHostDevice33CompleteAsyncDeviceRequest_InvokeE5IORPCP15OSMetaClassBasePFvS2_P8OSActionijEPK11OSMetaClass : 196 -> 200
~ __ZN18IOUSBHostInterface36_GetInterfaceDescriptorHeader_InvokeE5IORPCP15OSMetaClassBasePFiS2_P24IOUSBInterfaceDescriptorE : 164 -> 168
~ __ZN18IOUSBHostInterface11Open_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicejPhE : 236 -> 240
~ __ZN18IOUSBHostInterface12Close_InvokeE5IORPCP15OSMetaClassBasePFiS2_P9IOServicejE : 232 -> 236
~ __ZN18IOUSBHostInterface21GetFrameNumber_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN18IOUSBHostInterface24CurrentMicroframe_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN18IOUSBHostInterface26ReferenceMicroframe_InvokeE5IORPCP15OSMetaClassBasePFiS2_PyS3_E : 172 -> 176
~ __ZN18IOUSBHostInterface15CopyPipe_InvokeE5IORPCP15OSMetaClassBasePFiS2_hPP13IOUSBHostPipeE : 188 -> 192
~ __ZN18IOUSBHostInterface29SelectAlternateSetting_InvokeE5IORPCP15OSMetaClassBasePFiS2_hE : 164 -> 168
~ __ZN18IOUSBHostInterface20GetPortStatus_InvokeE5IORPCP15OSMetaClassBasePFiS2_PjE : 164 -> 168
~ __ZN18IOUSBHostInterface20SetIdlePolicy_InvokeE5IORPCP15OSMetaClassBasePFiS2_jE : 164 -> 168
~ __ZN18IOUSBHostInterface20GetIdlePolicy_InvokeE5IORPCP15OSMetaClassBasePFiS2_PjE : 164 -> 168
~ __ZN18IOUSBHostInterface17CopyDevice_InvokeE5IORPCP15OSMetaClassBasePFiS2_PP15IOUSBHostDeviceE : 180 -> 184
~ __ZN13IOUSBHostPipe15GetSpeed_InvokeE5IORPCP15OSMetaClassBasePFiS2_PhE : 164 -> 168
~ __ZN13IOUSBHostPipe23GetDeviceAddress_InvokeE5IORPCP15OSMetaClassBasePFiS2_PhE : 164 -> 168
~ __ZN13IOUSBHostPipe12Abort_InvokeE5IORPCP15OSMetaClassBasePFiS2_jiP9IOServiceE : 232 -> 236
~ __ZN13IOUSBHostPipe17AdjustPipe_InvokeE5IORPCP15OSMetaClassBasePFiS2_PK32IOUSBStandardEndpointDescriptorsE : 164 -> 168
~ __ZN13IOUSBHostPipe21GetDescriptors_InvokeE5IORPCP15OSMetaClassBasePFiS2_P32IOUSBStandardEndpointDescriptors33IOUSBGetEndpointDescriptorOptionsE : 172 -> 176
~ __ZN13IOUSBHostPipe20SetIdlePolicy_InvokeE5IORPCP15OSMetaClassBasePFiS2_jE : 164 -> 168
~ __ZN13IOUSBHostPipe20GetIdlePolicy_InvokeE5IORPCP15OSMetaClassBasePFiS2_PjE : 164 -> 168
~ __ZN13IOUSBHostPipe17ClearStall_InvokeE5IORPCP15OSMetaClassBasePFiS2_bE : 168 -> 172
~ __ZN13IOUSBHostPipe14AsyncIO_InvokeE5IORPCP15OSMetaClassBasePFiS2_P18IOMemoryDescriptorjP8OSActionjE : 276 -> 280
~ __ZN13IOUSBHostPipe9IO_InvokeE5IORPCP15OSMetaClassBasePFiS2_P18IOMemoryDescriptorjPjjE : 236 -> 240
~ __ZN13IOUSBHostPipe14IsochIO_InvokeE5IORPCP15OSMetaClassBasePFiS2_P18IOMemoryDescriptorS4_yP8OSActionE : 328 -> 332
~ __ZN13IOUSBHostPipe33CreateMemoryDescriptorRing_InvokeE5IORPCP15OSMetaClassBasePFiS2_jE : 164 -> 168
~ __ZN13IOUSBHostPipe26SetMemoryDescriptor_InvokeE5IORPCP15OSMetaClassBasePFiS2_P18IOMemoryDescriptorjE : 232 -> 236
~ __ZN13IOUSBHostPipe21AsyncIOBundled_InvokeE5IORPCP15OSMetaClassBasePFiS2_jjPjPKjiP8OSActionjE : 256 -> 260
~ __ZN13IOUSBHostPipe22CompleteAsyncIO_InvokeE5IORPCP15OSMetaClassBasePFvS2_P8OSActionijyEPK11OSMetaClass : 200 -> 204
~ __ZN13IOUSBHostPipe27CompleteAsyncIsochIO_InvokeE5IORPCP15OSMetaClassBasePFvS2_P8OSActioniEPK11OSMetaClass : 196 -> 200
~ __ZN13IOUSBHostPipe29CompleteAsyncIOBundled_InvokeE5IORPCP15OSMetaClassBasePFvS2_P8OSActionjjPKjiPKiiEPK11OSMetaClass : 248 -> 252
```
