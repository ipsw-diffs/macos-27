## Erase Assistant

> `/System/Library/CoreServices/Erase Assistant.app/Contents/MacOS/Erase Assistant`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-285.1.3.0.0
-  __TEXT.__text: 0xe3ec
+285.1.4.0.0
+  __TEXT.__text: 0xe70c
   __TEXT.__auth_stubs: 0x3d0
-  __TEXT.__objc_stubs: 0x3000
-  __TEXT.__objc_methlist: 0x1238
+  __TEXT.__objc_stubs: 0x30a0
+  __TEXT.__objc_methlist: 0x1208
   __TEXT.__const: 0xa8
-  __TEXT.__cstring: 0xe67
+  __TEXT.__cstring: 0xec3
   __TEXT.__oslogstring: 0x937
   __TEXT.__objc_classname: 0x2de
-  __TEXT.__objc_methname: 0x386c
-  __TEXT.__objc_methtype: 0xb3c
+  __TEXT.__objc_methname: 0x388c
+  __TEXT.__objc_methtype: 0xb32
   __TEXT.__gcc_except_tab: 0x78
   __TEXT.__dlopen_cstrs: 0x64
-  __TEXT.__unwind_info: 0x448
+  __TEXT.__unwind_info: 0x440
   __DATA_CONST.__const: 0x568
-  __DATA_CONST.__cfstring: 0x12a0
+  __DATA_CONST.__cfstring: 0x1320
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__auth_got: 0x1f8
-  __DATA_CONST.__got: 0x2e8
-  __DATA.__objc_const: 0x1f98
-  __DATA.__objc_selrefs: 0xfd0
-  __DATA.__objc_ivar: 0x100
+  __DATA_CONST.__got: 0x310
+  __DATA.__objc_const: 0x1f68
+  __DATA.__objc_selrefs: 0xff0
+  __DATA.__objc_ivar: 0xfc
   __DATA.__objc_data: 0x5f0
   __DATA.__data: 0x480
   __DATA.__bss: 0x28

   - /System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 337
-  Symbols:   171
-  CStrings:  980
+  Functions: 333
+  Symbols:   176
+  CStrings:  985
 
Symbols:
+ _NSFontAttributeName
+ _NSFontTextStyleCaption1
+ _NSForegroundColorAttributeName
+ _NSLinkAttributeName
+ _OBJC_CLASS_$_NSMutableAttributedString
CStrings:
+ " %@"
+ "OVERWRITE_STORAGE_CAPTION"
+ "OVERWRITE_STORAGE_LEARN_MORE"
+ "OVERWRITE_STORAGE_LEARN_MORE_URL"
+ "addAttributes:range:"
+ "initWithString:attributes:"
+ "rangeOfString:options:"
+ "setAllowsEditingTextAttributes:"
+ "setAttributedStringValue:"
+ "setSelectable:"
+ "stringByAppendingFormat:"
+ "wrappingLabelWithString:"
- "@\"NSView\""
- "T@\"NSView\",&,V_bottomLeadingAccessoryView"
- "_bottomLeadingAccessoryView"
- "bottomLeadingAccessoryView"
- "centerYAnchor"
- "removeFromSuperview"
- "setBottomLeadingAccessoryView:"
```
