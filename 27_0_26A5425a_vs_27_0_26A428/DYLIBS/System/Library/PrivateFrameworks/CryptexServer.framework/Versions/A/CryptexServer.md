## CryptexServer

> `/System/Library/PrivateFrameworks/CryptexServer.framework/Versions/A/CryptexServer`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

 761.1.1.0.0
-  __TEXT.__text: 0x2f2d6c
+  __TEXT.__text: 0x2f3330
   __TEXT.__objc_methlist: 0x104
   __TEXT.__const: 0x58416
   __TEXT.__cstring: 0x1d2c3

   __TEXT.__swift5_mpenum: 0xa8
   __TEXT.__gcc_except_tab: 0x30f4
   __TEXT.__unwind_info: 0xc5d8
-  __TEXT.__eh_frame: 0x19adc
+  __TEXT.__eh_frame: 0x19af4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
Functions:
~ __ZL12table_selectP10ge_precompia : 448 -> 452
~ _CCryptoBoringSSL_ec_key_parse_parameters : 1280 -> 1288
~ _CCryptoBoringSSL_EVP_PBE_scrypt : 728 -> 720
~ _CCryptoBoringSSL_CRYPTO_ctr128_encrypt_ctr32 : 496 -> 504
~ __ZL16copy_from_prebufP9bignum_stiPKyii : 188 -> 192
~ _CCryptoBoringSSL_bn_rshift_words : 248 -> 252
~ __ZL27ec_GFp_mont_get_comb_windowPK11ec_group_stP11EC_JACOBIANPK10EC_PRECOMPPK9EC_SCALARj : 424 -> 416
~ _CCryptoBoringSSL_BCM_mldsa65_parse_public_key : 204 -> 208
~ __ZN5mldsa12_GLOBAL__N_125mldsa_marshal_private_keyILi6ELi5EEEiP6cbb_stPKNS0_11private_keyIXT_EXT0_EEE : 348 -> 360
~ _CCryptoBoringSSL_BCM_mldsa65_parse_private_key : 372 -> 384
~ __ZN5mldsa12_GLOBAL__N_125mldsa_public_from_privateILi6ELi5EEEiPNS0_10public_keyIXT_EEEPKNS0_11private_keyIXT_EXT0_EEE : 416 -> 432
~ __ZN5mldsa12_GLOBAL__N_113mldsa_sign_muILi6ELi5EEEiPhPKNS0_11private_keyIXT_EXT0_EEEPKhS8_ : 2552 -> 2648
~ __ZN5mldsa12_GLOBAL__N_124mldsa_marshal_public_keyILi6EEEiP6cbb_stPKNS0_10public_keyIXT_EEE : 136 -> 140
~ _CCryptoBoringSSL_BCM_mldsa87_parse_public_key : 204 -> 208
~ _CCryptoBoringSSL_BCM_mldsa87_marshal_private_key : 364 -> 376
~ _CCryptoBoringSSL_BCM_mldsa87_parse_private_key : 380 -> 392
~ _CCryptoBoringSSL_BCM_mldsa87_generate_key_external_entropy : 744 -> 768
~ __ZN5mldsa12_GLOBAL__N_125mldsa_public_from_privateILi8ELi7EEEiPNS0_10public_keyIXT_EEEPKNS0_11private_keyIXT_EXT0_EEE : 416 -> 432
~ __ZN5mldsa12_GLOBAL__N_113mldsa_sign_muILi8ELi7EEEiPhPKNS0_11private_keyIXT_EXT0_EEEPKhS8_ : 2552 -> 2648
~ __ZN5mldsa12_GLOBAL__N_124mldsa_marshal_public_keyILi8EEEiP6cbb_stPKNS0_10public_keyIXT_EEE : 136 -> 140
~ _CCryptoBoringSSL_BCM_mldsa44_parse_public_key : 204 -> 208
~ _CCryptoBoringSSL_BCM_mldsa44_marshal_private_key : 364 -> 376
~ _CCryptoBoringSSL_BCM_mldsa44_parse_private_key : 380 -> 392
~ _CCryptoBoringSSL_BCM_mldsa44_generate_key_external_entropy : 740 -> 764
~ __ZN5mldsa12_GLOBAL__N_125mldsa_public_from_privateILi4ELi4EEEiPNS0_10public_keyIXT_EEEPKNS0_11private_keyIXT_EXT0_EEE : 404 -> 420
~ __ZN5mldsa12_GLOBAL__N_113mldsa_sign_muILi4ELi4EEEiPhPKNS0_11private_keyIXT_EXT0_EEEPKhS8_ : 2576 -> 2668
~ __ZN5mldsa12_GLOBAL__N_124mldsa_marshal_public_keyILi4EEEiP6cbb_stPKNS0_10public_keyIXT_EEE : 136 -> 140
~ __ZN5mlkem12_GLOBAL__N_124mlkem_decap_no_self_testILi3EEEvPhPKhPKNS0_11private_keyIXT_EEE : 776 -> 788
~ __ZN5mlkem12_GLOBAL__N_124mlkem_decap_no_self_testILi4EEEvPhPKhPKNS0_11private_keyIXT_EEE : 772 -> 784
~ _CCryptoBoringSSL_BCM_mlkem1024_generate_key_external_seed : 652 -> 684
~ __ZN5mlkem12_GLOBAL__N_124mlkem_marshal_public_keyILi3EEE12bcm_status_tP6cbb_stPKNS0_10public_keyIXT_EEE : 160 -> 164
~ __ZN5mlkem12_GLOBAL__N_124mlkem_marshal_public_keyILi4EEE12bcm_status_tP6cbb_stPKNS0_10public_keyIXT_EEE : 160 -> 164
~ __ZN5mlkem12_GLOBAL__N_125mlkem_marshal_private_keyILi3EEEiP6cbb_stPKNS0_11private_keyIXT_EEE : 208 -> 212
~ _CCryptoBoringSSL_BCM_mlkem1024_marshal_private_key : 208 -> 212
~ __ZN5mlkem12_GLOBAL__N_123mlkem_parse_private_keyILi3EEEiPNS0_11private_keyIXT_EEEP6cbs_st : 208 -> 212
~ _CCryptoBoringSSL_BCM_mlkem1024_parse_private_key : 216 -> 220
~ __ZL17bn_sub_part_wordsPyPKyS1_ii : 180 -> 184
~ __ZL27ecp_nistz256_point_mul_basePK11ec_group_stP11EC_JACOBIANPK9EC_SCALAR : 516 -> 520
~ __ZL30ecp_nistz256_points_mul_publicPK11ec_group_stP11EC_JACOBIANPK9EC_SCALARPKS2_S6_ : 504 -> 508
~ __ZN5mldsa12_GLOBAL__N_148mldsa_generate_key_external_entropy_no_self_testILi6ELi5EEEiPhPNS0_11private_keyIXT_EXT0_EEEPKh : 740 -> 764
~ __ZN5mldsa12_GLOBAL__N_113matrix_expandILi6ELi5EEEvPNS0_6matrixIXT_EXT0_EEEPKh : 160 -> 168
~ __ZN5mldsa12_GLOBAL__N_111matrix_multILi6ELi5EEEvPNS0_6vectorIXT_EEEPKNS0_6matrixIXT_EXT0_EEEPKNS2_IXT0_EEE : 224 -> 248
~ __ZN5mldsa12_GLOBAL__N_134mldsa_verify_internal_no_self_testILi6ELi5EEEiPKNS0_10public_keyIXT_EEEPKhS7_mS7_mS7_m : 1512 -> 1556
~ __ZN5mlkem12_GLOBAL__N_145mlkem_generate_key_external_seed_no_self_testILi3EEEvPhPNS0_11private_keyIXT_EEEPKh : 652 -> 684
~ __ZN5mlkem12_GLOBAL__N_113matrix_expandILi3EEEvPNS0_6matrixIXT_EEEPKh : 248 -> 256
~ __ZN4bssl16CCryptoBoringSSL6VectorINSt3__110unique_ptrI9bignum_stNS0_8internal7DeleterEEEE9MaybeGrowEv : 232 -> 228
~ __ZN5mldsa12_GLOBAL__N_134mldsa_verify_internal_no_self_testILi8ELi7EEEiPKNS0_10public_keyIXT_EEEPKhS7_mS7_mS7_m : 1516 -> 1560
~ __ZN5mldsa12_GLOBAL__N_113matrix_expandILi8ELi7EEEvPNS0_6matrixIXT_EXT0_EEEPKh : 164 -> 168
~ __ZN5mldsa12_GLOBAL__N_111matrix_multILi8ELi7EEEvPNS0_6vectorIXT_EEEPKNS0_6matrixIXT_EXT0_EEEPKNS2_IXT0_EEE : 240 -> 248
~ __ZN5mldsa12_GLOBAL__N_134mldsa_verify_internal_no_self_testILi4ELi4EEEiPKNS0_10public_keyIXT_EEEPKhS7_mS7_mS7_m : 1528 -> 1568
~ __ZN5mldsa12_GLOBAL__N_113matrix_expandILi4ELi4EEEvPNS0_6matrixIXT_EXT0_EEEPKh : 156 -> 164
~ __ZN5mldsa12_GLOBAL__N_111matrix_multILi4ELi4EEEvPNS0_6vectorIXT_EEEPKNS0_6matrixIXT_EXT0_EEEPKNS2_IXT0_EEE : 220 -> 244
~ __ZN5mldsa12_GLOBAL__N_113vector_encodeILi4EEEvPhPKNS0_6vectorIXT_EEEi : 304 -> 312
~ __ZN5mlkem12_GLOBAL__N_130mlkem_parse_public_key_no_hashILi3EEEiPNS0_10public_keyIXT_EEEP6cbs_st : 164 -> 168
~ __ZN5mlkem12_GLOBAL__N_111encrypt_cpaILi3EEEvPhPKNS0_10public_keyIXT_EEEPKhS8_ : 964 -> 1004
~ __ZN5mlkem12_GLOBAL__N_120scalar_inner_productILi3EEEvPNS0_6scalarEPKNS0_6vectorIXT_EEES7_ : 220 -> 224
~ __ZN5mlkem12_GLOBAL__N_111encrypt_cpaILi4EEEvPhPKNS0_10public_keyIXT_EEEPKhS8_ : 964 -> 1004
~ __ZN5mlkem12_GLOBAL__N_120scalar_inner_productILi4EEEvPNS0_6scalarEPKNS0_6vectorIXT_EEES7_ : 220 -> 224
~ __ZN5mlkem12_GLOBAL__N_113matrix_expandILi4EEEvPNS0_6matrixIXT_EEEPKh : 244 -> 252
~ __ZN5mlkem12_GLOBAL__N_130mlkem_parse_public_key_no_hashILi4EEEiPNS0_10public_keyIXT_EEEP6cbs_st : 164 -> 168
~ __ZL13poly3_mul_auxPK10poly3_spanS1_S1_S1_m : 752 -> 760
~ _CCryptoBoringSSL_KYBER_generate_key_external_entropy : 584 -> 612
~ __ZL13matrix_expandP6matrixPKh : 352 -> 360
~ __ZL10vector_nttP6vector : 292 -> 296
~ __ZL24kyber_marshal_public_keyP6cbb_stPKN12_GLOBAL__N_110public_keyE : 148 -> 152
~ __ZL11encrypt_cpaPhPKN12_GLOBAL__N_110public_keyEPKhS5_ : 948 -> 984
~ _CCryptoBoringSSL_KYBER_decap : 780 -> 788
~ __ZL30kyber_parse_public_key_no_hashPN12_GLOBAL__N_110public_keyEP6cbs_st : 164 -> 168
~ _CCryptoBoringSSL_KYBER_marshal_private_key : 196 -> 200
~ _CCryptoBoringSSL_KYBER_parse_private_key : 208 -> 212
~ __ZL20scalar_inner_productP6scalarPK6vectorS3_ : 220 -> 224
~ _CCryptoBoringSSL_PEM_read_bio : 1520 -> 1528
~ sub_23f75a7d0 -> sub_23eadec04 : 16 -> 28
~ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_10CryptexKit11PkgObjectIdVyAD0G4MetaVG_Tg504$s10e4Kit6g56EnvV0A6ServerE6RecordV6encode2toys7Encoder_p_tKFSayAA0C8hi2Vyv2C4J27VGGShyANGXEfU_SbAN_ANtXEfU_Tf1nnncn_n : 2504 -> 2508
~ _$s13CryptexServer12PkgInventoryC7vfsInit33_9EDA62DDC8CCBC284DF525D42ACCF48ALLyyKF : 1192 -> 1176
~ _$s13CryptexServer12PkgInventoryC12listRequiredSDy0A3Kit0C3RefVSaySSGGyKF : 1812 -> 1792
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_6System8FilePathVTg5 : 908 -> 916
~ _$ss17_NativeDictionaryV4copyyyFSS_6System8FilePathVTg5 : 648 -> 656
~ _$s13CryptexServer11DyldClosureV04saveD4File33_1D9A308638CCE106A28546C1D6D07CF0LL4path6parent7content10attributes3pidySS_SSSays5UInt8VGSDySSAMGs5Int32Vt6System5ErrnoVYKF : 2132 -> 2136
~ _$s13CryptexServer11DyldClosureV14removeClosures33_1D9A308638CCE106A28546C1D6D07CF0LL7matcherSi7removed_Si5totaltSbSS_SStXE_tF : 1864 -> 1868
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_10CryptexKit8Response_pAF14RequestWrapperV_So13audit_token_tatYaKcTg5 : 688 -> 692
~ _$s11AppleImage48ManifestV14CryptexSigningE8unsigned12certificates12measurements10propertiesACSay4X50911CertificateVG_AD0D0V12MeasurementsVSayAA8PropertyVGtFZ : 1016 -> 1020
~ _$s11AppleImage48ManifestV14CryptexSigningE8unsigned12certificates12measurements10propertiesACSay4X50911CertificateVG_SDySS9CryptoKit6Digest_pGSayAA8PropertyVGtFZ : 2124 -> 2128
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_9CryptoKit12SHA384DigestVTg5 : 908 -> 916
~ _$ss17_NativeDictionaryV4copyyyFSS_9CryptoKit12SHA384DigestVTg5 : 648 -> 656
~ _$s21_CertificateInternals10_TinyArrayV7StorageOAASHRzlE4hash4intoys6HasherVz_tF4X50925RelativeDistinguishedNameV9AttributeV_Tg5 : 1056 -> 1096
~ _$s4X50911CertificateV10ExtensionsVyAExKcSTRzAC9ExtensionV7ElementRtzlufCSayAGG_Tt0g5 : 1172 -> 1164
~ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_SnySiG_Tgq5 : 1124 -> 1128
~ _$ss30_copySequenceToContiguousArrayys0dE0Vy7ElementQzGxSTRzlF4X509015ReverseDNSLabelB0V_Tgq5 : 936 -> 960
~ _$ss6HasherV4X509E7combine10contentsOfyx_tSTRzSHR_7ElementQzRs_r0_lFAC15NameConstraintsV8DNSNamesV_SSTgq5 : 572 -> 576
~ _$ss6HasherV4X509E7combine10contentsOfyx_tSTRzSHR_7ElementQzRs_r0_lFAC15NameConstraintsV14EmailAddressesV_SSTgq5 : 584 -> 588
~ _$ss6HasherV4X509E7combine10contentsOfyx_tSTRzSHR_7ElementQzRs_r0_lFAC15NameConstraintsV10URIDomainsV_SSTgq5 : 576 -> 580
~ _$s4X50911CertificateV10ExtensionsVyAExKcSTRzAC9ExtensionV7ElementRtzlufC : 1608 -> 1604
~ _$s4X5098VerifierV8validate4leaf13intermediates18diagnosticCallbackAA27CertificateValidationResultOAA0H0V_AA0H5StoreVyAA22VerificationDiagnosticVcSgtYaFAA13PolicyBuilderV33CachedVerifyingCriticalExtensionsVy_AR6Tuple2Vy_AA020OCSPResponderSigningN0VAR7_EitherVy_AA07RFC5280N0VA0_GGG_Tg5TY7_ : 5844 -> 5872
~ _$s4X5098VerifierV8validate4leaf13intermediates18diagnosticCallbackAA27CertificateValidationResultOAA0H0V_AA0H5StoreVyAA22VerificationDiagnosticVcSgtYaFAA13PolicyBuilderV33CachedVerifyingCriticalExtensionsVy_AR6Tuple2Vy_AA020OCSPResponderSigningN0VAR7_EitherVy_AA07RFC5280N0VA0_GGG_Tg5TY16_ : 5568 -> 5572
~ _$s4X50925RelativeDistinguishedNameV9removeAll5whereySbAC9AttributeVKXE_tKF : 1132 -> 1140
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy4X50925RelativeDistinguishedNameVG_s010CollectionH3OneVyANGTgq5Tf4nngn_n : 424 -> 428
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy4X50911GeneralNameOG_s010CollectionH3OneVyANGTgq5Tf4nngn_n : 424 -> 428
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy4X50916ExtendedKeyUsageV0M0VG_s010CollectionH3OneVyAPGTgq5Tf4nngn_n : 364 -> 372
~ _$s4X50911CertificateV10PrivateKeyV03SecD7WrapperV14isSerializableSbvg : 204 -> 208
~ _$s4X50911CertificateV10PrivateKeyV03SecD7WrapperV08validateeD010attributesySDySSs8Sendable_pG_tKFZTf4nd_n : 572 -> 576
~ _$s4X50911CertificateV10PrivateKeyV03SecD7WrapperV7keyType10attributesAG0dH0OSDySSs8Sendable_pG_tKFZTf4nd_n : 960 -> 968
~ _$sSD8grouping2bySDyxSay7ElementQyd__GGqd__n_xADqd_0_YKXEtqd_0_YKcAERs_STRd__s5ErrorRd_0_r0_lufC : 1764 -> 1756
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lF4X50911GeneralNameO_s18LazyFilterSequenceVySayAGGGTg5 : 600 -> 608
~ _$s10Foundation4DataV6append10contentsOfyx_tSTRzs5UInt8V7ElementRtzlFs8RepeatedVyAGG_Tgq5 : 1772 -> 1796
~ _$ss30_copySequenceToContiguousArrayys0dE0Vy7ElementQzGxSTRzlF9SwiftASN10H14NodeCollectionV_Tgq5 : 836 -> 848
~ _$sSr15_stableSortImpl2byySbx_xtKXE_tKFySryxGz_SiztKXEfU_SnySiG_Tgq5 : 1108 -> 1112
~ _$s19CryptoBoringWrapper0B7SSLAEADO11AEADContextC15_openContiguous10ciphertext5nonce3tag17authenticatedData10Foundation0L0VAM_xAMq_tKAK0G5BytesRzAkNR_r0_lF : 696 -> 748
~ _$s19CryptoBoringWrapper0B7SSLAEADO11AEADContextC15_openContiguous10ciphertext5nonce3tag17authenticatedData10Foundation0L0VAM_xAMq_tKAK0G5BytesRzAkNR_r0_lFAMSWKXEfU_AMSWKXEfU_ : 652 -> 660
~ _$s19CryptoBoringWrapper0B7SSLAEADO11AEADContextC15_openContiguous24combinedCiphertextAndTag5nonce17authenticatedData10Foundation0N0VAL_xq_tKAJ0G5BytesRzAjMR_r0_lF : 664 -> 684
~ _$s10Foundation4DataV19CryptoBoringWrapperE6append7bytesOf12paddedToSizeyAD25ArbitraryPrecisionIntegerV_SitKF : 1392 -> 1396
~ _$s10Foundation4DataV6append10contentsOfyx_tSTRzs5UInt8V7ElementRtzlFs8RepeatedVyAGG_Tg5 : 1772 -> 1796
~ _$s19CryptoBoringWrapper0B7SSLAEADO11AEADContextC15_openContiguous24combinedCiphertextAndTag5nonce17authenticatedData10Foundation0N0VAL_xq_tKAJ0G5BytesRzAjMR_r0_lFALSWKXEfU_ALSWKXEfU_0A3Kit3AESO3GCMO0A6ExtrasE4_SIVO5NonceV_ALTg5 : 564 -> 616
~ _$s9CryptoKit3AESO3GCMO0A6ExtrasE4_SIVO5NonceVAJycfCTf4d_n : 836 -> 840
~ _$s12CryptoExtras17OpenSSLAESCFBImplO17_encryptOrDecrypt__5using2iv10Foundation4DataVAC4ModeO_SW0A3Kit12SymmetricKeyVAL3AESOAAE4_CFBO2IVVtFZTf4nnnnd_n : 1232 -> 1236
~ _$s12CryptoExtras17OpenSSLAESCTRImplO8_encrypt_5using5nonce10Foundation4DataVSW_0A3Kit12SymmetricKeyVAJ3AESOAAE4_CTRO5NonceVtFZTf4nnnd_n : 1300 -> 1304
~ _$s12CryptoExtras3ARCO12PresentationV10credential1a1r1z19presentationContext5nonce10generatorG0I1HAEy_xGAC10CredentialVy_xG_1G_7Element6ScalarQZA2U10Foundation4DataVSiAR_ASQZAYtKcfCAA18OpenSSLHashToCurveVy0A3Kit4P256OG_Tt8g5Tm : 4420 -> 4416
~ _$s12CryptoExtras8VerifierV6verify5proofSbAA5ProofVyxG_tKFAA18OpenSSLHashToCurveVy0A3Kit4P256OG_Tg5 : 2012 -> 2032
~ _$s12CryptoExtras8VerifierV6verify5proofSbAA5ProofVyxG_tKFAA18OpenSSLHashToCurveVy0A3Kit4P384OG_Tg5 : 2012 -> 2032
~ _$s12CryptoExtras3ARCO18CredentialResponseV7request16serverPrivateKey0g6PublicI010generatorG0K1H1b11ciphersuiteAEy_xGAC0D7RequestVy_xG_AC06ServerhI0Vy_1G_7Element6ScalarQZGAC0njI0Vy_xGAS_ATQZA_AvC11CiphersuiteVy_xGtKcfCAA18OpenSSLHashToCurveVy0A3Kit4P256OG_Tt7g5Tm : 4276 -> 4264
~ _$s12CryptoExtras3ARCO18CredentialResponseV6verify7request15serverPublicKey10generatorG0K1H11ciphersuiteSbAC0D7RequestVy_xG_AC06ServeriJ0Vy_xG1G_7ElementQZAtC11CiphersuiteVy_xGtKFAA18OpenSSLHashToCurveVy0A3Kit4P256OG_Tg5Tf4xnnnnn_nTm : 3276 -> 3256
~ _$s12CryptoExtras3ARCO12PresentationV6verify16serverPrivateKey2X12m219presentationContext0K5Limit5nonce10generatorG0O1H11ciphersuiteSbAC06ServergH0Vy_1G_7Element6ScalarQZG_AR_ASQZAU10Foundation4DataVS2iA2wC11CiphersuiteVy_xGtKFAA18OpenSSLHashToCurveVy0A3Kit4P256OG_Tg5Tf4xnnnnnnnnn_nTm : 3872 -> 3860
~ _$s9CryptoKit8InsecureO0A6ExtrasE11ChaCha20CTRO5NonceVAHycfC : 836 -> 840
~ _$s12CryptoExtras06CommonA6PBKDF2V9deriveKey4from4salt5using15outputByteCount6rounds0A3Kit09SymmetricF0Vx_q_AA3KDFO8InsecureO0D0V12HashFunctionVS2itK10Foundation12DataProtocolRzAuVR_r0_lFZ : 1112 -> 1116
~ _$s12CryptoExtras15BoringSSLScryptV9deriveKey4from4salt15outputByteCount6rounds9blockSize11parallelism9maxMemory0A3Kit09SymmetricF0Vx_q_S5iSgtK10Foundation12DataProtocolRzApQR_r0_lFZ : 1312 -> 1316
~ _$s12CryptoExtras22BoringSSLRSAPrivateKeyV7Backing33_207EAA3F6E17E9956D23C900B2D04ED1LLC7decrypt_7padding10Foundation4DataVx_AA4_RSAO10EncryptionO7PaddingVtKAI0S8ProtocolRzlF : 2948 -> 2952
~ _$s12CryptoExtras21BoringSSLRSAPublicKeyV7Backing33_207EAA3F6E17E9956D23C900B2D04ED1LLC7encrypt_7padding10Foundation4DataVx_AA4_RSAO10EncryptionO7PaddingVtKAI0S8ProtocolRzlF : 2312 -> 2316
~ _$ss17_NativeDictionaryV4copyyyFSS_11AppleImage46TaggedVyAD12SignedObjectOGTg5 : 456 -> 460
CStrings:
+ "@(#)VERSION:Darwin Cryptex Server Framework Version 1.0.0: Sat Aug  8 17:33:13 PDT 2026; root:libcryptex-761.1.1~11/CryptexServer/RELEASE_ARM64E"
+ "Darwin Cryptex Server Framework Version 1.0.0: Sat Aug  8 17:33:13 PDT 2026; root:libcryptex-761.1.1~11/CryptexServer/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Cryptex Server Framework Version 1.0.0: Sat Aug  8 19:46:12 PDT 2026; root:libcryptex-761.1.1~12/CryptexServer/RELEASE_ARM64E"
- "Darwin Cryptex Server Framework Version 1.0.0: Sat Aug  8 19:46:12 PDT 2026; root:libcryptex-761.1.1~12/CryptexServer/RELEASE_ARM64E"
```
