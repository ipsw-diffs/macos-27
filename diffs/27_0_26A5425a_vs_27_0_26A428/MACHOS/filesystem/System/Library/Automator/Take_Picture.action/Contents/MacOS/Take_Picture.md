## Take Picture

> `/System/Library/Automator/Take Picture.action/Contents/MacOS/Take Picture`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1546.0.0.0.0
-  __TEXT.__text: 0xb2c
+  __TEXT.__text: 0xaa8
   __TEXT.__auth_stubs: 0xb0
   __TEXT.__objc_stubs: 0x4a0
   __TEXT.__objc_methlist: 0x434

   __TEXT.__objc_methtype: 0x41e
   __TEXT.__cstring: 0x7a
   __TEXT.__ustring: 0x70
-  __TEXT.__unwind_info: 0x80
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__cfstring: 0x160
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
Functions:
~ -[NSImageFromCGImageRef transformedValue:] : 92 -> 80
~ -[TakePicture closed] : 172 -> 160
~ -[TakePicture runAsynchronouslyWithInput:] : 216 -> 192
~ -[TakePicture completeRunWithFilePath:error:] : 100 -> 88
~ -[TakePicture deviceBrowser:didAddDevice:moreComing:] : 192 -> 180
~ -[TakePicture device:didOpenSessionWithError:] : 128 -> 116
~ -[TakePicture deviceDidBecomeReady:] : 192 -> 168
~ -[TakePicture cameraDevice:didAddItem:] : 380 -> 368
~ -[TakePicture didDownloadFile:error:options:contextInfo:] : 276 -> 264
```
