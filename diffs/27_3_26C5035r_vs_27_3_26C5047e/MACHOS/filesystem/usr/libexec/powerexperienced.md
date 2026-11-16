## powerexperienced

> `/usr/libexec/powerexperienced`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-182.60.2.0.0
-  __TEXT.__text: 0x167b8
+182.60.3.0.0
+  __TEXT.__text: 0x16f0c
   __TEXT.__auth_stubs: 0x520
-  __TEXT.__objc_stubs: 0x2ee0
-  __TEXT.__objc_methlist: 0x1f44
+  __TEXT.__objc_stubs: 0x3020
+  __TEXT.__objc_methlist: 0x1ff4
   __TEXT.__const: 0x138
-  __TEXT.__cstring: 0x1143
-  __TEXT.__objc_methname: 0x36a1
-  __TEXT.__oslogstring: 0x262b
+  __TEXT.__cstring: 0x11e9
+  __TEXT.__objc_methname: 0x38ef
+  __TEXT.__oslogstring: 0x2869
   __TEXT.__objc_classname: 0x347
   __TEXT.__objc_methtype: 0x6bb
   __TEXT.__gcc_except_tab: 0x38
-  __TEXT.__unwind_info: 0x7d8
-  __DATA_CONST.__const: 0x878
-  __DATA_CONST.__cfstring: 0x1240
+  __TEXT.__unwind_info: 0x7e8
+  __DATA_CONST.__const: 0x888
+  __DATA_CONST.__cfstring: 0x1300
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_intobj: 0xc0
   __DATA_CONST.__auth_got: 0x2a0
   __DATA_CONST.__got: 0xd0
-  __DATA.__objc_const: 0x4790
-  __DATA.__objc_selrefs: 0xeb0
-  __DATA.__objc_ivar: 0x21c
+  __DATA.__objc_const: 0x48e0
+  __DATA.__objc_selrefs: 0xf28
+  __DATA.__objc_ivar: 0x238
   __DATA.__objc_data: 0x820
   __DATA.__data: 0x420
   __DATA.__bss: 0x238

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 737
+  Functions: 755
   Symbols:   119
-  CStrings:  1212
+  CStrings:  1257
 
CStrings:
+ "Resetting TLC Mitigation Background and Utility Power Budgets"
+ "Setting TLC Mitigation Background and Utility Power Budgets %.2f and %.2f"
+ "TB,V_tlcEnabled"
+ "TB,V_tlcPredicted"
+ "TLCMitigationHighSOC"
+ "TLCMitigationHighSOCPackagePowerTarget"
+ "TLCMitigationLowSOC"
+ "TLCMitigationLowSOCPackagePowerTarget"
+ "TLCMitigationSOCThreshold"
+ "TLCMitigationsEnabled"
+ "TQ,V_tlcHighSOCPowerOption"
+ "TQ,V_tlcLowSOCPowerOption"
+ "Tf,V_tlcBgPowerTarget"
+ "Tf,V_tlcUtilityPowerTarget"
+ "Ti,V_tlcSOCThreshold"
+ "Trial: TLC Mitigation High SOC Package Power Target = %lld"
+ "Trial: TLC Mitigation Low SOC Package Power Target = %lld"
+ "Trial: TLC Mitigation SOC Threshold = %lld"
+ "Trial: TLC Mitigations Enabled = %d"
+ "Trial:No trial value for TLC Mitigation High SOC Package Power Target"
+ "Trial:No trial value for TLC Mitigation Low SOC Package Power Target"
+ "Trial:No trial value for TLC Mitigation SOC Threshold"
+ "Trial:No trial value for TLC Mitigations Enabled"
+ "_tlcBgPowerTarget"
+ "_tlcEnabled"
+ "_tlcHighSOCPowerOption"
+ "_tlcLowSOCPowerOption"
+ "_tlcPredicted"
+ "_tlcSOCThreshold"
+ "_tlcUtilityPowerTarget"
+ "c!r"
+ "setTlcBgPowerTarget:"
+ "setTlcEnabled:"
+ "setTlcHighSOCPowerOption:"
+ "setTlcLowSOCPowerOption:"
+ "setTlcPredicted:"
+ "setTlcSOCThreshold:"
+ "setTlcUtilityPowerTarget:"
+ "tlcBgPowerTarget"
+ "tlcEnabled"
+ "tlcHighSOCPowerOption"
+ "tlcLowSOCPowerOption"
+ "tlcPredicted"
+ "tlcSOCThreshold"
+ "tlcUtilityPowerTarget"
+ "updateTLCBGUtilityPowerTargets:"
- "C!R"
```
