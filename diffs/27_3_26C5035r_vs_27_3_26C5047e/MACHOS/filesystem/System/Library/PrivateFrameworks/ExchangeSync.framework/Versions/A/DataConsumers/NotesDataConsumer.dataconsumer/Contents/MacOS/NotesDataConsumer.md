## NotesDataConsumer

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/DataConsumers/NotesDataConsumer.dataconsumer/Contents/MacOS/NotesDataConsumer`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2080.300.31.0.0
-  __TEXT.__text: 0x967c
-  __TEXT.__auth_stubs: 0x240
-  __TEXT.__objc_stubs: 0x1820
-  __TEXT.__objc_methlist: 0x6ac
+2080.300.51.0.0
+  __TEXT.__text: 0x99c4
+  __TEXT.__auth_stubs: 0x250
+  __TEXT.__objc_stubs: 0x1960
+  __TEXT.__objc_methlist: 0x704
   __TEXT.__const: 0xb0
-  __TEXT.__gcc_except_tab: 0x44c
+  __TEXT.__gcc_except_tab: 0x470
   __TEXT.__cstring: 0x13c
-  __TEXT.__oslogstring: 0x2275
-  __TEXT.__objc_methname: 0x1ae5
+  __TEXT.__oslogstring: 0x2318
+  __TEXT.__objc_methname: 0x1c6b
   __TEXT.__objc_classname: 0x43
-  __TEXT.__objc_methtype: 0x40c
-  __TEXT.__unwind_info: 0x300
-  __DATA_CONST.__const: 0x348
+  __TEXT.__objc_methtype: 0x42a
+  __TEXT.__unwind_info: 0x308
+  __DATA_CONST.__const: 0x368
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x130
-  __DATA_CONST.__got: 0x98
-  __DATA.__objc_const: 0x5c8
-  __DATA.__objc_selrefs: 0x770
-  __DATA.__objc_ivar: 0x3c
+  __DATA_CONST.__auth_got: 0x138
+  __DATA_CONST.__got: 0xb0
+  __DATA.__objc_const: 0x640
+  __DATA.__objc_selrefs: 0x7d0
+  __DATA.__objc_ivar: 0x44
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x120
-  __DATA.__bss: 0x10
+  __DATA.__bss: 0x20
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/ExchangeSync
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 172
-  Symbols:   67
-  CStrings:  437
+  Functions: 179
+  Symbols:   71
+  CStrings:  456
 
Symbols:
+ _OBJC_CLASS_$_EXSNotesChangeTokenPolicy
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSMutableIndexSet
+ _objc_setProperty_atomic
CStrings:
+ "@\"NSDate\""
+ "@\"NSIndexSet\"16@0:8"
+ "EXSNotesDataConsumer: ExchangeNotes token unchanged for account %{public}@, but our last fetch may have run before a commit in the same second, so fetching again."
+ "T@\"NSDate\",&,V_lastFetchIssuedAt"
+ "T@\"NSString\",C,V_lastFetchedChangeToken"
+ "_lastFetchIssuedAt"
+ "_lastFetchedChangeToken"
+ "addIndex:"
+ "containsIndex:"
+ "date"
+ "indexSetWithIndex:"
+ "lastFetchIssuedAt"
+ "lastFetchedChangeToken"
+ "maxChangeItemsPerPush"
+ "pushedItemTypes"
+ "repushesPartlyAppliedBatchesSafely"
+ "setLastFetchIssuedAt:"
+ "setLastFetchedChangeToken:"
+ "shouldFetchUnchangedToken:lastFetchedToken:lastFetchIssuedAt:"
```
