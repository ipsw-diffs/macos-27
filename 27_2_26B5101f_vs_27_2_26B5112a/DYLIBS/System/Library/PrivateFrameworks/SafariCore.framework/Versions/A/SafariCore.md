## SafariCore

> `/System/Library/PrivateFrameworks/SafariCore.framework/Versions/A/SafariCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-625.2.7.1.0
-  __TEXT.__text: 0x1f9a44
+625.2.8.11.6
+  __TEXT.__text: 0x1f9a40
   __TEXT.__objc_methlist: 0xd68c
   __TEXT.__const: 0x7d64
   __TEXT.__gcc_except_tab: 0x7f38
Symbols:
+ -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]
+ ___94-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:]_block_invoke
- -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]
- ___79-[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:]_block_invoke
Functions:
~ -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:] -> -[WBSAnalyticsLogger didDetectSearchEngineBannerWithLinkToApp:wasUserLoggedIn:pageLoadSource:] : 120 -> 116
CStrings:
+ "pageLoadSource"
- "wasUserLoggedIn"
```
