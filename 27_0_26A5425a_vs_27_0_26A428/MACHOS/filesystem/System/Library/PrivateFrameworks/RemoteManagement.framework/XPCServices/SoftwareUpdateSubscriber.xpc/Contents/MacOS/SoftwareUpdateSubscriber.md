## SoftwareUpdateSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/SoftwareUpdateSubscriber.xpc/Contents/MacOS/SoftwareUpdateSubscriber`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 2718.0.18.0.0
-  __TEXT.__text: 0x5c08
+  __TEXT.__text: 0x5b60
   __TEXT.__auth_stubs: 0x180
   __TEXT.__objc_stubs: 0xcc0
   __TEXT.__objc_methlist: 0x568

   __TEXT.__objc_methtype: 0x531
   __TEXT.__const: 0x28
   __TEXT.__oslogstring: 0x797
-  __TEXT.__unwind_info: 0xd8
+  __TEXT.__unwind_info: 0x100
   __DATA_CONST.__const: 0x30
   __DATA_CONST.__cfstring: 0x6c0
   __DATA_CONST.__objc_classlist: 0x40
Functions:
~ +[RMModelStatusSoftwareUpdateBetaEnrollment supportedOS] : 532 -> 520
~ +[RMModelStatusSoftwareUpdateDeviceID supportedOS] : 776 -> 764
~ -[SoftwareUpdateAdapter configurationClasses] : 132 -> 120
~ -[SoftwareUpdateAdapter allDeclarationKeysForScope:error:] : 2336 -> 2324
~ -[SoftwareUpdateAdapter declarationKeyForConfiguration:] : 156 -> 144
~ +[SoftwareUpdateApplicator supportedConfigurationTypes] : 116 -> 104
~ -[SoftwareUpdateCombinedAdapter _recommendationCadenceLocalizedStringForString:] : 264 -> 252
~ -[SoftwareUpdateCombinedAdapter declarationKeyForConfiguration:] : 60 -> 48
~ -[SoftwareUpdateCombinedAdapter _localizedStringForRMModelSettingsState:] : 264 -> 252
~ +[SoftwareUpdateSettingsApplicator supportedConfigurationTypes] : 116 -> 104
~ +[SoftwareUpdateStatus supportedStatusKeys] : 248 -> 236
~ +[SoftwareUpdateStatus supportedStatusClasses] : 232 -> 220
~ ___copy_helper_block_e8_32s40b : 72 -> 60
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
```
