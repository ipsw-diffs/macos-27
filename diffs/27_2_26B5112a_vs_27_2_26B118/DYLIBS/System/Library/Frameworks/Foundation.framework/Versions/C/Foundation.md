## Foundation

> `/System/Library/Frameworks/Foundation.framework/Versions/C/Foundation`

```diff

 5027.1.8.0.0
-  __TEXT.__text: 0xd681b0
+  __TEXT.__text: 0xd68230
   __TEXT.__delay_stubs: 0x800
   __TEXT.__delay_helper: 0x184
   __TEXT.__objc_methlist: 0x2d6ac

   __TEXT.__gcc_except_tab: 0x73b8
   __TEXT.__ustring: 0x53e
   __TEXT.__dof_NSProcess: 0x34f
-  __TEXT.__dof_NSXPCProx: 0x7a2
+  __TEXT.__dof_NSXPCProx: 0x7a3
   __TEXT.__dof_NSXPCList: 0x2e9
   __TEXT.__dof_NSXPCConn: 0x26ce
   __TEXT.__dof_NSXPCLis0: 0x865
Functions:
~ -[NSUUID init] : 108 -> 100
~ +[NSNumber initialize] : 84 -> 92
~ +[NSNumber numberWithFloat:] : 208 -> 200
~ +[NSNumber allocWithZone:] : 48 -> 40
~ ___copy_helper_block_e8_32r : 20 -> 28
~ +[NSValue valueWithPointer:] : 104 -> 112
~ _cachedObjCTypeInfoIsEqual : 40 -> 48
~ -[NSValue pointerValue] : 136 -> 144
~ -[NSThread main] : 180 -> 172
~ +[NSValue valueWithRect:] : 108 -> 116
~ -[NSFileManager removeItemAtPath:error:] : 28 -> 20
~ +[NSValue valueWithWeakObject:] : 56 -> 64
~ +[NSValue allocWithZone:] : 36 -> 48
~ -[NSFileManager createDirectoryAtPath:withIntermediateDirectories:attributes:error:] : 16 -> 20
~ -[NSConcreteValue hash] : 212 -> 260
~ -[NSConcreteValue _value] : 12 -> 4
~ -[NSValue rectValue] : 152 -> 160
~ -[NSConcreteMapTable keyEnumerator] : 64 -> 56
~ +[NSObject(NSDelayedPerforming) cancelPreviousPerformRequestsWithTarget:] : 588 -> 592
~ -[NSObject(DefaultObservationImplementations) receiveObservedValue:] : 260 -> 264
~ -[NSComparisonPredicateOperator options] : 24 -> 32
~ -[NSUserActivity(NSUserActivityPrivate) _suggestedActionType] : 28 -> 36
~ -[NSString(NSURLUtilities) stringByAddingPercentEncodingWithAllowedCharacters:] : 148 -> 144
~ -[NSKeyedUnarchiver delegate] : 24 -> 20
~ -[NSNumberFormatter _regenerateFormatter] : 2280 -> 2272
~ -[NSURL(NSURL) hasDirectoryPath] : 224 -> 216
~ _parseJSONUnicodePointAtLocation : 496 -> 504
~ +[NSCharacterSet illegalCharacterSet] : 20 -> 12
~ +[NSValue supportsSecureCoding] : 20 -> 12
~ -[NSPlaceholderValue initWithCoder:] : 12 -> 20
~ __NSGetValueWithMethod : 248 -> 256
~ ____NSSetSizeValueAndNotify_block_invoke : 76 -> 68
~ -[NSValue classForCoder] : 16 -> 20
~ +[NSURL(NSURL) fileURLWithPath:isDirectory:relativeToURL:] : 80 -> 84
~ sub_180cb9ccc -> sub_180cb9d1c : 72 -> 68
~ -[NSDistributedLock description] : 112 -> 116
~ -[NSString(NSUserDefaults_NSURLExtras) _web_HTTPStyleLanguageCodeWithoutRegion] : 96 -> 92
~ -[NSWeakObjectValue hash] : 44 -> 48
~ -[NSValue hash] : 392 -> 448
~ -[NSValue initWithCoder:] : 72 -> 80
~ -[NSValue objCType] : 44 -> 36
~ -[NSValue initWithBytes:objCType:] : 48 -> 40
```
