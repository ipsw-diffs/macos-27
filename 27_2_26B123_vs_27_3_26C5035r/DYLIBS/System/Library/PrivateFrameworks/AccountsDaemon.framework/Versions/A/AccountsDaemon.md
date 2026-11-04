## AccountsDaemon

> `/System/Library/PrivateFrameworks/AccountsDaemon.framework/Versions/A/AccountsDaemon`

```diff

-1125.0.0.0.0
-  __TEXT.__text: 0x8a640
+1127.0.0.0.0
+  __TEXT.__text: 0x8a868
   __TEXT.__objc_methlist: 0x3cc4
   __TEXT.__const: 0xd1a
-  __TEXT.__oslogstring: 0x928a
+  __TEXT.__oslogstring: 0x936a
   __TEXT.__cstring: 0x3e63
   __TEXT.__gcc_except_tab: 0x24ac
   __TEXT.__swift5_typeref: 0x6d2

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2507
+  Functions: 2508
   Symbols:   4359
-  CStrings:  1203
+  CStrings:  1205
 
Functions:
~ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:] : 3644 -> 4144
~ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:].cold.6 : 84 -> 52
+ -[ACDAccountStore _setAccountManagedObjectRelationships:withAccount:oldAccount:error:].cold.7
CStrings:
+ "\"%@: client %@ saved a credential against a stale username (%@, persisted is %@). Storing under the persisted username.\""
+ "\"Unable to build an account from the database for %@; falling back to the client's account to save its credential\""
```
