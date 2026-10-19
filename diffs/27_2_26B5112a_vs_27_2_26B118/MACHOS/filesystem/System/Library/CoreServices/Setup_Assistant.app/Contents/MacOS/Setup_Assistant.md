## Setup Assistant

> `/System/Library/CoreServices/Setup Assistant.app/Contents/MacOS/Setup Assistant`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 7550.2.3.0.0
-  __TEXT.__text: 0x19c4e8
+  __TEXT.__text: 0x19c4d8
   __TEXT.__auth_stubs: 0x2db0
   __TEXT.__objc_stubs: 0x26cc0
   __TEXT.__objc_methlist: 0x16d3c
Functions:
~ sub_10011aa90 : 896 -> 884
~ sub_10016d864 -> sub_10016d858 : 596 -> 592
CStrings:
+ "macOS 27 Golden Gate"
- "macOS 27 Golden Gate Beta"
```
