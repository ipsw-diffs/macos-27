## Flurry

> `/System/Library/ExtensionKit/Extensions/Flurry.appex/Contents/MacOS/Flurry`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 2027.0.1.0.0
-  __TEXT.__text: 0x492c
+  __TEXT.__text: 0x47e8
   __TEXT.__auth_stubs: 0x4c0
   __TEXT.__objc_stubs: 0x860
   __TEXT.__objc_methlist: 0x2f0

   __TEXT.__oslogstring: 0x90
   __TEXT.__swift5_types: 0x10
   __TEXT.__swift5_reflstr: 0x48
-  __TEXT.__unwind_info: 0x190
+  __TEXT.__unwind_info: 0x1d0
   __DATA_CONST.__const: 0x78
   __DATA_CONST.__cfstring: 0x160
   __DATA_CONST.__objc_classlist: 0x38
Functions:
~ _MakeTexture : 1448 -> 1444
~ _SmoothTexture : 300 -> 308
~ _UpdateSmoke_ScalarBase : 1748 -> 1824
~ _DrawSmoke_Scalar : 1168 -> 1160
~ -[AppleFlurryOpenGLView reshape] : 148 -> 136
~ -[AppleFlurryOpenGLView lock] : 80 -> 68
~ -[AppleFlurryOpenGLView unlock] : 76 -> 64
~ -[AppleFlurryOpenGLView drawRect:] : 116 -> 104
~ +[AppleFlurryView initialize] : 56 -> 44
~ -[AppleFlurryView drawRect:] : 72 -> 60
~ -[AppleFlurryView animateOneFrame] : 80 -> 68
~ -[AppleFlurryView reloadDefaults:] : 464 -> 452
~ -[AppleFlurryView gl_init] : 316 -> 304
~ -[AppleFlurryView gl_display] : 412 -> 400
~ -[AppleFlurryView gl_reshape::] : 228 -> 216
~ _GLSetupRC : 524 -> 528
~ _GLRenderScene : 348 -> 336
~ +[AppleFlurry flurryWithStreamCount:colorMode:thickness:speed:] : 128 -> 116
~ +[AppleFlurry flurryWithDictionary:] : 184 -> 172
~ -[AppleFlurry encodeWithCoder:] : 164 -> 152
~ sub_1000046c0 -> sub_100004658 : 484 -> 464
~ ___swift_allocate_value_buffer : 100 -> 80
~ ___swift_project_value_buffer : 56 -> 36
~ sub_1000049bc -> sub_100004918 : 1108 -> 1088
~ sub_100004e10 -> sub_100004d58 : 60 -> 48
~ sub_100004fe8 -> sub_100004f24 : 72 -> 60
~ sub_100005040 -> sub_100004f70 : 72 -> 60
~ sub_100005098 -> sub_100004fbc : 72 -> 60
~ sub_1000050f0 -> sub_100005008 : 72 -> 60
~ sub_100005148 -> sub_100005054 : 72 -> 60
~ sub_100005318 -> sub_100005218 : 1284 -> 1252
~ sub_10000581c -> sub_1000056fc : 60 -> 48
~ sub_100005ba8 -> sub_100005a7c : 100 -> 88
~ sub_100005c40 -> sub_100005b08 : 124 -> 112
```
