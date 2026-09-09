## libUAEHZoom.dylib

> `/System/Library/PrivateFrameworks/UniversalAccess.framework/Versions/Current/Frameworks/UAEHCommon.framework/Versions/A/Libraries/libUAEHZoom.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

 778.1.1.0.0
-  __TEXT.__text: 0xe2c
+  __TEXT.__text: 0xd60
   __TEXT.__objc_methlist: 0x2cc
   __TEXT.__oslogstring: 0x22
   __TEXT.__cstring: 0x2
-  __TEXT.__unwind_info: 0xc0
+  __TEXT.__unwind_info: 0xd8
   __TEXT.__objc_stubs: 0x500
   __TEXT.__auth_stubs: 0x160
   __TEXT.__objc_classname: 0x2c
Functions:
~ _handleEvent : 76 -> 64
~ _handleMessage : 100 -> 88
~ _initialize : 136 -> 124
~ _libraryWillUnload : 72 -> 60
~ _updateSettings : 68 -> 56
~ _userSessionDidChange : 68 -> 56
~ -[UAEHZoomDriver description] : 80 -> 68
~ -[UAEHZoomDriver startZoomWindow] : 120 -> 108
~ -[UAEHZoomDriver userSessionDidChange] : 220 -> 196
~ -[UAEHZoomDriver _zoomIsNeededBasedOnPreferences] : 92 -> 80
~ -[UAEHZoomDriver _settingsChangedNotificationsToObserve] : 156 -> 144
~ -[UAEHZoomDriver fullscreenZoomManagerStartCapturingKeyAndMouseEvents] : 116 -> 104
~ -[UAEHZoomDriver fullscreenZoomManagerStopCapturingKeyAndMouseEvents] : 116 -> 104
~ -[UAEHZoomDriver _startZoomWindowIfNeeded] : 92 -> 80
~ -[UAEHZoomDriver _stopZoomWindow] : 64 -> 52
~ -[UAEHZoomDriver .cxx_destruct] : 84 -> 72
```
