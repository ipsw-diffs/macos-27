## CardDAVPlugin

> `/System/Library/Address Book Plug-Ins/CardDAVPlugin.sourcebundle/Contents/MacOS/CardDAVPlugin`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1119.200.1.0.0
-  __TEXT.__text: 0x489a0
+1119.300.1.0.0
+  __TEXT.__text: 0x48c2c
   __TEXT.__auth_stubs: 0x600
-  __TEXT.__objc_stubs: 0x8100
-  __TEXT.__objc_methlist: 0x2cf4
+  __TEXT.__objc_stubs: 0x8120
+  __TEXT.__objc_methlist: 0x2cfc
   __TEXT.__const: 0x138
   __TEXT.__gcc_except_tab: 0x2634
   __TEXT.__cstring: 0x2bd2
-  __TEXT.__oslogstring: 0x90e9
+  __TEXT.__oslogstring: 0x918c
   __TEXT.__objc_classname: 0x4a3
-  __TEXT.__objc_methname: 0x905c
+  __TEXT.__objc_methname: 0x9081
   __TEXT.__objc_methtype: 0x1480
-  __TEXT.__unwind_info: 0x1358
+  __TEXT.__unwind_info: 0x1360
   __DATA_CONST.__const: 0x818
   __DATA_CONST.__cfstring: 0x3500
   __DATA_CONST.__objc_classlist: 0xe8

   __DATA_CONST.__auth_got: 0x310
   __DATA_CONST.__got: 0x790
   __DATA.__objc_const: 0x3c68
-  __DATA.__objc_selrefs: 0x2738
+  __DATA.__objc_selrefs: 0x2740
   __DATA.__objc_ivar: 0x29c
   __DATA.__objc_data: 0x910
   __DATA.__data: 0x870

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 1233
-  Symbols:   2968
-  CStrings:  2871
+  Functions: 1236
+  Symbols:   2972
+  CStrings:  2873
 
Symbols:
+ -[CardDAVSource refreshUserNameFromACAccountIfNeeded]
+ GCC_except_table129
+ GCC_except_table131
+ GCC_except_table143
+ GCC_except_table165
+ GCC_except_table168
+ GCC_except_table176
+ GCC_except_table179
+ GCC_except_table184
+ GCC_except_table188
+ GCC_except_table191
+ _CDXRediscoveryActionFor
+ _CDXShouldRefreshUserName
+ _objc_msgSend$refreshUserNameFromACAccountIfNeeded
- GCC_except_table127
- GCC_except_table130
- GCC_except_table142
- GCC_except_table163
- GCC_except_table167
- GCC_except_table174
- GCC_except_table177
- GCC_except_table183
- GCC_except_table187
- GCC_except_table190
CStrings:
+ "-applyOrRevertAction - url or username has changed (urlChanged %@, userNameChanged %@): url was %@ now %@"
+ "-refreshUserNameFromACAccountIfNeeded: cached username %@ no longer matches live account username %@; updating"
+ "refreshUserNameFromACAccountIfNeeded"
- "-applyOrRevertAction - url has changed: was %@ now %@"
```
