## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-577.40.5.0.0
-  __TEXT.__text: 0x132fdc
+577.40.6.0.0
+  __TEXT.__text: 0x133bd8
   __TEXT.__auth_stubs: 0x1c20
   __TEXT.__objc_stubs: 0x1f20
   __TEXT.__init_offsets: 0x24
   __TEXT.__objc_methlist: 0x4ac
-  __TEXT.__gcc_except_tab: 0x15fe0
+  __TEXT.__gcc_except_tab: 0x16108
   __TEXT.__const: 0xa3d4
-  __TEXT.__cstring: 0x15e65
-  __TEXT.__oslogstring: 0x19b29
+  __TEXT.__cstring: 0x15f05
+  __TEXT.__oslogstring: 0x19bc9
   __TEXT.__objc_methname: 0x1b34
   __TEXT.__objc_classname: 0xda
   __TEXT.__objc_methtype: 0x8c5

   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_proto: 0x4
   __TEXT.__swift5_types: 0x14
-  __TEXT.__unwind_info: 0x9578
+  __TEXT.__unwind_info: 0x95b8
   __TEXT.__eh_frame: 0x3a8
-  __DATA_CONST.__const: 0xaaf8
+  __DATA_CONST.__const: 0xab18
   __DATA_CONST.__cfstring: 0xc80
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6168
+  Functions: 6174
   Symbols:   671
-  CStrings:  3712
+  CStrings:  3714
 
CStrings:
+ "SELECT session_id FROM sessions WHERE cadence = ?1 AND start <= ?2 UNION SELECT DISTINCT tm.session_id FROM transform_metadata tm LEFT JOIN sessions s ON tm.session_id = s.session_id WHERE s.session_id IS NULL AND tm.session_id IS NOT NULL"
+ "SessionNotAcceptingEvents"
+ "[FW Event] ERROR: Event '%s' dropped: session '%{public}s' does not exist or has ended."
+ "[SessionManager] Failed to re-create session row for leftover state: %s"
+ "[Sink] No session row for %{public}s; stamping log with the cadence log start instead"
- "SELECT session_id FROM sessions WHERE state = ?1 AND cadence = ?2 AND start <= ?3"
- "[Transform Manager] Session %s not enabled for transform, using main session"
- "sessionsEnabled"
```
