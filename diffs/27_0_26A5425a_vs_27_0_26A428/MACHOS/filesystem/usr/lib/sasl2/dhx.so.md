## dhx.so

> `/usr/lib/sasl2/dhx.so`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 195.0.0.0.0
-  __TEXT.__text: 0x102cc
+  __TEXT.__text: 0xfce4
   __TEXT.__auth_stubs: 0x290
   __TEXT.__gcc_except_tab: 0x834
   __TEXT.__const: 0x296
   __TEXT.__cstring: 0xa20
-  __TEXT.__unwind_info: 0x708
+  __TEXT.__unwind_info: 0x888
   __DATA_CONST.__const: 0x12b0
   __DATA_CONST.__auth_got: 0x150
   __DATA_CONST.__got: 0x40
Functions:
~ __ZN7AuthDHXD0Ev : 56 -> 44
~ _dhx_server_mech_step : 1100 -> 1104
~ _dhx_server_mech_dispose : 80 -> 68
~ _dhx_both_mech_dispose : 168 -> 156
~ _dhx_client_mech_dispose : 76 -> 64
~ __ZN19DSEncryptedEndpointD0Ev : 56 -> 44
~ _dhx_server_encode : 184 -> 176
~ _dhx_client_encode : 192 -> 184
~ __ZNK8CryptoPP13AbstractGroupINS_7IntegerEE10AccumulateERS1_RKS1_ : 84 -> 72
~ __ZNK8CryptoPP13AbstractGroupINS_7IntegerEE6ReduceERS1_RKS1_ : 84 -> 72
~ __ZNK8CryptoPP13AbstractGroupINS_7IntegerEE21CascadeScalarMultiplyERKS1_S4_S4_S4_ : 1572 -> 1536
~ __ZNK8CryptoPP13AbstractGroupINS_7IntegerEE20SimultaneousMultiplyEPS1_RKS1_PS4_j : 1372 -> 1336
~ __ZN8CryptoPP12WindowSlider14FindNextWindowEv : 308 -> 292
~ __ZNSt3__16vectorIN8CryptoPP7IntegerENS_9allocatorIS2_EEE6resizeEmRKS2_ : 440 -> 424
~ __ZNK8CryptoPP12AbstractRingINS_7IntegerEE19CascadeExponentiateERKS1_S4_S4_S4_ : 128 -> 116
~ __ZNK8CryptoPP12AbstractRingINS_7IntegerEE24SimultaneousExponentiateEPS1_RKS1_PS4_j : 112 -> 100
~ __ZNK8CryptoPP12AbstractRingINS_7IntegerEE20MultiplicativeGroupT10AccumulateERS1_RKS1_ : 88 -> 76
~ __ZNK8CryptoPP12AbstractRingINS_7IntegerEE20MultiplicativeGroupT6ReduceERS1_RKS1_ : 88 -> 76
~ __ZN8CryptoPP17RecursiveMultiplyEPjS0_PKjS2_j : 2500 -> 2492
~ __ZN8CryptoPP15RecursiveSquareEPjS0_PKjj : 360 -> 324
~ __ZN8CryptoPP23RecursiveMultiplyBottomEPjS0_PKjS2_j : 1176 -> 1164
~ __ZN8CryptoPP20RecursiveMultiplyTopEPjS0_PKjS2_S2_j : 1008 -> 992
~ __ZN8CryptoPP18AsymmetricMultiplyEPjS0_PKjjS2_j : 736 -> 688
~ __ZN8CryptoPP25RecursiveInverseModPower2EPjS0_PKjj : 392 -> 380
~ __ZN8CryptoPP6DivideEPjS0_S0_PKjjS2_j : 1616 -> 1620
~ __ZN8CryptoPP7IntegerC2El : 252 -> 248
~ __ZN8CryptoPP8SecBlockIjE8CleanNewEj : 176 -> 164
~ __ZNK8CryptoPP7Integer6EncodeERNS_22BufferedTransformationEjNS0_10SignednessE : 520 -> 516
~ __ZNK8CryptoPP7Integer4PlusERKS0_ : 240 -> 236
~ __ZNK8CryptoPP7Integer5MinusERKS0_ : 240 -> 236
~ __ZN8CryptoPP7IntegerlSEj : 336 -> 332
~ __ZN8CryptoPP16PositiveMultiplyERNS_7IntegerERKS0_S3_ : 560 -> 548
~ __ZN8CryptoPP14PositiveDivideERNS_7IntegerES1_RKS0_S3_ : 732 -> 708
~ __ZNK8CryptoPP7Integer7CompareERKS0_ : 96 -> 84
~ __ZNK8CryptoPP7Integer21MultiplicativeInverseEv : 116 -> 104
~ __ZNK8CryptoPP7Integer10InverseModERKS0_ : 1116 -> 1092
~ __ZNK8CryptoPP17ModularArithmetic19CascadeExponentiateERKNS_7IntegerES3_S3_S3_ : 572 -> 560
~ __ZNK8CryptoPP24MontgomeryRepresentation10ConvertOutERKNS_7IntegerE : 192 -> 180
~ __ZNK8CryptoPP24MontgomeryRepresentation19CascadeExponentiateERKNS_7IntegerES3_S3_S3_ : 128 -> 116
~ __ZNK8CryptoPP17ModularArithmetic24SimultaneousExponentiateEPNS_7IntegerERKS1_PS3_j : 524 -> 512
~ __ZNK8CryptoPP24MontgomeryRepresentation24SimultaneousExponentiateEPNS_7IntegerERKS1_PS3_j : 112 -> 100
~ __ZN8CryptoPP17ModularArithmeticD0Ev : 208 -> 196
~ __ZNK8CryptoPP17ModularArithmetic6DivideERKNS_7IntegerES3_ : 120 -> 108
~ __ZN8CryptoPP24MontgomeryRepresentationD0Ev : 56 -> 44
~ __ZN8CryptoPP9ExceptionD0Ev : 56 -> 44
~ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE25__init_copy_ctor_externalEPKcm : 68 -> 56
~ __ZN8CryptoPP9ExceptionD2Ev : 96 -> 84
~ __ZN8CryptoPP5StoreC2Ev : 280 -> 200
~ __ZN8CryptoPP9ArraySink3PutEPKhj : 88 -> 84
~ __ZN8CryptoPP7Integer12DivideByZeroD0Ev : 56 -> 44
~ __ZN8CryptoPP17EuclideanDomainOfINS_7IntegerEED0Ev : 216 -> 204
~ __ZNSt3__16vectorIN8CryptoPP7IntegerENS_9allocatorIS2_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__16vectorIN8CryptoPP12WindowSliderENS_9allocatorIS2_EEE16__destroy_vectorclB9nqe220106Ev : 84 -> 72
~ __ZNSt3__116allocator_traitsINS_9allocatorIN8CryptoPP12WindowSliderEEEE7destroyB9nqe220106IS3_Li0EEEvRS4_PT_ : 136 -> 124
~ __ZNSt3__16vectorIN8CryptoPP12WindowSliderENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 360 -> 356
~ _OUTLINED_FUNCTION_0 : 44 -> 32
~ _OUTLINED_FUNCTION_1 : 44 -> 32
~ __ZNK8CryptoPP11StringStore6CopyToERNS_22BufferedTransformationEm : 96 -> 92
~ __ZN8CryptoPP22BufferedTransformation5FlushEbi : 196 -> 184
~ __ZN8CryptoPP22BufferedTransformation10MessageEndEi : 176 -> 164
~ __ZN8CryptoPP22BufferedTransformation16MessageSeriesEndEi : 176 -> 164
~ __ZN8CryptoPP22BufferedTransformation13PutMessageEndEPKhji : 112 -> 100
~ __ZN8CryptoPP22BufferedTransformation12ChannelFlushERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEbi : 304 -> 260
~ __ZN8CryptoPP22BufferedTransformation17ChannelMessageEndERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEi : 300 -> 256
~ __ZN8CryptoPP22BufferedTransformation23ChannelMessageSeriesEndERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEi : 300 -> 256
~ __ZN8CryptoPP22BufferedTransformation20ChannelPutMessageEndERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPKhji : 264 -> 200
~ __ZNK8CryptoPP22BufferedTransformation14MaxRetrievableEv : 216 -> 192
~ __ZNK8CryptoPP22BufferedTransformation14AnyRetrievableEv : 216 -> 204
~ __ZN8CryptoPP22BufferedTransformation3GetERh : 228 -> 184
~ __ZN8CryptoPP22BufferedTransformation3GetEPhj : 276 -> 264
~ __ZNK8CryptoPP22BufferedTransformation4PeekERh : 228 -> 184
~ __ZNK8CryptoPP22BufferedTransformation4PeekEPhj : 276 -> 264
~ __ZN8CryptoPP22BufferedTransformation4SkipEm : 236 -> 212
~ __ZNK8CryptoPP22BufferedTransformation6CopyToERS0_m : 192 -> 180
~ __ZN8CryptoPP22BufferedTransformation10TransferToERS0_m : 192 -> 180
~ __ZNK8CryptoPP22BufferedTransformation21TotalBytesRetrievableEv : 212 -> 168
~ __ZNK8CryptoPP22BufferedTransformation16NumberOfMessagesEv : 216 -> 192
~ __ZNK8CryptoPP22BufferedTransformation11AnyMessagesEv : 196 -> 156
~ __ZN8CryptoPP22BufferedTransformation14GetNextMessageEv : 164 -> 152
~ __ZN8CryptoPP22BufferedTransformation12SkipMessagesEj : 236 -> 212
~ __ZN8CryptoPP22BufferedTransformation18TransferMessagesToERS0_j : 388 -> 376
~ __ZNK8CryptoPP22BufferedTransformation14CopyMessagesToERS0_j : 192 -> 180
~ __ZN8CryptoPP22BufferedTransformation7SkipAllEv : 228 -> 216
~ __ZN8CryptoPP22BufferedTransformation13TransferAllToERS0_ : 256 -> 244
~ __ZNK8CryptoPP22BufferedTransformation9CopyAllToERS0_ : 280 -> 236
~ __ZN8CryptoPP22BufferedTransformation19SetRetrievalChannelERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 180 -> 168
~ __ZN8CryptoPP22BufferedTransformation6AttachEPS0_ : 364 -> 340
```
