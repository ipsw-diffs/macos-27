## com.apple.driver.DiskImages

> `com.apple.driver.DiskImages`

```diff

-710.0.0.0.0
-  __TEXT.__cstring: 0x1b45
-  __TEXT_EXEC.__text: 0xdd88
+710.60.2.0.0
+  __TEXT.__cstring: 0x1c13
+  __TEXT_EXEC.__text: 0xdde4
   __TEXT_EXEC.__auth_stubs: 0x550
   __DATA.__data: 0x188
   __DATA.__common: 0x1a0

   __DATA_CONST.__got: 0xb0
   Functions: 374
   Symbols:   906
-  CStrings:  283
+  CStrings:  285
 
Functions:
~ __ZN13IOHDIXHDDrive19processPropertyListEv : 976 -> 1068
CStrings:
+ "710.60.2"
+ "IOHDIXHDDrive::processPropertyList: rejecting attach, bad block-size multiple %llu (rdar://185717528)\n"
+ "IOHDIXHDDrive::processPropertyList: rejecting attach, non-512 block size %lld (rdar://185717528)\n"
- "710"
```
