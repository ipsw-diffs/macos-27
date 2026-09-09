## SCSITaskLib

> `/System/Library/Extensions/IOSCSIArchitectureModelFamily.kext/Contents/PlugIns/SCSITaskUserClient.kext/Contents/PlugIns/SCSITaskLib.plugin/Contents/MacOS/SCSITaskLib`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 565.0.1.0.0
-  __TEXT.__text: 0x30ec
+  __TEXT.__text: 0x3054
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__gcc_except_tab: 0x90
   __TEXT.__cstring: 0xb5
   __TEXT.__const: 0x54
-  __TEXT.__unwind_info: 0x1f8
+  __TEXT.__unwind_info: 0x268
   __DATA_CONST.__const: 0x328
   __DATA_CONST.__cfstring: 0x100
   __DATA_CONST.__auth_got: 0x180
Functions:
~ __ZN24MMCDeviceUserClientClassD2Ev : 88 -> 76
~ __ZN24MMCDeviceUserClientClassD0Ev : 56 -> 44
~ __ZN13SCSITaskClassD0Ev : 56 -> 44
~ __ZN19SCSITaskDeviceClassD2Ev : 132 -> 120
~ __ZN19SCSITaskDeviceClassD0Ev : 56 -> 44
~ sub_27b4 -> sub_2778 : 32 -> 20
~ _SCSITaskLibFactory : 268 -> 244
~ __ZN16SCSITaskIUnknown14sFactoryAddRefEv : 152 -> 140
~ __ZN16SCSITaskIUnknown15sFactoryReleaseEv : 176 -> 164
~ __ZN13SCSITaskClass21sAbortAndReleaseTasksEPKvPv : 132 -> 120
~ __ZN13SCSITaskClass18SetSenseDataBufferEPvh : 160 -> 152
~ __ZN13SCSITaskClass15ResetForNewTaskEv : 180 -> 168
```
