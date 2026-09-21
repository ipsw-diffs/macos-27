## UIIntelligenceIntents

> `/System/Library/PrivateFrameworks/UIIntelligenceIntents.framework/Versions/A/UIIntelligenceIntents`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-9127.1.5.0.0
-  __TEXT.__text: 0x2e3ac
+9127.1.7.0.0
+  __TEXT.__text: 0x2e3a4
   __TEXT.__objc_methlist: 0x1ac
   __TEXT.__const: 0x42e0
   __TEXT.__constg_swiftt: 0x998

   __AUTH_CONST.__objc_const: 0x2a0
   __AUTH_CONST.__auth_got: 0x978
   __AUTH.__data: 0x1b8
-  __DATA.__data: 0xcd0
-  __DATA.__bss: 0x5d90
+  __DATA.__data: 0xc78
+  __DATA.__bss: 0x5c10
   __DATA.__common: 0x330
+  __DATA_DIRTY.__data: 0x58
+  __DATA_DIRTY.__bss: 0x180
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
Functions:
~ sub_2a66904ac -> sub_2acef6594 : 2408 -> 2400
CStrings:
+ "Present Writing Tools result "
+ "The text to be inserted into the app’s active text field."
+ "Window number (stringified) of the window that hosts the target text field. When provided on macOS, the bridge activates that window (`makeKeyAndOrderFront:`) before starting Writing Tools so AppKit’s default `keyWindow.firstResponder` coordinator walk lands on the intended field — necessary when a transient popover has stolen key focus."
- "Present writing tools result "
- "The text to be inserted into the app's active text field."
- "Window number (stringified) of the window that hosts the target text field. When provided on macOS, the bridge activates that window (`makeKeyAndOrderFront:`) before starting Writing Tools so AppKit's default `keyWindow.firstResponder` coordinator walk lands on the intended field — necessary when a transient popover has stolen key focus."
```
