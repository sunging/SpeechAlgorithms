# 语音算法

各类语音算法的实现代码可通过 [DownGit](https://minhaskamal.github.io/DownGit/#/home) 单独下载。

# 目录

## 语音信号处理
| 标题 | 代码链接 |
| ---- | :------: |
| 生成含噪声/回声/混响/啸叫的语音样本 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechAugmentation) |
| 语音信号任意采样率重采样 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/Resample) |
| 音频数字水印的嵌入与提取 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/Watermarking) |
| 语音语速与音调调整 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/VoiceChange) |
| 分帧、加窗与离散傅里叶变换（DFT） | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/EnframeWindowFFT) |
| 基于互相关的音频对齐 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/AudioAlignment) |
| 基于音频指纹的音乐识别系统 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/AudioFingerPrinting) |
| 格尔泽尔算法（Goertzel Algorithm） | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/Goertzel) |
| 雨声生成 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/DesignSound) |

## 语音前端算法
| 标题 | 代码链接 |
| ---- | :------: |
| 基于谱减法的语音增强 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpectralSubtraction) |
| 基于时频掩码的语音分离 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechSperation) |
| 自适应滤波回声消除原理与实现 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/AcousticEchoCancellation) |
| 利用AMR编解码器生成语音活动检测（VAD）标签 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/VoiceActivityDetection/VADCoder) |
| WebRTC VAD（语音活动检测）原理与实现 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/WebRTC_VAD) |
| 基于卡尔曼滤波的声学回声消除算法 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/AcousticEchoCancellation) |
| WebRTC ANR（自动噪声抑制）原理与实现 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/WebRTC_ANR) |
| WebRTC AGC（自动增益控制）原理与实现 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/WebRTC_AGC) |
| WebRTC AEC（声学回声消除）原理与实现 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/WebRTC_AEC) |
| 基于深度神经网络（DNN）的单通道语音增强 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechEnhancement) |
| 语音增强的数据增强方法 | [代码](https://github.com/Ryuk17/noise-xorcist/tree/main/datasets) |
| 啸叫样本生成方法 | [代码](https://github.com/Ryuk17/noise-xorcist/tree/main/datasets) |
| 瞬态噪声抑制 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/TransientInterferenceSuppression) |
| 基于长短期记忆网络（LSTM）的端点检测 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/VoiceActivityDetection) |

## 麦克风阵列算法
| 标题 | 代码链接 |
| ---- | :------: |
| CGMM-MVDR波束形成算法 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/Beamforming/CGMM-MVDR) |
| 基于到达时间差（TDOA）的声源定位 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SoundSourceLocalization) |
| 基于SRP-PHAT的声源定位 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SoundSourceLocalization) |

## 语音模式识别
| 标题 | 代码链接 |
| ---- | :------: |
| 基于卷积神经网络（CNN）的语音指令识别 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/CommandRecognition) |
| 说话人性别识别 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/GenderClassify) |
| 基于XGBoost的环境声音分类 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/EnvironmentSoundClassification) |
| CTC前缀束搜索算法 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/CtcSearcher) |

## 语音编解码
| 标题 | 代码链接 |
| ---- | :------: |
| 人工智能语音编解码器 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechCodec) |
| G.711语音编解码器 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechCodec/G711) |

## 语音评估指标
| 标题 | 代码链接 |
| ---- | :------: |
| 语音质量评估指标 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechQualityMeasures) |
| 语音可懂度评估指标 | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/SpeechIntelligibilityMetrics) |
| 语音相似度评估（动态时间规整） | [代码](https://github.com/Ryuk17/SpeechAlgorithms/tree/master/DynamicTimeWarping) |