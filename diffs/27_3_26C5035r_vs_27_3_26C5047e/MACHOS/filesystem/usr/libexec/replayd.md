## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-770.2.1.0.0
-  __TEXT.__text: 0xcae38
+770.4.1.0.0
+  __TEXT.__text: 0xcb138
   __TEXT.__auth_stubs: 0x1d10
   __TEXT.__objc_stubs: 0xf2e0
   __TEXT.__objc_methlist: 0x78cc
   __TEXT.__const: 0x430
-  __TEXT.__oslogstring: 0x16418
-  __TEXT.__cstring: 0x177e3
+  __TEXT.__oslogstring: 0x164ca
+  __TEXT.__cstring: 0x177eb
   __TEXT.__objc_classname: 0xb35
-  __TEXT.__objc_methname: 0x1693a
-  __TEXT.__objc_methtype: 0x4234
+  __TEXT.__objc_methname: 0x16935
+  __TEXT.__objc_methtype: 0x4220
   __TEXT.__gcc_except_tab: 0x1004
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__unwind_info: 0x35a8
-  __DATA_CONST.__const: 0x29a0
+  __TEXT.__unwind_info: 0x35b0
+  __DATA_CONST.__const: 0x2990
   __DATA_CONST.__cfstring: 0x6420
   __DATA_CONST.__objc_classlist: 0x300
   __DATA_CONST.__objc_catlist: 0x30

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3871
+  Functions: 3873
   Symbols:   884
-  CStrings:  7591
+  CStrings:  7592
 
CStrings:
+ " [ERROR] %{public}s:%d Rejecting AppsAndWindowsPinnedToDisplay filter with individual window ID"
+ " [ERROR] %{public}s:%d failed to open %@ error %@"
+ " [INFO] %{public}s:%d %p added video input with resolution %zux%zu transform=[%.0f %.0f %.0f %.0f] and started writing"
+ "-[RPRecordingManager processSaveToPhotos:mixAudioTracks:ignoreDoNotDisturb:isClip:handler:]"
+ "openURL:configuration:completionHandler:"
+ "processSaveToPhotos:mixAudioTracks:ignoreDoNotDisturb:isClip:handler:"
- " [INFO] %{public}s:%d %p added video input with resolution %zux%zu and started writing"
- "-[RPRecordingManager processSaveToPhotos:mixAudioTracks:ignoreDoNotDisturb:isClip:]"
- "openApplicationAtURL:configuration:completionHandler:"
- "processSaveToPhotos:mixAudioTracks:ignoreDoNotDisturb:isClip:"
- "v36@0:8@16B24B28B32"
```
