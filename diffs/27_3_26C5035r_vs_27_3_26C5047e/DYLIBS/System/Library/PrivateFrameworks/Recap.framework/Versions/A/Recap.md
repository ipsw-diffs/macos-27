## Recap

> `/System/Library/PrivateFrameworks/Recap.framework/Versions/A/Recap`

```diff

-202.2.4.0.0
-  __TEXT.__text: 0x207b0
-  __TEXT.__objc_methlist: 0x3420
-  __TEXT.__const: 0x340
-  __TEXT.__cstring: 0x1b9f
-  __TEXT.__oslogstring: 0x425
-  __TEXT.__gcc_except_tab: 0xb3c
+202.2.9.0.0
+  __TEXT.__text: 0x226d4
+  __TEXT.__objc_methlist: 0x34a0
+  __TEXT.__const: 0x358
+  __TEXT.__cstring: 0x206d
+  __TEXT.__oslogstring: 0x45b
+  __TEXT.__gcc_except_tab: 0xcdc
   __TEXT.__ustring: 0x1e
   __TEXT.__dlopen_cstrs: 0x5c
-  __TEXT.__unwind_info: 0xb30
+  __TEXT.__unwind_info: 0xb98
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1a0
+  __DATA_CONST.__const: 0x1e0
   __DATA_CONST.__objc_classlist: 0x140
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0xd0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1c68
+  __DATA_CONST.__objc_selrefs: 0x1ce0
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x4a0
-  __DATA_CONST.__got: 0x2e8
-  __AUTH_CONST.__const: 0x810
-  __AUTH_CONST.__cfstring: 0x2020
-  __AUTH_CONST.__objc_const: 0x50c0
+  __DATA_CONST.__got: 0x2f0
+  __AUTH_CONST.__const: 0x930
+  __AUTH_CONST.__cfstring: 0x23e0
+  __AUTH_CONST.__objc_const: 0x50f8
   __AUTH_CONST.__objc_intobj: 0x3c0
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x258
-  __AUTH_CONST.__auth_got: 0x5d8
+  __AUTH_CONST.__auth_got: 0x5e8
   __AUTH.__objc_data: 0x730
-  __DATA.__objc_ivar: 0x38c
+  __DATA.__objc_ivar: 0x390
   __DATA.__data: 0x9c8
   __DATA.__bss: 0x118
   __DATA.__common: 0x4

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 995
-  Symbols:   2647
-  CStrings:  375
+  Functions: 1020
+  Symbols:   2704
+  CStrings:  408
 
Symbols:
+ +[RCPSyntheticEventStream _eventStreamWithCLIArguments:displayUUID:overridesDisplayUUID:]
+ +[RCPSyntheticEventStream eventStreamWithCLIArguments:overridingDisplayUUID:]
+ -[RCPEventScreen isBuiltIn]
+ -[RCPEventScreen setBuiltIn:]
+ -[RCPEventStream cliArgumentsApproximatingGesture:]
+ -[RCPEventStream cliCommandApproximatingGesture:]
+ -[RCPEventStream streamsBySplittingWithType:marks:filenameAdditions:]
+ -[RCPPlayerPlaybackOptions description]
+ -[RCPSyntheticEventStream pinchAtCenter:startSpan:endSpan:angle:duration:]
+ GCC_except_table11
+ GCC_except_table31
+ GCC_except_table41
+ GCC_except_table43
+ GCC_except_table61
+ _CGDisplayIsBuiltin
+ _IOHIDEventGetEvent
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_IVAR_$_RCPEventScreen._builtIn
+ __RCPCLICoordinateString
+ __RCPCLINumberString
+ __RCPResolveDisplayUUIDArgument
+ ___69-[RCPEventStream streamsBySplittingWithType:marks:filenameAdditions:]_block_invoke
+ ___69-[RCPEventStream streamsBySplittingWithType:marks:filenameAdditions:]_block_invoke_2
+ ___69-[RCPEventStream streamsBySplittingWithType:marks:filenameAdditions:]_block_invoke_3
+ ___89+[RCPSyntheticEventStream _eventStreamWithCLIArguments:displayUUID:overridesDisplayUUID:]_block_invoke
+ ____RCPCLIDigitizerPath_block_invoke
+ ____RCPResolveDisplayUUIDArgument_block_invoke
+ ___block_descriptor_32_e41_B24?0"RCPEventScreen"8"NSDictionary"16l
+ ___block_descriptor_32_e68_Q40?0"RCPEvent"8Q16"NSNumber"24"_RCPEventDigitizerStreamState"32l
+ ___block_descriptor_40_e8_32s_e68_Q40?0"RCPEvent"8Q16"NSNumber"24"_RCPEventDigitizerStreamState"32l
+ ___block_descriptor_48_e8_32r40r_e30_v32?0^{__IOHIDEvent=}8Q16^B24l
+ ___block_descriptor_57_e8_32s40s48r_e34_v16?0"<RCPEventStreamComposer>"8l
+ ___block_descriptor_88_e8_32s40s48s56s64bs72r80r_e21_v24?0"RCPEvent"8Q16l
+ ___block_descriptor_96_e8_32s40s48s56s64s72r80r_e21_v24?0"RCPEvent"8Q16l
+ ___copy_helper_block_e8_32r40r
+ ___copy_helper_block_e8_32s40s48s56s64b72r80r
+ ___copy_helper_block_e8_32s40s48s56s64s72r80r
+ ___destroy_helper_block_e8_32r40r
+ ___destroy_helper_block_e8_32s40s48s56s64s72r80r
+ _kRCPFingerLiftDelay
+ _kRCPMultiTapInterval
+ _objc_msgSend$_addEvent:
+ _objc_msgSend$_eventStreamWithCLIArguments:displayUUID:overridesDisplayUUID:
+ _objc_msgSend$caseInsensitiveCompare:
+ _objc_msgSend$cliArgumentsApproximatingGesture:
+ _objc_msgSend$containsString:
+ _objc_msgSend$countOfContactsChangeAmount
+ _objc_msgSend$countOfContactsTouching
+ _objc_msgSend$countOfContactsTouchingDidChange
+ _objc_msgSend$dataWithJSONObject:options:error:
+ _objc_msgSend$emptyCopy
+ _objc_msgSend$filteredArrayUsingPredicate:
+ _objc_msgSend$hasSuffix:
+ _objc_msgSend$ingestEvent:
+ _objc_msgSend$initWithData:encoding:
+ _objc_msgSend$isBuiltIn
+ _objc_msgSend$predicateWithBlock:
+ _objc_msgSend$setBuiltIn:
+ _objc_msgSend$streamStateWithEnvironment:
+ _objc_msgSend$timeIntervalSinceStreamStart
+ _objc_msgSend$touchDownAtPoints:touchCount:
+ _objc_msgSend$useHIDEventTimestampsForDelivery
- GCC_except_table20
- GCC_except_table37
- GCC_except_table59
- ___71+[RCPSyntheticEventStream eventStreamWithCLIArguments:withDisplayUUID:]_block_invoke
- ___block_descriptor_56_e8_32s40s48r_e34_v16?0"<RCPEventStreamComposer>"8l
CStrings:
+ " { playbackSpeedFactor: %g, minDelayBetweenSends: %g, useHIDEventTimestampsForDelivery: %@, linkEventDeliveryToDisplayRefreshRate: %@, transform: [%g, %g, %g, %g, %g, %g], displayUUIDOverrideSpecified: %@, displayUUIDOverride: %@, customizeHIDEvent: %@"
+ " }"
+ "%.*f"
+ "%0.6f"
+ "'%@'"
+ "--displayUUID %@ needs a device with exactly two built-in displays, found %lu"
+ "."
+ "0"
+ "08:36:23"
+ "B24@?0@\"RCPEventScreen\"8@\"NSDictionary\"16"
+ "Nov 10 2026"
+ "Please specify an x and y spacing between fingers for multi-finger tap\n"
+ "Q40@?0@\"RCPEvent\"8Q16@\"NSNumber\"24@\"_RCPEventDigitizerStreamState\"32"
+ "The inner built-in display has no display UUID on this device"
+ "a touch position is negative or not finite, which recap cannot express"
+ "event %lu comes from a different sender than the events before it"
+ "event %lu has %lu contacts"
+ "event %lu has no sender properties"
+ "event %lu is not a digitizer event (IOHIDEventType %u)"
+ "inner"
+ "more than one touch sequence (the second starts at event %lu)"
+ "nil"
+ "no contact touches the digitizer"
+ "outer"
+ "pinchAtCenter: called with %lu touches down; ignoring"
+ "recap -c"
+ "set"
+ "spacing"
+ "the recording has no events"
+ "the recording has no screen size"
+ "the recording has no usable timing"
+ "the sender has no primary usage page and usage"
+ "the touch ends with a cancel at event %lu"
+ "the touch never lifts"
+ "the touch returns to where it started"
- "00:56:38"
- "Oct 29 2026"
```
