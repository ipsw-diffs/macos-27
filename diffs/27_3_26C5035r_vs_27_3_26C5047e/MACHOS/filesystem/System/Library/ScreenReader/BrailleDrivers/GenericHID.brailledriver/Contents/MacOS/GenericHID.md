## GenericHID

> `/System/Library/ScreenReader/BrailleDrivers/GenericHID.brailledriver/Contents/MacOS/GenericHID`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1050.3.12.0.0
-  __TEXT.__text: 0x57cc
+1050.3.22.0.0
+  __TEXT.__text: 0x57bc
   __TEXT.__auth_stubs: 0x350
   __TEXT.__objc_stubs: 0x1020
   __TEXT.__objc_methlist: 0x6fc

   __TEXT.__objc_classname: 0xa6
   __TEXT.__objc_methname: 0x1161
   __TEXT.__objc_methtype: 0x335
-  __TEXT.__oslogstring: 0x5a8
+  __TEXT.__oslogstring: 0x59c
   __TEXT.__unwind_info: 0x160
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__cfstring: 0x200
Functions:
~ sub_2888 : 1680 -> 1664
CStrings:
+ "Enqueuing router event - index: %u, isDown: %u"
- "Received HID input callback - usagePage: 0x%x, usage: 0x%x"
```
