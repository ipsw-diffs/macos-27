## HybridDatabase

> `/System/Library/PrivateFrameworks/HybridDatabase.framework/Versions/A/HybridDatabase`

```diff

-60.3.1.0.0
-  __TEXT.__text: 0x7e0e48
+60.10.0.0.0
+  __TEXT.__text: 0x7e1200
   __TEXT.__init_offsets: 0x3c
-  __TEXT.__gcc_except_tab: 0x53f50
+  __TEXT.__gcc_except_tab: 0x53f80
   __TEXT.__const: 0xe8880
   __TEXT.__swift5_typeref: 0x920
   __TEXT.__swift5_reflstr: 0x72d

   __TEXT.__constg_swiftt: 0xb1c
   __TEXT.__swift5_fieldmd: 0xb70
   __TEXT.__swift5_builtin: 0xc8
-  __TEXT.__cstring: 0x8fe07
+  __TEXT.__cstring: 0x9007b
   __TEXT.__swift5_proto: 0x1ec
   __TEXT.__swift5_types: 0xf8
   __TEXT.__oslogstring: 0x314d
   __TEXT.__swift5_capture: 0x1e0
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x1e6d8
+  __TEXT.__unwind_info: 0x1e700
   __TEXT.__eh_frame: 0x4098
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4d6b0
+  __DATA_CONST.__const: 0x4d710
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x20
   __DATA_CONST.__objc_selrefs: 0xc8
   __DATA_CONST.__got: 0x550
-  __AUTH_CONST.__const: 0x396b8
+  __AUTH_CONST.__const: 0x396d8
   __AUTH_CONST.__cfstring: 0x60
   __AUTH_CONST.__objc_const: 0xb70
   __AUTH_CONST.__weak_auth_got: 0x28

   __AUTH.__thread_vars: 0x78
   __AUTH.__thread_bss: 0x28
   __DATA.__data: 0x494
-  __DATA.__bss: 0x4048
+  __DATA.__bss: 0x40a8
   __DATA.__common: 0x18
   __DATA_DIRTY.__data: 0xa58
   __DATA_DIRTY.__common: 0x30

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 22309
+  Functions: 22314
   Symbols:   437
-  CStrings:  8620
+  CStrings:  8626
 
CStrings:
+ "60.10"
+ "CREATE REL TABLE {} (FROM {} TO {}) WITH (storage_direction='{}');"
+ "Cannot read file identifier. path: {}. Error: {}"
+ "Database::registerDBFilePath: trying to open file {} which has already been opened by a different HDB object in the process. Please close the other HDB object before opening a new one."
+ "MisuseMultipleDBObjectsOpenForSameFile"
+ "both"
+ "virtual FileIdentifier kuzu::common::FileSystem::getFileIdentifier(const FileInfo &) const"
+ "virtual FileIdentifier kuzu::common::LocalFileSystem::getFileIdentifier(const FileInfo &) const"
+ "void kuzu::common::string_format_detail::stringFormatHelper(std::string &, std::string_view, Arg &&, Args &&...) [Arg = std::string &, Args = <const char *const &>]"
+ "void kuzu::common::string_format_detail::stringFormatHelper(std::string &, std::string_view, Arg &&, Args &&...) [Arg = std::string &, Args = <std::string &, const char *const &>]"
+ "void kuzu::common::string_format_detail::stringFormatHelper(std::string &, std::string_view, Arg &&, Args &&...) [Arg = std::string, Args = <std::string &, std::string &, const char *const &>]"
+ "void kuzu::main::Database::registerDBFilePath(const std::string &)"
- "60.3.1"
- "A term alternative must differ from the original phrase and from the other alternatives of the same query fragment. Got '{}' more than once."
- "CREATE REL TABLE {} (FROM {} TO {}) WITH (storage_direction='fwd');"
- "Query fragments with the same terms must be given the same term alternatives. Got two fragments for '{}' with different alternatives."
- "void kuzu::fts_extension::validateConsistentPhraseAlternatives(const std::vector<PhraseGroup> &)"
- "void kuzu::fts_extension::validateDistinctPhrasesInGroup(const PhraseGroup &)"
```
