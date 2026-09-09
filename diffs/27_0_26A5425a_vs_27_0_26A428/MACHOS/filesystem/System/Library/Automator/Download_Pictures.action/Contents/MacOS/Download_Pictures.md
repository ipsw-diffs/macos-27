## Download Pictures

> `/System/Library/Automator/Download Pictures.action/Contents/MacOS/Download Pictures`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 1546.0.0.0.0
-  __TEXT.__text: 0xc14
+  __TEXT.__text: 0xb78
   __TEXT.__auth_stubs: 0xc0
   __TEXT.__objc_stubs: 0x580
   __TEXT.__objc_methlist: 0x454

   __TEXT.__objc_methtype: 0x430
   __TEXT.__cstring: 0x8e
   __TEXT.__ustring: 0x22
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__cfstring: 0x140
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
Functions:
~ -[NSImageFromCGImageRef transformedValue:] : 92 -> 80
~ -[DownloadPictures runAsynchronouslyWithInput:] : 144 -> 120
~ -[DownloadPictures downloadNextFile] : 392 -> 368
~ -[DownloadPictures completeRunWithError:] : 136 -> 124
~ -[DownloadPictures deviceBrowser:didAddDevice:moreComing:] : 148 -> 136
~ -[DownloadPictures device:didOpenSessionWithError:] : 104 -> 92
~ -[DownloadPictures deviceDidBecomeReady:] : 176 -> 164
~ -[DownloadPictures cameraDevice:didAddItem:] : 120 -> 108
~ -[DownloadPictures cameraDevice:didRemoveItem:] : 120 -> 108
~ -[DownloadPictures didDownloadFile:error:options:contextInfo:] : 204 -> 192
~ -[DownloadPictures updateCurrentDownloadCountUI] : 192 -> 180
```
