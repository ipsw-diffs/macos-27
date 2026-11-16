## swift-backtrace

> `/usr/libexec/swift/swift-backtrace`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-6.4.2.1.9
-  __TEXT.__text: 0x22b70
+6.4.4.3.15
+  __TEXT.__text: 0x22d44
   __TEXT.__auth_stubs: 0x1180
   __TEXT.__const: 0x72e
   __TEXT.__gcc_except_tab: 0x648

   __TEXT.__swift5_proto: 0x44
   __TEXT.__swift5_types: 0x48
   __TEXT.__unwind_info: 0x518
-  __TEXT.__eh_frame: 0xb60
+  __TEXT.__eh_frame: 0xb70
   __DATA_CONST.__const: 0x1328
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ _$s32swift_backtrace_macosx_arm64e_x114SwiftBacktraceV16interactWithUseryyFZ : 27744 -> 27756
~ _$s32swift_backtrace_macosx_arm64e_x16TargetC12fetchThreads5limit3top5cache11symbolicateySiSg_SiSbAA14SwiftBacktraceV13SymbolicationOtF : 7300 -> 7344
~ _$s32swift_backtrace_macosx_arm64e_x16TargetC14redoBacktraces5limit3top5cache11symbolicateySiSg_SiSbAA14SwiftBacktraceV13SymbolicationOtF : 5152 -> 5192
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCs5UInt8V_Tt1gq5 : 112 -> 124
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSnySiG_Tgq5 : 256 -> 280
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF7Runtime8CrashLogV5FrameVys6UInt64V_G_Tg5 : 452 -> 480
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSs_Tg5 : 264 -> 288
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF32swift_backtrace_macosx_arm64e_x112TargetThreadV_Tg5Tm : 432 -> 476
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5 : 264 -> 288
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSpys4Int8VGSg_Tg5 : 256 -> 280
~ _$ss22_ContiguousArrayBufferV19_uninitializedCount15minimumCapacityAByxGSi_SitcfCSi_Tt1g5 : 128 -> 152
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSS_Tg5 : 264 -> 288
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSi_Tg5 : 256 -> 280
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF7Runtime8CrashLogV6ThreadVys6UInt64V_G_Tg5Tm : 444 -> 496
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF7Runtime9BacktraceV5ImageV_Tg5Tm : 432 -> 476
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFSpys4Int8VGSg_Tg5 : 256 -> 280
```
