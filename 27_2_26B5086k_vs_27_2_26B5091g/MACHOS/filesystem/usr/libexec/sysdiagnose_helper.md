## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1598.40.4.0.0
-  __TEXT.__text: 0x25c28
+  __TEXT.__text: 0x25d6c
   __TEXT.__auth_stubs: 0xdf0
   __TEXT.__objc_stubs: 0x1b20
   __TEXT.__objc_methlist: 0x780
   __TEXT.__const: 0x390
-  __TEXT.__cstring: 0x975c
+  __TEXT.__cstring: 0x97af
   __TEXT.__objc_methname: 0x1c3d
   __TEXT.__oslogstring: 0x284d
   __TEXT.__objc_classname: 0x128

   - /usr/lib/swift/libswiftos.dylib
   Functions: 349
   Symbols:   310
-  CStrings:  2300
+  CStrings:  2303
 
Functions:
~ sub_1000121cc : 68644 -> 68968
CStrings:
+ "OpenBandExtraSensesOnLastWLPerMode"
+ "OpenBandExtraSensesPerMode"
+ "OpenBandReadsPerMode"
```
