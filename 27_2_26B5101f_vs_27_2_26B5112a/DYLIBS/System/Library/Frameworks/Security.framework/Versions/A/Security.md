## Security

> `/System/Library/Frameworks/Security.framework/Versions/A/Security`

```diff

-62460.40.74.0.0
-  __TEXT.__text: 0x34c6a4
+62460.40.78.0.0
+  __TEXT.__text: 0x34c6c0
   __TEXT.__objc_methlist: 0x67cc
-  __TEXT.__const: 0x266ae
+  __TEXT.__const: 0x266ce
   __TEXT.__dlopen_cstrs: 0xb5
   __TEXT.__cstring: 0x2aa85
   __TEXT.__gcc_except_tab: 0x2f424

   - /usr/lib/libxar.1.dylib
   - /usr/lib/libz.1.dylib
   Functions: 12743
-  Symbols:   26243
+  Symbols:   26244
   CStrings:  10098
 
Symbols:
+ SecKeyCopySystemKey.gsmakObjectIDBytes
Functions:
~ sub_184f26028 -> sub_184f2d028 : 60 -> 64
~ _SecKeyCopySystemKey : 684 -> 708
```
