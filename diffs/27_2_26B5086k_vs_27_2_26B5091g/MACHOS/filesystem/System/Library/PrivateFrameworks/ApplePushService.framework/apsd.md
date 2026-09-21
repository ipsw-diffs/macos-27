## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1168.200.31.0.0
-  __TEXT.__text: 0x144f30
+1168.200.41.0.0
+  __TEXT.__text: 0x144fb8
   __TEXT.__auth_stubs: 0x3570
   __TEXT.__objc_stubs: 0x12120
   __TEXT.__init_offsets: 0xc

   __TEXT.__const: 0x186c0
   __TEXT.__objc_methname: 0x1d525
   __TEXT.__cstring: 0xf2c4
-  __TEXT.__oslogstring: 0x16645
+  __TEXT.__oslogstring: 0x166a5
   __TEXT.__objc_classname: 0x135b
   __TEXT.__objc_methtype: 0x5179
   __TEXT.__gcc_except_tab: 0x2624

   - /usr/lib/swift/libswiftos.dylib
   Functions: 7279
   Symbols:   1197
-  CStrings:  9206
+  CStrings:  9207
 
Functions:
~ sub_1000ac888 : 276 -> 404
~ sub_100120a5c -> sub_100120adc : 208 -> 204
~ sub_1001239e0 -> sub_100123a5c : 484 -> 496
CStrings:
+ "%@ ignoring connect notification from stream %@ that is no longer bound to an interface"
```
