## com.apple.iokit.IOUSBHostFamily

> `com.apple.iokit.IOUSBHostFamily`

```diff

-1617.60.3.0.0
+1617.60.7.0.0
   __TEXT.__cstring: 0xa4be
   __TEXT.__os_log: 0x873b
   __TEXT.__const: 0x2018
-  __TEXT_EXEC.__text: 0x9355c
+  __TEXT_EXEC.__text: 0x936a0
   __TEXT_EXEC.__auth_stubs: 0xd50
   __DATA.__data: 0x1f0
   __DATA.__common: 0x980
Symbols:
+ __ZZN15IOUSBHostDevice23AsyncDeviceRequest_ImplEP9IOServicehhtttP18IOMemoryDescriptorP8OSActionjE21kalloc_type_view_5984
+ __ZZN15IOUSBHostDevice23AsyncDeviceRequest_ImplEP9IOServicehhtttP18IOMemoryDescriptorP8OSActionjE21kalloc_type_view_6015
+ __ZZN15IOUSBHostDevice36asyncDeviceRequestCompletionCallbackEPvS0_ijE21kalloc_type_view_5965
- __ZZN15IOUSBHostDevice23AsyncDeviceRequest_ImplEP9IOServicehhtttP18IOMemoryDescriptorP8OSActionjE21kalloc_type_view_5983
- __ZZN15IOUSBHostDevice23AsyncDeviceRequest_ImplEP9IOServicehhtttP18IOMemoryDescriptorP8OSActionjE21kalloc_type_view_6014
- __ZZN15IOUSBHostDevice36asyncDeviceRequestCompletionCallbackEPvS0_ijE21kalloc_type_view_5964
Functions:
~ __ZN11StandardUSB26getNextInterfaceDescriptorEPKNS_23ConfigurationDescriptorEPKNS_10DescriptorE : 68 -> 76
~ __ZN11StandardUSB25getNextEndpointDescriptorEPKNS_23ConfigurationDescriptorEPKNS_19InterfaceDescriptorEPKNS_10DescriptorE : 12 -> 52
~ __ZN11StandardUSB37getNextInterfaceAssociationDescriptorEPKNS_23ConfigurationDescriptorEPKNS_10DescriptorE : 68 -> 76
~ __ZN11StandardUSB43getUSB20ExtensionDeviceCapabilityDescriptorEPKNS_13BOSDescriptorE : 16 -> 56
~ __ZN11StandardUSB39getSuperSpeedDeviceCapabilityDescriptorEPKNS_13BOSDescriptorE : 16 -> 56
~ __ZN11StandardUSB43getSuperSpeedPlusDeviceCapabilityDescriptorEPKNS_13BOSDescriptorE : 16 -> 76
~ __ZN11StandardUSB24getContainerIDDescriptorEPKNS_13BOSDescriptorE : 16 -> 56
~ __ZN11StandardUSB39getPlatformCapabilityDescriptorWithUUIDEPKNS_13BOSDescriptorEPh : 96 -> 116
~ __ZN11StandardUSB22getBillboardDescriptorEPKNS_13BOSDescriptorE : 16 -> 56
~ __ZN11StandardUSB35validateDeviceCapabilityDescriptorsEPKNS_13BOSDescriptorE : 272 -> 340
~ ____ZN16AppleUSBHostPort23enumerateDeviceCompleteEP15IOUSBHostDevicei_block_invoke : 6040 -> 6068
~ __ZN15IOUSBHostDevice21setConfigurationGatedEhb : 10200 -> 10132
```
