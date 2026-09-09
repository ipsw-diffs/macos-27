## IMDebug

> `/System/Applications/Podcasts.app/Contents/Frameworks/IMDebug.framework/Versions/A/IMDebug`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 4027.140.2.0.0
-  __TEXT.__text: 0x76f8
+  __TEXT.__text: 0x75b0
   __TEXT.__auth_stubs: 0x630
   __TEXT.__objc_stubs: 0x1340
   __TEXT.__objc_methlist: 0x424

   __TEXT.__gcc_except_tab: 0x194
   __TEXT.__objc_methname: 0xfc5
   __TEXT.__oslogstring: 0x24
-  __TEXT.__unwind_info: 0x238
+  __TEXT.__unwind_info: 0x270
   __DATA_CONST.__const: 0x1a8
   __DATA_CONST.__cfstring: 0x3a0
   __DATA_CONST.__objc_classlist: 0x48
Functions:
~ -[UIViewController(RecursiveDescription) recursiveDescription] : 96 -> 84
~ +[IMDebugDataManager deviceName] : 84 -> 72
~ +[IMDebugDataManager writeDebugDataWithProgress:] : 1816 -> 1804
~ -[IMDebugScreenShotDataProvider debugData] : 240 -> 228
~ ___42-[IMDebugScreenShotDataProvider debugData]_block_invoke : 128 -> 116
~ -[IMDebugUserDefaultsDataProvider debugData] : 132 -> 120
~ -[IMDebugViewControllerHierarchyDataProvider debugData] : 280 -> 268
~ -[IMDebugViewHierarchyDataProvider debugData] : 280 -> 268
~ _do_banner : 56 -> 44
~ _unzRepair : 1424 -> 1420
~ _unzOpen2 : 904 -> 896
~ _unzlocal_GetCurrentFileInfoInternal : 1084 -> 1080
~ _unzReadCurrentFile : 828 -> 824
~ _unzGetGlobalComment : 176 -> 172
~ _zipOpen2 : 1348 -> 1340
~ _add_data_in_datablock : 332 -> 328
~ _zipWriteInFileInZip : 332 -> 328
~ +[DebugUI initializeDebugUI:] : 160 -> 148
~ +[DebugUI showDebugUI] : 456 -> 444
~ +[DebugUI debugViewController] : 84 -> 72
~ +[DebugUI createScreenShotOfPresentedViewController:] : 172 -> 160
~ ___36-[IMDebugViewController viewDidLoad]_block_invoke : 64 -> 52
~ ___35-[IMDebugViewController gatherData]_block_invoke_2 : 144 -> 132
~ -[IMDebugViewController dismiss] : 72 -> 60
~ -[IMDebugViewController setScreenShotImage:] : 296 -> 284
~ -[IMDebugViewController .cxx_destruct] : 204 -> 192
~ +[DebugUtil isDebugEnabled] : 76 -> 64
~ ___31+[DebugUtil _isInternalInstall]_block_invoke : 88 -> 76
~ +[DebugUtil getIPAddress] : 236 -> 224
~ +[DebugUtil applicationDocumentsDirectory] : 116 -> 104
~ +[DebugUtil allViewControllers] : 208 -> 196
~ +[DebugUtil sharedApplicationIfPossible] : 84 -> 72
```
