## BiomePubSub

> `/System/Library/PrivateFrameworks/BiomePubSub.framework/Versions/A/BiomePubSub`

```diff

-259.2.0.2.0
-  __TEXT.__text: 0x421f4
+259.5.0.0.0
+  __TEXT.__text: 0x42150
   __TEXT.__objc_methlist: 0x5894
   __TEXT.__const: 0x1010
   __TEXT.__cstring: 0x11bf
Symbols:
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
Functions:
~ -[_BPSMerged applyDownstreamWhileLocked:apply:] : 244 -> 240
~ -[_BPSAbstractOrderedMerge _completeWhileLockedWithCompletion:] : 284 -> 280
~ -[_BPSAbstractOrderedMerge receiveCompletion:atIndex:] : 640 -> 636
~ -[_BPSAbstractOrderedMerge flushBufferAndRequestMoreWhileLocked] : 728 -> 724
~ -[_BPSFlatMapOuter receiveCompletion:] : 884 -> 876
~ -[_BPSFlatMapOuter requestDemand:] : 1628 -> 1616
~ -[_BPSFlatMapOuter receiveInnerInput:index:] : 556 -> 548
~ -[_BPSFlatMapOuter receiveInnerCompletion:index:] : 1108 -> 1100
~ -[_BPSAbstractCombineLatest receiveInput:atIndex:] : 752 -> 748
~ -[_BPSAbstractCombineLatest receiveCompletion:atIndex:] : 1084 -> 1076
~ -[BPSSink cancel] : 340 -> 336
~ -[BPSSink subscribeTo:] : 360 -> 356
~ -[BPSSink requestNextEvents] : 276 -> 272
~ -[BPSSink completeWithError:] : 628 -> 624
~ -[BPSSink _cancel] : 100 -> 96
~ -[BPSDrivableSink cancel] : 340 -> 336
~ -[BPSDrivableSink subscribeTo:] : 360 -> 356
~ -[BPSDrivableSink requestNextEvents] : 316 -> 312
~ -[BPSDrivableSink completeWithError:] : 344 -> 340
~ -[BPSDrivableSink _cancel] : 100 -> 96
~ -[_BPSAbstractZip receiveSubscription:index:] : 708 -> 704
~ -[_BPSAbstractZip receiveInput:index:] : 1428 -> 1424
~ -[_BPSAbstractZip lockSendCompletion:index:] : 488 -> 484
~ -[_BPSInnerConduit offerInput:] : 268 -> 264
~ -[BPSPassThroughSubject startWithSubscriber:] : 104 -> 100
~ -[BPSPassThroughSubject nextEvent] : 192 -> 188
~ -[BPSPassThroughSubject reset] : 120 -> 116
~ -[BPSPassThroughSubject bookmark] : 92 -> 88
~ -[BPSPassThroughSubject applyBookmark:] : 100 -> 96
~ -[BPSPassThroughSubject sendCompletion] : 108 -> 104
~ -[BPSPassThroughSubject sendEvent:] : 148 -> 144
~ -[_BPSAbstractCorrelateOrderedMerge _completeWhileLockedWithCompletion:] : 284 -> 280
~ -[_BPSAbstractCorrelateOrderedMerge receiveCompletion:atIndex:] : 640 -> 636
~ -[_BPSAbstractCorrelateOrderedMerge flushBufferAndRequestMoreWhileLocked] : 884 -> 880
~ ___38-[BPSFuture initWithAttemptToFulfill:]_block_invoke : 500 -> 496
~ -[BPSFuture startWithSubscriber:] : 104 -> 100
~ -[BPSFuture nextEvent] : 168 -> 164
~ -[BPSFuture completed] : 84 -> 80
~ -[BPSFuture reset] : 84 -> 80
~ -[_BPSInnerFutureConduit requestDemand:] : 440 -> 436
~ -[_BPSInnerFutureConduit fulfill:] : 356 -> 352
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyp_Tg5 : 264 -> 288
```
