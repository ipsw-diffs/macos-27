## nearbyd

> `/usr/libexec/nearbyd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-578.0.3.0.0
-  __TEXT.__text: 0x4e67a8
+578.0.3.0.2
+  __TEXT.__text: 0x4e7334
   __TEXT.__auth_stubs: 0x27e0
   __TEXT.__objc_stubs: 0x14800
   __TEXT.__init_offsets: 0x2e4
   __TEXT.__objc_methlist: 0xe93c
-  __TEXT.__gcc_except_tab: 0x4cfc8
+  __TEXT.__gcc_except_tab: 0x4d040
   __TEXT.__const: 0x3eea08
-  __TEXT.__cstring: 0x35917
+  __TEXT.__cstring: 0x35931
   __TEXT.__objc_methname: 0x20fa3
   __TEXT.__oslogstring: 0x56c02
   __TEXT.__objc_classname: 0x1c5e
-  __TEXT.__objc_methtype: 0x209ea
+  __TEXT.__objc_methtype: 0x20b7a
   __TEXT.__ustring: 0x60
   __TEXT.__swift5_typeref: 0x1e8
   __TEXT.__swift5_capture: 0x114

   __TEXT.__swift5_reflstr: 0x2b5
   __TEXT.__swift5_fieldmd: 0x22c
   __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x1f048
+  __TEXT.__unwind_info: 0x1f070
   __TEXT.__eh_frame: 0x48
   __DATA_CONST.__const: 0x1dfb8
   __DATA_CONST.__cfstring: 0x15b20

   __DATA.__objc_ivar: 0x18f8
   __DATA.__objc_data: 0x3db8
   __DATA.__data: 0x35c4
-  __DATA.__bss: 0xd4f0
+  __DATA.__bss: 0xd520
   __DATA.__common: 0xe08
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21798
+  Functions: 21806
   Symbols:   953
-  CStrings:  17915
+  CStrings:  17917
 
CStrings:
+ "C03DDF74/A584A42A"
+ "C03DDF74/A9A8962C"
+ "{unordered_map<unsigned long long, std::pair<signed char, std::optional<std::string>>, std::hash<unsigned long long>, std::equal_to<unsigned long long>, std::allocator<std::pair<const unsigned long long, std::pair<signed char, std::optional<std::string>>>>>=\"__table_\"{__hash_table<std::__hash_value_type<unsigned long long, std::pair<signed char, std::optional<std::string>>>, std::__unordered_map_hasher<unsigned long long, std::pair<const unsigned long long, std::pair<signed char, std::optional<std::string>>>, std::hash<unsigned long long>, std::equal_to<unsigned long long>>, std::__unordered_map_equal<unsigned long long, std::pair<const unsigned long long, std::pair<signed char, std::optional<std::string>>>, std::equal_to<unsigned long long>, std::hash<unsigned long long>>, std::allocator<std::pair<const unsigned long long, std::pair<signed char, std::optional<std::string>>>>>=\"__bucket_list_\"{unique_ptr<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, std::pair<signed char, std::optional<std::string>>>, void *> *> *[], std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, std::pair<signed char, std::optional<std::string>>>, void *> *> *>>>=\"\"{?=\"__ptr_\"^^v\"__deleter_\"{__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, std::pair<signed char, std::optional<std::string>>>, void *> *> *>>=\"\"{?=\"__size_\"Q}}}}\"\"{?=\"__first_node_\"{__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, std::pair<signed char, std::optional<std::string>>>, void *> *>=\"__next_\"^v}}\"\"{?=\"__size_\"Q}\"\"{?=\"__max_load_factor_\"f}}}"
- "{unordered_map<unsigned long long, signed char, std::hash<unsigned long long>, std::equal_to<unsigned long long>, std::allocator<std::pair<const unsigned long long, signed char>>>=\"__table_\"{__hash_table<std::__hash_value_type<unsigned long long, signed char>, std::__unordered_map_hasher<unsigned long long, std::pair<const unsigned long long, signed char>, std::hash<unsigned long long>, std::equal_to<unsigned long long>>, std::__unordered_map_equal<unsigned long long, std::pair<const unsigned long long, signed char>, std::equal_to<unsigned long long>, std::hash<unsigned long long>>, std::allocator<std::pair<const unsigned long long, signed char>>>=\"__bucket_list_\"{unique_ptr<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, signed char>, void *> *> *[], std::__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, signed char>, void *> *> *>>>=\"\"{?=\"__ptr_\"^^v\"__deleter_\"{__bucket_list_deallocator<std::allocator<std::__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, signed char>, void *> *> *>>=\"\"{?=\"__size_\"Q}}}}\"\"{?=\"__first_node_\"{__hash_node_base<std::__hash_node<std::__hash_value_type<unsigned long long, signed char>, void *> *>=\"__next_\"^v}}\"\"{?=\"__size_\"Q}\"\"{?=\"__max_load_factor_\"f}}}"
```
