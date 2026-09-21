## authd

> `/System/Library/Frameworks/Security.framework/Versions/A/XPCServices/authd.xpc/Contents/MacOS/authd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62460.40.49.501.1
-  __TEXT.__text: 0x25f20
-  __TEXT.__auth_stubs: 0x1380
+62460.40.56.501.1
+  __TEXT.__text: 0x2677c
+  __TEXT.__auth_stubs: 0x1390
   __TEXT.__lazy_helpers: 0x63c
-  __TEXT.__objc_stubs: 0xc00
+  __TEXT.__objc_stubs: 0xc20
   __TEXT.__objc_methlist: 0x154
   __TEXT.__const: 0xb20
-  __TEXT.__cstring: 0x2ea9
-  __TEXT.__oslogstring: 0x4c23
+  __TEXT.__cstring: 0x3060
+  __TEXT.__oslogstring: 0x4d2b
   __TEXT.__dlopen_cstrs: 0x5d
-  __TEXT.__gcc_except_tab: 0xd74
-  __TEXT.__objc_methname: 0x9c0
+  __TEXT.__gcc_except_tab: 0xd5c
+  __TEXT.__objc_methname: 0x9da
   __TEXT.__objc_classname: 0xf
   __TEXT.__objc_methtype: 0x140
-  __TEXT.__unwind_info: 0x7e8
-  __DATA_CONST.__const: 0x22c8
+  __TEXT.__unwind_info: 0x7f8
+  __DATA_CONST.__const: 0x2398
   __DATA_CONST.__cfstring: 0x10e0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x9d0
-  __DATA_CONST.__got: 0x190
+  __DATA_CONST.__auth_got: 0x9d8
+  __DATA_CONST.__got: 0x198
   __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x230
-  __DATA.__objc_selrefs: 0x310
+  __DATA.__objc_selrefs: 0x318
   __DATA.__objc_ivar: 0x30
   __DATA.__objc_data: 0x50
   __DATA.__lazy_load_got: 0x98

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 463
-  Symbols:   397
-  CStrings:  1047
+  Functions: 470
+  Symbols:   399
+  CStrings:  1058
 
Symbols:
+ __xpc_error_peer_code_signing_requirement
+ _xpc_connection_set_peer_code_signing_requirement
CStrings:
+ "B32@?0@\"NSString\"8Q16^B24"
+ "DELETE FROM rules WHERE type = 1 AND name = ?"
+ "Removing right %{public}s: a case variant of a right governed by a wildcard rule"
+ "Rule %{public}s not found"
+ "SELECT * FROM rules WHERE name = ? COLLATE NOCASE ORDER BY (identifier IS NULL) DESC, id ASC LIMIT 1"
+ "SELECT COUNT(name) AS cnt FROM rules WHERE name = ? COLLATE NOCASE AND type = ?"
+ "SELECT id,name,created,identifier,requirement FROM rules WHERE name = ? COLLATE NOCASE ORDER BY (identifier IS NULL) DESC, id ASC LIMIT 1"
+ "SELECT name FROM rules WHERE type = 1 AND name GLOB '*[A-Z]*'"
+ "SELECT name FROM rules WHERE type = 1 AND name LIKE '%.'"
+ "Using local version of %{public}s"
+ "agent: peer has to satisfy %{public}s"
+ "agent: the responder does not satisfy the required code identity"
+ "agent: unable to require the peer code identity %{public}s (%d)"
+ "identifier \"com.apple.SecurityAgent\" and anchor apple"
+ "identifier \"com.apple.authorizationhost\" and anchor apple"
+ "indexOfObjectPassingTest:"
- "Rule %s not found"
- "SELECT * FROM rules WHERE name = ? LIMIT 1"
- "SELECT COUNT(name) AS cnt FROM rules WHERE name = ? AND type = 1"
- "SELECT id,created,identifier,requirement FROM rules WHERE name = ? LIMIT 1"
- "Using local version of %s"
```
