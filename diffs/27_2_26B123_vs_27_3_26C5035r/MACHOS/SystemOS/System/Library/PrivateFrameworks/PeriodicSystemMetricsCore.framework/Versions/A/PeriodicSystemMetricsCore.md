## PeriodicSystemMetricsCore

> `/System/Library/PrivateFrameworks/PeriodicSystemMetricsCore.framework/Versions/A/PeriodicSystemMetricsCore`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-9.0.0.0.0
-  __TEXT.__text: 0x10890
+10.0.0.0.0
+  __TEXT.__text: 0x11170
   __TEXT.__auth_stubs: 0x550
-  __TEXT.__objc_stubs: 0x1520
-  __TEXT.__objc_methlist: 0x15cc
+  __TEXT.__objc_stubs: 0x1480
+  __TEXT.__objc_methlist: 0x1654
   __TEXT.__const: 0x968
-  __TEXT.__gcc_except_tab: 0x1334
-  __TEXT.__cstring: 0x6a4
-  __TEXT.__objc_methname: 0x1e0d
-  __TEXT.__objc_classname: 0x3de
-  __TEXT.__objc_methtype: 0x830
+  __TEXT.__gcc_except_tab: 0x1480
+  __TEXT.__cstring: 0x6a7
+  __TEXT.__objc_methname: 0x1e1a
+  __TEXT.__objc_classname: 0x41b
+  __TEXT.__objc_methtype: 0x870
   __TEXT.__oslogstring: 0x3f3
-  __TEXT.__unwind_info: 0xb80
+  __TEXT.__unwind_info: 0xc00
   __DATA_CONST.__const: 0x798
   __DATA_CONST.__cfstring: 0x7e0
-  __DATA_CONST.__objc_classlist: 0x140
+  __DATA_CONST.__objc_classlist: 0x158
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6b8
-  __DATA_CONST.__objc_superrefs: 0x128
+  __DATA_CONST.__objc_selrefs: 0x6a8
+  __DATA_CONST.__objc_superrefs: 0x140
   __DATA_CONST.__objc_intobj: 0x3a8
   __DATA_CONST.__objc_arraydata: 0x250
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__auth_got: 0x2c0
   __DATA_CONST.__got: 0xf8
-  __DATA.__objc_const: 0x2fb8
-  __DATA.__objc_ivar: 0x1d4
-  __DATA.__objc_data: 0xc80
+  __DATA.__objc_const: 0x3250
+  __DATA.__objc_ivar: 0x1f0
+  __DATA.__objc_data: 0xd70
   __DATA.__data: 0x1d8
-  __DATA.__bss: 0x128
+  __DATA.__bss: 0x130
   - /AppleInternal/Library/Frameworks/PerformanceControlKitInternal.framework/Versions/A/PerformanceControlKitInternal
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 736
-  Symbols:   1584
-  CStrings:  584
+  Functions: 752
+  Symbols:   1633
+  CStrings:  593
 
Symbols:
+ +[PSMMutableVMStatsExt1 new]
+ -[PSMImmutableVMStatsExt1 .cxx_destruct]
+ -[PSMImmutableVMStatsExt1 activeInternalCount]
+ -[PSMImmutableVMStatsExt1 copyWithZone:]
+ -[PSMImmutableVMStatsExt1 cppPointer]
+ -[PSMImmutableVMStatsExt1 executableCount]
+ -[PSMImmutableVMStatsExt1 inactiveInternalCount]
+ -[PSMImmutableVMStatsExt1 initWithBufRef:cppPointer:]
+ -[PSMImmutableVMStatsExt1 initWithBufRef:rawPointer:]
+ -[PSMImmutableVMStatsExt1 mutableCopyWithZone:]
+ -[PSMImmutableVMStatsExt1 pageinsDelta]
+ -[PSMMediumCadenceBuffer vmStatsExt1]
+ -[PSMMediumCadenceBufferBuilder setVmStatsExt1:]
+ -[PSMMutableVMStats initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:]
+ -[PSMMutableVMStatsExt1 _checkMutationWithSelector:]
+ -[PSMMutableVMStatsExt1 activeInternalCount]
+ -[PSMMutableVMStatsExt1 copyWithZone:]
+ -[PSMMutableVMStatsExt1 cppPointer]
+ -[PSMMutableVMStatsExt1 dealloc]
+ -[PSMMutableVMStatsExt1 executableCount]
+ -[PSMMutableVMStatsExt1 inactiveInternalCount]
+ -[PSMMutableVMStatsExt1 initWithPageinsDelta:executableCount:activeInternalCount:inactiveInternalCount:]
+ -[PSMMutableVMStatsExt1 init]
+ -[PSMMutableVMStatsExt1 mutableCopyWithZone:]
+ -[PSMMutableVMStatsExt1 pageinsDelta]
+ -[PSMMutableVMStatsExt1 setActiveInternalCount:]
+ -[PSMMutableVMStatsExt1 setExecutableCount:]
+ -[PSMMutableVMStatsExt1 setInactiveInternalCount:]
+ -[PSMMutableVMStatsExt1 setPageinsDelta:]
+ -[PSMVMStats initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:]
+ -[PSMVMStatsExt1 activeInternalCount]
+ -[PSMVMStatsExt1 copyWithZone:]
+ -[PSMVMStatsExt1 cppPointer]
+ -[PSMVMStatsExt1 executableCount]
+ -[PSMVMStatsExt1 hash]
+ -[PSMVMStatsExt1 inactiveInternalCount]
+ -[PSMVMStatsExt1 initWithPageinsDelta:executableCount:activeInternalCount:inactiveInternalCount:]
+ -[PSMVMStatsExt1 init]
+ -[PSMVMStatsExt1 init_]
+ -[PSMVMStatsExt1 isEqual:]
+ -[PSMVMStatsExt1 mutableCopyWithZone:]
+ -[PSMVMStatsExt1 pageinsDelta]
+ GCC_except_table101
+ GCC_except_table139
+ GCC_except_table151
+ GCC_except_table158
+ GCC_except_table169
+ GCC_except_table17
+ GCC_except_table170
+ GCC_except_table192
+ GCC_except_table196
+ GCC_except_table20
+ GCC_except_table203
+ GCC_except_table212
+ GCC_except_table213
+ GCC_except_table231
+ GCC_except_table233
+ GCC_except_table24
+ GCC_except_table240
+ GCC_except_table249
+ GCC_except_table267
+ GCC_except_table269
+ GCC_except_table27
+ GCC_except_table284
+ GCC_except_table285
+ GCC_except_table30
+ GCC_except_table303
+ GCC_except_table305
+ GCC_except_table312
+ GCC_except_table37
+ GCC_except_table38
+ GCC_except_table415
+ GCC_except_table435
+ GCC_except_table45
+ GCC_except_table455
+ GCC_except_table53
+ GCC_except_table56
+ GCC_except_table65
+ GCC_except_table66
+ _OBJC_CLASS_$_PSMImmutableVMStatsExt1
+ _OBJC_CLASS_$_PSMMutableVMStatsExt1
+ _OBJC_CLASS_$_PSMVMStatsExt1
+ _OBJC_IVAR_$_PSMImmutableVMStatsExt1._br
+ _OBJC_IVAR_$_PSMImmutableVMStatsExt1._ptr
+ _OBJC_IVAR_$_PSMMediumCadenceBufferChanges._changeTypeVmStatsExt1
+ _OBJC_IVAR_$_PSMMediumCadenceBufferChanges._replacementVmStatsExt1
+ _OBJC_IVAR_$_PSMMutableVMStatsExt1._allowMutation
+ _OBJC_IVAR_$_PSMMutableVMStatsExt1._deleteWhenDone
+ _OBJC_IVAR_$_PSMMutableVMStatsExt1._ptr
+ _OBJC_METACLASS_$_PSMImmutableVMStatsExt1
+ _OBJC_METACLASS_$_PSMMutableVMStatsExt1
+ _OBJC_METACLASS_$_PSMVMStatsExt1
+ _OUTLINED_FUNCTION_10
+ __OBJC_$_CLASS_METHODS_PSMMutableVMStatsExt1
+ __OBJC_$_INSTANCE_METHODS_PSMImmutableVMStatsExt1
+ __OBJC_$_INSTANCE_METHODS_PSMMutableVMStatsExt1
+ __OBJC_$_INSTANCE_METHODS_PSMVMStatsExt1
+ __OBJC_$_INSTANCE_VARIABLES_PSMImmutableVMStatsExt1
+ __OBJC_$_INSTANCE_VARIABLES_PSMMutableVMStatsExt1
+ __OBJC_$_PROP_LIST_PSMMutableVMStatsExt1
+ __OBJC_$_PROP_LIST_PSMVMStatsExt1
+ __OBJC_CLASS_PROTOCOLS_$_PSMImmutableVMStatsExt1
+ __OBJC_CLASS_PROTOCOLS_$_PSMVMStatsExt1
+ __OBJC_CLASS_RO_$_PSMImmutableVMStatsExt1
+ __OBJC_CLASS_RO_$_PSMMutableVMStatsExt1
+ __OBJC_CLASS_RO_$_PSMVMStatsExt1
+ __OBJC_METACLASS_RO_$_PSMImmutableVMStatsExt1
+ __OBJC_METACLASS_RO_$_PSMMutableVMStatsExt1
+ __OBJC_METACLASS_RO_$_PSMVMStatsExt1
+ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder9AddStructIN16PSMMediumCadence11VMStatsExt1EEEvtPKT_
+ __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE11target_typeEv
+ __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE6targetERKSt9type_info
+ __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
+ __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7__cloneEv
+ __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE11target_typeEv
+ __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE6targetERKSt9type_info
+ __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
+ __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7__cloneEv
+ __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE11target_typeEv
+ __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE6targetERKSt9type_info
+ __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
+ __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7__cloneEv
+ __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7destroyEv
+ __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED0Ev
+ __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED1Ev
+ __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEclEOmOS5_
+ __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7destroyEv
+ __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEED0Ev
+ __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEED1Ev
+ __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEclEOmOS5_
+ __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7destroyEv
+ __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED0Ev
+ __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED1Ev
+ __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEclEOmOS5_
+ __ZTINSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
+ __ZTINSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
+ __ZTINSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
+ __ZTIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9
+ __ZTIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5
+ __ZTIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7
+ __ZTSNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
+ __ZTSNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
+ __ZTSNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
+ __ZTSZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9
+ __ZTSZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5
+ __ZTSZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7
+ __ZTVNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_9FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
+ __ZTVNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
+ __ZTVNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
+ ___block_descriptor_56_e8_32s40n9_8_8_s0_s8_e39_v16?0"PSMMediumCadenceBufferBuilder"8l
+ ___copy_helper_block_e8_32s40n9_8_8_s0_s8
+ ___destroy_helper_block_e8_32s40n7_8_s0_s8
+ __vmStats.statsExt1
+ _objc_msgSend$initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:
+ _objc_msgSend$initWithPageinsDelta:executableCount:activeInternalCount:inactiveInternalCount:
- -[PSMImmutableVMStats activeInternalCount]
- -[PSMImmutableVMStats executableCount]
- -[PSMImmutableVMStats inactiveInternalCount]
- -[PSMImmutableVMStats pageinsDelta]
- -[PSMImmutableVMStats purgeablePageableCount]
- -[PSMImmutableVMStats purgeableWiredCount]
- -[PSMImmutableVMStats realtimeCount]
- -[PSMMutableVMStats activeInternalCount]
- -[PSMMutableVMStats executableCount]
- -[PSMMutableVMStats inactiveInternalCount]
- -[PSMMutableVMStats initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:pageinsDelta:executableCount:purgeablePageableCount:purgeableWiredCount:activeInternalCount:inactiveInternalCount:realtimeCount:]
- -[PSMMutableVMStats pageinsDelta]
- -[PSMMutableVMStats purgeablePageableCount]
- -[PSMMutableVMStats purgeableWiredCount]
- -[PSMMutableVMStats realtimeCount]
- -[PSMMutableVMStats setActiveInternalCount:]
- -[PSMMutableVMStats setExecutableCount:]
- -[PSMMutableVMStats setInactiveInternalCount:]
- -[PSMMutableVMStats setPageinsDelta:]
- -[PSMMutableVMStats setPurgeablePageableCount:]
- -[PSMMutableVMStats setPurgeableWiredCount:]
- -[PSMMutableVMStats setRealtimeCount:]
- -[PSMVMStats activeInternalCount]
- -[PSMVMStats executableCount]
- -[PSMVMStats inactiveInternalCount]
- -[PSMVMStats initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:pageinsDelta:executableCount:purgeablePageableCount:purgeableWiredCount:activeInternalCount:inactiveInternalCount:realtimeCount:]
- -[PSMVMStats pageinsDelta]
- -[PSMVMStats purgeablePageableCount]
- -[PSMVMStats purgeableWiredCount]
- -[PSMVMStats realtimeCount]
- GCC_except_table152
- GCC_except_table171
- GCC_except_table178
- GCC_except_table187
- GCC_except_table188
- GCC_except_table206
- GCC_except_table208
- GCC_except_table215
- GCC_except_table223
- GCC_except_table224
- GCC_except_table242
- GCC_except_table244
- GCC_except_table25
- GCC_except_table259
- GCC_except_table260
- GCC_except_table278
- GCC_except_table280
- GCC_except_table287
- GCC_except_table35
- GCC_except_table389
- GCC_except_table39
- GCC_except_table47
- GCC_except_table48
- GCC_except_table60
- GCC_except_table61
- GCC_except_table99
- _OUTLINED_FUNCTION_11
- __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE11target_typeEv
- __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE6targetERKSt9type_info
- __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
- __ZNKSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7__cloneEv
- __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE11target_typeEv
- __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE6targetERKSt9type_info
- __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
- __ZNKSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7__cloneEv
- __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE11target_typeEv
- __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE6targetERKSt9type_info
- __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7__cloneEPNS0_6__baseIS6_EE
- __ZNKSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7__cloneEv
- __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEE7destroyEv
- __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED0Ev
- __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED1Ev
- __ZNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEclEOmOS5_
- __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEE7destroyEv
- __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEED0Ev
- __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEED1Ev
- __ZNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEclEOmOS5_
- __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEE7destroyEv
- __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED0Ev
- __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED1Ev
- __ZNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEclEOmOS5_
- __ZTINSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
- __ZTINSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
- __ZTINSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
- __ZTIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7
- __ZTIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3
- __ZTIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5
- __ZTSNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
- __ZTSNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
- __ZTSNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
- __ZTSZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7
- __ZTSZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3
- __ZTSZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5
- __ZTVNSt3__110__function6__funcIZ108-[AFBBufferBuilder(PSMGpuPowerControllerStateEntry) psmCreateVectorOfGpuPowerControllerStateEntryFromArray:]E3$_7FvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEEE
- __ZTVNSt3__110__function6__funcIZ86-[AFBBufferBuilder(PSMGpuPerfStateEntry) psmCreateVectorOfGpuPerfStateEntryFromArray:]E3$_3FvmPN16PSMMediumCadence17GpuPerfStateEntryEEEE
- __ZTVNSt3__110__function6__funcIZ90-[AFBBufferBuilder(PSMGpuSwPerfStateEntry) psmCreateVectorOfGpuSwPerfStateEntryFromArray:]E3$_5FvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEEE
- ___block_descriptor_48_e8_32s40s_e39_v16?0"PSMMediumCadenceBufferBuilder"8l
- ___copy_helper_block_e8_32s40s
- ___destroy_helper_block_e8_32s40s
- _objc_msgSend$initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:pageinsDelta:executableCount:purgeablePageableCount:purgeableWiredCount:activeInternalCount:inactiveInternalCount:realtimeCount:
- _objc_msgSend$purgeablePageableCount
- _objc_msgSend$purgeableWiredCount
- _objc_msgSend$realtimeCount
- _objc_msgSend$setPurgeablePageableCount:
- _objc_msgSend$setPurgeableWiredCount:
- _objc_msgSend$setRealtimeCount:
CStrings:
+ "@\"PSMVMStatsExt1\""
+ "@32@0:8I16I20I24I28"
+ "@64@0:8I16I20I24I28I32I36I40I44I48I52I56I60"
+ "PSMImmutableVMStatsExt1"
+ "PSMMutableVMStatsExt1"
+ "PSMVMStatsExt1"
+ "Tr^{VMStats=IIIIIIIIIIII},R,N"
+ "Tr^{VMStatsExt1=IIII},R,N"
+ "^{VMStats=IIIIIIIIIIII}"
+ "^{VMStatsExt1=IIII}"
+ "_changeTypeVmStatsExt1"
+ "_replacementVmStatsExt1"
+ "initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:"
+ "initWithPageinsDelta:executableCount:activeInternalCount:inactiveInternalCount:"
+ "psmCreateVMStatsExt1FromVMStatsExt1:"
+ "psmCreateVectorOfVMStatsExt1FromArray:"
+ "psmCreateVectorOfVMStatsExt1WithCount:block:"
+ "r^{VMStats=IIIIIIIIIIII}"
+ "r^{VMStats=IIIIIIIIIIII}16@0:8"
+ "r^{VMStatsExt1=IIII}"
+ "r^{VMStatsExt1=IIII}16@0:8"
- "@92@0:8I16I20I24I28I32I36I40I44I48I52I56I60I64I68I72I76I80I84I88"
- "Tr^{VMStats=IIIIIIIIIIIIIIIIIII},R,N"
- "^{VMStats=IIIIIIIIIIIIIIIIIII}"
- "initWithActiveCount:speculativeCount:inactiveCount:freeCount:wireCount:compressorPageCount:internalPageCount:externalPageCount:totalUncompressedPagesInCompressor:swappedCount:swapCount:pageSharedRegionCount:pageinsDelta:executableCount:purgeablePageableCount:purgeableWiredCount:activeInternalCount:inactiveInternalCount:realtimeCount:"
- "purgeablePageableCount"
- "purgeableWiredCount"
- "r^{VMStats=IIIIIIIIIIIIIIIIIII}"
- "r^{VMStats=IIIIIIIIIIIIIIIIIII}16@0:8"
- "realtimeCount"
- "setPurgeablePageableCount:"
- "setPurgeableWiredCount:"
- "setRealtimeCount:"
```
