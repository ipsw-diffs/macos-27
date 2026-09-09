## com.apple.CalendarUI

> `/System/Library/Accessibility/BundlesBase/com.apple.CalendarUI.axbundle/Versions/A/com.apple.CalendarUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

 334.1.0.0.0
-  __TEXT.__text: 0xa49c
+  __TEXT.__text: 0x9f38
   __TEXT.__auth_stubs: 0x260
   __TEXT.__objc_stubs: 0x19a0
   __TEXT.__objc_methlist: 0xf94

   __TEXT.__objc_methname: 0x167d
   __TEXT.__objc_methtype: 0x1bc
   __TEXT.__oslogstring: 0x6e
-  __TEXT.__unwind_info: 0x488
+  __TEXT.__unwind_info: 0x528
   __DATA_CONST.__const: 0x260
   __DATA_CONST.__cfstring: 0x1d80
   __DATA_CONST.__objc_classlist: 0x240
Functions:
~ +[EKUIAlarmButtonAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[EKUIAlarmButtonAccessibility _axcGadget] : 312 -> 300
~ ___42-[EKUIAlarmButtonAccessibility _axcGadget]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40r : 72 -> 60
~ ___destroy_helper_block_e8_32s40r : 64 -> 52
~ +[CalUITextFieldEditorAccessibility _accessibilityPerformValidations:] : 132 -> 120
~ -[CalUITextFieldEditorAccessibility _axcWindow] : 164 -> 152
~ +[EKUIAttendeesGadgetAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ +[EKUITokenButtonAccessibility _accessibilityPerformValidations:] : 336 -> 324
~ -[EKUITokenButtonAccessibility accessibilityLabel] : 776 -> 764
~ +[CalUIDayViewAllDayViewAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[CalUIDayViewAllDayViewAccessibility _axcAllDayLabel] : 332 -> 320
~ ___54-[CalUIDayViewAllDayViewAccessibility _axcAllDayLabel]_block_invoke : 80 -> 68
~ -[CalUIDayViewAllDayViewAccessibility _axcAllDayEvents] : 540 -> 528
~ ___55-[CalUIDayViewAllDayViewAccessibility _axcAllDayEvents]_block_invoke : 80 -> 68
~ ___55-[CalUIDayViewAllDayViewAccessibility _axcAllDayEvents]_block_invoke_2 : 80 -> 68
~ +[CalUITextFieldCellAccessibility _accessibilityPerformValidations:] : 168 -> 156
~ -[CalUITextFieldCellAccessibility _axcFieldEditor] : 164 -> 152
~ -[CalUITextFieldCellAccessibility _axcControlView] : 212 -> 200
~ -[CalUITextFieldCellAccessibility accessibilityActionNames] : 388 -> 376
~ +[CalUIDateItemViewAccessibility _accessibilityPerformValidations:] : 188 -> 176
~ ___61-[CalUIDateItemViewAccessibility initWithDelegate:date:unit:]_block_invoke : 80 -> 68
~ -[CalUIDateItemViewAccessibility _axcTodayDescriptionForUnit:] : 148 -> 136
~ +[AXCalendarUIGlue accessibilityPrincipalClassInitializeBundle] : 156 -> 144
~ ___63+[AXCalendarUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_2 : 104 -> 92
~ ___63+[AXCalendarUIGlue accessibilityPrincipalClassInitializeBundle]_block_invoke_3 : 768 -> 756
~ _accessibilityLocalizedString : 184 -> 172
~ -[EKUIAttachmentTableViewAccessibility accessibilitySelectedRows] : 276 -> 264
~ -[EKUIAttachmentTableViewAccessibility _axcSelectedCell] : 364 -> 352
~ -[CalUIAXMiniMonthProxyAccessibility _axcMonthView] : 192 -> 180
~ -[CalUIAXMiniMonthProxyAccessibility _axcCalendar] : 80 -> 68
~ +[EKUIEndRepeatGadgetAccessibility _accessibilityPerformValidations:] : 280 -> 268
~ -[EKUIEndRepeatGadgetAccessibility _axcLabel] : 332 -> 320
~ ___45-[EKUIEndRepeatGadgetAccessibility _axcLabel]_block_invoke : 80 -> 68
~ -[EKUIEndRepeatGadgetAccessibility _axcDatePicker] : 164 -> 152
~ -[EKUIEndRepeatGadgetAccessibility _axcNumberOfTimesField] : 164 -> 152
~ -[EKUIEndRepeatGadgetAccessibility _axcEndRepeatTypePicker] : 164 -> 152
~ -[CalUICalendarPickerTouchBarItemControllerAccessibility _buttonForCalendar:] : 140 -> 128
~ -[CalUIVoiceOverFriendlyMatrixAccessibility accessibilityLabel] : 232 -> 220
~ -[CalUIVoiceOverFriendlyMatrixAccessibility accessibilitySelectedChildren] : 384 -> 372
~ +[EKUIAlarmGadgetAccessibility _accessibilityPerformValidations:] : 176 -> 164
~ -[EKUIAlarmGadgetAccessibility _axcAlarmPicker] : 332 -> 320
~ ___47-[EKUIAlarmGadgetAccessibility _axcAlarmPicker]_block_invoke : 80 -> 68
~ +[EKUIRecurrenceSummaryGadgetAccessibility _accessibilityPerformValidations:] : 144 -> 132
~ +[CalUIColorPickerButtonAccessibility _accessibilityPerformValidations:] : 124 -> 112
~ -[CalUIColorPickerButtonAccessibility _axcHumanReadableColorName] : 244 -> 232
~ +[EKUIAttachmentCellViewAccessibility _accessibilityPerformValidations:] : 336 -> 324
~ -[EKUIAttachmentCellViewAccessibility accessibilityLabel] : 96 -> 84
~ -[EKUIAttachmentCellViewAccessibility menu] : 104 -> 92
~ -[EKUIAttachmentCellViewAccessibility axcOpenAttachment] : 112 -> 100
~ -[EKUIAttachmentCellViewAccessibility _axcMenu] : 116 -> 104
~ -[EKUIAttachmentCellViewAccessibility _axcTokenField:menuForRepresentedObject:] : 448 -> 436
~ ___79-[EKUIAttachmentCellViewAccessibility _axcTokenField:menuForRepresentedObject:]_block_invoke : 84 -> 72
~ ___copy_helper_block_e8_32s40s48s56r : 88 -> 76
~ ___destroy_helper_block_e8_32s40s48s56r : 80 -> 68
~ -[EKUIAttachmentCellViewAccessibility _axcTokenField:displayStringForRepresentedObject:] : 384 -> 372
~ ___88-[EKUIAttachmentCellViewAccessibility _axcTokenField:displayStringForRepresentedObject:]_block_invoke : 88 -> 76
~ -[CalUISuggestionsFieldAccessibility _axcSelfAsTextField] : 108 -> 96
~ +[CalUIMiniMonthViewFormatterAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[CalUIBoxOccurrenceContentViewAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ -[CalUIBoxOccurrenceContentViewAccessibility accessibilityHelp] : 152 -> 140
~ -[CalUIBoxOccurrenceContentViewAccessibility _axcStyledTitle] : 1428 -> 1416
~ ___61-[CalUIBoxOccurrenceContentViewAccessibility _axcStyledTitle]_block_invoke : 80 -> 68
~ __61-[CalUIBoxOccurrenceContentViewAccessibility _axcStyledTitle]_block_invoke.396 : 80 -> 68
~ -[CalUIBoxOccurrenceContentViewAccessibility _axcCalendar] : 368 -> 356
~ ___58-[CalUIBoxOccurrenceContentViewAccessibility _axcCalendar]_block_invoke : 80 -> 68
~ ___56-[CalUIBoxOccurrenceContentViewAccessibility _axcAllDay]_block_invoke : 80 -> 68
~ ___58-[CalUIBoxOccurrenceContentViewAccessibility _axcNewEvent]_block_invoke : 80 -> 68
~ ___copy_helper_block_e8_32s40s48r : 80 -> 68
~ ___destroy_helper_block_e8_32s40s48r : 72 -> 60
~ -[CalUIBoxOccurrenceContentViewAccessibility _axcEventTitle] : 368 -> 356
~ ___60-[CalUIBoxOccurrenceContentViewAccessibility _axcEventTitle]_block_invoke : 80 -> 68
~ -[CalUIBoxOccurrenceContentViewAccessibility _axcEventLocation] : 368 -> 356
~ ___63-[CalUIBoxOccurrenceContentViewAccessibility _axcEventLocation]_block_invoke : 80 -> 68
~ -[CalUIBoxOccurrenceContentViewAccessibility _axcCalendarTitle] : 96 -> 84
~ +[CalUIEventViewTouchBarAccessibility _accessibilityPerformValidations:] : 144 -> 132
~ +[CalUIEventViewTouchBarAccessibility _CalUIEventViewTouchBarInstance] : 236 -> 224
~ +[CalUIEventViewTouchBarAccessibility accessibilitySetupExistingObjects] : 104 -> 92
~ -[CalUIEventViewTouchBarAccessibility _accessibilitySetup] : 76 -> 64
~ -[CalUIEventViewTouchBarAccessibility createInspectorFieldsTouchBarItem] : 108 -> 96
~ -[CalUIEventViewTouchBarAccessibility _axcInspectorFieldsTouchBarItem] : 164 -> 152
~ -[CalUINewFeaturesViewAccessibility accessibilityChildren] : 156 -> 144
~ +[CalUIDayMiniMonthDayCellAccessibility _accessibilityPerformValidations:] : 172 -> 160
~ -[CalUIDayMiniMonthDayCellAccessibility _axcMonthProxy] : 164 -> 152
~ -[CalUIDayMiniMonthDayCellAccessibility _axcCalendar] : 80 -> 68
~ -[CalUIDayMiniMonthDayCellAccessibility accessibilityLabel] : 324 -> 312
~ -[EKUIMapViewAccessibility accessibilityChildrenInNavigationOrder] : 540 -> 528
~ +[CalUIEventTimeViewControllerAccessibility _accessibilityPerformValidations:] : 200 -> 188
~ -[CalUIEventTimeViewControllerAccessibility viewAtIndex:level:] : 592 -> 580
~ ___63-[CalUIEventTimeViewControllerAccessibility viewAtIndex:level:]_block_invoke : 92 -> 80
~ -[CalUIEventTimeViewControllerAccessibility viewOverlayAtIndex:level:] : 372 -> 360
~ -[AXBCalendarTimeTrackMockElement accessibilityParent] : 76 -> 64
~ -[AXBCalendarTimeTrackMockElement accessibilityLabel] : 76 -> 64
~ +[EKUILabeledGadgetAccessibility _accessibilityPerformValidations:] : 196 -> 184
~ -[EKUILabeledGadgetAccessibility _axcControlView] : 164 -> 152
~ -[EKUILabeledGadgetAccessibility _axcLabel] : 332 -> 320
~ ___43-[EKUILabeledGadgetAccessibility _axcLabel]_block_invoke : 80 -> 68
~ -[NSDate(CalendarUIAccessibility) dateOnlyComponentsInCalendar:] : 120 -> 108
~ +[EKUILocationTableCellViewAccessibility _accessibilityPerformValidations:] : 160 -> 148
~ -[EKUILocationTableCellViewAccessibility _axcTitleField] : 164 -> 152
~ -[EKUILocationTableCellViewAccessibility _axcAccessibilityChildrenInNavigationOrder] : 164 -> 152
~ -[EKUILocationTableCellViewAccessibility accessibilityLabel] : 520 -> 508
~ +[EKUIGadgetContainerViewAccessibility _accessibilityPerformValidations:] : 136 -> 124
~ +[CalUIDayMiniMonthViewAccessibility _accessibilityPerformValidations:] : 896 -> 884
~ -[CalUIDayMiniMonthViewAccessibility _axcCalendar] : 164 -> 152
~ ___67-[CalUIDayMiniMonthViewAccessibility _accessibilityMoveFocusToDay:]_block_invoke : 112 -> 100
~ __67-[CalUIDayMiniMonthViewAccessibility _accessibilityMoveFocusToDay:]_block_invoke.481 : 84 -> 72
~ +[CalUIDayViewGadgetAccessibility _accessibilityPerformValidations:] : 204 -> 192
~ -[CalUIDayViewGadgetAccessibility accessibilityLabel] : 384 -> 372
~ ___53-[CalUIDayViewGadgetAccessibility accessibilityLabel]_block_invoke : 80 -> 68
~ -[CalUIDayViewGadgetAccessibility accessibilityChildren] : 420 -> 408
~ ___56-[CalUIDayViewGadgetAccessibility accessibilityChildren]_block_invoke : 80 -> 68
~ -[CalUIDayViewGadgetAccessibility _axcAllDayChildren] : 596 -> 584
~ ___53-[CalUIDayViewGadgetAccessibility _axcAllDayChildren]_block_invoke : 80 -> 68
~ ___53-[CalUIDayViewGadgetAccessibility _axcAllDayChildren]_block_invoke_2 : 80 -> 68
```
