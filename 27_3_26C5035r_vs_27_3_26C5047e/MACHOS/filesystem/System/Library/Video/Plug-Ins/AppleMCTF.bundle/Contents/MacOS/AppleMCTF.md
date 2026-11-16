## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-913.63.1.0.0
-  __TEXT.__text: 0x88e80
+913.71.1.0.0
+  __TEXT.__text: 0x88f18
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x28d9b
+  __TEXT.__cstring: 0x28dcb
   __TEXT.__const: 0x22aa8
   __TEXT.__gcc_except_tab: 0x62c
   __TEXT.__objc_methname: 0xb
-  __TEXT.__unwind_info: 0xbb8
+  __TEXT.__unwind_info: 0xbb0
   __DATA_CONST.__const: 0x5430
   __DATA_CONST.__cfstring: 0x980
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libobjc.A.dylib
   Functions: 676
   Symbols:   346
-  CStrings:  3474
+  CStrings:  3475
 
Functions:
~ sub_ef8 : 4856 -> 4884
~ sub_21f0 -> sub_220c : 4588 -> 4616
~ sub_33dc -> sub_3414 : 7120 -> 7148
~ sub_35728 -> sub_3577c : 1008 -> 1004
~ sub_480e4 -> sub_48134 : 11248 -> 11256
~ sub_4c5c8 -> sub_4c620 : 7768 -> 7784
~ sub_79764 -> sub_797cc : 756 -> 800
~ sub_7ccac -> sub_7cd40 : 40 -> 44
CStrings:
+ "01:04:57"
+ "913.71.1"
+ "MachThreadPriorityForThreadEmittingFrames = %d\n"
+ "Nov 10 2026"
- "01:26:18"
- "913.63.1"
- "Oct 30 2026"
```
