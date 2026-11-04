## TypistFramework

> `/System/Library/PrivateFrameworks/TypistFramework.framework/Versions/A/TypistFramework`

```diff

-501.0.0.0.0
-  __TEXT.__text: 0x12b98
-  __TEXT.__objc_methlist: 0x1594
-  __TEXT.__const: 0x272
-  __TEXT.__ustring: 0xaa0
-  __TEXT.__cstring: 0x2a72
+505.0.0.0.0
+  __TEXT.__text: 0x19324
+  __TEXT.__objc_methlist: 0x1934
+  __TEXT.__const: 0x3f2
+  __TEXT.__ustring: 0xb0e
+  __TEXT.__cstring: 0x3052
   __TEXT.__gcc_except_tab: 0x1fc
   __TEXT.__oslogstring: 0xc
   __TEXT.__swift5_typeref: 0xaa

   __TEXT.__swift5_fieldmd: 0x94
   __TEXT.__swift5_proto: 0x4
   __TEXT.__swift5_types: 0x10
-  __TEXT.__unwind_info: 0x5f8
+  __TEXT.__unwind_info: 0x750
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe8
-  __DATA_CONST.__objc_classlist: 0xb8
+  __DATA_CONST.__const: 0x108
+  __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf90
-  __DATA_CONST.__objc_classrefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x50
-  __DATA_CONST.__objc_arraydata: 0x1fa0
-  __DATA_CONST.__got: 0x1e0
-  __AUTH_CONST.__const: 0x8e8
-  __AUTH_CONST.__cfstring: 0x9cc0
-  __AUTH_CONST.__objc_const: 0x2310
-  __AUTH_CONST.__objc_intobj: 0x1308
-  __AUTH_CONST.__objc_arrayobj: 0x48
+  __DATA_CONST.__objc_selrefs: 0x12a8
+  __DATA_CONST.__objc_superrefs: 0x68
+  __DATA_CONST.__objc_arraydata: 0x2008
+  __DATA_CONST.__got: 0x218
+  __AUTH_CONST.__const: 0x9d8
+  __AUTH_CONST.__cfstring: 0xa360
+  __AUTH_CONST.__objc_const: 0x27e0
+  __AUTH_CONST.__objc_intobj: 0x1320
+  __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0x430
-  __AUTH.__objc_data: 0x598
+  __AUTH_CONST.__objc_doubleobj: 0x70
+  __AUTH_CONST.__auth_got: 0x4a8
+  __AUTH.__objc_data: 0x688
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x13c
+  __DATA.__objc_ivar: 0x178
   __DATA.__data: 0x1e0
-  __DATA.__bss: 0x260
+  __DATA.__bss: 0x280
   __DATA_DIRTY.__objc_data: 0x1b8
   __DATA_DIRTY.__bss: 0x58
   - /System/Library/Frameworks/Carbon.framework/Versions/A/Carbon

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 559
-  Symbols:   1336
-  CStrings:  1280
+  Functions: 653
+  Symbols:   1564
+  CStrings:  1337
 
Symbols:
+ +[NSCharacterSet(Devanagari) headlineBearingCharacterSet]
+ +[TypistDevanagariSyllable hasHeadline:]
+ +[TypistKeyboardData getForceLegacyImplementation]
+ +[TypistKeyboardDataInputUIClient generateSnapshotForInputMode:keyplaneName:]
+ +[TypistKeyboardDataInputUIClient isActiveKeyboardEquivalentTo:]
+ +[TypistKeyboardDataInputUIClient isKeyboardVisible]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualGroupSpanForTouchCount:overlapStyle:holdDuration:overlapRatio:]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualIsPlainTapAction:]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualIsWaitAction:]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualOverlapStyleForRollToChordMix:uniform:]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualPressOrderForTouchCount:transposed:uniform:]
+ +[TypistKeyboardUtilities(BimanualUtilities) bimanualScheduleForPressOrder:overlapStyle:holdDuration:overlapRatio:]
+ +[TypistKeyboardUtilities(BimanualUtilities) fingerIndexForKeyCenter:withinBounds:fingerCount:]
+ +[TypistKeyboardUtilities(BimanualUtilities) validateBimanualOverlapRatio:forOverlapStyle:touchCount:]
+ +[TypistKeyboardUtilities(MathUtilities) _microDragTagActions:taggedCopies:fingerForAction:]
+ +[TypistKeyboardUtilities(MathUtilities) acceptsTapNoiseForKey:]
+ +[TypistKeyboardUtilities(MathUtilities) annotateMicroDragAction:withSample:]
+ +[TypistKeyboardUtilities(MathUtilities) annotatePressDurationAction:withSample:]
+ +[TypistKeyboardUtilities(MathUtilities) indexOfNearestThumbArcForKeyCenter:references:count:millimetresPerPoint:]
+ +[TypistKeyboardUtilities(MathUtilities) inverseNormalCDF:]
+ +[TypistKeyboardUtilities(MathUtilities) isMicroDragTouchDownAction:]
+ +[TypistKeyboardUtilities(MathUtilities) isPlaneControlKey:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragEligibleForLettersPlane:acceptsTapNoise:tenKey:kana:flick:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragFilledBoundsForTouchDownBounds:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragFingerSourceForBimanualRate:twoThumb:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragSampleForTuning:uniformMix:uniformMagnitude:uniformDirection:uniformFallback:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragStream:taggingFingersWith:]
+ +[TypistKeyboardUtilities(MathUtilities) microDragTuningForTwoThumb:scale:median:spread:severity:substantialRate:directionSpread:]
+ +[TypistKeyboardUtilities(MathUtilities) pointOffsetFromEdge:ofRect:offset:crossAxisFraction:]
+ +[TypistKeyboardUtilities(MathUtilities) pressDurationSampleForTuning:uniformDuration:uniformSplit:]
+ +[TypistKeyboardUtilities(MathUtilities) pressDurationTuningForMedian:spread:]
+ +[TypistKeyboardUtilities(RecapUtilities) _bimanualRenamingReleasesForSchedule:touchCount:]
+ +[TypistKeyboardUtilities(RecapUtilities) _commandsForSegment:segmentOffset:bimanualGroups:displayUUID:]
+ +[TypistKeyboardUtilities(RecapUtilities) _compileCLICommandsFromActions:]
+ +[TypistKeyboardUtilities(RecapUtilities) _composeBimanualGroup:segmentActions:segmentOffset:intoComposer:slots:lastTime:]
+ +[TypistKeyboardUtilities(RecapUtilities) _composeSerialTapAction:intoComposer:commandString:commandDescription:]
+ +[TypistKeyboardUtilities(RecapUtilities) _composedCommandForSegment:segmentOffset:groups:displayUUID:]
+ +[TypistKeyboardUtilities(RecapUtilities) bimanualDragEndsForGroup:segmentActions:segmentOffset:moveDuration:]
+ +[TypistKeyboardUtilities(RecapUtilities) bimanualRenamedTouchesForSchedule:touchCount:]
+ +[TypistKeyboardUtilities(RecapUtilities) bimanualTimelineForSchedule:startPoints:dragEnds:moveDuration:touchFrequency:]
+ +[TypistKeyboardUtilities(RecapUtilities) convertRecapCommandsFromListOfActions:bimanualGroups:]
+ +[TypistKeyboardUtilities(RecapUtilities) flattenedActionsForKeystrokeStream:]
+ +[TypistKeyboardUtilities(RecapUtilities) microDragActivePoints:forSlots:currentPoints:]
+ +[TypistKeyboardUtilities(RecapUtilities) microDragCLIFragmentForAction:radiusAddition:]
+ +[TypistKeyboardUtilities(RecapUtilities) microDragMoveStepCountForDuration:touchFrequency:]
+ +[TypistKeyboardUtilities(RecapUtilities) plainTapCLIFragmentForAction:radiusAddition:]
+ +[TypistKeyboardUtilities(RecapUtilities) resolveMicroDragEndpointsForActions:screenSize:]
+ -[TYBimanualGroup .cxx_destruct]
+ -[TYBimanualGroup actionRange]
+ -[TYBimanualGroup description]
+ -[TYBimanualGroup fingerIndexes]
+ -[TYBimanualGroup hasConsistentActionRange]
+ -[TYBimanualGroup initWithActionRange:taps:fingerIndexes:pressOrder:overlapStyle:holdDuration:overlapRatio:trailingInterval:]
+ -[TYBimanualGroup isTransposed]
+ -[TYBimanualGroup keyDescription]
+ -[TYBimanualGroup overlapStyle]
+ -[TYBimanualGroup pressOrder]
+ -[TYBimanualGroup schedule]
+ -[TYBimanualGroup taps]
+ -[TYBimanualGroup trailingInterval]
+ -[TYBimanualTimelineEvent .cxx_destruct]
+ -[TYBimanualTimelineEvent description]
+ -[TYBimanualTimelineEvent initWithKind:time:touchIndex:movedPoints:]
+ -[TYBimanualTimelineEvent kind]
+ -[TYBimanualTimelineEvent movedPoints]
+ -[TYBimanualTimelineEvent time]
+ -[TYBimanualTimelineEvent touchIndex]
+ -[TYBimanualTouchEvent description]
+ -[TYBimanualTouchEvent initWithTouchIndex:time:isDown:]
+ -[TYBimanualTouchEvent isDown]
+ -[TYBimanualTouchEvent time]
+ -[TYBimanualTouchEvent touchIndex]
+ -[TYRecapCommand initWithCommandType:eventStream:commandString:commandDescription:]
+ -[TypistKeyboard _recapCommandsForKeystrokeStream:]
+ -[TypistKeyboard _warnOnceIfBimanualIsUnreachableUnderPrediction]
+ GCC_except_table45
+ _CGRectGetHeight
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _CGRectGetMidX
+ _CGRectGetMidY
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _CGRectGetWidth
+ _CGRectIsInfinite
+ _CGRectIsNull
+ _NSStringFromClass
+ _OBJC_CLASS_$_NSMapTable
+ _OBJC_CLASS_$_NSMutableIndexSet
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_NSSet
+ _OBJC_CLASS_$_TYBimanualGroup
+ _OBJC_CLASS_$_TYBimanualTimelineEvent
+ _OBJC_CLASS_$_TYBimanualTouchEvent
+ _OBJC_IVAR_$_TYBimanualGroup._actionRange
+ _OBJC_IVAR_$_TYBimanualGroup._fingerIndexes
+ _OBJC_IVAR_$_TYBimanualGroup._isTransposed
+ _OBJC_IVAR_$_TYBimanualGroup._overlapStyle
+ _OBJC_IVAR_$_TYBimanualGroup._pressOrder
+ _OBJC_IVAR_$_TYBimanualGroup._schedule
+ _OBJC_IVAR_$_TYBimanualGroup._taps
+ _OBJC_IVAR_$_TYBimanualGroup._trailingInterval
+ _OBJC_IVAR_$_TYBimanualTimelineEvent._kind
+ _OBJC_IVAR_$_TYBimanualTimelineEvent._movedPoints
+ _OBJC_IVAR_$_TYBimanualTimelineEvent._time
+ _OBJC_IVAR_$_TYBimanualTimelineEvent._touchIndex
+ _OBJC_IVAR_$_TYBimanualTouchEvent._isDown
+ _OBJC_IVAR_$_TYBimanualTouchEvent._time
+ _OBJC_IVAR_$_TYBimanualTouchEvent._touchIndex
+ _OBJC_METACLASS_$_TYBimanualGroup
+ _OBJC_METACLASS_$_TYBimanualTimelineEvent
+ _OBJC_METACLASS_$_TYBimanualTouchEvent
+ _TYBimanualReleaseSlot
+ _TYMicroDragDescription
+ _TYMicroDragEndPoint
+ _TYMicroDragHasNumber
+ _TYMicroDragMove
+ _TYMicroDragSettle
+ _TYOptionalRadiusAddition
+ _TYTapHasHold
+ _TYTapHold
+ __OBJC_$_CLASS_METHODS_TypistKeyboardUtilities(BimanualUtilities|KeyboardSettings|MathUtilities|RecapUtilities)
+ __OBJC_$_INSTANCE_METHODS_TYBimanualGroup
+ __OBJC_$_INSTANCE_METHODS_TYBimanualTimelineEvent
+ __OBJC_$_INSTANCE_METHODS_TYBimanualTouchEvent
+ __OBJC_$_INSTANCE_VARIABLES_TYBimanualGroup
+ __OBJC_$_INSTANCE_VARIABLES_TYBimanualTimelineEvent
+ __OBJC_$_INSTANCE_VARIABLES_TYBimanualTouchEvent
+ __OBJC_$_PROP_LIST_TYBimanualGroup
+ __OBJC_$_PROP_LIST_TYBimanualTimelineEvent
+ __OBJC_$_PROP_LIST_TYBimanualTouchEvent
+ __OBJC_CLASS_RO_$_TYBimanualGroup
+ __OBJC_CLASS_RO_$_TYBimanualTimelineEvent
+ __OBJC_CLASS_RO_$_TYBimanualTouchEvent
+ __OBJC_METACLASS_RO_$_TYBimanualGroup
+ __OBJC_METACLASS_RO_$_TYBimanualTimelineEvent
+ __OBJC_METACLASS_RO_$_TYBimanualTouchEvent
+ ___103+[TypistKeyboardUtilities(RecapUtilities) _composedCommandForSegment:segmentOffset:groups:displayUUID:]_block_invoke
+ ___115+[TypistKeyboardUtilities(BimanualUtilities) bimanualScheduleForPressOrder:overlapStyle:holdDuration:overlapRatio:]_block_invoke
+ ___120+[TypistKeyboardUtilities(RecapUtilities) bimanualTimelineForSchedule:startPoints:dragEnds:moveDuration:touchFrequency:]_block_invoke
+ ___57+[NSCharacterSet(Devanagari) headlineBearingCharacterSet]_block_invoke
+ ___71+[TypistKeyboardUtilities(BimanualUtilities) bimanualIsPlainTapAction:]_block_invoke
+ ___74+[TypistKeyboardUtilities(RecapUtilities) _compileCLICommandsFromActions:]_block_invoke
+ ___block_descriptor_32_e61_q24?0"TYBimanualTimelineEvent"8"TYBimanualTimelineEvent"16l
+ ___block_descriptor_40_e8_32s_e46_v32?0"NSNumber"8"NSMutableDictionary"16^B24l
+ ___block_descriptor_48_e8_32s_e55_q24?0"TYBimanualTouchEvent"8"TYBimanualTouchEvent"16l
+ ___block_descriptor_88_e8_32s40s48s56s64s_e34_v16?0"<RCPEventStreamComposer>"8l
+ ___copy_helper_block_e8_32s40s48s56s64s
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ _bimanualIsPlainTapAction:.nonTapCommands
+ _bimanualIsPlainTapAction:.onceToken
+ _exp
+ _headlineBearingCharacterSet.onceToken
+ _headlineBearingCharacterSet.set
+ _nextafter
+ _objc_msgSend$_bimanualRenamingReleasesForSchedule:touchCount:
+ _objc_msgSend$_commandsForSegment:segmentOffset:bimanualGroups:displayUUID:
+ _objc_msgSend$_compileCLICommandsFromActions:
+ _objc_msgSend$_composeBimanualGroup:segmentActions:segmentOffset:intoComposer:slots:lastTime:
+ _objc_msgSend$_composeSerialTapAction:intoComposer:commandString:commandDescription:
+ _objc_msgSend$_composedCommandForSegment:segmentOffset:groups:displayUUID:
+ _objc_msgSend$_microDragTagActions:taggedCopies:fingerForAction:
+ _objc_msgSend$_recapCommandsForKeystrokeStream:
+ _objc_msgSend$actionRange
+ _objc_msgSend$addIndex:
+ _objc_msgSend$allKeys
+ _objc_msgSend$bimanualDragEndsForGroup:segmentActions:segmentOffset:moveDuration:
+ _objc_msgSend$bimanualIsPlainTapAction:
+ _objc_msgSend$bimanualIsWaitAction:
+ _objc_msgSend$bimanualScheduleForPressOrder:overlapStyle:holdDuration:overlapRatio:
+ _objc_msgSend$bimanualTimelineForSchedule:startPoints:dragEnds:moveDuration:touchFrequency:
+ _objc_msgSend$boolValue
+ _objc_msgSend$containsObject:
+ _objc_msgSend$convertRecapCommandsFromListOfActions:bimanualGroups:
+ _objc_msgSend$defaultPressure
+ _objc_msgSend$defaultRadius
+ _objc_msgSend$exchangeObjectAtIndex:withObjectAtIndex:
+ _objc_msgSend$flattenedActionsForKeystrokeStream:
+ _objc_msgSend$getForceLegacyImplementation
+ _objc_msgSend$hasConsistentActionRange
+ _objc_msgSend$headlineBearingCharacterSet
+ _objc_msgSend$indexOfNearestThumbArcForKeyCenter:references:count:millimetresPerPoint:
+ _objc_msgSend$indexOfObject:
+ _objc_msgSend$initWithCommandType:eventStream:commandString:commandDescription:
+ _objc_msgSend$initWithKind:time:touchIndex:movedPoints:
+ _objc_msgSend$initWithTouchIndex:time:isDown:
+ _objc_msgSend$inverseNormalCDF:
+ _objc_msgSend$isDown
+ _objc_msgSend$isEqual:
+ _objc_msgSend$isMicroDragTouchDownAction:
+ _objc_msgSend$isPlaneControlKey:
+ _objc_msgSend$isTransposed
+ _objc_msgSend$keyDescription
+ _objc_msgSend$kind
+ _objc_msgSend$liftUpActivePointsByIndex:
+ _objc_msgSend$liftUpAtPoints:touchCount:
+ _objc_msgSend$mapTableWithKeyOptions:valueOptions:
+ _objc_msgSend$microDragActivePoints:forSlots:currentPoints:
+ _objc_msgSend$microDragCLIFragmentForAction:radiusAddition:
+ _objc_msgSend$microDragMoveStepCountForDuration:touchFrequency:
+ _objc_msgSend$moveToPoints:touchCount:pressure:duration:radius:
+ _objc_msgSend$movedPoints
+ _objc_msgSend$null
+ _objc_msgSend$numberWithBool:
+ _objc_msgSend$numberWithUnsignedInteger:
+ _objc_msgSend$overlapStyle
+ _objc_msgSend$plainTapCLIFragmentForAction:radiusAddition:
+ _objc_msgSend$pointValue
+ _objc_msgSend$rectValue
+ _objc_msgSend$removeObjectAtIndex:
+ _objc_msgSend$schedule
+ _objc_msgSend$senderPropertiesWithDisplayUUID:
+ _objc_msgSend$setObject:atIndexedSubscript:
+ _objc_msgSend$setWithArray:
+ _objc_msgSend$sortUsingComparator:
+ _objc_msgSend$sortWithOptions:usingComparator:
+ _objc_msgSend$sortedArrayUsingSelector:
+ _objc_msgSend$stringWithString:
+ _objc_msgSend$taps
+ _objc_msgSend$time
+ _objc_msgSend$touchDownAtPoints:touchCount:radius:
+ _objc_msgSend$touchFrequency
+ _objc_msgSend$touchIndex
+ _objc_msgSend$touchScreenDigitizerSender
+ _objc_msgSend$trailingInterval
+ _objc_msgSend$unsignedIntegerValue
+ _objc_msgSend$validateBimanualOverlapRatio:forOverlapStyle:touchCount:
+ _objc_msgSend$validateTouchPoint:withinBounds:
+ _objc_msgSend$valueWithPoint:
+ _objc_msgSend$valueWithRect:
+ _objc_opt_isKindOfClass
+ _objc_opt_respondsToSelector
+ _pow
- GCC_except_table17
- __OBJC_$_CLASS_METHODS_TypistKeyboardUtilities(KeyboardSettings|MathUtilities|RecapUtilities)
- ___81+[TypistKeyboardUtilities(RecapUtilities) convertRecapCommandsFromListOfActions:]_block_invoke
- _arc4random_uniform
- _objc_msgSend$convertRecapCommands:
CStrings:
+ " (drag %.1fpt%@)"
+ " D%lu %@@%.4f(%.0f,%.0f) n=%lu"
+ " M%lu %@@%.4f(%.1f,%.1f)"
+ " ROCK"
+ " TRANSPOSED"
+ " U%lu %@@%.4f MISSING-SLOT"
+ " U%lu %@@%.4f idx%lu OUT-OF-ORDER"
+ " U%lu %@@%.4f tail"
+ " n=%lu"
+ " transposed"
+ " | trailing=%.4f span=%.4f"
+ "# %@[%lu] %@ %@ "
+ "%.2f"
+ "%@ n=%lu"
+ "%@ when %@ lifts first"
+ "%@%@"
+ "+"
+ ","
+ ", transposed"
+ "1"
+ "<%@ %@ %@%@>"
+ "<%@ move %@ at %.4fs>"
+ "<%@ touch %lu %@ at %.4fs>"
+ "?"
+ "Failed to extract layout prefix from keyboardID: [%@]"
+ "Typing "
+ "[%@ %@%@] "
+ "bimanual trace: %@[%lu] %@%@ hold=%.4f |"
+ "bimanual: DROPPING group %@ - it puts %lu touches down at once, past Recap's limit of %d. Playing those taps serially instead."
+ "bimanual: DROPPING group %@ - it spans %lu actions but holds %lu taps, which would lose or duplicate a keystroke. Playing those taps serially instead. This is a bug in the group builder."
+ "bimanual: dropping %lu group(s), segment contains a \"%@\" which cannot be composed"
+ "bimanual: tap %lu of %@ is \"%@\" but action %lu is \"%@\". Playing it without a drag."
+ "chord"
+ "down"
+ "keyboardID is nil or empty, cannot determine region code"
+ "micro-drag: not dragging %@ in %@ %@ - Recap renames %@"
+ "microDragAngularOffset"
+ "microDragEndX"
+ "microDragEndY"
+ "microDragFallbackAngle"
+ "microDragFinger"
+ "microDragMagnitude"
+ "microDragMove"
+ "microDragSettle"
+ "microDragSubstantial"
+ "pressDurationHold"
+ "q24@?0@\"TYBimanualTimelineEvent\"8@\"TYBimanualTimelineEvent\"16"
+ "q24@?0@\"TYBimanualTouchEvent\"8@\"TYBimanualTouchEvent\"16"
+ "roll"
+ "t %@ %@ %@%.4f "
+ "t %@ %@ %@%.4f d %@ %@ %.4f "
+ "tap"
+ "transposed "
+ "up"
+ "v32@?0@\"NSNumber\"8@\"NSMutableDictionary\"16^B24"
+ "wait %@ "
+ "कखगघङचछजझञटठडढणतथदधनपफबभमयरलवशषसहळअआइईउऊऋऌएऐओऔऑॲािीॉोौ"
```
