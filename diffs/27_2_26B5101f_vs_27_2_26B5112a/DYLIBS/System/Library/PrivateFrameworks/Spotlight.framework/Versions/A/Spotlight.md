## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Versions/A/Spotlight`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2465.1.7.0.0
-  __TEXT.__text: 0xe71d8
+2465.1.9.0.0
+  __TEXT.__text: 0xe6f38
   __TEXT.__objc_methlist: 0x5724
   __TEXT.__const: 0x2640
   __TEXT.__gcc_except_tab: 0x43a0
   __TEXT.__cstring: 0x6ee1
-  __TEXT.__oslogstring: 0x5d5f
+  __TEXT.__oslogstring: 0x5c3f
   __TEXT.__ustring: 0x32
   __TEXT.__constg_swiftt: 0xa3c
   __TEXT.__swift5_typeref: 0xe89

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4858
+  __DATA_CONST.__objc_selrefs: 0x4850
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0xa18
   __DATA_CONST.__got: 0x15f8
   __AUTH_CONST.__const: 0x49e8
-  __AUTH_CONST.__cfstring: 0x6fe0
+  __AUTH_CONST.__cfstring: 0x6fc0
   __AUTH_CONST.__objc_const: 0x8550
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x8d0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3508
-  Symbols:   6956
-  CStrings:  1533
+  Functions: 3507
+  Symbols:   6953
+  CStrings:  1528
 
Symbols:
+ +[SPKGenerativeSearchMailQueryBase appScopeBundleIdentifiers]
+ +[SPKGenerativeSearchSiriTranscriptQuery appScopeBundleIdentifiers]
+ _objc_msgSend$isAllowedUnderAppScopeInContext:
- -[SPSearchQueryContext(GenerativeSearch) appScopeBundleIdentifier]
- -[SPSearchQueryContext(GenerativeSearch) appScopeEntity]
- -[SPSearchQueryContext(GenerativeSearch) isAppScopedSearch]
- _objc_msgSend$appScopeEntity
- _objc_msgSend$effectiveBundleIdentifier
- _objc_msgSend$isAppScopedSearch
CStrings:
+ "(global)"
+ "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled: scope=%{public}@"
- "(nil)"
- "(null)"
- "[qid=%lu][GenerativeSearch][AppScope] Bundle ID: %{public}@"
- "[qid=%lu][GenerativeSearch][AppScope] Detected app-scoped search"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Disabled: app-scoped to %{public}@"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled for Mail app-scoped search"
- "[qid=%lu][SPKGenerativeSearchMailQuery] Enabled: using GenerativeSearch for mail"
```
