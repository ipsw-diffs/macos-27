## http

> `/System/Library/Filesystems/NetFSPlugins/http.bundle/Contents/MacOS/http`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-413.40.2.0.0
-  __TEXT.__text: 0x3eec
-  __TEXT.__auth_stubs: 0x710
-  __TEXT.__cstring: 0x11f4
+413.60.1.0.1
+  __TEXT.__text: 0x3ea8
+  __TEXT.__auth_stubs: 0x720
+  __TEXT.__cstring: 0x1242
   __TEXT.__unwind_info: 0xd0
   __DATA_CONST.__cfstring: 0x640
-  __DATA_CONST.__auth_got: 0x388
+  __DATA_CONST.__auth_got: 0x390
   __DATA_CONST.__got: 0xe0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA.__data: 0x70

   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
   - /usr/lib/libSystem.B.dylib
   Functions: 25
-  Symbols:   163
-  CStrings:  177
+  Symbols:   164
+  CStrings:  179
 
Symbols:
+ _strpbrk
Functions:
~ sub_1ab4 : 3012 -> 2944
CStrings:
+ ",="
+ "WebDAV AttemptMount: ignoring volume name with option separator characters"
```
