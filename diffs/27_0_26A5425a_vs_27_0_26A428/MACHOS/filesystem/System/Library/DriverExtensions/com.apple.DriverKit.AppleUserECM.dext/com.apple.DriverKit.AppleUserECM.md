## com.apple.DriverKit.AppleUserECM

> `/System/Library/DriverExtensions/com.apple.DriverKit.AppleUserECM.dext/com.apple.DriverKit.AppleUserECM`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 73.0.2.0.0
-  __TEXT.__text: 0x60fc
+  __TEXT.__text: 0x607c
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__const: 0xbb0
   __TEXT.__cstring: 0x6d6
Functions:
~ sub_1000043a0 : 32 -> 20
~ sub_1000043e0 -> sub_1000043d4 : 28 -> 16
~ __ZN12AppleUserECM15RxComplete_ImplEP8OSActionjjPKjiPKii : 820 -> 800
~ sub_100006744 -> sub_100006718 : 36 -> 24
~ sub_100006780 -> sub_100006748 : 28 -> 16
~ sub_100006810 -> sub_1000067cc : 24 -> 12
~ sub_100006828 -> sub_1000067d8 : 40 -> 28
~ sub_100006850 -> sub_1000067f4 : 28 -> 16
~ sub_100006898 -> sub_100006830 : 32 -> 20
~ sub_1000068b8 -> sub_100006844 : 24 -> 12
~ __ZN12AppleUserECM8activateEv : 1188 -> 1192
~ __ZN12AppleUserECM26InterruptReadComplete_ImplEP8OSActionijy : 972 -> 968
```
