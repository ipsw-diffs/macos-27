## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/Versions/A/AppPredictionClient`

```diff

 671.0.1.0.1
-  __TEXT.__text: 0x19fa24
+  __TEXT.__text: 0x19fa20
   __TEXT.__objc_methlist: 0x18a2c
   __TEXT.__const: 0x700
   __TEXT.__cstring: 0x1bdfc
Functions:
~ -[ATXAppDirectoryResponse initWithSuggestionLayout:includeRemoteApps:recentApps:hiddenApps:otherAppsOnScreen:numAppsToPredict:error:] : 1532 -> 1548
~ -[ATXDocumentPredictionManager documentSuggestionWithLimit:documentScope:] : 724 -> 700
~ +[ATXSpotlightClientResponse _limitingResults:scores:spotlightRecentIndex:limit:] : 1036 -> 1040
~ _OUTLINED_FUNCTION_0 : 20 -> 16
~ _OUTLINED_FUNCTION_1 : 16 -> 20
~ __66+[NSDate(TimeManipulationForTesting) test_beginManipulationOfTime]_block_invoke.cold.1 : 92 -> 80
~ __58+[NSDate(TimeManipulationForTesting) test_setCurrentDate:]_block_invoke.cold.1 : 80 -> 92
```
