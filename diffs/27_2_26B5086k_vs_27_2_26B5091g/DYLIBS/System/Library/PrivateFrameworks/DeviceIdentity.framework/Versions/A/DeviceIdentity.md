## DeviceIdentity

> `/System/Library/PrivateFrameworks/DeviceIdentity.framework/Versions/A/DeviceIdentity`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1145.40.4.0.0
-  __TEXT.__text: 0x20944
+1145.40.5.0.0
+  __TEXT.__text: 0x2094c
   __TEXT.__objc_methlist: 0x444
   __TEXT.__cstring: 0x45bf
   __TEXT.__gcc_except_tab: 0xe90

   __AUTH_CONST.__auth_got: 0x460
   __AUTH.__data: 0x10
   __DATA.__objc_ivar: 0x54
-  __DATA.__data: 0xf8
+  __DATA.__data: 0x88
   __DATA.__bss: 0xa8
   __DATA_DIRTY.__objc_data: 0xa0
-  __DATA_DIRTY.__data: 0x10
+  __DATA_DIRTY.__data: 0x80
   __DATA_DIRTY.__bss: 0x68
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CryptoTokenKit.framework/Versions/A/CryptoTokenKit
Functions:
~ _X509ExtensionParseBasicConstraints : 208 -> 204
~ _X509ChainBuildPathPartial : 484 -> 496
CStrings:
+ "macOS Device Activator (MobileActivation-1145.40.5)"
- "macOS Device Activator (MobileActivation-1145.40.4)"
```
