## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/Versions/A/ReminderKit`

```diff

-4107.0.0.0.0
-  __TEXT.__text: 0x146f84
-  __TEXT.__objc_methlist: 0x15c70
+4112.0.0.0.0
+  __TEXT.__text: 0x1479f0
+  __TEXT.__objc_methlist: 0x15db0
   __TEXT.__const: 0x1717
   __TEXT.__oslogstring: 0x11951
-  __TEXT.__cstring: 0xe78f
-  __TEXT.__gcc_except_tab: 0x8100
+  __TEXT.__cstring: 0xe80d
+  __TEXT.__gcc_except_tab: 0x80dc
   __TEXT.__ustring: 0x2aa
   __TEXT.__dlopen_cstrs: 0xb4
-  __TEXT.__unwind_info: 0x85b8
+  __TEXT.__unwind_info: 0x8618
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd90
+  __DATA_CONST.__const: 0xdb0
   __DATA_CONST.__objc_classlist: 0xc28
   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7be8
+  __DATA_CONST.__objc_selrefs: 0x7c88
   __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0xa50
+  __DATA_CONST.__objc_superrefs: 0xa58
   __DATA_CONST.__objc_arraydata: 0x988
-  __DATA_CONST.__got: 0xf70
-  __AUTH_CONST.__const: 0x4d70
-  __AUTH_CONST.__cfstring: 0xe680
-  __AUTH_CONST.__objc_const: 0x24868
+  __DATA_CONST.__got: 0xf80
+  __AUTH_CONST.__const: 0x4dd0
+  __AUTH_CONST.__cfstring: 0xe720
+  __AUTH_CONST.__objc_const: 0x249c8
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_arrayobj: 0x1c8
   __AUTH_CONST.__objc_intobj: 0xf0

   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x41a0
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x1158
+  __DATA.__objc_ivar: 0x1170
   __DATA.__data: 0x1aa4
-  __DATA.__bss: 0x44c
+  __DATA.__bss: 0x444
   __DATA.__common: 0x28
   __DATA_DIRTY.__objc_data: 0x37f0
   __DATA_DIRTY.__data: 0x8

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8891
-  Symbols:   17184
-  CStrings:  2967
+  Functions: 8922
+  Symbols:   17242
+  CStrings:  2973
 
Symbols:
+ +[REMRecurrenceRuleFormatter _symbolsCache]
+ +[REMRecurrenceRuleFormatter supportsSecureCoding]
+ -[REMRecurrenceRuleFormatter .cxx_destruct]
+ -[REMRecurrenceRuleFormatter _andDaysOfWeekString:]
+ -[REMRecurrenceRuleFormatter _byDayOfWeekOrdinalStrings]
+ -[REMRecurrenceRuleFormatter _customByDayItemFormatLocalizedString]
+ -[REMRecurrenceRuleFormatter _customDayCombinationDescription:]
+ -[REMRecurrenceRuleFormatter _dayOfMonthAsString:]
+ -[REMRecurrenceRuleFormatter _fullDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:weeksOfTheYear:daysOfTheYear:setPositions:startDate:]
+ -[REMRecurrenceRuleFormatter _localizedOfMonthStringForMonth:]
+ -[REMRecurrenceRuleFormatter _localizedStringForKey:value:table:]
+ -[REMRecurrenceRuleFormatter _numberedWeekDayString:]
+ -[REMRecurrenceRuleFormatter _orDaysOfWeekString:]
+ -[REMRecurrenceRuleFormatter _readableMonths]
+ -[REMRecurrenceRuleFormatter _readableWeekDays]
+ -[REMRecurrenceRuleFormatter _shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:]
+ -[REMRecurrenceRuleFormatter _stringForByDayOfWeek:setPositions:]
+ -[REMRecurrenceRuleFormatter _stringForDayOfWeek:]
+ -[REMRecurrenceRuleFormatter _stringForMonthNumber:]
+ -[REMRecurrenceRuleFormatter _stringWithFormat:]
+ -[REMRecurrenceRuleFormatter _symbols:fromCalendar:]
+ -[REMRecurrenceRuleFormatter _weekDayPositionAsString:]
+ -[REMRecurrenceRuleFormatter copyWithZone:]
+ -[REMRecurrenceRuleFormatter encodeWithCoder:]
+ -[REMRecurrenceRuleFormatter formattingContext]
+ -[REMRecurrenceRuleFormatter getObjectValue:forString:errorDescription:]
+ -[REMRecurrenceRuleFormatter initWithCoder:]
+ -[REMRecurrenceRuleFormatter locale]
+ -[REMRecurrenceRuleFormatter localizationBundle]
+ -[REMRecurrenceRuleFormatter referenceDate]
+ -[REMRecurrenceRuleFormatter setFormattingContext:]
+ -[REMRecurrenceRuleFormatter setLocale:]
+ -[REMRecurrenceRuleFormatter setLocalizationBundle:]
+ -[REMRecurrenceRuleFormatter setReferenceDate:]
+ -[REMRecurrenceRuleFormatter setStyle:]
+ -[REMRecurrenceRuleFormatter setTimeZone:]
+ -[REMRecurrenceRuleFormatter stringForObjectValue:]
+ -[REMRecurrenceRuleFormatter stringFromRecurrenceRule:referenceDate:]
+ -[REMRecurrenceRuleFormatter stringFromRepeatType:]
+ -[REMRecurrenceRuleFormatter style]
+ -[REMRecurrenceRuleFormatter timeZone]
+ _OBJC_CLASS_$_NSCache
+ _OBJC_CLASS_$_NSFormatter
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._formattingContext
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._locale
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._localizationBundle
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._referenceDate
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._style
+ _OBJC_IVAR_$_REMRecurrenceRuleFormatter._timeZone
+ _OBJC_METACLASS_$_NSFormatter
+ __OBJC_$_CLASS_PROP_LIST_REMRecurrenceRuleFormatter
+ __OBJC_$_INSTANCE_METHODS_REMRecurrenceRuleFormatter
+ __OBJC_$_INSTANCE_VARIABLES_REMRecurrenceRuleFormatter
+ __OBJC_$_PROP_LIST_REMRecurrenceRuleFormatter
+ __OBJC_CLASS_PROTOCOLS_$_REMRecurrenceRuleFormatter
+ ___132-[REMRecurrenceRuleFormatter _shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:]_block_invoke
+ ___43+[REMRecurrenceRuleFormatter _symbolsCache]_block_invoke
+ ___45-[REMRecurrenceRuleFormatter _readableMonths]_block_invoke
+ ___47-[REMRecurrenceRuleFormatter _readableWeekDays]_block_invoke
+ ___block_descriptor_32_e29_"NSArray"16?0"NSCalendar"8l
+ __shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:.__WeekdaysByDayArray
+ __shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:.__WeekendsByDayArray
+ __shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:.onceToken
+ __symbolsCache.cache
+ __symbolsCache.onceToken
+ _objc_msgSend$_fullDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:weeksOfTheYear:daysOfTheYear:setPositions:startDate:
+ _objc_msgSend$_localizedStringForKey:value:table:
+ _objc_msgSend$_shortDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:
+ _objc_msgSend$_stringWithFormat:
+ _objc_msgSend$_symbols:fromCalendar:
+ _objc_msgSend$_symbolsCache
+ _objc_msgSend$autoupdatingCurrentLocale
+ _objc_msgSend$formattingContext
+ _objc_msgSend$initWithFormat:locale:arguments:
+ _objc_msgSend$languageIdentifier
+ _objc_msgSend$localizationBundle
+ _objc_msgSend$localizedStringForKey:value:table:localizations:
+ _objc_msgSend$referenceDate
+ _objc_msgSend$setFormattingContext:
+ _objc_msgSend$setLocale:
+ _objc_msgSend$stringFromRecurrenceRule:referenceDate:
+ _objc_msgSend$stringFromRepeatType:
+ _recurrenceCalendar
- +[REMRecurrenceRuleFormatter _andDaysOfWeekString:]
- +[REMRecurrenceRuleFormatter _byDayOfWeekOrdinalStrings]
- +[REMRecurrenceRuleFormatter _customByDayItemFormatLocalizedString]
- +[REMRecurrenceRuleFormatter _customDayCombinationDescription:]
- +[REMRecurrenceRuleFormatter _dayOfMonthAsString:]
- +[REMRecurrenceRuleFormatter _daysOfWeek]
- +[REMRecurrenceRuleFormatter _localizedOfMonthStringForMonth:]
- +[REMRecurrenceRuleFormatter _numberedWeekDayString:]
- +[REMRecurrenceRuleFormatter _orDaysOfWeekString:]
- +[REMRecurrenceRuleFormatter _readableMonths]
- +[REMRecurrenceRuleFormatter _readableWeekDays]
- +[REMRecurrenceRuleFormatter _stringForByDayOfWeek:setPositions:]
- +[REMRecurrenceRuleFormatter _stringForDayOfWeek:]
- +[REMRecurrenceRuleFormatter _stringForMonthNumber:]
- +[REMRecurrenceRuleFormatter _weekDayPositionAsString:]
- ___165+[REMRecurrenceRuleFormatter shortNaturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:timeZone:lowercase:]_block_invoke
- __daysOfWeek.sDaysOfWeek
- _naturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:weeksOfTheYear:daysOfTheYear:setPositions:end:withStartDate:.readableMonthArray
- _naturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:weeksOfTheYear:daysOfTheYear:setPositions:end:withStartDate:.readableWeekDayArray
- _objc_msgSend$_daysOfWeek
- _objc_sync_enter
- _objc_sync_exit
- _shortNaturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:timeZone:lowercase:.__WeekdaysByDayArray
- _shortNaturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:timeZone:lowercase:.__WeekendsByDayArray
- _shortNaturalLanguageDescriptionForFrequency:interval:daysOfTheWeek:daysOfTheMonth:monthsOfTheYear:setPositions:date:timeZone:lowercase:.onceToken
CStrings:
+ "-[NSCalendar standaloneMonthSymbols] invalid, reverting to US dates"
+ "-[NSCalendar standaloneWeekdaySymbols] invalid, reverting to US dates"
+ "@\"NSArray\"16@?0@\"NSCalendar\"8"
+ "formattingContext"
+ "referenceDate"
+ "standaloneMonthSymbols"
+ "standaloneWeekdaySymbols"
+ "style"
- "-[NSDateFormatter monthSymbols] invalid, reverting to US dates"
- "-[NSDateFormatter weekdaySymbols] invalid, reverting to US dates"
```
