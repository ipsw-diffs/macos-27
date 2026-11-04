## com.apple.driver.AppleA7IOP

> `com.apple.driver.AppleA7IOP`

```diff

-342.40.3.0.0
-  __TEXT.__cstring: 0xff7
-  __TEXT_EXEC.__text: 0x6350
+342.60.5.0.0
+  __TEXT.__cstring: 0xe19
+  __TEXT_EXEC.__text: 0x4678
   __TEXT_EXEC.__auth_stubs: 0x310
   __DATA.__data: 0xc8
-  __DATA.__common: 0xb0
-  __DATA_CONST.__mod_init_func: 0x20
-  __DATA_CONST.__mod_term_func: 0x20
-  __DATA_CONST.__const: 0x2b60
-  __DATA_CONST.__kalloc_type: 0x100
+  __DATA.__common: 0x88
+  __DATA_CONST.__mod_init_func: 0x18
+  __DATA_CONST.__mod_term_func: 0x18
+  __DATA_CONST.__const: 0x1ff0
+  __DATA_CONST.__kalloc_type: 0xc0
   __DATA_CONST.__auth_got: 0x188
   __DATA_CONST.__got: 0x50
-  Functions: 281
-  Symbols:   588
-  CStrings:  106
+  Functions: 195
+  Symbols:   517
+  CStrings:  98
 
Symbols:
+ __ZNK10AppleA7IOP24_needsInboxWriteReadbackEv
- __GLOBAL__sub_I_AppleWrapperMailbox.cpp
- __ZL23AppleWrapperMailbox_ktv
- __ZN19AppleWrapperMailbox10enableSRAMEb
- __ZN19AppleWrapperMailbox10gMetaClassE
- __ZN19AppleWrapperMailbox10getMailboxEjPvb
- __ZN19AppleWrapperMailbox10initializeEv
- __ZN19AppleWrapperMailbox10resetStateEv
- __ZN19AppleWrapperMailbox10superClassE
- __ZN19AppleWrapperMailbox11enablePowerEv
- __ZN19AppleWrapperMailbox11physToSlaveEy
- __ZN19AppleWrapperMailbox11postMailboxEjPvjb
- __ZN19AppleWrapperMailbox12_enablePowerEbj
- __ZN19AppleWrapperMailbox12_generateNMIEv
- __ZN19AppleWrapperMailbox12_mapFirmwareEyP18IOMemoryDescriptorj
- __ZN19AppleWrapperMailbox12ringDoorbellEj
- __ZN19AppleWrapperMailbox13_inboxHandlerEP22IOInterruptEventSource
- __ZN19AppleWrapperMailbox13_inboxHandlerEP22IOInterruptEventSource_vfpthunk_
- __ZN19AppleWrapperMailbox13_publishBelowEP15IORegistryEntry
- __ZN19AppleWrapperMailbox14_outboxHandlerEP22IOInterruptEventSource
- __ZN19AppleWrapperMailbox14_outboxHandlerEP22IOInterruptEventSource_vfpthunk_
- __ZN19AppleWrapperMailbox14_unmapFirmwareEv
- __ZN19AppleWrapperMailbox14getMailboxBulkEPvPj
- __ZN19AppleWrapperMailbox14waitForMailboxEj
- __ZN19AppleWrapperMailbox15_underflowCheckEjjPKc
- __ZN19AppleWrapperMailbox16_setMapperActiveEb
- __ZN19AppleWrapperMailbox16_syncIOPTimebaseEv
- __ZN19AppleWrapperMailbox16disablePowerLateEv
- __ZN19AppleWrapperMailbox16getStructuredLogEv
- __ZN19AppleWrapperMailbox17setDoorbellActionEPFvP8OSObjectPvjES1_S2_j
- __ZN19AppleWrapperMailbox18_enableInboxFilterEv
- __ZN19AppleWrapperMailbox18slaveMemoryOptionsEv
- __ZN19AppleWrapperMailbox19startCPUWithOptionsEP15IOSlaveFirmwarej
- __ZN19AppleWrapperMailbox20_inboxUnderflowCheckEjj
- __ZN19AppleWrapperMailbox20publishNumberToIORegEPKcy
- __ZN19AppleWrapperMailbox20slaveMemoryAlignmentEv
- __ZN19AppleWrapperMailbox21_get_integer_propertyEP15IORegistryEntryPKcPj
- __ZN19AppleWrapperMailbox21_outboxUnderflowCheckEjj
- __ZN19AppleWrapperMailbox21getMailboxDebugStatusEv
- __ZN19AppleWrapperMailbox21supportReleaseOnEntryEv
- __ZN19AppleWrapperMailbox22getMailboxDebugEntriesEv
- __ZN19AppleWrapperMailbox23enableMailboxInterruptsEb
- __ZN19AppleWrapperMailbox25getWrapperPhysicalAddressEv
- __ZN19AppleWrapperMailbox29_get_integer_property_defaultEP15IORegistryEntryPKcj
- __ZN19AppleWrapperMailbox4_regEj
- __ZN19AppleWrapperMailbox5startEP9IOService
- __ZN19AppleWrapperMailbox7_runCPUEb
- __ZN19AppleWrapperMailbox7stopCPUEb
- __ZN19AppleWrapperMailbox7stopCPUEbb
- __ZN19AppleWrapperMailbox7stopCPUEv
- __ZN19AppleWrapperMailbox8startCPUEP15IOSlaveFirmware
- __ZN19AppleWrapperMailbox9MetaClassC1Ev
- __ZN19AppleWrapperMailbox9MetaClassC2Ev
- __ZN19AppleWrapperMailbox9MetaClassD0Ev
- __ZN19AppleWrapperMailbox9MetaClassD1Ev
- __ZN19AppleWrapperMailbox9metaClassE
- __ZN19AppleWrapperMailboxC2EPK11OSMetaClass
- __ZN19AppleWrapperMailboxD0Ev
- __ZN19AppleWrapperMailboxD1Ev
- __ZN19AppleWrapperMailboxD2Ev
- __ZN19AppleWrapperMailboxdlEPvm
- __ZN19AppleWrapperMailboxnwEm
- __ZNK19AppleWrapperMailbox12getMetaClassEv
- __ZNK19AppleWrapperMailbox15mailboxItemSizeEv
- __ZNK19AppleWrapperMailbox16_ignoreMailboxesEv
- __ZNK19AppleWrapperMailbox19_mailboxesAvailableEv
- __ZNK19AppleWrapperMailbox23_apInitializesMailboxesEv
- __ZNK19AppleWrapperMailbox25_inboxEmptyInterruptIndexEv
- __ZNK19AppleWrapperMailbox29_outboxNotEmptyInterruptIndexEv
- __ZNK19AppleWrapperMailbox8_runningEv
- __ZNK19AppleWrapperMailbox9MetaClass5allocEv
- __ZTV19AppleWrapperMailbox
- __ZTVN19AppleWrapperMailbox9MetaClassE
CStrings:
- "12111112122212121112221111121211121122222111"
- "AppleWrapperMailbox"
- "site.AppleWrapperMailbox"
- "virtual IOPhysicalAddress AppleWrapperMailbox::getWrapperPhysicalAddress()"
- "virtual IOReturn AppleWrapperMailbox::getMailboxBulk(void *, unsigned int *)"
- "virtual bool AppleWrapperMailbox::_outboxHandler(IOInterruptEventSource *)"
- "virtual bool AppleWrapperMailbox::setDoorbellAction(IOSlaveCPU::DoorbellAction, OSObject *, void *, UInt32)"
- "virtual bool AppleWrapperMailbox::start(IOService *)"
```
