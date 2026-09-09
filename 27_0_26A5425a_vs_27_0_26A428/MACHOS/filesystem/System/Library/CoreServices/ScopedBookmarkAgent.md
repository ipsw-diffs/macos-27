## ScopedBookmarkAgent

> `/System/Library/CoreServices/ScopedBookmarkAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 609.0.0.0.0
-  __TEXT.__text: 0xc4a0
+  __TEXT.__text: 0xc29c
   __TEXT.__auth_stubs: 0xb30
   __TEXT.__objc_stubs: 0xca0
   __TEXT.__objc_methlist: 0x208

   __TEXT.__oslogstring: 0x178c
   __TEXT.__objc_classname: 0x13
   __TEXT.__objc_methtype: 0x15c
-  __TEXT.__unwind_info: 0x338
+  __TEXT.__unwind_info: 0x4a8
   __DATA_CONST.__const: 0x170
   __DATA_CONST.__cfstring: 0x980
   __DATA_CONST.__objc_classlist: 0x10
Functions:
~ -[AppInfo appScopeKey] : 176 -> 164
~ -[AppInfo revocableAppScopeKey] : 676 -> 664
~ -[AppInfo .cxx_destruct] : 116 -> 104
~ +[KeyManager shared] : 68 -> 56
~ ___20+[KeyManager shared]_block_invoke : 76 -> 64
~ ___29-[KeyManager initWithSuffix:]_block_invoke : 84 -> 72
~ -[KeyManager _fetchDataProtectionAgentKey] : 844 -> 832
~ -[KeyManager dataProtectionAgentKey] : 116 -> 104
~ -[KeyManager setDataProtectionAgentKey:] : 140 -> 128
~ -[KeyManager keyEncryptionKeyURL] : 656 -> 644
~ -[KeyManager readKeyEncryptionKey] : 320 -> 308
~ -[KeyManager keyEncryptionKey] : 160 -> 148
~ -[KeyManager dataProcessedWithKEK:encrypt:] : 460 -> 448
~ -[KeyManager _fetchLegacyAgentKey] : 1052 -> 1040
~ -[KeyManager legacyAgentKey] : 116 -> 104
~ -[KeyManager setLegacyAgentKey:] : 136 -> 124
~ -[KeyManager _fetchAgentKey] : 576 -> 564
~ -[KeyManager agentKey] : 116 -> 104
~ -[KeyManager _migrateAgentKey] : 1092 -> 1080
~ -[KeyManager scopeKeyForCollection:create:] : 528 -> 516
~ -[KeyManager collectionTokenForFile:create:] : 528 -> 516
~ -[KeyManager collectionTokenForPath:] : 320 -> 308
~ -[KeyManager scopeKeyForSigningIdentifier:] : 468 -> 456
~ -[KeyManager appInfoForAuditToken:] : 548 -> 536
~ -[KeyManager flushCachedAppInfo] : 68 -> 56
~ -[KeyManager scheduleFlushOfCachedAppInfo] : 88 -> 76
~ -[KeyManager .cxx_destruct] : 128 -> 116
~ __Z27GetRevocableClientsSnapshotv : 396 -> 384
~ __ZL20_GetRevocableClientsv : 68 -> 56
~ __Z42GetRevocableClientSnapshotForAppIdentifierP8NSString : 472 -> 460
~ __Z32CreateRevocableClientFromAppInfoP7AppInfo : 476 -> 464
~ __Z8asStringRKPKv : 2608 -> 2568
~ __ZNSt3__119basic_ostringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9nqn220106Ev : 420 -> 380
~ __Z8asStringP5FSRef : 608 -> 568
~ ____ZL21handle_create_requestPU24objcproto13OS_xpc_object8NSObjectS1_13audit_token_t_block_invoke : 228 -> 216
~ _OUTLINED_FUNCTION_5 : 28 -> 16
CStrings:
+ "15:42:56"
+ "Aug  8 2026"
- "00:59:01"
- "Aug 10 2026"
```
