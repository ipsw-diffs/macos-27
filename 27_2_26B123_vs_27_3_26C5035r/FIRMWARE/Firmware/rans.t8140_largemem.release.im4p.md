## rans.t8140_largemem.release.im4p

> `Firmware/rans.t8140_largemem.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x45a0
-  __TEXT.__text: 0x1e65c0
-  __TEXT.shared: 0xe03c
+  __TEXT.__text: 0x1e662c
+  __TEXT.shared: 0xe060
   __TEXT.read: 0x70e0
   __TEXT.__const: 0x5b18
-  __TEXT.__cstring: 0x25047
+  __TEXT.__cstring: 0x25045
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x1c
   __DATA._rtk_boot: 0x8000
Functions:
~ sub_7c900 : 56668 -> 56676
~ sub_9ccf4 -> sub_9ccfc : 7456 -> 7548
~ sub_137824 -> sub_137888 : 3156 -> 3164
~ sub_1ee45c -> sub_1ee4c8 : 356 -> 360
CStrings:
+ "241.60.3"
+ "241.60.3~407"
+ "AppleStorageFirmwareASP3-241.60.3~407"
- "241.40.4"
- "241.40.4~1099"
- "AppleStorageFirmwareASP3-241.40.4~1099"
```
