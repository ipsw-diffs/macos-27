## Authorization

> `/System/Library/MonitorPanels/AppleDisplay.monitorPanels/Contents/Resources/Authorization.monitorPanel/Contents/MacOS/Authorization`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 2027.0.1.0.0
-  __TEXT.__text: 0x740
+  __TEXT.__text: 0x704
   __TEXT.__auth_stubs: 0xa0
   __TEXT.__objc_stubs: 0xe0
   __TEXT.__objc_methlist: 0x74

   __TEXT.__objc_methname: 0xf7
   __TEXT.__objc_classname: 0x13
   __TEXT.__objc_methtype: 0x35
-  __TEXT.__unwind_info: 0x78
+  __TEXT.__unwind_info: 0xa8
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
Functions:
~ -[AuthorizationPanel handleAuthorizationChangedNotification] : 128 -> 104
~ -[AuthorizationPanel authorizationViewDidAuthorize:] : 128 -> 116
~ -[AuthorizationPanel authorizationViewDidDeauthorize:] : 128 -> 116
~ _OUTLINED_FUNCTION_1 : 28 -> 16
```
