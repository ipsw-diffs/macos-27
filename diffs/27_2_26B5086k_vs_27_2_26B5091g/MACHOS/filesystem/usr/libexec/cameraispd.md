## cameraispd

> `/usr/libexec/cameraispd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-20.104.2.0.0
-  __TEXT.__text: 0x8bde0
+20.105.2.0.0
+  __TEXT.__text: 0x8bd78
   __TEXT.__auth_stubs: 0x18d0
   __TEXT.__objc_stubs: 0x9c0
   __TEXT.__init_offsets: 0x1c
   __TEXT.__objc_methlist: 0x334
-  __TEXT.__cstring: 0x66b7
-  __TEXT.__const: 0x1ff10
+  __TEXT.__cstring: 0x6661
+  __TEXT.__const: 0x1ff80
   __TEXT.__gcc_except_tab: 0xed0
   __TEXT.__oslogstring: 0x49ff
   __TEXT.__objc_methname: 0xa0c

   __TEXT.__objc_methtype: 0x5f9
   __TEXT.__unwind_info: 0x1820
   __DATA_CONST.__const: 0x8b18
-  __DATA_CONST.__cfstring: 0x2920
+  __DATA_CONST.__cfstring: 0x2860
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_intobj: 0x18
   __DATA_CONST.__auth_got: 0xc78
-  __DATA_CONST.__got: 0x1408
+  __DATA_CONST.__got: 0x1438
   __DATA_CONST.__auth_ptr: 0x40
   __DATA.__objc_const: 0x5c8
   __DATA.__objc_selrefs: 0x3a0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 1384
-  Symbols:   1059
-  CStrings:  1559
+  Symbols:   1065
+  CStrings:  1553
 
Symbols:
+ _kFigCaptureStreamMetadata_SmartTapAlgorithmMetadata
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_FocusBias
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_MaskConfidence
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ObjectID
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_TotalPoints
+ _kFigCaptureStreamSegmentFocusTrackingDataKey_ValidCoverage
Functions:
~ sub_10004b888 : 52520 -> 52524
~ sub_10005870c -> sub_100058710 : 165352 -> 165244
CStrings:
+ "20.105.2"
- "20.104.2"
- "FocusBias"
- "MaskConfidence"
- "ObjectID"
- "SmartTapAlgorithmMetadata"
- "TotalPoints"
- "ValidCoverage"
```
