## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

-1517.1.12.0.0
-  __TEXT.__text: 0x24ff90
+1517.2.2.0.0
+  __TEXT.__text: 0x250e9c
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0xee6c
-  __TEXT.__const: 0xad8
-  __TEXT.__cstring: 0x33db0
-  __TEXT.__oslogstring: 0x22b2a
-  __TEXT.__gcc_except_tab: 0x34d60
+  __TEXT.__objc_methlist: 0xeedc
+  __TEXT.__const: 0xb08
+  __TEXT.__cstring: 0x3403d
+  __TEXT.__oslogstring: 0x22b6c
+  __TEXT.__gcc_except_tab: 0x34e98
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
-  __TEXT.__unwind_info: 0x102d8
+  __TEXT.__unwind_info: 0x10338
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3f48
+  __DATA_CONST.__const: 0x3f08
   __DATA_CONST.__objc_classlist: 0x7a8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ed8
+  __DATA_CONST.__objc_selrefs: 0x6f18
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0xa10
   __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0xaba0
-  __AUTH_CONST.__cfstring: 0x1e1e0
-  __AUTH_CONST.__objc_const: 0x166a8
+  __AUTH_CONST.__const: 0xac20
+  __AUTH_CONST.__cfstring: 0x1e300
+  __AUTH_CONST.__objc_const: 0x16728
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x738
   __AUTH_CONST.__objc_arrayobj: 0x138
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x1ed0
+  __AUTH_CONST.__auth_got: 0x1ed8
   __AUTH.__objc_data: 0x3b60
   __AUTH.__data: 0x248
-  __DATA.__objc_ivar: 0xc6c
+  __DATA.__objc_ivar: 0xc78
   __DATA.__data: 0x15ec
-  __DATA.__bss: 0x1a78
+  __DATA.__bss: 0x1a88
   __DATA.__common: 0x5
   __DATA_DIRTY.__objc_data: 0x1130
   __DATA_DIRTY.__data: 0x250
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0xc00
+  __DATA_DIRTY.__bss: 0xc10
   __DATA_DIRTY.__common: 0x18
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/CarbonCore.framework/Versions/A/CarbonCore

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 11222
-  Symbols:   18897
-  CStrings:  7996
+  Functions: 11246
+  Symbols:   18919
+  CStrings:  8009
 
Symbols:
+ +[LSBundleRecord _bundleRecordForApplicationIdentifier:fetchingPlaceholder:context:pluginFindOptions:error:]
+ +[LSBundleRecord bundleRecordForApplicationIdentifier:fetchingPlaceholder:error:]
+ -[ICLBundleRecord(LSExtensions) ls_applicationIdentifier]
+ -[LSApplicationRecord isPebblePlayPlaceholder]
+ -[LSBundleRecord _LSRecord_resolve_applicationIdentifier]
+ -[LSBundleRecord _LSRecord_resolve_associatedDomains]
+ -[LSBundleRecord applicationIdentifierWithContext:tableID:unitID:unitBytes:]
+ -[LSBundleRecord associatedDomainsWithContext:tableID:unitID:unitBytes:]
+ -[LSBundleRecord associatedDomains]
+ -[_LSCoreTypesRecordProxy associatedDomains]
+ GCC_except_table196
+ GCC_except_table214
+ GCC_except_table224
+ GCC_except_table229
+ GCC_except_table250
+ GCC_except_table257
+ GCC_except_table266
+ GCC_except_table272
+ GCC_except_table279
+ GCC_except_table284
+ GCC_except_table285
+ GCC_except_table291
+ GCC_except_table294
+ GCC_except_table302
+ GCC_except_table305
+ GCC_except_table312
+ GCC_except_table334
+ GCC_except_table336
+ GCC_except_table337
+ GCC_except_table344
+ GCC_except_table347
+ GCC_except_table362
+ _MGGetBoolAnswer
+ _OBJC_IVAR_$_LSBundleRecordBuilder._canChange_windowCornerCompat
+ _OBJC_IVAR_$_LSBundleRecordBuilder._prefersWindowCornerCompat
+ _OBJC_IVAR_$_LSBundleRecordBuilder._prefersWindowCornerCompatExplicit
+ __LSBundleSearchOrderEnumerate
+ __LSBundleSearchOrderForPlaceholderFetchBehavior
+ __LSGetAssociatedDomains
+ __ZL37windowCornerCompatSystemEnforcedValuev
+ __ZNK14LaunchServices16BindingEvaluator14getBestBindingEP9LSContext
+ __ZNSt3__115__expected_baseI9LSBindingU8__strongP7NSErrorE6__repr22__destroy_union_memberB9nqn220106Ev
+ __ZNSt3__18expectedI9LSBindingU8__strongP7NSErrorEaSB9nqn220106EOS5_
+ __ZZ48+[LSBundleRecord _getBundleRecordFinderForNode:]EN3$_48__invokeERN14LaunchServices8Database7ContextEP6FSNodePU15__autoreleasingP7NSError
+ __ZZL37windowCornerCompatSystemEnforcedValuevE4once
+ __ZZL37windowCornerCompatSystemEnforcedValuevE9supported
+ ___108+[LSBundleRecord _bundleRecordForApplicationIdentifier:fetchingPlaceholder:context:pluginFindOptions:error:]_block_invoke
+ ___136-[LSApplicationRecord _initWithNode:bundleIdentifier:placeholderBehavior:systemPlaceholder:itemID:forceInBundleContainer:context:error:]_block_invoke_4
+ ____ZL37windowCornerCompatSystemEnforcedValuev_block_invoke
+ ___block_descriptor_32_e381_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
+ ___block_descriptor_32_e381_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
+ ___block_descriptor_32_e384_B36?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28l
+ ___block_descriptor_368_ea8_32r_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_40_e384_B36?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28l
+ ___block_descriptor_40_ea8_32s_e381_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
+ ___block_descriptor_44_e381_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
+ ___block_descriptor_44_ea8_32s_e61_B24?0^{LSContext=}8r^{LSBinding=I^{LSBundleData}I^{?}Q}16l
+ ___block_descriptor_48_ea8_32bs_e195_v28?0"NSString"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}III}20l
+ ___block_descriptor_48_ea8_32bs_e378_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
+ ___block_descriptor_56_ea8_32bs40bs_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_56_ea8_32bs40rc_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_56_ea8_32r40r_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_56_ea8_32r_e12_v24?0Q8^B16l
+ ___block_descriptor_56_ea8_32s40bs_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_56_ea8_32s40s_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_652_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32l
+ ___block_descriptor_72_e8_32bs40r48r_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_72_ea8_32s40s48r_e368_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
+ ___block_descriptor_96_ea8_32s40s48s56bs64r72r_e12_v24?0Q8^B16l
+ ___copy_helper_block_ea8_32s40s48s56b64r72r
+ _objc_msgSend$_bundleRecordForApplicationIdentifier:fetchingPlaceholder:context:pluginFindOptions:error:
+ _objc_msgSend$associatedDomains
+ _objc_msgSend$ls_applicationIdentifier
- +[LSBundleRecord _bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:]
- GCC_except_table178
- GCC_except_table191
- GCC_except_table198
- GCC_except_table223
- GCC_except_table238
- GCC_except_table247
- GCC_except_table248
- GCC_except_table249
- GCC_except_table254
- GCC_except_table268
- GCC_except_table273
- GCC_except_table274
- GCC_except_table275
- GCC_except_table276
- GCC_except_table277
- GCC_except_table281
- GCC_except_table282
- GCC_except_table297
- GCC_except_table298
- GCC_except_table308
- GCC_except_table325
- GCC_except_table328
- GCC_except_table330
- GCC_except_table340
- GCC_except_table341
- GCC_except_table342
- GCC_except_table343
- GCC_except_table358
- __ZZ48+[LSBundleRecord _getBundleRecordFinderForNode:]EN3$_18__invokeERN14LaunchServices8Database7ContextEP6FSNodePU15__autoreleasingP7NSError
- ___88+[LSBundleRecord _bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:]_block_invoke
- ___block_descriptor_32_e380_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
- ___block_descriptor_32_e380_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
- ___block_descriptor_32_e383_B36?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28l
- ___block_descriptor_368_ea8_32r_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_40_e383_B36?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28l
- ___block_descriptor_40_ea8_32s_e380_B28?0^{LSContext=}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
- ___block_descriptor_44_e380_B28?0"_LSDatabase"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
- ___block_descriptor_48_ea8_32bs_e194_v28?0"NSString"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}III}20l
- ___block_descriptor_48_ea8_32bs_e377_v28?0"NSString"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20l
- ___block_descriptor_48_ea8_32s40s_e61_B24?0^{LSContext=}8r^{LSBinding=I^{LSBundleData}I^{?}Q}16l
- ___block_descriptor_56_ea8_32bs40bs_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_56_ea8_32bs40rc_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_56_ea8_32r40r_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_56_ea8_32s40bs_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_56_ea8_32s40s_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_648_ea8_32s_e37_v40?0q8"NSString"16"NSString"24*32l
- ___block_descriptor_72_e8_32bs40r48r_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- ___block_descriptor_72_ea8_32s40s48r_e367_v28?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20l
- _objc_msgSend$_applicationIdentifier
- _objc_msgSend$_bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:
CStrings:
+ "+[LSBundleRecord _bundleRecordForApplicationIdentifier:fetchingPlaceholder:context:pluginFindOptions:error:]"
+ "B28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
+ "B28@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
+ "B36@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28"
+ "HasRoundedCornerDisplay"
+ "LSPlaceholderFetchBehaviorAlwaysRemote is not a valid input to %s"
+ "LSRoundedWindowCornerCompatPreferred"
+ "NSPrefersDisplayBottomSafeAreaCompatibilityMode"
+ "RoundedWindowCornerCompat"
+ "Window Corner Radius"
+ "_kLSURLApplicationPrefersRoundedWindowCornerCompatibilityKey"
+ "_kLSURLCanSetApplicationPrefersRoundedWindowCornerCompatibilityKey"
+ "associated domains"
+ "auto LSBundleRecord::_bundleRecordForApplicationIdentifier:fetchingPlaceholder:context:pluginFindOptions:error:::(anonymous class)::operator()(LSBundleType) const"
+ "unexpected bundle type %d"
+ "v24@?0Q8^B16"
+ "v28@?0@\"NSString\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
+ "v28@?0@\"NSString\"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}III}20"
+ "v28@?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20"
+ "void _LSBundleSearchOrderEnumerate(LSBundlePlaceholderSearchOrder, void (^const __strong _Nonnull)(LSBundleType, BOOL *))"
- "+[LSBundleRecord _bundleRecordForApplicationIdentifier:context:pluginFindOptions:error:]"
- "B28@?0@\"_LSDatabase\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
- "B28@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
- "B36@?0^{LSContext=@}8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20*28"
- "v28@?0@\"NSString\"8I16r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}20"
- "v28@?0@\"NSString\"8I16r^{LSPluginData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IIIII{LSVersionNumber=[32C]}III}20"
- "v28@?0I8r^{LSBundleData={LSBundleBaseData=IIIIIIIIii{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}IIIIIIIIIICCII{LSBundleBaseFlags=b1b1b1b1b1b1b1}}IQIICCCCCCCCCC{LSBundleMoreFlags=b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1}IIQQI{LSVersionNumber=[32C]}{LSVersionNumber=[32C]}Ii{LSVersionNumber=[32C]}QQIIIIIIIIIIIQIQQQIQQIIIQIQQIIIQIIIIIIIIIIIIIIIICCC[0I]IIiIIIIII}12*20"
```
