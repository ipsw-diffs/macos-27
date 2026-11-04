## com.apple.SafariServices

> `/System/Library/Frameworks/SafariServices.framework/Versions/A/XPCServices/com.apple.SafariServices.xpc/Contents/MacOS/com.apple.SafariServices`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA.__objc_const`

```diff

-7625.2.8.11.9
-  __TEXT.__text: 0x183c
-  __TEXT.__auth_stubs: 0x270
-  __TEXT.__objc_stubs: 0x520
+7626.1.12.11.4
+  __TEXT.__text: 0x1d60
+  __TEXT.__auth_stubs: 0x2a0
+  __TEXT.__objc_stubs: 0x640
   __TEXT.__objc_methlist: 0x44
   __TEXT.__const: 0x8
-  __TEXT.__gcc_except_tab: 0x2d0
-  __TEXT.__cstring: 0x40d
+  __TEXT.__gcc_except_tab: 0x384
+  __TEXT.__cstring: 0x4a0
   __TEXT.__objc_classname: 0x1e
   __TEXT.__objc_methtype: 0x8
-  __TEXT.__objc_methname: 0x397
-  __TEXT.__unwind_info: 0x140
-  __DATA_CONST.__const: 0x100
-  __DATA_CONST.__cfstring: 0xa0
+  __TEXT.__objc_methname: 0x494
+  __TEXT.__unwind_info: 0x168
+  __DATA_CONST.__const: 0x160
+  __DATA_CONST.__cfstring: 0xc0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x148
-  __DATA_CONST.__got: 0xd8
+  __DATA_CONST.__auth_got: 0x160
+  __DATA_CONST.__got: 0xf8
   __DATA.__objc_const: 0xc0
-  __DATA.__objc_selrefs: 0x148
+  __DATA.__objc_selrefs: 0x190
   __DATA.__bss: 0x10
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 27
-  Symbols:   76
-  CStrings:  79
+  Functions: 31
+  Symbols:   83
+  CStrings:  96
 
Symbols:
+ _NSPOSIXErrorDomain
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_WBSOpenURLsWithTopicPayload
+ _xpc_array_apply
+ _xpc_dictionary_get_array
+ _xpc_string_get_string_ptr
CStrings:
+ ""
+ "B24@?0Q8@\"NSObject<OS_xpc_object>\"16"
+ "URLWithString:"
+ "addObject:"
+ "archivedDataWithRootObject:requiringSecureCoding:error:"
+ "array"
+ "com.apple.private.safari.can-open-urls-with-topic"
+ "error"
+ "errorWithDomain:code:userInfo:"
+ "initWithURLs:topic:"
+ "invalidPayloadErrorWithDescription:"
+ "open-urls-with-topic"
+ "openInSafariWithCompletionHandler:"
+ "topic"
+ "urls"
+ "v20@?0B8@\"NSError\"12"
+ "validationFailureDescriptionForURLs:topic:"
```
