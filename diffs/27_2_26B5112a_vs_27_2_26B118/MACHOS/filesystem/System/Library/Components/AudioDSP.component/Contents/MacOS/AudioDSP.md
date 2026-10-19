## AudioDSP

> `/System/Library/Components/AudioDSP.component/Contents/MacOS/AudioDSP`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 881.210.10.1.0
-  __TEXT.__text: 0x3c5f88
-  __TEXT.__realtime: 0x17ab1c
+  __TEXT.__text: 0x3c704c
+  __TEXT.__realtime: 0x17aaa8
   __TEXT.__auth_stubs: 0x40f0
-  __TEXT.__objc_stubs: 0x1620
+  __TEXT.__objc_stubs: 0x1640
   __TEXT.__objc_methlist: 0x424
-  __TEXT.__const: 0xa3f10
-  __TEXT.__cstring: 0x3606f
-  __TEXT.__gcc_except_tab: 0x33b48
-  __TEXT.__oslogstring: 0x34750
-  __TEXT.__objc_methname: 0x1323
+  __TEXT.__const: 0xa3f30
+  __TEXT.__cstring: 0x3618f
+  __TEXT.__gcc_except_tab: 0x33ca8
+  __TEXT.__oslogstring: 0x35482
+  __TEXT.__objc_methname: 0x1341
   __TEXT.__objc_classname: 0xf4
   __TEXT.__objc_methtype: 0xae4
-  __TEXT.__unwind_info: 0x10b70
+  __TEXT.__unwind_info: 0x10b88
   __TEXT.__eh_frame: 0xf8
   __DATA_CONST.__const: 0x32170
-  __DATA_CONST.__cfstring: 0x20f80
+  __DATA_CONST.__cfstring: 0x210e0
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__got: 0x488
   __DATA_CONST.__auth_ptr: 0x8
   __DATA.__objc_const: 0x8b0
-  __DATA.__objc_selrefs: 0x690
+  __DATA.__objc_selrefs: 0x698
   __DATA.__objc_ivar: 0x3c
   __DATA.__objc_data: 0x1e0
   __DATA.__data: 0x3208

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 12184
+  Functions: 12187
   Symbols:   1336
-  CStrings:  12084
+  CStrings:  12106
 
CStrings:
+ "%25s:%-5d EXCEPTION (%d) [!validContext is false]: \"Unable to load BNNS Context\""
+ "%25s:%-5d EXCEPTION (%d) [(mInputSize != mNumMelBands*2) is false]: \"mInputSize is wrong.\""
+ "%25s:%-5d EXCEPTION (%d) [(mInputSize != mNumMelBands*mNumContextFrames*(1+mDeltaFeature)) is false]: \"mInputSize is wrong.\""
+ "%25s:%-5d EXCEPTION (%d) [activationDict_ref.get_cf() == nullptr is false]: \"Missing dictionary Activation.\""
+ "%25s:%-5d EXCEPTION (%d) [activationFunction_ref.get_cf() == nullptr is false]: \"Failed to retrieve activation function (Function) from dictionary Activation.\""
+ "%25s:%-5d EXCEPTION (%d) [biasDataType_ref.get_cf() == nullptr is false]: \"Missing dictionary DataType from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [biasDict_ref.get_cf() == nullptr is false]: \"Missing dictionary Bias from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"BlockSize not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"ECOutScale not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"FFT2Mel matrix not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve BlockSize.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve ECleeScale.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve ECoutScale.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve HangA01.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve HangA10.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve InputScale.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve NumContextFrames.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve NumLayers.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve WaitFrames.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve forgetting factor Lambda_TC.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve sample rate.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Failed to retrieve threshold.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"KalmanObservationStd not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"KalmanProcessStd not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"LambdaPSD_TC not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"MCLPOutScale not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar Alpha from dictionary Activation.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar Beta from dictionary Activation.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataBias from dictionary Bias.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataBias from dictionary InputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataBias from dictionary OutputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataBias from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataScale from dictionary Bias.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataScale from dictionary InputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataScale from dictionary OutputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar DataScale from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar Size from dictionary InputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing scalar Size from dictionary OutputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing vector Data from dictionary Bias.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"Missing vector Data from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"NumContextFrames not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"NumInputChannels not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"SampleRate not loaded\""
+ "%25s:%-5d EXCEPTION (%d) [err != noErr is false]: \"WaitFrames not loaded.\""
+ "%25s:%-5d EXCEPTION (%d) [inState.size() != outState.size() is false]: \"Input state %s size (%zu) not matching the output state size %s (%zu).\""
+ "%25s:%-5d EXCEPTION (%d) [inputDataType_ref.get_cf() == nullptr is false]: \"Missing dictionary DataType.\""
+ "%25s:%-5d EXCEPTION (%d) [inputDescDict_ref.get_cf() == nullptr is false]: \"Missing dictionary InputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [inputName_ref.get_cf() == nullptr is false]: \"Failed to retrieve InputName from (%s).\""
+ "%25s:%-5d EXCEPTION (%d) [inputName_ref.get_cf() == nullptr is false]: \"Failed to retrieve InputName.\""
+ "%25s:%-5d EXCEPTION (%d) [ioStates_ref.get_cf() == nullptr is false]: \"Failed to retrieve InputOutputStates.\""
+ "%25s:%-5d EXCEPTION (%d) [layer.mBiasVector.size() != weightsSizeOutput is false]: \"NeuralNetBNNS: Layer (%u), bias size (%lu) is not matching the weight output vector size (%lu).\""
+ "%25s:%-5d EXCEPTION (%d) [layer.mWeightsQuantized.size() != weightsNumberOfCoefficients is false]: \"NeuralNetBNNS: Layer (%u), number of weights (%lu) is not matching the required number of weights (%lu).\""
+ "%25s:%-5d EXCEPTION (%d) [layerType_ref.get_cf() == nullptr is false]: \"Failed to retrieve layer type (Type) from dictionary LayerDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [mDNNLayer[layerIdx].mFilter == nullptr is false]: \"NeuralNetBNNS: Layer (%u), filter not created.\""
+ "%25s:%-5d EXCEPTION (%d) [mGraph.data == nullptr is false]: \"unable to compile program %s\""
+ "%25s:%-5d EXCEPTION (%d) [mInputSize != featureVectorSize is false]: \"mInputSize of NeuralNet (%u) is not matching the feature vector size (%u).\""
+ "%25s:%-5d EXCEPTION (%d) [mOutputSize != mNumFFTBins is false]: \"NeuralNet output size (%u) is not matching the number of FFT bins (%u).\""
+ "%25s:%-5d EXCEPTION (%d) [modelNetExt == \".ir\" is false]: \"No MIL fallback option available\""
+ "%25s:%-5d EXCEPTION (%d) [modelNetPathBase_ref.get_cf() == nullptr is false]: \"Failed to retrieve ModelNetPathBase.\""
+ "%25s:%-5d EXCEPTION (%d) [modelNetPathRelative_ref.get_cf() == nullptr is false]: \"Failed to retrieve ModelNetPath.\""
+ "%25s:%-5d EXCEPTION (%d) [modelNetPath_ref.get_cf() == nullptr is false]: \"Failed to retrieve ModelNetPath.\""
+ "%25s:%-5d EXCEPTION (%d) [modelPlistInfo.streamingMode_int >= static_cast<UInt32>(StreamingMode::NumModes) is false]: \"StreamingMode (%u) is out of range, a value smaller than (%d) is expected.\""
+ "%25s:%-5d EXCEPTION (%d) [nnLayers[i].mWeightsQuantized.size() != weightsNumberOfCoefficients is false]: \"Number of weights in Data (%lu) does not match the required number of weights (%lu).\""
+ "%25s:%-5d EXCEPTION (%d) [numStates_ref.get_cf() == nullptr is false]: \"Failed to retrieve NumStates from InputOutputStates.\""
+ "%25s:%-5d EXCEPTION (%d) [outputDataType_ref.get_cf() == nullptr is false]: \"Failed to retrieve output data type (DataType) from dictionary OutputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [outputDescDict_ref.get_cf() == nullptr is false]: \"Missing dictionary OutputVectorDescriptor.\""
+ "%25s:%-5d EXCEPTION (%d) [outputName_ref.get_cf() == nullptr is false]: \"Failed to retrieve OutputName from (%s).\""
+ "%25s:%-5d EXCEPTION (%d) [outputName_ref.get_cf() == nullptr is false]: \"Failed to retrieve OutputName.\""
+ "%25s:%-5d EXCEPTION (%d) [pNeuralNetImpl == nullptr is false]: \"NeuralNet implementation not initialized.\""
+ "%25s:%-5d EXCEPTION (%d) [state_ref.get_cf() == nullptr is false]: \"Missing dictionary (%s).\""
+ "%25s:%-5d EXCEPTION (%d) [topLevelDict_ref.get_cf() == nullptr is false]: \"Missing dictionary: %s\""
+ "%25s:%-5d EXCEPTION (%d) [weightsDataType_ref.get_cf() == nullptr is false]: \"Missing DataType from dictionary Weights.\""
+ "%25s:%-5d EXCEPTION (%d) [weightsDict_ref.get_cf() == nullptr is false]: \"Missing dictionary Weights.\""
+ "/System/Library/Audio/Tunings/Generic/CinematicSeparation/Tunings/separate_and_remix_music.austrip"
+ "/System/Library/Audio/Tunings/Generic/CinematicSeparation/Tunings/separate_and_remix_music.dspg"
+ "/System/Library/Audio/Tunings/Generic/CinematicSeparation/Tunings/separate_and_remix_music.propstrip"
+ "01:07:51"
+ "01:08:05"
+ "01:08:25"
+ "Failed to create new music austrip plist"
+ "Failed to create new music propstrip plist"
+ "Failed to initialize new music AUDSPGraph"
+ "Failed to open new music austrip file"
+ "Failed to open new music propstrip file"
+ "Failed to reset new music graph"
+ "Failed to set Music dictionary"
+ "Failed to set Spatial dictionary"
+ "Failed to set Voice dictionary"
+ "Failed to set configure AUDSPGraph graph for new music"
+ "Failed to set new music AUDSPGraph graph text file path"
+ "Failed to set new music austrip on AUDSPGraph"
+ "Failed to set new music propstrip on AUDSPGraph"
+ "Failed to set parameters on new music graph"
+ "audiomix_music"
+ "dictionaryWithObjectsAndKeys:"
+ "parameter %d is missing"
- "%25s:%-5d EXCEPTION (%d): \"BlockSize not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"ECOutScale not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"FFT2Mel matrix not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve BlockSize.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve ECleeScale.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve ECoutScale.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve HangA01.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve HangA10.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve InputName from (%s).\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve InputName.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve InputOutputStates.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve InputScale.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve ModelNetPath.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve ModelNetPathBase.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve NumContextFrames.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve NumLayers.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve NumStates from InputOutputStates.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve OutputName from (%s).\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve OutputName.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve WaitFrames.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve activation function (Function) from dictionary Activation.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve forgetting factor Lambda_TC.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve layer type (Type) from dictionary LayerDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve output data type (DataType) from dictionary OutputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve sample rate.\""
- "%25s:%-5d EXCEPTION (%d): \"Failed to retrieve threshold.\""
- "%25s:%-5d EXCEPTION (%d): \"Input state %s size (%zu) not matching the output state size %s (%zu).\""
- "%25s:%-5d EXCEPTION (%d): \"KalmanObservationStd not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"KalmanProcessStd not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"LambdaPSD_TC not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"MCLPOutScale not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing DataType from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary (%s).\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary Activation.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary Bias from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary DataType from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary DataType.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary InputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary OutputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing dictionary: %s\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar Alpha from dictionary Activation.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar Beta from dictionary Activation.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataBias from dictionary Bias.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataBias from dictionary InputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataBias from dictionary OutputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataBias from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataScale from dictionary Bias.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataScale from dictionary InputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataScale from dictionary OutputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar DataScale from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar Size from dictionary InputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing scalar Size from dictionary OutputVectorDescriptor.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing vector Data from dictionary Bias.\""
- "%25s:%-5d EXCEPTION (%d): \"Missing vector Data from dictionary Weights.\""
- "%25s:%-5d EXCEPTION (%d): \"NeuralNet implementation not initialized.\""
- "%25s:%-5d EXCEPTION (%d): \"NeuralNet output size (%u) is not matching the number of FFT bins (%u).\""
- "%25s:%-5d EXCEPTION (%d): \"NeuralNetBNNS: Layer (%u), bias size (%lu) is not matching the weight output vector size (%lu).\""
- "%25s:%-5d EXCEPTION (%d): \"NeuralNetBNNS: Layer (%u), filter not created.\""
- "%25s:%-5d EXCEPTION (%d): \"NeuralNetBNNS: Layer (%u), number of weights (%lu) is not matching the required number of weights (%lu).\""
- "%25s:%-5d EXCEPTION (%d): \"No MIL fallback option available\""
- "%25s:%-5d EXCEPTION (%d): \"NumContextFrames not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"NumInputChannels not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"Number of weights in Data (%lu) does not match the required number of weights (%lu).\""
- "%25s:%-5d EXCEPTION (%d): \"SampleRate not loaded\""
- "%25s:%-5d EXCEPTION (%d): \"StreamingMode (%u) is out of range, a value smaller than (%d) is expected.\""
- "%25s:%-5d EXCEPTION (%d): \"Unable to load BNNS Context\""
- "%25s:%-5d EXCEPTION (%d): \"WaitFrames not loaded.\""
- "%25s:%-5d EXCEPTION (%d): \"mInputSize is wrong.\""
- "%25s:%-5d EXCEPTION (%d): \"mInputSize of NeuralNet (%u) is not matching the feature vector size (%u).\""
- "%25s:%-5d EXCEPTION (%d): \"unable to compile program %s\""
- "01:37:03"
- "01:37:13"
- "01:37:28"
```
