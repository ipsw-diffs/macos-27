## com.apple.driver.AFKHIDTBDevice

> `com.apple.driver.AFKHIDTBDevice`

```diff

   __TEXT.__const: 0x98
   __TEXT.__cstring: 0xef3
   __TEXT.__os_log: 0x400
-  __TEXT_EXEC.__text: 0x600c
+  __TEXT_EXEC.__text: 0x61d8
   __TEXT_EXEC.__auth_stubs: 0x4b0
   __DATA.__data: 0xc8
   __DATA.__common: 0x38
Functions:
~ __ZN14AFKHIDTBDevice9MetaClassC1Ev : 72 -> 76
~ __ZN14AFKHIDTBDeviceC2EPK11OSMetaClass : 64 -> 68
~ __ZN14AFKHIDTBDeviceC1EPK11OSMetaClass : 64 -> 68
~ __ZN14AFKHIDTBDeviceD2Ev : 240 -> 244
~ __ZN14AFKHIDTBDeviceD1Ev : 240 -> 244
~ __ZN14AFKHIDTBDeviceD0Ev : 68 -> 72
~ __ZN14AFKHIDTBDevice9MetaClassC2Ev : 72 -> 76
~ __ZNK14AFKHIDTBDevice9MetaClass5allocEv : 52 -> 56
~ __ZN14AFKHIDTBDeviceC2Ev : 100 -> 104
~ __ZN14AFKHIDTBDevice5startEP9IOService : 1028 -> 1032
~ __ZN7libkern20intrusive_shared_ptrI20AFKTightbeamEndpoint27intrusive_osobject_retainerE5resetEPS1_NS_8retain_tE : 116 -> 120
~ __ZN14AFKHIDTBDevice21setupDevicePropertiesEv : 140 -> 144
~ __ZN14AFKHIDTBDevice32serviceMatchingThreadCallHandlerEPv : 336 -> 340
~ __ZN14AFKHIDTBDevice26handleMatchingNotificationEPvP9IOServiceP10IONotifier : 244 -> 248
~ __ZN14AFKHIDTBDevice28completeServiceMatchingGatedEv : 636 -> 640
~ __ZN14AFKHIDTBDevice16handleSendReportEyPK23afkhidtbdevice_report_s : 276 -> 280
~ __ZN14AFKHIDTBDevice4freeEv : 176 -> 180
~ __ZNK14AFKHIDTBDevice18newProductIDNumberEv : 144 -> 148
~ __ZNK14AFKHIDTBDevice21newSerialNumberStringEv : 144 -> 148
~ __ZNK14AFKHIDTBDevice23newReportIntervalNumberEv : 144 -> 148
~ __ZNK14AFKHIDTBDevice19newLocationIDNumberEv : 144 -> 148
~ ____ZN14AFKHIDTBDevice21setupDevicePropertiesEv_block_invoke : 488 -> 492
~ __ZNK14AFKHIDTBDevice19newReportDescriptorEPP18IOMemoryDescriptor : 892 -> 896
~ ___Block_byref_object_dispose_ : 72 -> 76
~ ____ZNK14AFKHIDTBDevice19newReportDescriptorEPP18IOMemoryDescriptor_block_invoke : 716 -> 720
~ ___copy_helper_block_8_32r40r48r : 96 -> 100
~ ___destroy_helper_block_8_32r40r48r : 80 -> 84
~ __ZN14AFKHIDTBDevice9setReportEP18IOMemoryDescriptor15IOHIDReportTypej : 232 -> 236
~ __ZN14AFKHIDTBDevice14setReportGatedEP18IOMemoryDescriptor15IOHIDReportTypej : 688 -> 692
~ __ZN14AFKHIDTBDevice9getReportEP18IOMemoryDescriptor15IOHIDReportTypej : 232 -> 236
~ ____ZN14AFKHIDTBDevice14setReportGatedEP18IOMemoryDescriptor15IOHIDReportTypej_block_invoke : 152 -> 156
~ ____ZN14AFKHIDTBDevice14getReportGatedEP18IOMemoryDescriptor15IOHIDReportTypej_block_invoke : 540 -> 544
~ ___copy_helper_block_8_32r40r : 80 -> 84
~ ___destroy_helper_block_8_32r40r : 68 -> 72
~ _GLOBAL__sub_I_AFKHIDTBDevice.cpp : 80 -> 84
~ _u8__v_visit : 476 -> 480
~ ___u8__v_visit_block_invoke : 136 -> 140
~ _u8__v_assign_copy : 292 -> 296
~ _u8__v_assign_owned : 56 -> 60
~ _u8__v_copyout : 244 -> 248
~ ___u8__v_copyout_block_invoke : 40 -> 44
~ _afkhidtbdevice_report__marshal_sizeof : 36 -> 40
~ _afkhidtbdevice_report__marshal : 204 -> 208
~ _afkhidtbdevice_report__unmarshal : 428 -> 432
~ _afkhidtbdevice_devicedescription__marshal_sizeof : 144 -> 148
~ _afkhidtbdevice_devicedescription__marshal : 176 -> 180
~ _afkhidtbdevice_devicedescription__encode : 448 -> 452
~ _afkhidtbdevice_devicedescription__unmarshal : 288 -> 292
~ _afkhidtbdevice_devicedescription__decode : 392 -> 396
~ _afkhidtbdevice_device_getreport : 720 -> 724
~ _afkhidtbdevice_device_setreport : 556 -> 560
~ _afkhidtbdevice_device_getreportdescriptor : 620 -> 624
~ _afkhidtbdevice_device_getdevicedescription : 492 -> 496
~ _afkhidtbdevice_device__init : 84 -> 88
~ _afkhidtbdevice_device__init_static : 112 -> 116
~ _afkhidtbdevice_device__server_start : 40 -> 44
~ _afkhidtbdevice_device__server_start_owned : 184 -> 188
~ ___afkhidtbdevice_device__server_start_owned_block_invoke : 1432 -> 1436
~ ___afkhidtbdevice_device__server_start_owned_block_invoke_2 : 376 -> 380
~ __afkhidtbdevice_device__server_start_owned_block_invoke.31 : 232 -> 236
~ __afkhidtbdevice_device__server_start_owned_block_invoke.38 : 376 -> 380
~ __afkhidtbdevice_device__server_start_owned_block_invoke.45 : 472 -> 476
~ _afkhidtbdevice_deviceclient_sendreport : 312 -> 316
~ _afkhidtbdevice_deviceclient__init : 84 -> 88
~ _afkhidtbdevice_deviceclient__init_static : 112 -> 116
~ _afkhidtbdevice_deviceclient__server_start : 40 -> 44
~ _afkhidtbdevice_deviceclient__server_start_owned : 184 -> 188
~ ___afkhidtbdevice_deviceclient__server_start_owned_block_invoke : 380 -> 384
~ _u8__v_raw_encode : 228 -> 232
~ _u64__opt_decode : 96 -> 100
~ __ZN14AFKHIDTBDevice4stopEP9IOService : 292 -> 296
~ __ZN14AFKHIDTBDevice11handleStartEP9IOService : 656 -> 660
~ __ZN14AFKHIDTBDevice19serializeDebugStateEPvP11OSSerialize : 348 -> 352
~ __ZN14AFKHIDTBDevice14getReportGatedEP18IOMemoryDescriptor15IOHIDReportTypej : 444 -> 448
~ _ZN14AFKHIDTBDevice5startEP9IOService.cold.1 : 92 -> 96
~ _ZN14AFKHIDTBDevice5startEP9IOService.cold.2 : 92 -> 96
~ _ZN14AFKHIDTBDevice5startEP9IOService.cold.3 : 92 -> 96
~ _ZN14AFKHIDTBDevice5startEP9IOService.cold.4 : 168 -> 172
~ _ZN14AFKHIDTBDevice28completeServiceMatchingGatedEv.cold.1 : 92 -> 96
~ _ZN14AFKHIDTBDevice28completeServiceMatchingGatedEv.cold.2 : 92 -> 96
~ _ZN14AFKHIDTBDevice28completeServiceMatchingGatedEv.cold.3 : 92 -> 96
~ _ZNK14AFKHIDTBDevice19newReportDescriptorEPP18IOMemoryDescriptor.cold.1 : 116 -> 120
~ _ZNK14AFKHIDTBDevice19newReportDescriptorEPP18IOMemoryDescriptor.cold.2 : 96 -> 100
~ u8__v_count.cold.1 : 28 -> 32
~ u8__v_visit.cold.1 : 44 -> 48
~ u8__v_visit.cold.2 : 44 -> 48
~ u8__v_visit.cold.3 : 28 -> 32
~ u8__v_copyout.cold.1 : 28 -> 32
~ afkhidtbdevice_report__marshal_sizeof.cold.1 : 20 -> 24
~ afkhidtbdevice_device_getreport.cold.1 : 28 -> 32
~ afkhidtbdevice_device_getreport.cold.2 : 44 -> 48
~ afkhidtbdevice_device_setreport.cold.2 : 44 -> 48
~ afkhidtbdevice_device_getreportdescriptor.cold.2 : 44 -> 48
~ afkhidtbdevice_device_getdevicedescription.cold.2 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.1 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.2 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.3 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.4 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.5 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.6 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.7 : 28 -> 32
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.8 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.9 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.10 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.12 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.13 : 24 -> 28
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.14 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.cold.15 : 28 -> 32
~ __afkhidtbdevice_device__server_start_owned_block_invoke_2.cold.3 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.31.cold.1 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.38.cold.3 : 44 -> 48
~ __afkhidtbdevice_device__server_start_owned_block_invoke.45.cold.2 : 44 -> 48
~ __afkhidtbdevice_deviceclient__server_start_owned_block_invoke.cold.1 : 28 -> 32
~ __afkhidtbdevice_deviceclient__server_start_owned_block_invoke.cold.2 : 44 -> 48
~ u8__v_raw_encode.cold.1 : 28 -> 32
```
