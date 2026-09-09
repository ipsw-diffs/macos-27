## AppleHIDALS

> `/System/Library/Extensions/AppleHIDALSService.kext/Contents/PlugIns/AppleHIDALS.plugin/Contents/MacOS/AppleHIDALS`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 2300.1.2.0.0
-  __TEXT.__text: 0xcef8
+  __TEXT.__text: 0xce50
   __TEXT.__auth_stubs: 0x910
   __TEXT.__gcc_except_tab: 0x218
   __TEXT.__const: 0xde
   __TEXT.__cstring: 0x6a6
   __TEXT.__oslogstring: 0x1490
-  __TEXT.__unwind_info: 0x1f8
+  __TEXT.__unwind_info: 0x3d0
   __DATA_CONST.__const: 0x1f8
   __DATA_CONST.__cfstring: 0xb80
   __DATA_CONST.__auth_got: 0x490
Functions:
~ __ZN17HidPluginIUnknown13factoryAddRefEv : 140 -> 128
~ __ZN17HidPluginIUnknown14factoryReleaseEv : 156 -> 144
~ __Z30SystemPowerStateUpdateCallbackPvjjS_ : 416 -> 404
~ __ZN11AppleUSBALS31dispatchAmbientLightSensorEventEdydddd : 348 -> 336
~ _IOHIDPlugInFactory : 156 -> 144
~ __ZN11AppleUSBALS20setDefaultPropertiesEv : 144 -> 132
~ __ZN11AppleUSBALSD0Ev : 56 -> 44
~ __ZN11AppleUSBALS19setIntValueForUsageEjjl : 72 -> 60
~ __ZN11AppleUSBALS21getFloatValueForUsageEjjPf : 96 -> 84
~ __ZN11AppleUSBALS19getIntValueForUsageEjjPl : 96 -> 84
~ __ZN11AppleUSBALS22synchronizePreferencesEv : 96 -> 84
~ __ZN11AppleUSBALS14getScaledValueEdP14__IOHIDElement : 184 -> 172
~ __ZN11AppleUSBALS21setFloatValueForUsageEjjd : 80 -> 68
~ sub_c058 -> sub_bfbc : 28 -> 16
```
