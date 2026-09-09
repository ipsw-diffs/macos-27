## NRDUpdated

> `/usr/libexec/NRDUpdated`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2718.0.18.0.0
-  __TEXT.__text: 0xb190
+  __TEXT.__text: 0xaf44
   __TEXT.__auth_stubs: 0x4b0
   __TEXT.__objc_stubs: 0x1b80
   __TEXT.__objc_methlist: 0xc54

   __TEXT.__objc_classname: 0x204
   __TEXT.__objc_methtype: 0x85f
   __TEXT.__gcc_except_tab: 0x1a0
-  __TEXT.__unwind_info: 0x350
+  __TEXT.__unwind_info: 0x468
   __DATA_CONST.__const: 0x740
   __DATA_CONST.__cfstring: 0xe20
   __DATA_CONST.__objc_classlist: 0x30
Functions:
~ +[NRDUpdateDaemonServerImpl sharedInstance] : 68 -> 56
~ ___43+[NRDUpdateDaemonServerImpl sharedInstance]_block_invoke : 88 -> 76
~ ___51-[NRDUpdateDaemonServerImpl updateHelper:callback:]_block_invoke : 232 -> 220
~ ___copy_helper_block_e8_32s40s48b : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48s : 68 -> 56
~ -[NRDUpdateDaemonServerImpl .cxx_destruct] : 104 -> 92
~ -[NRDUpdateDCore _infoClassForAction:] : 80 -> 68
~ ___44-[NRDUpdateDCore registerUpdatedFSMhandlers]_block_invoke_2 : 192 -> 180
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[NRDUpdateDCore findLocalBrainAsset] : 780 -> 768
~ -[NRDUpdateDCore cleanBeforeScan] : 64 -> 52
~ ___copy_helper_block_e8_32s40s48s : 68 -> 56
~ -[NRDUpdateDCore .cxx_destruct] : 284 -> 272
~ _OUTLINED_FUNCTION_1 : 28 -> 16
~ _OUTLINED_FUNCTION_3 : 28 -> 16
~ _nrdSharedLogger : 68 -> 56
~ ___nrdSharedLogger_block_invoke : 72 -> 60
~ -[NRDRemoteableBlock .cxx_destruct] : 68 -> 56
~ -[NRDBackgroundActivitySchedulerServerImpl identifier:] : 116 -> 104
~ -[NRDBackgroundActivitySchedulerServerImpl qualityOfService:] : 100 -> 88
~ -[NRDBackgroundActivitySchedulerServerImpl repeats:] : 100 -> 88
~ -[NRDBackgroundActivitySchedulerServerImpl interval:] : 96 -> 84
~ -[NRDBackgroundActivitySchedulerServerImpl tolerance:] : 96 -> 84
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ -[NRDBackgroundActivitySchedulerServerImpl shouldDefer:] : 100 -> 88
~ -[NRDBackgroundActivitySchedulerServerImpl preregistered:] : 100 -> 88
~ -[NRDBackgroundActivitySchedulerServerImpl delay:] : 96 -> 84
~ -[NRDBackgroundActivitySchedulerServerImpl _setAdditionalXPCActivityProperties:] : 76 -> 64
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[NRDBackgroundActivitySchedulerServerImpl _isAppRefresh:] : 100 -> 88
~ -[NRDUpdateBrainClientImpl _invalidateConnection] : 84 -> 72
~ ___copy_helper_block_e8_32r40r : 80 -> 68
~ ___destroy_helper_block_e8_32r40r : 68 -> 56
~ -[NRDUpdateBrainClientImpl connectToServerIfNecessary] : 84 -> 72
~ -[NRDUpdateBrainClientImpl noteConnectionDropped] : 60 -> 48
~ ___copy_helper_block_e8_32o40b48r : 96 -> 84
~ ___destroy_helper_block_e8_32o40b48r : 80 -> 68
~ ___copy_helper_block_e8_32o40o48o56b64r : 128 -> 116
~ ___destroy_helper_block_e8_32o40o48o56b64r : 104 -> 92
~ ___copy_helper_block_e8_32o40o48b56r : 112 -> 100
~ ___destroy_helper_block_e8_32o40o48b56r : 92 -> 80
~ ___copy_helper_block_e8_32b40r : 80 -> 68
~ ___destroy_helper_block_e8_32b40r : 68 -> 56
~ ___copy_helper_block_e8_32o40b : 80 -> 68
~ ___destroy_helper_block_e8_32o40b : 68 -> 56
~ ___75-[NRDUpdateBrainClientImpl downloadNeRDUpdate:options:progress:completion:]_block_invoke_3 : 84 -> 72
~ ___74-[NRDUpdateBrainClientImpl installNeRDUpdate:options:progress:completion:]_block_invoke_3 : 84 -> 72
CStrings:
+ "18:34:46"
+ "Aug  8 2026"
- "02:55:06"
- "Aug 10 2026"
```
