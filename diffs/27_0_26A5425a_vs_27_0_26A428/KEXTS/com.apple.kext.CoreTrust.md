## com.apple.kext.CoreTrust

> `com.apple.kext.CoreTrust`

```diff

 207.0.5.0.0
   __TEXT.__const: 0x8f08
-  __TEXT_EXEC.__text: 0xad78
+  __TEXT_EXEC.__text: 0xaf20
   __TEXT_EXEC.__auth_stubs: 0x220
   __DATA.__data: 0xd8
   __DATA.__common: 0x10
Functions:
~ _CTCopyDeviceIdentifiers : 292 -> 296
~ _CTConvertDashTerminatedHexstringTo64BitInteger : 252 -> 256
~ _CTEvaluateBAASystem : 72 -> 76
~ _CTEvaluateBAASystemWithId : 164 -> 168
~ _CTFillBAAIdentity : 164 -> 168
~ _CTEvaluateBAASystemTestRoot : 156 -> 160
~ _CTEvaluateBAAUser : 164 -> 168
~ _CTEvaluateBAAUserTestRoot : 156 -> 160
~ _CTEvaluateBAASepApp : 156 -> 160
~ _CTEvaluateBAAAccessory : 156 -> 160
~ _CTGetBAARootType : 296 -> 300
~ _CTGetBAASubCAType : 296 -> 300
~ _CMSParseContentInfoSignedDataWithOptions : 556 -> 560
~ _ccder_blob_decode_ber_tl : 160 -> 164
~ _CMSParseSignedData : 1004 -> 1008
~ _ccder_blob_decode_eoc : 164 -> 168
~ _CMSParseSignerInfos : 1620 -> 1624
~ _CMSBuildPath : 736 -> 740
~ _validateSignerInfo : 2152 -> 2156
~ _validateSignerInfoAndChain : 116 -> 120
~ _CMSVerifySignedDataWithLeaf : 88 -> 92
~ _CMSVerify : 580 -> 584
~ _CMSVerifyAndReturnSignedData : 104 -> 108
~ _CMSParseImplicitCertificateSet : 804 -> 808
~ _CMSParseEncapsulatedContent : 428 -> 432
~ _ccder_blob_eat_ber_inner : 320 -> 324
~ _CMSGetCertificateUsingIssuerSerialNumber : 132 -> 136
~ _CMSAttributeParseContentType : 184 -> 188
~ _CMSAttributeParseMessageDigest : 296 -> 300
~ _CMSAttributeParseAppleHashAgilityV2 : 536 -> 540
~ _CMSAttributeParseSigningTime : 220 -> 224
~ _CMSAttributeParseAppleHashAgility : 184 -> 188
~ _CMSAttributeParseSMIMECapabilities : 148 -> 152
~ _CTParseCertificateSet : 312 -> 316
~ _CTParseExtensionValue : 240 -> 244
~ _CTParseKey : 204 -> 208
~ _CTGetSKIDFromCertificate : 256 -> 260
~ _CTGetAKIDFromCertificate : 256 -> 260
~ _CTEvaluateCertsForPolicy : 836 -> 840
~ _CTEvaluateSatori : 68 -> 72
~ _CTEvaluatePragueSignatureCMS : 128 -> 132
~ _CTEvaluateKDLSignatureCMS : 128 -> 132
~ _CTGetSEKType : 236 -> 240
~ _CTEvaluateSEK : 208 -> 212
~ _CTGetICDPFederationType : 288 -> 292
~ _find_digest : 140 -> 144
~ _algorithmIsPQCComposite : 120 -> 124
~ _find_digestOID_for_signingOID : 396 -> 400
~ _validateSignaturePQCComposite : 324 -> 328
~ _validateOIDs : 192 -> 196
~ _validateSignatureRSA : 652 -> 656
~ _oidForPubKeyLength : 96 -> 100
~ _validateSignatureEC : 636 -> 640
~ _ccec_cp_for_oid : 236 -> 240
~ _coretrust_kext_start : 60 -> 64
~ _CTEvaluateAMFICodeSignatureCMS_MaxDigestType : 692 -> 696
~ _CTEvaluateAMFICodeSignatureCMS : 68 -> 72
~ _CTEvaluateAMFICodeSignatureCMSPubKey : 712 -> 716
~ _CTEvaluateProvisioningProfile : 148 -> 152
~ _CTAmfiInitializeContext : 116 -> 120
~ _CTAmfiInitializeContextWithOptions : 740 -> 744
~ _CTParseAmfiCMS_internal : 916 -> 920
~ _CTAmfiVerifyCMS : 360 -> 364
~ _CTAmfiVerifyCertificateChain : 488 -> 492
~ _CTParseAmfiCMS : 316 -> 320
~ _CTVerifyAmfiCMS : 200 -> 204
~ _CTVerifyAmfiCertificateChain : 160 -> 164
~ _CTGetSKIDAmfiCMS : 668 -> 672
~ _ccder_blob_decode_AlgorithmIdentifierNULL : 388 -> 392
~ _ccder_blob_check_null : 100 -> 104
~ _X509CertificateParseImplicit : 2456 -> 2460
~ _der_get_boolean : 264 -> 268
~ _X509ExtensionParseKeyUsage : 208 -> 212
~ _X509ExtensionParseBasicConstraints : 200 -> 204
~ _X509ExtensionParseAuthorityKeyIdentifier : 288 -> 292
~ _X509ExtensionParseSubjectKeyIdentifier : 196 -> 200
~ _X509ExtensionParseExtendedKeyUsage : 272 -> 276
~ _X509CertificateVerifyOnlyOneAppleExtension : 136 -> 140
~ _X509ExtensionParseAppleExtension : 1808 -> 1812
~ _X509CertificateParseWithExtension : 284 -> 288
~ _X509CertificateParseSPKI : 512 -> 516
~ _X509CertificateParseKey : 176 -> 180
~ _X509CertificateCheckSignatureDigest : 568 -> 572
~ _X509CertificateCheckSignature : 196 -> 200
~ _X509MatchSignatureAlgorithm : 468 -> 472
~ _X509CertificateCheckSignatureWithPublicKey : 456 -> 460
~ _X509CertificateSubjectNameGetCommonName : 804 -> 808
~ _X509ExtensionParseDeviceAttestationIdentity : 332 -> 336
~ _CTImg4VerifyChain : 572 -> 576
~ _CTImg4VerifySignatureWithPublicKey : 408 -> 412
~ _CTImg4CreateContext : 600 -> 604
~ _X509ChainParseCertificateSet : 452 -> 456
~ _X509ChainGetCertificateUsingKeyIdentifier : 104 -> 108
~ _X509ChainBuildPathPartial : 484 -> 488
~ _X509ChainGetAppleRootUsingKeyIdentifier : 184 -> 188
~ _X509ChainGetBAARootUsingKeyIdentifier : 168 -> 172
~ _X509ChainCheckPathWithOptions : 1468 -> 1472
~ _X509PolicySetFlagsForCommonNames : 276 -> 280
~ _X509PolicySetFlagsForRoots : 536 -> 540
~ _X509PolicySetFlagsForTestAnchor : 184 -> 188
~ _DERParseInteger : 132 -> 136
~ _DERDecodeSeqInit : 188 -> 192
~ _DERDecodeSeqNext : 188 -> 192
~ _DERImg4DecodeProperty : 304 -> 308
~ _DERImg4DecodeContentFindItemWithTag : 104 -> 108
~ _Img4DecodeEvaluateCertificatePropertiesInternal : 604 -> 608
```
