## OSUpdate

> `/System/Library/PrivateFrameworks/OSUpdate.framework/Versions/A/OSUpdate`

```diff

 2412.1.1.0.0
-  __TEXT.__text: 0x92abc
+  __TEXT.__text: 0x92a98
   __TEXT.__objc_methlist: 0x7b94
   __TEXT.__const: 0x201
-  __TEXT.__cstring: 0x813d
+  __TEXT.__cstring: 0x8138
   __TEXT.__oslogstring: 0xdc6b
   __TEXT.__gcc_except_tab: 0x1b34
   __TEXT.__ustring: 0xc

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3350
-  Symbols:   7225
+  Functions: 3349
+  Symbols:   7226
   CStrings:  2241
 
Symbols:
+ _OUTLINED_FUNCTION_19
+ _OUTLINED_FUNCTION_29
- _OUTLINED_FUNCTION_30
Functions:
- _OUTLINED_FUNCTION_0
~ +[SUOSUUpdatesAvailablePolicy _reminderDaysForCount:finalNotification:] : 124 -> 96
~ -[SUOSUProduct initWithSUDescriptor:].cold.1 : 84 -> 88
~ -[SUOSUProduct splatRevoked].cold.1 : 128 -> 112
~ -[SUOSUProduct semiSplatActivated].cold.1 : 108 -> 112
~ -[SUOSUProduct semiSplatActivated].cold.2 : 84 -> 108
~ -[SUOSUProduct semiSplatEnabled].cold.1 : 112 -> 116
CStrings:
+ "macOS 27 Golden Gate"
- "macOS 27 Golden Gate Beta"
```
