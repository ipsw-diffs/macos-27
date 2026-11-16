## IPConfiguration

> `/System/Library/SystemConfiguration/IPConfiguration.bundle/Contents/MacOS/IPConfiguration`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-557.60.2.0.0
-  __TEXT.__text: 0x5d674
+557.60.4.0.0
+  __TEXT.__text: 0x5d7d4
   __TEXT.__auth_stubs: 0x11c0
   __TEXT.__const: 0x320
-  __TEXT.__cstring: 0x4349
-  __TEXT.__oslogstring: 0x63a1
+  __TEXT.__cstring: 0x4366
+  __TEXT.__oslogstring: 0x63c4
   __TEXT.__unwind_info: 0xf28
   __DATA_CONST.__const: 0x1e58
   __DATA_CONST.__cfstring: 0x2ca0

   - /usr/lib/libobjc.A.dylib
   Functions: 1046
   Symbols:   528
-  CStrings:  1766
+  CStrings:  1768
 
Functions:
~ sub_10a68 : 2840 -> 2884
~ sub_134bc -> sub_134e8 : 948 -> 936
~ sub_18c18 -> sub_18c38 : 24 -> 344
CStrings:
+ "%s(%s): router IP/hwaddr not valid"
+ "service_router_set_all_valid"
```
