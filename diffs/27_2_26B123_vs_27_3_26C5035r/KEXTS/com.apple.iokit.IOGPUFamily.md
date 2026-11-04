## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

```diff

-162.16.1.0.0
-  __TEXT.__cstring: 0x6a09
-  __TEXT.__os_log: 0x568f
+163.1.4.0.0
+  __TEXT.__cstring: 0x6ba5
+  __TEXT.__os_log: 0x567d
   __TEXT.__const: 0xe4
-  __TEXT_EXEC.__text: 0x485ac
+  __TEXT_EXEC.__text: 0x494e8
   __TEXT_EXEC.__auth_stubs: 0xe30
-  __DATA.__data: 0x460
-  __DATA.__common: 0x8e8
+  __DATA.__data: 0x4b0
+  __DATA.__common: 0x8f0
   __DATA.__bss: 0x9
   __DATA_CONST.__mod_init_func: 0x110
   __DATA_CONST.__mod_term_func: 0x110
-  __DATA_CONST.__const: 0xd2d8
+  __DATA_CONST.__const: 0xd318
   __DATA_CONST.__kalloc_type: 0x1240
   __DATA_CONST.__kalloc_var: 0x1090
   __DATA_CONST.__assert: 0x28
   __DATA_CONST.__auth_got: 0x718
   __DATA_CONST.__got: 0x130
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 2170
-  Symbols:   3631
-  CStrings:  981
+  Functions: 2182
+  Symbols:   3644
+  CStrings:  989
 
Symbols:
+ __ZN11IOGPUMemory21decrementPrepareCountEv
+ __ZN11IOGPUMemory21incrementPrepareCountEv
+ __ZN11IOGPUMemory5evictEy
+ __ZN14IOGPUScheduler28freeToWireSysMemoryStrictLRUEy21eIOGPUWiredMemoryTypeP11IOGPUMemory
+ __ZN14IOGPUScheduler32decrementOutstandingCommandCountEj
+ __ZN14IOGPUWorkQueue15pruneRingBufferERj
+ __ZN16IOGPUGroupMemory5evictEy
+ __ZNK11IOGPUMemory26getNeededWiredMemoryLengthEv
+ __ZNK16IOGPUGroupMemory26getNeededWiredMemoryLengthEv
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2407
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2413
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2169
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2232
+ __ZZN14IOGPUScheduler17scheduleWorkqueueEP14IOGPUWorkQueueE11_os_log_fmt
+ __ZZN14IOGPUScheduler20registerCommandQueueEPK17IOGPUCommandQueueE21kalloc_type_view_2416
+ __ZZN14IOGPUScheduler20registerCommandQueueEPK17IOGPUCommandQueueE21kalloc_type_view_2424
+ __ZZN14IOGPUScheduler28freeToWireSysMemoryStrictLRUEy21eIOGPUWiredMemoryTypeP11IOGPUMemoryE11_os_log_fmt
+ __ZZN14IOGPUScheduler4freeEvE20kalloc_type_view_309
+ __ZZN14IOGPUScheduler4initEP5IOGPUE20kalloc_type_view_141
+ __ZZN16IOGPUGroupMemory22addMemoryFromResourcesEPP13IOGPUResourcejE11_os_log_fmt_2
+ __ZZN16IOGPUGroupMemory5evictEyE11_os_log_fmt
+ __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_225
+ __ZZN5IOGPU4freeEvE21kalloc_type_view_1020
+ __ZZN5IOGPU5startEP9IOServiceE20kalloc_type_view_370
+ _gIOGPUDisablePartialEvict
+ _sysctl__iogpu_disable_partial_evict
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2394
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2400
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2162
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_2225
- __ZZN14IOGPUScheduler20registerCommandQueueEPK17IOGPUCommandQueueE21kalloc_type_view_2301
- __ZZN14IOGPUScheduler20registerCommandQueueEPK17IOGPUCommandQueueE21kalloc_type_view_2309
- __ZZN14IOGPUScheduler4freeEvE20kalloc_type_view_312
- __ZZN14IOGPUScheduler4initEP5IOGPUE20kalloc_type_view_144
- __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_221
- __ZZN22IOGPUCommandDescriptor7prepareEjE11_os_log_fmt_2
- __ZZN22IOGPUCommandDescriptor7prepareEjE11_os_log_fmt_3
- __ZZN5IOGPU4freeEvE21kalloc_type_view_1009
- __ZZN5IOGPU5startEP9IOServiceE20kalloc_type_view_359
CStrings:
+ "\"Evicted member not found in main set\" @%s:%d"
+ "%s <%s> (%p) : required > max : descriptorBytes = <%llu> preparedBytes : <%llu> maxWired = <%llu> maxWiredInternal = <%llu> currentWired = <%llu>\n"
+ "%s: failed to grow pending set to %u, reclaim may have to allocate\n"
+ "%s: nothing to reclaim, bytes == 0, type %u\n"
+ "%s: pending set full at %u members, stopping eviction early\n"
+ "%s: promoting NoResources->NoMemory on workQueue %p: outstanding=%u throttled=%u prepareSeed=%u/%u\n"
+ "1211111121211222222222211211222111222221111121112222111122212222122222221"
+ "1212222221211122111112222221111122222222"
+ "Disable residency-set reclaim mitigations: demand full-teardown instead of partial evict(bytes), and skip the collector's per-group grace"
+ "IOReturn IOGPUScheduler::freeToWireSysMemoryStrictLRU(uint64_t, eIOGPUWiredMemoryType, IOGPUMemory *)"
+ "disable_partial_evict"
+ "virtual bool IOGPUGroupMemory::evict(uint64_t)"
+ "void IOGPUScheduler::scheduleWorkqueue(IOGPUWorkQueue *)"
- "%s <%s> (%p) : required > max : requiredBytes = <%llu> preparedBytes : <%llu> maxWired = <%llu> maxWiredInternal = <%llu> currentWired = <%llu>\n"
- "%s <%s>: preparedBytes != requiredBytes : preparedBytes = <%llu> requiredBytes = <%llu> maxWired = <%llu> preWiring = <%llu> currentWired = <%llu> wiring delta = <%llu>\n\n"
- "%s <%s>: requiredBytes = <%llu> maxWired = <%llu> preparedBytes : <%llu> remainingBytes : <%lld> remainingPages = <%lld>\n\n"
- "121111112121122222222221121122211122222111112111222222111122212222122222221"
- "12122222212111221111122222211111222222"
```
