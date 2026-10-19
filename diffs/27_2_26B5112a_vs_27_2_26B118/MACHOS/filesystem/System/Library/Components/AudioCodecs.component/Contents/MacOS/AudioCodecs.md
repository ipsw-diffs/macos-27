## AudioCodecs

> `/System/Library/Components/AudioCodecs.component/Contents/MacOS/AudioCodecs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

 818.205.0.0.0
-  __TEXT.__text: 0x61a93c
+  __TEXT.__text: 0x61aa08
   __TEXT.__realtime: 0x3b4
   __TEXT.__auth_stubs: 0x1910
   __TEXT.__const: 0x334b98
   __TEXT.__cstring: 0xc7e2
   __TEXT.__gcc_except_tab: 0x134c8
-  __TEXT.__oslogstring: 0x1bc3c
+  __TEXT.__oslogstring: 0x1bcc2
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0xb1a8
   __TEXT.__eh_frame: 0x6a8

   - /usr/lib/libc++.1.dylib
   Functions: 9878
   Symbols:   17833
-  CStrings:  3536
+  CStrings:  3537
 
Functions:
~ __ZN17HOASpatialDecoder11DeserializeER16TBitstreamReaderIjE : 5000 -> 5096
~ __ZN14APACHOADecoder10InitializeERK11ACParamListN4apac12observer_ptrINS3_10IASCConfigEEE : 6932 -> 7040
CStrings:
+ "%25s:%-5d  Failed to initialize: mNumHOAcoeffs exceeds kMaxNumSCs_DynSelSCs4EachSB array dimension in HOASpatialDecoder::Initialize()"
+ "16:17:22"
- "21:58:45"
```
