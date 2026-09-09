## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 3977.0.23.0.0
-  __TEXT.__text: 0x26de8
+  __TEXT.__text: 0x26c64
   __TEXT.__objc_methlist: 0x2d54
   __TEXT.__gcc_except_tab: 0x164
   __TEXT.__const: 0x186

   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__got: 0x430
   __AUTH_CONST.__const: 0x3a0
-  __AUTH_CONST.__cfstring: 0x1d20
+  __AUTH_CONST.__cfstring: 0x1d00
   __AUTH_CONST.__objc_const: 0x5c68
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x10

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 966
   Symbols:   2727
-  CStrings:  303
+  CStrings:  302
 
Functions:
~ +[OBPrivacyFlow _splashPlistFromBundle:forContentName:] : 192 -> 4
~ -[OBPrivacyFlow _splashLocalizedStringForKey:language:preferredDeviceType:] : 408 -> 208
CStrings:
- "-seed"
```
