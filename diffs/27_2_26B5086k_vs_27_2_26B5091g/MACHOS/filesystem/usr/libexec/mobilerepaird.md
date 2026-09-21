## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1307.40.46.0.0
-  __TEXT.__text: 0xaf24
+1307.40.51.0.0
+  __TEXT.__text: 0xb1d8
   __TEXT.__auth_stubs: 0x480
-  __TEXT.__objc_stubs: 0x1980
-  __TEXT.__objc_methlist: 0x904
+  __TEXT.__objc_stubs: 0x19a0
+  __TEXT.__objc_methlist: 0x914
   __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x3b0
-  __TEXT.__objc_methname: 0x1de6
-  __TEXT.__cstring: 0x1b02
+  __TEXT.__objc_methname: 0x1e11
+  __TEXT.__cstring: 0x1bbf
   __TEXT.__oslogstring: 0x76c
   __TEXT.__objc_classname: 0x162
   __TEXT.__objc_methtype: 0x364
-  __TEXT.__unwind_info: 0x2b8
-  __DATA_CONST.__const: 0x3e0
-  __DATA_CONST.__cfstring: 0x1740
+  __TEXT.__unwind_info: 0x2c0
+  __DATA_CONST.__const: 0x410
+  __DATA_CONST.__cfstring: 0x1780
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__auth_got: 0x250
   __DATA_CONST.__got: 0x280
   __DATA.__objc_const: 0x10d8
-  __DATA.__objc_selrefs: 0x818
+  __DATA.__objc_selrefs: 0x820
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x370
   __DATA.__data: 0x190

   - /usr/lib/libbootpolicy.dylib
   - /usr/lib/libimage4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 218
+  Functions: 220
   Symbols:   155
-  CStrings:  654
+  CStrings:  658
 
CStrings:
+ "-[MRBaseComponentHandler sendFinishRepairNotificationShownAnalytics]_block_invoke"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairNotificationShown)"
+ "FinishRepairNotificationShown"
+ "sendFinishRepairNotificationShownAnalytics"
```
