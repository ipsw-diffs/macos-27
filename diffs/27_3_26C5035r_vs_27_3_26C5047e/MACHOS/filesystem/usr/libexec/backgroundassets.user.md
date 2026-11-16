## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-279.40.8.0.0
-  __TEXT.__text: 0x5ce3c
+279.60.2.0.0
+  __TEXT.__text: 0x5cefc
   __TEXT.__auth_stubs: 0x1670
-  __TEXT.__objc_stubs: 0x75a0
+  __TEXT.__objc_stubs: 0x7580
   __TEXT.__objc_methlist: 0x34ec
   __TEXT.__const: 0x1ae8
   __TEXT.__objc_classname: 0x84e
-  __TEXT.__objc_methtype: 0x1952
+  __TEXT.__objc_methtype: 0x1932
   __TEXT.__oslogstring: 0x6cc4
   __TEXT.__cstring: 0x4110
-  __TEXT.__objc_methname: 0x9ae8
+  __TEXT.__objc_methname: 0x9ad8
   __TEXT.__gcc_except_tab: 0x14c8
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__constg_swiftt: 0x428

   __DATA_CONST.__got: 0x5b8
   __DATA_CONST.__auth_ptr: 0x360
   __DATA.__objc_const: 0x59d0
-  __DATA.__objc_selrefs: 0x2128
+  __DATA.__objc_selrefs: 0x2120
   __DATA.__objc_ivar: 0x3b0
   __DATA.__objc_data: 0x1210
   __DATA.__data: 0x12e8

   - /usr/lib/swift/libswiftos.dylib
   Functions: 1992
   Symbols:   656
-  CStrings:  2583
+  CStrings:  2582
 
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ sub_100002804 : 2972 -> 2936
~ sub_10000490c -> sub_1000048e8 : 268 -> 272
~ sub_10001381c -> sub_1000137fc : 408 -> 404
~ sub_100014000 -> sub_100013fdc : 108 -> 104
~ sub_10001406c -> sub_100014044 : 116 -> 112
~ sub_1000143f4 -> sub_1000143c8 : 1464 -> 1460
~ sub_1000149f8 -> sub_1000149c8 : 72 -> 68
~ sub_100014a40 -> sub_100014a0c : 2224 -> 2220
~ sub_100015330 -> sub_1000152f8 : 1556 -> 1548
~ sub_100015ae0 -> sub_100015aa0 : 620 -> 616
~ sub_100016038 -> sub_100015ff4 : 368 -> 364
~ sub_1000161a8 -> sub_100016160 : 580 -> 576
~ sub_1000163ec -> sub_1000163a0 : 1036 -> 1032
~ sub_100016958 -> sub_100016908 : 296 -> 292
~ sub_100016a80 -> sub_100016a2c : 348 -> 344
~ sub_100016bdc -> sub_100016b84 : 436 -> 432
~ sub_100016d90 -> sub_100016d34 : 200 -> 196
~ sub_100016e58 -> sub_100016df8 : 300 -> 296
~ sub_100016f84 -> sub_100016f20 : 300 -> 296
~ sub_1000170b0 -> sub_100017048 : 120 -> 116
~ sub_100017554 -> sub_1000174e8 : 288 -> 284
~ sub_1000177b4 -> sub_100017744 : 368 -> 364
~ sub_100017924 -> sub_1000178b0 : 424 -> 416
~ sub_100041184 -> sub_100041108 : 10784 -> 11028
~ sub_1000464c4 -> sub_10004653c : 112 -> 124
~ sub_10004e0a4 -> sub_10004e128 : 432 -> 460
~ sub_10005045c -> sub_1000504fc : 1828 -> 1844
~ sub_100056874 -> sub_100056924 : 11544 -> 11508
~ sub_1000597d8 -> sub_100059864 : 432 -> 460
~ sub_100059988 -> sub_100059a30 : 260 -> 284
CStrings:
+ "_resetAllowsCellularAccess"
+ "_resetAllowsConstrainedNetworkAccess"
+ "_resetAllowsExpensiveNetworkAccess"
+ "{os_unfair_recursive_lock_s=\"_os_unfair_recursive_lock_opaque\"[2I]}"
- "allowsCellularAccess"
- "allowsConstrainedNetworkAccess"
- "allowsExpensiveNetworkAccess"
- "setAllowsConstrainedNetworkAccess:"
- "{os_unfair_recursive_lock_s=\"ourl_lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}\"ourl_count\"I}"
```
