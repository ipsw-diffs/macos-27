## devmodectl

> `/usr/bin/devmodectl`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 1171.0.12.0.0
-  __TEXT.__text: 0x18ec
+  __TEXT.__text: 0x1874
   __TEXT.__auth_stubs: 0x200
   __TEXT.__objc_stubs: 0x2c0
   __TEXT.__objc_methlist: 0x80

   __TEXT.__objc_classname: 0xa
   __TEXT.__objc_methtype: 0x8d
   __TEXT.__const: 0x180
-  __TEXT.__unwind_info: 0xb8
+  __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__const: 0x368
   __DATA_CONST.__cfstring: 0x300
   __DATA_CONST.__objc_classlist: 0x8
Functions:
~ _getAMDErrorString : 40 -> 28
~ _getDictionaryFromConnection : 84 -> 72
~ +[DeviceRef fromMobileDevice:] : 112 -> 100
~ -[DeviceRef connect] : 40 -> 28
~ -[DeviceRef startSession] : 40 -> 28
~ -[DeviceRef udid] : 44 -> 32
~ -[DeviceRef .cxx_destruct] : 68 -> 56
~ _device_callback : 892 -> 880
~ _OUTLINED_FUNCTION_0 : 32 -> 20
~ _device_callback : 1024 -> 1012
```
