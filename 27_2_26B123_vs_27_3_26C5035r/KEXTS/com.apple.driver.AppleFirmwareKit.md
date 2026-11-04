## com.apple.driver.AppleFirmwareKit

> `com.apple.driver.AppleFirmwareKit`

```diff

-743.40.4.0.0
+743.60.3.0.0
   __TEXT.__const: 0x288
-  __TEXT.__cstring: 0x48f4
-  __TEXT.__os_log: 0x148a
-  __TEXT_EXEC.__text: 0x41310
+  __TEXT.__cstring: 0x48fd
+  __TEXT.__os_log: 0x14f8
+  __TEXT_EXEC.__text: 0x418dc
   __TEXT_EXEC.__auth_stubs: 0x980
   __DATA.__data: 0x508
   __DATA.__common: 0x728
   __DATA.__bss: 0x20
   __DATA_CONST.__mod_init_func: 0x100
   __DATA_CONST.__mod_term_func: 0x100
-  __DATA_CONST.__const: 0x155a0
-  __DATA_CONST.__kalloc_type: 0x1880
+  __DATA_CONST.__const: 0x15600
+  __DATA_CONST.__kalloc_type: 0x1840
   __DATA_CONST.__auth_got: 0x4c0
   __DATA_CONST.__got: 0x148
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 2186
-  Symbols:   2828
-  CStrings:  762
+  Functions: 2179
+  Symbols:   2831
+  CStrings:  768
 
Symbols:
+ __ZN21IOSubMemoryDescriptor12withSubRangeEP18IOMemoryDescriptoryyj
+ __ZN22AFKIOServiceClientBase22copyMatchingDictionaryEv
+ __ZN36AFKMemoryDescriptorManagerUserClient12destroyEntryEPNS_9DescEntryE
+ __ZN36AFKMemoryDescriptorManagerUserClient18setBackingForTokenEyP18IOMemoryDescriptor
+ __ZNK23AFKMemoryDescriptorImpl16getBackingMemoryEv
+ __ZZN23AFKMemoryDescriptorImpldlEPvmE19kalloc_type_view_29
+ __ZZN23AFKMemoryDescriptorImplnwEmE19kalloc_type_view_29
+ __ZZN25AFKEndpointInterfaceRelay22handleMemoryDescriptorEP20AFKEndpointInterfacejyP19AFKMemoryDescriptorjE11_os_log_fmt
+ __ZZN30AFKEPInterfaceKextV2Allocation13releaseBufferEvE21kalloc_type_view_1745
+ __ZZN30AFKEPInterfaceKextV2AllocationnwEmE21kalloc_type_view_1730
+ __ZZN36AFKMemoryDescriptorManagerUserClient12destroyEntryEPNS_9DescEntryEE20kalloc_type_view_862
+ __ZZN36AFKMemoryDescriptorManagerUserClient13addDescriptorEP19AFKMemoryDescriptorE20kalloc_type_view_737
+ __ZZN36AFKMemoryDescriptorManagerUserClient18setBackingForTokenEyP18IOMemoryDescriptorE11_os_log_fmt
+ ____ZN36AFKMemoryDescriptorManagerUserClient19serializeDebugStateEPvP11OSSerialize_block_invoke
+ _afk_msgr_deinit.kalloc_type_view_539
- __ZN18AFKIOServiceClient13handleServiceEP9IOService
- __ZN18AFKIOServiceClient4freeEv
- __ZN18IOMemoryDescriptor11withAddressEPvyj
- __ZN36AFKMemoryDescriptorManagerUserClient15setIOMDForTokenEyP18IOMemoryDescriptor
- __ZZN23AFKMemoryDescriptorImpldlEPvmE19kalloc_type_view_28
- __ZZN23AFKMemoryDescriptorImplnwEmE19kalloc_type_view_28
- __ZZN30AFKEPInterfaceKextV2Allocation13releaseBufferEvE21kalloc_type_view_1744
- __ZZN30AFKEPInterfaceKextV2AllocationnwEmE21kalloc_type_view_1729
- __ZZN36AFKMemoryDescriptorManagerUserClient13addDescriptorEP19AFKMemoryDescriptorE20kalloc_type_view_696
- __ZZN36AFKMemoryDescriptorManagerUserClient25releaseDescriptorForTokenEyE20kalloc_type_view_802
- __ZZN36AFKMemoryDescriptorManagerUserClient4freeEvE20kalloc_type_view_215
- _afk_msgr_deinit.kalloc_type_view_523
CStrings:
+ "\"((void*)0) != messenger->buffer\" @%s:%d"
+ "\"inBounds\" @%s:%d"
+ "\"rv->_commandHeader.maxRspSize <= rv->_oobHdr.rspSize\" @%s:%d"
+ "%s(%s:%#llx): %s: memDescCopy:0x%x pktType:%u\n"
+ "%s(%s:%#llx): %s: token 0x%llx already maps different memory\n\n"
+ "1211111212221212111111122"
+ "AOP2CSID"
+ "AOP2CSIM"
+ "aop2.wificsi"
+ "aop2.wificsi.mcache"
+ "handleMemoryDescriptor"
+ "setBackingForToken"
- "\"!__os_warn_unused(__builtin_add_overflow((offset), (numBytes), (&endRange))) && endRange <= _length\" @%s:%d"
- "\"_assertCnt\" @%s:%d"
- "\"_secMemory\" @%s:%d"
- "\"found\" @%s:%d"
- "\"numBytes <= dst->getCapacity()\" @%s:%d"
- "12111112122212121111111212"
```
