## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`

```diff

-913.43.1.0.0
+913.48.1.0.0
   __TEXT.__text: 0x8787c
   __TEXT.__auth_stubs: 0xd70
   __TEXT.__objc_stubs: 0x20
CStrings:
+ "23:07:12"
+ "913.48.1"
+ "Sep  4 2026"
+ "num <= (((16) > (15) ? (16) : (15)) + 1)"
+ "pSnapshot->num_ref_frame <= ((16) > (15) ? (16) : (15))"
- "20:49:05"
- "913.43.1"
- "Aug 11 2026"
- "num <= (((16) > (16) ? (16) : (16)) + 1)"
- "pSnapshot->num_ref_frame <= ((16) > (16) ? (16) : (16))"
```
