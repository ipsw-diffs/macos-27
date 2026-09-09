## com.apple.iCal

> `/System/Library/Accessibility/BundlesBase/com.apple.iCal.axbundle/Versions/A/com.apple.iCal`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xd454
+  __TEXT.__text: 0xcfbc
   __TEXT.__auth_stubs: 0x340
   __TEXT.__objc_stubs: 0x1a60
   __TEXT.__objc_methlist: 0xa9c

   __TEXT.__objc_methname: 0x17dd
   __TEXT.__objc_methtype: 0x124
   __TEXT.__oslogstring: 0x71
-  __TEXT.__unwind_info: 0x388
+  __TEXT.__unwind_info: 0x440
   __DATA_CONST.__const: 0x458
   __DATA_CONST.__cfstring: 0x2180
   __DATA_CONST.__objc_classlist: 0x150
Functions:
~ +[AXCalAvailabilityScanner elementWithController:] : 228 -> 216
~ -[AXCalAvailabilityScanner accessibilityValueDescription] : 240 -> 228
~ ___53-[AXCalAvailabilityScanner accessibilityPerformPress]_block_invoke : 76 -> 64
~ ___copy_helper_block_e8_32s40s : 60 -> 48
~ ___destroy_helper_block_e8_32s40s : 60 -> 48
~ -[AXCalAvailabilityScanner accessibilityValue] : 832 -> 820
~ -[AXCalAvailabilityScanner accessibilityCustomActions] : 964 -> 952
~ ___54-[AXCalAvailabilityScanner accessibilityCustomActions]_block_invoke_2 : 100 -> 88
~ ___copy_helper_block_e8_32s40w : 68 -> 56
~ ___destroy_helper_block_e8_32s40w : 60 -> 48
~ -[AXCalAvailabilityScanner accessibilityLinkedUIElements] : 244 -> 232
~ -[AXCalAvailabilityScanner accessibilityCustomContent] : 848 -> 836
~ -[AXCalAvailabilityScanner _dateIntervalFormatter] : 84 -> 72
~ -[AXCalAvailabilityScanner _contentView] : 164 -> 152
~ -[AXCalAvailabilityScanner _currentEventView] : 164 -> 152
~ -[AXCalAvailabilityScanner _validCurrentEventView] : 444 -> 432
~ -[AXCalAvailabilityScanner _participantRows] : 88 -> 76
~ -[AXCalAvailabilityScanner _participantAtRow:] : 232 -> 220
~ -[AXCalAvailabilityScanner _participantAvailabilitySpansAtRow:] : 276 -> 264
~ -[AXCalAvailabilityScanner _contentInterval] : 280 -> 268
~ -[AXCalAvailabilityScanner _eventInterval] : 288 -> 276
~ -[AXCalAvailabilityScanner _defaultStartDate] : 228 -> 216
~ -[AXCalAvailabilityScanner _customActions] : 1380 -> 1368
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[AXCalAvailabilityScanner _controller] : 52 -> 40
~ -[AXCalAvailabilityScanner .cxx_destruct] : 100 -> 88
~ +[CalUIMonthDayViewAccessibility _accessibilityPerformValidations:] : 592 -> 580
~ -[CalUIMonthDayViewAccessibility accessibilityAttributeNames] : 228 -> 216
~ -[CalUIMonthDayViewAccessibility accessibilityAttributeValue:] : 2504 -> 2492
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ __62-[CalUIMonthDayViewAccessibility accessibilityAttributeValue:]_block_invoke.459 : 80 -> 68
~ ___62-[CalUIMonthDayViewAccessibility accessibilityPerformShowMenu]_block_invoke : 84 -> 72
~ +[CalUICanvasFrameViewAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[CalUICanvasFrameViewAccessibility accessibilityLabel] : 420 -> 408
~ +[CalUIViewControllerAccessibility _accessibilityPerformValidations:] : 796 -> 784
~ ___78-[CalUIViewControllerAccessibility handleOccurrenceModificationForMouseEvent:]_block_invoke : 160 -> 148
~ -[CalUIViewControllerAccessibility _accessibilityTodayOccurenceElement] : 1716 -> 1704
~ ___71-[CalUIViewControllerAccessibility _accessibilityTodayOccurenceElement]_block_invoke : 112 -> 100
~ __71-[CalUIViewControllerAccessibility _accessibilityTodayOccurenceElement]_block_invoke.484 : 84 -> 72
~ +[CalAvailabilityWindowControllerAccessibility _accessibilityPerformValidations:] : 464 -> 452
~ -[CalAvailabilityWindowControllerAccessibility navigationItem] : 108 -> 96
~ ___76-[CalAvailabilityWindowControllerAccessibility _axUpdateToolbarControlItem:]_block_invoke : 188 -> 176
~ -[EKAvailabilitySpan(AXCalAvailabilityUtilities) _axbLocalizedDescription] : 76 -> 64
~ +[CalUICalendarSidebarAccessibility _accessibilityPerformValidations:] : 264 -> 252
~ +[CalParticipantContainerAccessibility _accessibilityPerformValidations:] : 344 -> 332
~ -[CalParticipantContainerAccessibility accessibilityLabel] : 352 -> 340
~ -[CalParticipantContainerAccessibility accessibilityCustomContent] : 276 -> 264
~ ___66-[CalParticipantContainerAccessibility accessibilityCustomContent]_block_invoke : 312 -> 300
~ -[CalParticipantContainerAccessibility _axParticipantRowView] : 524 -> 512
~ +[CalUICalendarViewsControllerAccessibility _accessibilityPerformValidations:] : 588 -> 576
~ ___76-[CalUICalendarViewsControllerAccessibility _accessibilityPostLayoutChanged]_block_invoke : 80 -> 68
~ __76-[CalUICalendarViewsControllerAccessibility _accessibilityPostLayoutChanged]_block_invoke.426 : 84 -> 72
~ ___75-[CalUICalendarViewsControllerAccessibility _axcFontSizeCategoryDidChange:]_block_invoke : 84 -> 72
~ +[CalAvailabilityContentViewAccessibility _accessibilityPerformValidations:] : 848 -> 836
~ -[CalAvailabilityContentViewAccessibility accessibilityValueDescription] : 788 -> 776
~ -[CalAvailabilityContentViewAccessibility accessibilityLabel] : 276 -> 264
~ -[CalAvailabilityContentViewAccessibility accessibilityChildren] : 376 -> 364
~ +[CalUICalendarListViewAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[CalUICalendarListViewAccessibility accessibilityActionNames] : 128 -> 116
~ ___66-[CalUICalendarListViewAccessibility accessibilityPerformShowMenu]_block_invoke : 84 -> 72
~ -[CalUICalendarListViewAccessibility _axcSelfAsTableView] : 108 -> 96
~ +[CalUICalendarContainerViewAccessibility _accessibilityPerformValidations:] : 396 -> 384
~ -[CalUICalendarContainerViewAccessibility accessibilityChildren] : 572 -> 560
~ -[CalUICalendarContainerViewAccessibility accessibilityValueDescription] : 536 -> 524
~ +[CalUIDotOccurrenceAccessibility _accessibilityPerformValidations:] : 412 -> 400
~ -[CalUIDotOccurrenceAccessibility accessibilityParent] : 164 -> 152
~ -[CalUIDotOccurrenceAccessibility accessibilityCustomContent] : 1644 -> 1632
~ ___61-[CalUIDotOccurrenceAccessibility accessibilityCustomContent]_block_invoke : 84 -> 72
~ __61-[CalUIDotOccurrenceAccessibility accessibilityCustomContent]_block_invoke.412 : 84 -> 72
~ ___61-[CalUIDotOccurrenceAccessibility accessibilityCustomContent]_block_invoke_2 : 84 -> 72
~ +[AXiCalGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___57+[AXiCalGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___57+[AXiCalGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 516 -> 504
~ _AXCalActiveDescription : 484 -> 472
~ _accessibilityLocalizedString : 184 -> 172
~ +[CalUISearchFieldAccessibility _accessibilityPerformValidations:] : 232 -> 220
~ -[CalUISearchFieldAccessibility accessibilityLinkedUIElements] : 340 -> 328
~ +[CalUIDayLayerViewAccessibility _accessibilityPerformValidations:] : 508 -> 496
~ -[CalUIDayLayerViewAccessibility accessibilityLabel] : 292 -> 280
~ -[CalUIDayLayerViewAccessibility accessibilitySelectedChildren] : 1364 -> 1352
~ __63-[CalUIDayLayerViewAccessibility accessibilitySelectedChildren]_block_invoke.421 : 84 -> 72
~ ___67-[CalUIDayLayerViewAccessibility setAccessibilitySelectedChildren:]_block_invoke : 84 -> 72
~ __62-[CalUIDayLayerViewAccessibility accessibilityPerformShowMenu]_block_invoke.430 : 84 -> 72
~ +[CalUIAXMonthGridProxyAccessibility _accessibilityPerformValidations:] : 252 -> 240
~ -[CalUIAXMonthGridProxyAccessibility accessibilityLabel] : 388 -> 376
~ +[CALMainControllerAccessibility _accessibilityPerformValidations:] : 188 -> 176
~ +[CalUICalendarListBaseCellViewAccessibility _accessibilityPerformValidations:] : 344 -> 332
~ -[CalUICalendarListBaseCellViewAccessibility _axcInitAccessibility] : 112 -> 100
~ +[CalUIToolbarAccessibility _accessibilityPerformValidations:] : 368 -> 356
~ __ClearLabelForToolbarRadioGroup : 368 -> 356
~ -[CalUIToolbarAccessibility viewSwitcherItem] : 96 -> 84
~ -[CalUIToolbarAccessibility calendarListItem] : 108 -> 96
~ +[CalUIInspectorManagerAccessibility _accessibilityPerformValidations:] : 152 -> 140
~ -[CalUIInspectorManagerAccessibility openPopoverInspectorForEvent:relativeToView:onMainController:isProposed:] : 356 -> 344
```
