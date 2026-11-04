## SecurityInterface

> `/System/Library/Frameworks/SecurityInterface.framework/Versions/A/SecurityInterface`

```diff

-55222.40.4.0.0
-  __TEXT.__text: 0x1c288
-  __TEXT.__objc_methlist: 0x27f8
-  __TEXT.__const: 0x120
+55222.60.2.0.0
+  __TEXT.__text: 0x1e090
+  __TEXT.__objc_methlist: 0x2a48
+  __TEXT.__const: 0x168
   __TEXT.__gcc_except_tab: 0x4bc
-  __TEXT.__cstring: 0x28f2
+  __TEXT.__cstring: 0x295f
   __TEXT.__oslogstring: 0x529
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0x12c
-  __TEXT.__unwind_info: 0xc38
+  __TEXT.__unwind_info: 0xcd8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x138
-  __DATA_CONST.__objc_classlist: 0x188
+  __DATA_CONST.__objc_classlist: 0x190
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x21e0
+  __DATA_CONST.__objc_selrefs: 0x23f8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x140
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x480
+  __DATA_CONST.__got: 0x4a8
   __AUTH_CONST.__const: 0x3e0
-  __AUTH_CONST.__cfstring: 0x27c0
-  __AUTH_CONST.__objc_const: 0x4dd0
+  __AUTH_CONST.__cfstring: 0x2840
+  __AUTH_CONST.__objc_const: 0x50c8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x468
-  __AUTH.__objc_data: 0xf50
-  __DATA.__objc_ivar: 0x4ec
+  __AUTH.__objc_data: 0xfa0
+  __DATA.__objc_ivar: 0x534
   __DATA.__data: 0x200
   __DATA.__bss: 0x180
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 912
-  Symbols:   2743
-  CStrings:  412
+  Functions: 960
+  Symbols:   2880
+  CStrings:  416
 
Symbols:
+ +[SFCertificateView _isTrustValid:]
+ -[SFCertificateTrustPanel is2QWAC]
+ -[SFCertificateTrustPanel isQWAC]
+ -[SFCertificateTrustPanel(Accessors) _certListHeightConstraint]
+ -[SFCertificateTrustPanel(Accessors) _certViewHeightConstraint]
+ -[SFCertificateTrustPanel(Accessors) _verifiedFieldTopConstraint]
+ -[SFCertificateTrustPanel(Accessors) _verifiedField]
+ -[SFCertificateTrustPanel(Accessors) set_certListHeightConstraint:]
+ -[SFCertificateTrustPanel(Accessors) set_certViewHeightConstraint:]
+ -[SFCertificateTrustPanel(Accessors) set_verifiedField:]
+ -[SFCertificateTrustPanel(Accessors) set_verifiedFieldTopConstraint:]
+ -[SFCertificateTrustPanel(Private) _applyTrustSectionForRow:]
+ -[SFCertificateTrustPanel(Private) _attributedNameForData:chainRow:selected:]
+ -[SFCertificateTrustPanel(Private) _centerIconsOnCertificateImage]
+ -[SFCertificateTrustPanel(Private) _certPanelSheetDidEnd:returnCode:contextInfo:]
+ -[SFCertificateTrustPanel(Private) _chainHeaderCell]
+ -[SFCertificateTrustPanel(Private) _connectionParagraph:info:]
+ -[SFCertificateTrustPanel(Private) _listsTwoChains]
+ -[SFCertificateTrustPanel(Private) _qwacCertDataArray]
+ -[SFCertificateTrustPanel(Private) _qwacDataAtChainRow:]
+ -[SFCertificateTrustPanel(Private) _qwacIconView]
+ -[SFCertificateTrustPanel(Private) _qwacRowCount]
+ -[SFCertificateTrustPanel(Private) _qwacSeparatorCell]
+ -[SFCertificateTrustPanel(Private) _qwacTrust]
+ -[SFCertificateTrustPanel(Private) _rowAt:]
+ -[SFCertificateTrustPanel(Private) _rowContainsLeaf:]
+ -[SFCertificateTrustPanel(Private) _setTrust:]
+ -[SFCertificateTrustPanel(Private) _setTrustStatements:]
+ -[SFCertificateTrustPanel(Private) _showsTrustSectionForRow:]
+ -[SFCertificateTrustPanel(Private) _showsTrustStatements:]
+ -[SFCertificateTrustPanel(Private) _tableRowContainsLeaf:]
+ -[SFCertificateTrustPanel(Private) _tableRowForTLSChainRow:]
+ -[SFCertificateTrustPanel(Private) _tlsAnchorIsAppleRoot]
+ -[SFCertificateTrustPanel(Private) _tlsRowCount]
+ -[SFCertificateTrustPanel(Private) _trustStatements:]
+ -[SFCertificateTrustPanel(Private) _trustStatementsLeaf:]
+ -[SFCertificateTrustPanel(Private) _updateCertListHeight]
+ -[SFCertificateTrustPanel(Private) _updateCertViewHeight]
+ -[SFCertificateTrustPanel(Private) is2QWAC]
+ -[SFCertificateTrustPanel(Private) isQWAC]
+ -[SFCertificateTrustPanel(Private) numberOfRowsInTableView:]
+ -[SFCertificateTrustPanel(Private) setQwacTrust:]
+ -[SFCertificateTrustPanel(Private) tableView:dataCellForTableColumn:row:]
+ -[SFCertificateTrustPanel(Private) tableView:heightOfRow:]
+ -[SFCertificateTrustPanel(Private) tableView:objectValueForTableColumn:row:]
+ -[SFCertificateTrustPanel(Private) tableView:shouldSelectRow:]
+ -[SFCertificateView _certImageView]
+ -[SFCertificateView _minContentHeight]
+ -[SFQwacSeparatorCell drawInteriorWithFrame:inView:]
+ GCC_except_table101
+ _NSZeroSize
+ _OBJC_CLASS_$_NSCell
+ _OBJC_CLASS_$_NSTextFieldCell
+ _OBJC_CLASS_$_SFQwacSeparatorCell
+ _OBJC_IVAR_$_SFCertificateTrustPanel._is2QWAC
+ _OBJC_IVAR_$_SFCertificateTrustPanel._isQWAC
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._certListBaseHeight
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._certListHeightConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._certViewHeightConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._chainHeaderCell
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._iconCenterConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._informationFieldCollapseConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._listsTwoChainsState
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._qwacCertDataArray
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._qwacIconBottomConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._qwacIconView
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._qwacSeparatorCell
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._qwacTrust
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._tlsAnchorIsAppleRoot
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._verifiedField
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._verifiedFieldCollapseConstraint
+ _OBJC_IVAR_$_SFCertificateTrustPanel_ivars._verifiedFieldTopConstraint
+ _OBJC_METACLASS_$_NSCell
+ _OBJC_METACLASS_$_SFQwacSeparatorCell
+ __OBJC_$_INSTANCE_METHODS_SFQwacSeparatorCell
+ __OBJC_$_PROP_LIST_SFCertificateTrustPanel
+ __OBJC_CLASS_RO_$_SFQwacSeparatorCell
+ __OBJC_METACLASS_RO_$_SFQwacSeparatorCell
+ _kSecTrustQWACValidation
+ _kSecTrustResultValue
+ _objc_msgSend$CGColor
+ _objc_msgSend$_applyTrustSectionForRow:
+ _objc_msgSend$_attributedNameForData:chainRow:selected:
+ _objc_msgSend$_centerIconsOnCertificateImage
+ _objc_msgSend$_certImageView
+ _objc_msgSend$_certListHeightConstraint
+ _objc_msgSend$_certPanelSheetDidEnd:returnCode:contextInfo:
+ _objc_msgSend$_certViewHeightConstraint
+ _objc_msgSend$_chainHeaderCell
+ _objc_msgSend$_connectionParagraph:info:
+ _objc_msgSend$_isTrustValid:
+ _objc_msgSend$_listsTwoChains
+ _objc_msgSend$_minContentHeight
+ _objc_msgSend$_qwacCertDataArray
+ _objc_msgSend$_qwacDataAtChainRow:
+ _objc_msgSend$_qwacIconView
+ _objc_msgSend$_qwacRowCount
+ _objc_msgSend$_qwacSeparatorCell
+ _objc_msgSend$_rowAt:
+ _objc_msgSend$_setTrustStatements:
+ _objc_msgSend$_showsTrustSectionForRow:
+ _objc_msgSend$_showsTrustStatements:
+ _objc_msgSend$_tableRowContainsLeaf:
+ _objc_msgSend$_tableRowForTLSChainRow:
+ _objc_msgSend$_tlsAnchorIsAppleRoot
+ _objc_msgSend$_tlsRowCount
+ _objc_msgSend$_trustStatements:
+ _objc_msgSend$_trustStatementsLeaf:
+ _objc_msgSend$_updateCertListHeight
+ _objc_msgSend$_updateCertViewHeight
+ _objc_msgSend$_verifiedField
+ _objc_msgSend$_verifiedFieldTopConstraint
+ _objc_msgSend$centerXAnchor
+ _objc_msgSend$centerYAnchor
+ _objc_msgSend$clearColor
+ _objc_msgSend$colorWithSRGBRed:green:blue:alpha:
+ _objc_msgSend$constant
+ _objc_msgSend$constraintEqualToAnchor:multiplier:
+ _objc_msgSend$constraintGreaterThanOrEqualToAnchor:constant:
+ _objc_msgSend$dataCellForRow:
+ _objc_msgSend$firstItem
+ _objc_msgSend$initTextCell:
+ _objc_msgSend$is2QWAC
+ _objc_msgSend$isActive
+ _objc_msgSend$isQWAC
+ _objc_msgSend$lastObject
+ _objc_msgSend$layer
+ _objc_msgSend$secondItem
+ _objc_msgSend$separatorColor
+ _objc_msgSend$setBorderColor:
+ _objc_msgSend$setBorderWidth:
+ _objc_msgSend$setContentViewMargins:
+ _objc_msgSend$setCustomSpacing:afterView:
+ _objc_msgSend$setFillColor:
+ _objc_msgSend$setLineBreakMode:
+ _objc_msgSend$setQwacTrust:
+ _objc_msgSend$setTitlePosition:
+ _objc_msgSend$setWantsLayer:
+ _objc_msgSend$spacing
+ _objc_msgSend$trust
- -[SFCertificateTrustPanel(Private) _appendTrustStatements:toString:]
- GCC_except_table59
- _objc_msgSend$_appendTrustStatements:toString:
CStrings:
+ "EUTrustMark"
+ "Hide Certificates"
+ "Qualified Web Authentication Certificate"
+ "Show Certificates"
+ "TLS Certificate"
+ "Valid"
+ "\\U2022 This website is using an EU Qualified Web Authentication Certificate."
+ "lockClosing"
+ "lockOpening"
- "%@\n\n"
- "TrustQWACValidation"
- "\\U2022 %@ is using an EU Qualified Web Authentication certificate"
- "lock"
- "unlock"
```
