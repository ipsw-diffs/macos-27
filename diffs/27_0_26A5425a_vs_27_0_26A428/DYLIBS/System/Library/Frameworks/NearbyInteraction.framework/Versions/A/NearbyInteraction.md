## NearbyInteraction

> `/System/Library/Frameworks/NearbyInteraction.framework/Versions/A/NearbyInteraction`

```diff

 568.0.0.0.0
-  __TEXT.__text: 0x378b0
-  __TEXT.__objc_methlist: 0x40e8
-  __TEXT.__gcc_except_tab: 0x5748
-  __TEXT.__cstring: 0x525c
+  __TEXT.__text: 0x38260
+  __TEXT.__objc_methlist: 0x4208
+  __TEXT.__gcc_except_tab: 0x57b4
+  __TEXT.__cstring: 0x5275
   __TEXT.__const: 0x500
-  __TEXT.__oslogstring: 0xe6b
+  __TEXT.__oslogstring: 0xf2d
   __TEXT.__swift5_typeref: 0x83
   __TEXT.__swift5_reflstr: 0x4b
   __TEXT.__swift5_assocty: 0x48

   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_proto: 0x28
   __TEXT.__swift5_types: 0x10
-  __TEXT.__unwind_info: 0x2060
+  __TEXT.__unwind_info: 0x20a8
   __TEXT.__eh_frame: 0x100
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x598
-  __DATA_CONST.__objc_classlist: 0x1b0
+  __DATA_CONST.__const: 0x5a0
+  __DATA_CONST.__objc_classlist: 0x1c0
   __DATA_CONST.__objc_catlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x40
+  __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e38
-  __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x198
+  __DATA_CONST.__objc_selrefs: 0x1ea8
+  __DATA_CONST.__objc_protorefs: 0x20
+  __DATA_CONST.__objc_superrefs: 0x1a0
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x2b0
+  __DATA_CONST.__got: 0x2b8
   __AUTH_CONST.__const: 0xb88
-  __AUTH_CONST.__cfstring: 0x5a00
-  __AUTH_CONST.__objc_const: 0x76c8
+  __AUTH_CONST.__cfstring: 0x5a20
+  __AUTH_CONST.__objc_const: 0x7d00
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x2b8
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x3d0
-  __DATA.__objc_ivar: 0x4ec
-  __DATA.__data: 0x3d0
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x4fc
+  __DATA.__data: 0x4f0
   __DATA.__common: 0x12d
   __DATA.__bss: 0x580
   __DATA_DIRTY.__objc_data: 0x10e0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1536
-  Symbols:   3470
-  CStrings:  924
+  Functions: 1553
+  Symbols:   3540
+  CStrings:  930
 
Symbols:
+ +[NIBody bodyWithUUID:]
+ -[NIBody .cxx_destruct]
+ -[NIBody _initWithUUID:]
+ -[NIBody _motionBodyID]
+ -[NIBodyToken .cxx_destruct]
+ -[NIBodyToken _didUpdateBody:]
+ -[NIBodyToken session]
+ -[NIBodyToken setSession:]
+ -[NISession _debugInjectFakeUUID:degrees:]
+ -[NISession _didUpdateBody:]
+ -[NISession _didUpdateBodyInternal:]
+ -[NISession originBody]
+ -[NISession setOriginBody:]
+ GCC_except_table115
+ GCC_except_table146
+ GCC_except_table151
+ GCC_except_table152
+ GCC_except_table160
+ GCC_except_table166
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table175
+ GCC_except_table178
+ GCC_except_table180
+ GCC_except_table193
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table197
+ GCC_except_table209
+ GCC_except_table210
+ GCC_except_table213
+ GCC_except_table216
+ GCC_except_table219
+ GCC_except_table226
+ GCC_except_table229
+ GCC_except_table232
+ GCC_except_table235
+ GCC_except_table238
+ GCC_except_table241
+ GCC_except_table242
+ GCC_except_table245
+ GCC_except_table247
+ GCC_except_table248
+ GCC_except_table251
+ GCC_except_table252
+ GCC_except_table262
+ GCC_except_table266
+ GCC_except_table267
+ GCC_except_table273
+ GCC_except_table279
+ GCC_except_table283
+ GCC_except_table285
+ GCC_except_table288
+ GCC_except_table294
+ GCC_except_table299
+ GCC_except_table305
+ GCC_except_table308
+ GCC_except_table311
+ GCC_except_table312
+ GCC_except_table315
+ GCC_except_table317
+ GCC_except_table321
+ GCC_except_table322
+ GCC_except_table333
+ GCC_except_table336
+ GCC_except_table337
+ GCC_except_table34
+ GCC_except_table340
+ GCC_except_table342
+ GCC_except_table343
+ GCC_except_table347
+ GCC_except_table35
+ GCC_except_table353
+ GCC_except_table66
+ GCC_except_table68
+ GCC_except_table76
+ OBJC_IVAR_$_NIBody._motionBodyID
+ OBJC_IVAR_$_NIBodyToken._session
+ OBJC_IVAR_$_NISession._bodyToken
+ OBJC_IVAR_$_NISession._originBody
+ _OBJC_CLASS_$_NIBody
+ _OBJC_CLASS_$_NIBodyToken
+ _OBJC_METACLASS_$_NIBody
+ _OBJC_METACLASS_$_NIBodyToken
+ __OBJC_$_CLASS_METHODS_NIBody
+ __OBJC_$_INSTANCE_METHODS_NIBody
+ __OBJC_$_INSTANCE_METHODS_NIBodyToken
+ __OBJC_$_INSTANCE_VARIABLES_NIBody
+ __OBJC_$_INSTANCE_VARIABLES_NIBodyToken
+ __OBJC_$_PROP_LIST_NIBody
+ __OBJC_$_PROP_LIST_NIBodyToken
+ __OBJC_$_PROP_LIST_NIUUIDBodyIdentifiable
+ __OBJC_$_PROP_LIST_NIViewBodyIdentifiable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NIUUIDBodyIdentifiable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NIViewBodyIdentifiable
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NIViewBodyIdentifiable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NIUUIDBodyIdentifiable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NIViewBodyIdentifiable
+ __OBJC_$_PROTOCOL_REFS_NIBodyIdentifiable
+ __OBJC_$_PROTOCOL_REFS_NIUUIDBodyIdentifiable
+ __OBJC_$_PROTOCOL_REFS_NIViewBodyIdentifiable
+ __OBJC_CLASS_PROTOCOLS_$_NIBody
+ __OBJC_CLASS_RO_$_NIBody
+ __OBJC_CLASS_RO_$_NIBodyToken
+ __OBJC_LABEL_PROTOCOL_$_NIBodyIdentifiable
+ __OBJC_LABEL_PROTOCOL_$_NIUUIDBodyIdentifiable
+ __OBJC_LABEL_PROTOCOL_$_NIViewBodyIdentifiable
+ __OBJC_METACLASS_RO_$_NIBody
+ __OBJC_METACLASS_RO_$_NIBodyToken
+ __OBJC_PROTOCOL_$_NIBodyIdentifiable
+ __OBJC_PROTOCOL_$_NIUUIDBodyIdentifiable
+ __OBJC_PROTOCOL_$_NIViewBodyIdentifiable
+ __OBJC_PROTOCOL_REFERENCE_$_NIUUIDBodyIdentifiable
+ __OBJC_PROTOCOL_REFERENCE_$_NIViewBodyIdentifiable
+ ___23-[NISession originBody]_block_invoke
+ ___27-[NISession setOriginBody:]_block_invoke
+ ___28-[NISession _didUpdateBody:]_block_invoke
+ ___42-[NISession _debugInjectFakeUUID:degrees:]_block_invoke
+ _objc_msgSend$_debugInjectFakeUUID:degrees:
+ _objc_msgSend$_didUpdateBody:
+ _objc_msgSend$_didUpdateBodyInternal:
+ _objc_msgSend$_initWithUUID:
+ _objc_msgSend$_interfaceAngle
+ _objc_msgSend$_motionBodyID
+ _objc_msgSend$_startUpdatingBodyToken:
+ _objc_msgSend$_stopUpdatingBodyToken:
+ _objc_msgSend$_updateInterfaceAngle:forBodyWithUUID:
+ _objc_msgSend$conformsToProtocol:
+ _objc_msgSend$session
+ _objc_msgSend$setSession:
- GCC_except_table107
- GCC_except_table118
- GCC_except_table149
- GCC_except_table154
- GCC_except_table163
- GCC_except_table169
- GCC_except_table185
- GCC_except_table187
- GCC_except_table188
- GCC_except_table189
- GCC_except_table190
- GCC_except_table191
- GCC_except_table200
- GCC_except_table201
- GCC_except_table202
- GCC_except_table203
- GCC_except_table204
- GCC_except_table205
- GCC_except_table217
- GCC_except_table218
- GCC_except_table221
- GCC_except_table224
- GCC_except_table227
- GCC_except_table234
- GCC_except_table237
- GCC_except_table240
- GCC_except_table243
- GCC_except_table246
- GCC_except_table258
- GCC_except_table259
- GCC_except_table264
- GCC_except_table265
- GCC_except_table268
- GCC_except_table270
- GCC_except_table271
- GCC_except_table275
- GCC_except_table277
- GCC_except_table282
- GCC_except_table287
- GCC_except_table289
- GCC_except_table291
- GCC_except_table296
- GCC_except_table301
- GCC_except_table307
- GCC_except_table310
- GCC_except_table313
- GCC_except_table319
- GCC_except_table320
- GCC_except_table324
- GCC_except_table325
- GCC_except_table329
- GCC_except_table331
- GCC_except_table345
- GCC_except_table49
- GCC_except_table62
- GCC_except_table64
- GCC_except_table71
- GCC_except_table80
- GCC_except_table81
- __ZL53InternalInterruptionReasonToNISessionSuspensionReason36UWBSessionInterruptionReasonInternal
CStrings:
+ "Body updated: %{private}@, interfaceAngle = %{public}.0f°"
+ "Debug inject UUID: %{private}@, angleDegrees: %{public}.1f°"
+ "DeviceAngleNotSupported"
+ "Set originBody: %{private}p"
+ "_didUpdateBody is called with an unknown body"
+ "\xf0\xf0A1"
```
