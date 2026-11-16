## Exchange

> `/System/Library/Address Book Plug-Ins/Exchange.sourcebundle/Contents/MacOS/Exchange`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-2768.300.31.0.0
-  __TEXT.__text: 0xc15d4
-  __TEXT.__auth_stubs: 0x2770
+2768.300.51.0.0
+  __TEXT.__text: 0xc1a28
+  __TEXT.__auth_stubs: 0x2780
   __TEXT.__objc_stubs: 0x7240
   __TEXT.__objc_methlist: 0x1ef4
   __TEXT.__cstring: 0x28c5
   __TEXT.__objc_classname: 0x8a7
-  __TEXT.__const: 0x2c68
-  __TEXT.__oslogstring: 0x8ade
+  __TEXT.__const: 0x2a58
+  __TEXT.__oslogstring: 0x8b9e
   __TEXT.__objc_methtype: 0x868
   __TEXT.__gcc_except_tab: 0xdbc
   __TEXT.__objc_methname: 0x68d1
   __TEXT.__ustring: 0x172
-  __TEXT.__constg_swiftt: 0x11a8
-  __TEXT.__swift5_typeref: 0x1320
-  __TEXT.__swift5_reflstr: 0xc94
-  __TEXT.__swift5_fieldmd: 0x11a4
+  __TEXT.__constg_swiftt: 0x1130
+  __TEXT.__swift5_typeref: 0x12cc
+  __TEXT.__swift5_reflstr: 0xc54
+  __TEXT.__swift5_fieldmd: 0x1150
   __TEXT.__swift5_capture: 0x490
-  __TEXT.__swift5_types: 0x154
+  __TEXT.__swift5_types: 0x148
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x2c
   __TEXT.__swift_as_cont: 0x5c
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_mpenum: 0x78
   __TEXT.__swift5_protos: 0x3c
-  __TEXT.__swift5_proto: 0x130
-  __TEXT.__swift5_assocty: 0xf0
-  __TEXT.__unwind_info: 0x1ce8
+  __TEXT.__swift5_proto: 0x124
+  __TEXT.__swift5_assocty: 0xa8
+  __TEXT.__unwind_info: 0x1c98
   __TEXT.__eh_frame: 0x1270
-  __DATA_CONST.__const: 0x3be0
+  __DATA_CONST.__const: 0x3b40
   __DATA_CONST.__cfstring: 0x1b40
   __DATA_CONST.__objc_classlist: 0x180
   __DATA_CONST.__objc_catlist: 0x20

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x98
-  __DATA_CONST.__auth_got: 0x13c8
-  __DATA_CONST.__got: 0x1520
-  __DATA_CONST.__auth_ptr: 0x588
+  __DATA_CONST.__auth_got: 0x13d0
+  __DATA_CONST.__got: 0x14e0
+  __DATA_CONST.__auth_ptr: 0x590
   __DATA.__objc_const: 0x2df8
   __DATA.__objc_selrefs: 0x2108
   __DATA.__objc_ivar: 0xfc
   __DATA.__objc_data: 0x15e8
-  __DATA.__data: 0x1d60
+  __DATA.__data: 0x1c90
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1e90
+  __DATA.__bss: 0x1d10
   __DATA.__common: 0xd0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2014
+  Functions: 1981
   Symbols:   768
-  CStrings:  2204
+  CStrings:  2206
 
CStrings:
+ "Conversion: mapping fetch failed: %{public}s — EWS sync state not cleared"
+ "Conversion: no ids to rewrite; cleared the EWS sync state"
+ "Conversion: save failed clearing the EWS sync state: %{public}s — rolling back"
+ "No Graph field for update op, the edit won't be pushed: %{public}s.%{public}s"
+ "No edited fields for update-contact uid=%{public}s — sending an empty body"
+ "← %{public}ld subscription(s) visible"
+ "→ GET /subscriptions (reap, keeping %{public}s)"
+ "→ GET /subscriptions/getVapidPublicKey"
+ "→ delete subscription %{public}s"
+ "→ renew subscription %{public}s"
- "No Graph field for update op %{public}s.%{public}s"
- "No edited fields for update-contact uid=%{public}s — sending without clears"
- "could not encode the renewal body for %{public}s"
- "← %{public}ld subscription(s) visible on beta"
- "→ GET /beta/subscriptions (reap, keeping %{public}s)"
- "→ GET /beta/subscriptions/getVapidPublicKey"
- "→ delete subscription %{public}s (beta)"
- "→ renew subscription %{public}s (beta)"
```
