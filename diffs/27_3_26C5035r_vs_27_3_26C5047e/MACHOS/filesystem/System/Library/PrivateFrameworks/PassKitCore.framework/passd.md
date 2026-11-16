## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1696.3.3.1.0
-  __TEXT.__text: 0x59911c
-  __TEXT.__auth_stubs: 0x60c0
-  __TEXT.__objc_stubs: 0x726c0
-  __TEXT.__objc_methlist: 0x3601c
-  __TEXT.__const: 0x4478
-  __TEXT.__cstring: 0x670c4
+1696.3.5.4.0
+  __TEXT.__text: 0x59bc2c
+  __TEXT.__auth_stubs: 0x6150
+  __TEXT.__objc_stubs: 0x72840
+  __TEXT.__objc_methlist: 0x36104
+  __TEXT.__const: 0x4488
+  __TEXT.__cstring: 0x67a04
   __TEXT.__objc_classname: 0x7d88
-  __TEXT.__objc_methtype: 0x13eb2
-  __TEXT.__gcc_except_tab: 0x7ef8
-  __TEXT.__objc_methname: 0xa285c
-  __TEXT.__oslogstring: 0x528bb
+  __TEXT.__objc_methtype: 0x13ec2
+  __TEXT.__gcc_except_tab: 0x8274
+  __TEXT.__objc_methname: 0xa2acc
+  __TEXT.__oslogstring: 0x52acb
   __TEXT.__ustring: 0x10
   __TEXT.__swift5_typeref: 0x2454
   __TEXT.__constg_swiftt: 0x1bc8

   __TEXT.__swift_as_cont: 0x7c
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x18848
+  __TEXT.__unwind_info: 0x188e8
   __TEXT.__eh_frame: 0x1510
-  __DATA_CONST.__const: 0x2eda0
-  __DATA_CONST.__cfstring: 0x33520
+  __DATA_CONST.__const: 0x2f4e0
+  __DATA_CONST.__cfstring: 0x33860
   __DATA_CONST.__objc_classlist: 0x1a20
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x5e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x100
   __DATA_CONST.__objc_superrefs: 0xf68
-  __DATA_CONST.__objc_intobj: 0x1410
-  __DATA_CONST.__objc_arraydata: 0x588
+  __DATA_CONST.__objc_intobj: 0x1428
+  __DATA_CONST.__objc_arraydata: 0x598
   __DATA_CONST.__objc_dictobj: 0x2a8
-  __DATA_CONST.__objc_arrayobj: 0x588
+  __DATA_CONST.__objc_arrayobj: 0x5b8
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA_CONST.__auth_got: 0x3070
-  __DATA_CONST.__got: 0x3bd8
+  __DATA_CONST.__auth_got: 0x30b8
+  __DATA_CONST.__got: 0x3c18
   __DATA_CONST.__auth_ptr: 0x778
-  __DATA.__objc_const: 0x42a88
-  __DATA.__objc_selrefs: 0x1fb08
-  __DATA.__objc_ivar: 0x2904
+  __DATA.__objc_const: 0x42ad8
+  __DATA.__objc_selrefs: 0x1fb80
+  __DATA.__objc_ivar: 0x2908
   __DATA.__objc_data: 0x11b20
   __DATA.__data: 0x62c0
   __DATA.__bss: 0x3cb0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 27588
-  Symbols:   3504
-  CStrings:  34580
+  Functions: 27627
+  Symbols:   3520
+  CStrings:  34632
 
Symbols:
+ _OBJC_CLASS_$_PKCampaignAttributionSessionManager
+ _PKAnalyticsReporterAttributionAddLocalPendingCardReadyToUse
+ _PKAnalyticsReporterAttributionFetchNewToStatuses
+ _PKAnalyticsReporterAttributionSetLocalNewToStatusProvider
+ _PKAnalyticsReporterAttributionSetLocalPendingCardReadyToUseAddedHandler
+ _PKPassUniqueIdentifiersWithPendingCampaignAttribution
+ _PKPendingCampaignAttributionCampaignIdentifierKey
+ _PKPendingCampaignAttributionForPassUniqueIdentifier
+ _PKPendingCampaignAttributionNewToProductUserKey
+ _PKPendingCampaignAttributionNewToWalletUserKey
+ _PKPendingCampaignAttributionProductTypeKey
+ _PKPendingCampaignAttributionQueue
+ _PKPendingCampaignAttributionReferralSourceKey
+ _PKPendingCampaignAttributionSessionIDKey
+ _PKRemoveExpiredPendingCampaignAttributions
+ _PKRemovePendingCampaignAttributionForPassUniqueIdentifier
+ _os_unfair_recursive_lock_lock
- _os_unfair_recursive_lock_lock_with_options
CStrings:
+ "B32@?0@\"NSString\"8@\"PDUserNotification\"16^B24"
+ "CREATE INDEX IF NOT EXISTS dragonfruit_b_c_index ON dragonfruit (b, c);"
+ "CREATE INDEX IF NOT EXISTS tangerine_b_index ON tangerine (b);"
+ "CREATE TABLE IF NOT EXISTS account_migration (pid INTEGER, account_pid INTEGER, messaging_pid INTEGER, migration_effective_date INTEGER, learn_more_url TEXT, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS account_migration_feature_unavailability (pid INTEGER, account_migration_pid INTEGER, identifier TEXT, start_date INTEGER, end_date INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS account_migration_messaging (pid INTEGER, phase TEXT, scheduled_date TEXT, expiration_date INTEGER, user_notification_pid INTEGER, application_message_pid INTEGER, dashboard_message_pid INTEGER, sheet_pid INTEGER, notification_scheduled_date TEXT, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS blueberry (pid INTEGER, a INTEGER NOT NULL, b TEXT NOT NULL, c INTEGER, d TEXT, e TEXT, f TEXT, g TEXT, h TEXT, i INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS clementines (pid INTEGER, a INTEGER, b INTEGER, c TEXT, d TEXT, f INTEGER, g TEXT, h TEXT, i TEXT, j TEXT, k TEXT, l INTEGER, m TEXT, n INTEGER, o INTEGER, p INTEGER, business_chat_identifier TEXT, contact_number TEXT, privacy_policy_url TEXT, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS dragonfruit (pid INTEGER, a TEXT NOT NULL, b INTEGER NOT NULL, c TEXT NOT NULL, d INTEGER NOT NULL, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS leek (pid INTEGER, base_pid INTEGER, a TEXT, b TEXT, c TEXT, d INTEGER, e TEXT, f TEXT, g TEXT, h TEXT, k TEXT, l INTEGER, m INTEGER, n TEXT, o TEXT, p TEXT, q INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS tangerine (a INTEGER NOT NULL REFERENCES dragonfruit(pid) ON DELETE CASCADE, b INTEGER NOT NULL REFERENCES blueberry(pid) ON DELETE CASCADE, PRIMARY KEY (a, b));"
+ "CREATE TABLE IF NOT EXISTS user_notification_receipt (pid INTEGER, notification_identifier TEXT, notification_type TEXT, account_identifier TEXT, account_base_url TEXT, message_title TEXT, message_subtitle TEXT, message_body TEXT, date_scheduled INTEGER, scheduled_time_zone TEXT, date_delivered INTEGER, delivered_time_zone TEXT, date_reported INTEGER, requires_reporting INTEGER, PRIMARY KEY(pid));"
+ "CREATE UNIQUE INDEX IF NOT EXISTS blueberry_a_b_index ON blueberry (a, b);"
+ "CREATE UNIQUE INDEX IF NOT EXISTS dragonfruit_a_index ON dragonfruit (a);"
+ "Migrating database from user_version 26084 to 26085"
+ "Migrating database from user_version 26085 to 26086"
+ "Migrating database from user_version 26086 to 26087"
+ "Migrating database from user_version 26087 to 26088"
+ "Migrating database from user_version 26088 to 26089"
+ "Notification for this type is inflight, so delivery is not allowed. delivered notification: %@ suppressed notification: %@"
+ "Notification for this type was delivered on the same calendar day, so delivery is not allowed. delivered receipt: %@ suppressed notification: %@"
+ "UPDATE user_notification_receipt SET notification_type = 'PDUserNotificationTypeAccountPaymentPastDue' WHERE notification_identifier LIKE 'accountPaymentPastDue-%'"
+ "UPDATE user_notification_receipt SET notification_type = 'PDUserNotificationTypePassAccountState' WHERE notification_identifier LIKE 'accountStateChange-%'"
+ "UPDATE user_notification_receipt SET requires_reporting = 1"
+ "[Test Receipt] Past Due Body"
+ "[Test Receipt] Past Due Subtitle"
+ "[Test Receipt] Past Due Title"
+ "_hasCampaignAttributionAccess"
+ "_migrateFrom26084To26085:context:"
+ "_migrateFrom26085To26086:context:"
+ "_migrateFrom26086To26087:context:"
+ "_migrateFrom26087To26088:context:"
+ "_migrateFrom26088To26089:context:"
+ "_notificationDeliveryAllowed:"
+ "_pendingCampaignAttributionQueue"
+ "_predicateForPurgeableBeforeDate:"
+ "account_migration"
+ "account_migration_feature_unavailability"
+ "account_migration_messaging"
+ "addPendingCampaignAttribution:forPassUniqueIdentifier:"
+ "alert_body"
+ "campaignAttributionNewToStatuses"
+ "campaignAttributionNewToStatusesWithHandler:"
+ "deletePurgeableReceiptsBeforeDate:"
+ "deletePurgeableReceiptsBeforeDate:inDatabase:"
+ "initWithNotificationIdentifier:notificationType:accountIdentifier:accountBaseURL:requiresReporting:"
+ "insertUserNotificationReceiptForAccountIdentifier:deliveredDate:"
+ "migration_effective_date INTEGER"
+ "notification_scheduled_date TEXT"
+ "notification_type TEXT"
+ "preventMultipleSameDayDelivery"
+ "privacy_policy_url TEXT"
+ "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:newToWalletUser:newToProductUser:sessionIdentifier:"
+ "requiresReporting"
+ "requires_reporting"
+ "requires_reporting INTEGER"
+ "setRequiresReporting:"
+ "userNotificationReceiptsForNotificationType:"
+ "v32@0:8@\"NSDictionary\"16@\"NSString\"24"
+ "v32@?0@\"NSString\"8#16^B24"
+ "{os_unfair_recursive_lock_s=\"_os_unfair_recursive_lock_opaque\"[2I]}"
+ "\xf0\xf0Q"
- "CREATE TABLE IF NOT EXISTS clementines (pid INTEGER, a INTEGER, b INTEGER, c TEXT, d TEXT, f INTEGER, g TEXT, h TEXT, i TEXT, j TEXT, k TEXT, l INTEGER, m TEXT, n INTEGER, o INTEGER, p INTEGER, business_chat_identifier TEXT, contact_number TEXT, PRIMARY KEY (pid));"
- "CREATE TABLE IF NOT EXISTS leek (pid INTEGER, base_pid INTEGER, a TEXT, b TEXT, c TEXT, d INTEGER, e TEXT, f TEXT, g TEXT, h TEXT, k TEXT, l INTEGER, m INTEGER, PRIMARY KEY (pid));"
- "CREATE TABLE IF NOT EXISTS user_notification_receipt (pid INTEGER, notification_identifier TEXT, account_identifier TEXT, account_base_url TEXT, message_title TEXT, message_subtitle TEXT, message_body TEXT, date_scheduled INTEGER, scheduled_time_zone TEXT, date_delivered INTEGER, delivered_time_zone TEXT, date_reported INTEGER, PRIMARY KEY(pid));"
- "_predicateForReportedBeforeDate:"
- "deleteReportedUserNotificationReceiptsBeforeDate:"
- "deleteReportedUserNotificationReceiptsBeforeDate:inDatabase:"
- "initWithNotificationIdentifier:accountIdentifier:accountBaseURL:"
- "reportCampaignIdentifier:eventType:referralSource:deepLinkType:productType:"
- "{os_unfair_recursive_lock_s=\"ourl_lock\"{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}\"ourl_count\"I}"
- "\xf0\xf0A"
```
