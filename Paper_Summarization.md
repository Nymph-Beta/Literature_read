### D-DAE: Defense-Penetrating Model Extraction Attacks

2023 IEEE Symposium on Security and Privacy (SP).

Yanjiao Chen, Rui Guan, Xueluan Gong, Jianshuo Dong, Meng Xue,

- 类别：人工智能-机器学习安全-模型提取攻击-防御穿透型攻击方法研究
- 本文提出了D-DAE框架，旨在克服基于干扰的防御策略，使得攻击者能够有效地进行模型提取攻击。通过设计干扰检测和干扰恢复两个模块，D-DAE能够识别并逆转防御者施加的干扰，从而获得更准确的模型输出信息。
- 主要贡献：
  1.提出了一种新颖的防御穿透型模型提取攻击框架，首次尝试开发能够破解干扰式防御的模型提取攻击方法；
  2.设计了基于元学习的干扰检测算法，能够在没有访问受害模型原始训练数据集的情况下，识别出防御者采用的防御机制；
  3.开发了基于生成模型的干扰恢复机制，可从干扰的查询结果中恢复出干净的查询结果，增强了替代模型的准确性。
- 主要问题：
  1.实验验证主要集中在特定的数据集和防御策略上，对于更广泛或未知的防御策略的适应性有待进一步验证；
  2.框架的实用性和效率在实际大规模和动态的机器学习服务中还需进一步考察和优化。


### SoK: Cryptographic Neural-Network Computation

2023 IEEE Symposium on Security and Privacy (SP).

Lucien K. L. Ng, Sherman S. M. Chow,

- 类别：密码学-隐私保护计算-隐私保护神经网络-基于密码学的神经网络计算研究
- 本文系统性回顾了2016至2022年间基于密码学技术实现隐私保护的神经网络研究，覆盖了使用同态加密、安全多方计算以及非串通服务器的53篇文献。通过深入分析这些研究所采用的密码学技术及其与机器学习之间的相互作用，揭示了该领域内的重要进展和研究机会。
- 主要贡献：
  1.首次系统化地总结了基于密码学的隐私保护神经网络研究，包括同态加密、安全多方计算和非串通服务器等技术的应用；
  2.详细探讨了密码学技术在支持隐私保护神经网络计算中的作用，以及它们与机器学习技术结合时面临的挑战和解决策略；
  3.通过谱系图和广域网下最新技术水平的重新评估，突出了值得关注的发展和研究空白，为该领域的未来研究指明了方向。
- 主要问题：
  1.如何有效克服密码学技术在处理非线性层和保证模型训练效率方面的限制；
  2.在保障数据隐私的同时，特别是在广域网环境下，如何实现对深层神经网络的高效计算。


### BARS: Local Robustness Certification for Deep Learning based Traffic Analysis Systems,

Network and Distributed System Security (NDSS) Symposium 2023.

Kai Wang, Zhiliang Wang, Dongqi Han, Wenqi Chen, Jiahai Yang, Xingang Shi, Xia Yin

- 类别：网络安全-深度学习应用-流量分析系统的局部鲁棒性证明
- 本文提出了BARS框架，解决了基于深度学习的流量分析系统在面对逆向攻击时的鲁棒性问题。通过引入边界适应性随机平滑（boundary-adaptive randomized smoothing）和分布变换器（Distribution Transformer），BARS能够生成优化的平滑噪声，为流量分析系统提供更紧密的鲁棒性保证。
- 主要贡献：
  1.设计了分布变换器和特殊分布函数，通过基于梯度的搜索算法优化噪声形状和规模，为流量特征的高度异质性提供解决方案；
  2.在三个实际的深度学习基流量分析系统中实施和评估BARS，证明了其在紧密鲁棒性保证方面的优越性；
  3.通过五个应用案例展示了BARS的实际应用潜力，包括定量评估鲁棒性、降低误报率、防御逃避攻击等。
- 主要问题：
  1.特定的分布函数选择和参数优化对实现BARS的成功至关重要；
  2.虽然BARS在提供紧密鲁棒性保证方面表现出色，但其计算复杂度和实时性能仍需进一步研究和优化。


### BEAGLE: Forensics of Deep Learning Backdoor Attack for Better Defense,

Network and Distributed System Security (NDSS) Symposium 2023.

Siyuan Cheng, Guanhong Tao, Yingqi Liu, Shengwei An, Xiangzhe Xu, Shiwei Feng, Guangyu Shen, Kaiyuan Zhang, Qiuling Xu, Shiqing Ma, Xiangyu Zhang

- 类别：人工智能安全-深度学习-后门攻击取证与防御
- 本文提出了BEAGLE技术，专门用于深度学习模型后门攻击的取证分析，目的是为了更好地理解和防御此类攻击。通过分析攻击样本，如带有后门触发器的输入，BEAGLE能够将它们分解为干净的输入和对应的触发器，从而揭示攻击的本质。
- 主要贡献：
  1.引入了一种新颖的取证技术BEAGLE，它通过分布变换器和特定分布函数来优化生成的平滑噪声，针对深度学习模型后门攻击提供了一种全新的解决方案；
  2.在多个预训练模型和流行攻击类型上评估了BEAGLE，证明了其在提供紧密鲁棒性保证方面相较于现有方法的优势；
  3.通过五个应用案例展示了BEAGLE的实际应用价值，包括攻击分类、总结和专门扫描器的合成，有助于更有效地识别和防御后门攻击。
- 主要问题：
  1.对攻击样本的分析和取证过程中需要高精度的分布变换器和分布函数选择；
  2.虽然BEAGLE在后门攻击取证方面展现出显著优势，但其对大规模或复杂模型的适应性和效率仍需进一步探索和优化。


### HyperVision: Detecting Unknown Encrypted Malicious Traffic in Real Time via Flow Interaction Graph Analysis

Network and Distributed System Security (NDSS) Symposium 2023.

Chuanpu Fu, Qi Li, Ke Xu

- 类别：网络安全-加密流量分析-恶意流量实时检测
- 本文提出了HyperVision系统，针对实时检测未知加密恶意流量的挑战，通过流交互图分析来实现。在广泛的互联网流量加密背景下，HyperVision能够在不依赖已知攻击模式的先验知识的情况下，有效检测出未知模式的加密恶意流量。
- 主要贡献：
  1.开发了基于非监督机器学习的实时恶意流量检测系统HyperVision，特别针对未知加密恶意流量的检测，提供了一种新的解决方案；
  2.通过构建流交互图和分析图结构特征来捕捉流量模式，实现了对各种加密攻击流量的检测，无需任何已知攻击的标签化数据集；
  3.在92个数据集上验证了HyperVision的性能，其中包括48种加密恶意流量攻击，显示了其在AUC和F1分数方面的显著优势，能够检测超过50%的能够规避其他所有方法的攻击。
- 主要问题：
  1.流交互图的构建和分析对于系统性能至关重要，需要精确的图结构特征识别和高效的非监督学习算法；
  2.虽然HyperVision在检测未知加密恶意流量方面展现出优势，但如何进一步提高检测速度和减少误报率仍是未来研究的关键。


### PPA: Preference Profiling Attack Against Federated Learning

Network and Distributed System Security (NDSS) Symposium 2023.

- 类别：人工智能安全-联邦学习-隐私推断攻击
- 本文提出了偏好剖析攻击（PPA），一种新型的隐私推断攻击针对联邦学习中的数据隐私泄露。PPA通过分析本地用户模型的梯度变化，准确剖析用户的私有偏好，如识别用户最喜欢的商品或最常表达的面部表情。
- 主要贡献：
  1.提出PPA攻击框架，首次将梯度变化用于推断联邦学习中用户的私有偏好，有效识别未知模式的加密恶意流量；
  2.在四个数据集（MNIST、CIFAR10、RAF-DB 和 Products-10K）上广泛验证PPA的有效性，特别是在现实世界商业场景的应用案例中展示了其准确性；
  3.通过对PPA的实验评估，展示了其在面对现有非加密防御机制时的效果，以及在现实世界场景下的可扩展性和实用性。
- 主要问题：
  1.PPA的成功依赖于准确分析本地用户模型的梯度变化，需要复杂的算法来实现这一点；
  2.尽管PPA在隐私推断攻击方面表现出色，但如何进一步提高其抵抗现有防御机制的能力，降低误报率，仍需进一步研究和优化。


### Squint Hard Enough: Attacking Perceptual Hashing with Adversarial Machine Learning

USENIX Security '23

Jonathan Prokos, Neil Fendley, Matthew Green, Roei Schuster, Eran Tromer, Tushar M. Jois, and Yinzhi Cao

- 类别：网络安全-对抗机器学习-感知哈希攻击
- 本文探讨了利用对抗性机器学习技术攻击感知哈希函数的可能性。感知哈希被广泛应用于在线通信系统中，用于检测和过滤非法文件，如Microsoft的PhotoDNA或Facebook的PDQ。这些系统通过比较图像文件的摘要与已知非法内容的数据库，实现自动检测。文中特别关注将这些基于哈希的匹配系统集成到端到端加密（E2EE）系统中的提议，并从对抗角度评估这些感知哈希函数。
- 主要贡献：
  1.开发了针对感知哈希算法的威胁模型，特别是针对PhotoDNA和PDQ这两种广泛部署的算法；
  2.展示了如何有效生成针对性的第二原像攻击，即创建源图像的变体，使其与目标摘要匹配；
  3.探讨了生成促进检测规避的图像的方法，并基于流交互图分析，展示了现有感知哈希函数在对抗环境下的脆弱性。
- 主要问题：
  1.攻击的有效性依赖于对感知哈希算法的深入理解和精确的对抗样本生成；
  2.尽管本文成功展示了攻击方法，但对于如何提高攻击的隐蔽性和减少误报率仍需要进一步研究。


### UnGANable: Defending Against GAN-based Face Manipulation,

USENIX Security '23

Zheng Li, Ning Yu, Ahmed Salem, Michael Backes, Mario Fritz, Yang Zhang

- 类别：人工智能安全-图像处理-GAN面部操纵防御
- 本文提出了UnGANable系统，旨在防御基于生成对抗网络（GAN）的面部操纵攻击。通过在图像空间搜索伪装图像，UnGANable破坏GAN逆向过程，防止恶意操纵个人面部图像。
- 主要贡献：
  1.首次提出面向基于GAN逆向的面部操纵的防御系统UnGANable，通过搜索伪装图像破坏GAN逆向过程；
  2.考虑了基于优化的逆向和混合逆向两种逆向技术，根据防御者的知识背景，设计了五种不同的防御策略；
  3.在四个流行的GAN模型上进行广泛实验，验证了UnGANable的有效性和实用性，并超过多个基线方法。
- 主要问题：
  1.伪装图像的搜索与选择对于防御成功至关重要，需要精确的图像分析和优化算法；
  2.虽然UnGANable在防御GAN面部操纵方面取得了显著成果，但对抗自适应攻击策略的能力及其在不同场景下的通用性仍需进一步研究。


### V-Cloak: Intelligibility-, Naturalness-, & Timbre-Preserving Real-Time Voice Anonymization,

32nd USENIX Security Symposium, August 9–11, 2023, Anaheim, CA, USA.

Jiangyi Deng, Fei Teng, Yanjiao Chen, Zhejiang University; Xiaofu Chen, Zhaohui Wang, Wuhan University; Wenyuan Xu, Zhejiang University

- 类别：人工智能安全-语音匿名化-实时处理
- 本文提出了V-Cloak，一种实时保持语音可理解性、自然性和音质的同时，实现语音匿名化的系统。通过对原始音频进行一次性生成模型调整，V-Cloak有效对抗通过语音数据进行身份推断的恶意攻击者，是现有语音匿名化技术（如信号处理、语音转换/合成）的重要进步。
- 主要贡献：
  1.提出V-Cloak系统，采用一次性生成模型对原始音频进行匿名化处理，同时保留音频的可理解性、自然性和音质。
  2.通过精心设计的损失函数训练匿名器，包含匿名损失、可理解性损失和基于心理声学的自然性损失，实现有针对性和无针对性匿名化，达到不可识别和不可链接的匿名目标。
  3.在LibriSpeech（英语）、AISHELL（中文）、CommonVoice（法语）和CommonVoice（意大利语）四个数据集上的广泛实验，以及五个自动说话人验证（ASV）系统和十一个自动语音识别（ASR）系统的验证，证明V-Cloak在匿名性能上优于五个基线系统，并展示了其跨语言可理解性和对各种去噪技术和自适应攻击的鲁棒性。
- 主要问题：
  1.如何在实现真实时间语音匿名化的同时，防御自适应攻击？
  2.如何在匿名化音频时保持目标和主观的可理解性？
  3.如何在保留匿名化音频的自然性和音质时，对抗潜在的隐私泄露风险？


### xNIDS: Explaining Deep Learning-based Network Intrusion Detection Systems for Active Intrusion Responses,

文章会议：32nd USENIX Security Symposium, August 9–11, 2023, Anaheim, CA, USA.

作者：Jiangyi Deng, Fei Teng, Yanjiao Chen, Xiaofu Chen, Zhaohui Wang, Wenyuan Xu

- 类别：网络安全-网络入侵检测-深度学习解释性
- 本文提出了xNIDS框架，旨在通过解释基于深度学习的网络入侵检测系统（DL-NIDS）的检测结果，生成可操作的防御规则以实施主动入侵响应。xNIDS通过一个解释模型，近似和采样历史输入以及捕获结构化数据的特征依赖性，提供高保真度的解释，使网络操作者能够理解DL-NIDS的决策过程，从而更有效地排除检测错误并提高系统的入侵响应能力。
- 主要贡献：
  1.开发了xNIDS框架，利用解释模型提高DL-NIDS的可解释性，并基于这些解释生成可操作的防御规则；
  2.通过处理历史输入和复杂特征依赖性，xNIDS能够为DL-NIDS的检测结果提供高保真度的解释；
  3.在四个最先进的DL-NIDS上进行实验评估，证明了xNIDS在生成解释性能上超越以往方法，并有效地利用这些解释生成针对性的防御规则。
- 主要问题：
  1.如何在保持高保真度解释的同时，确保生成的防御规则既实用又有效？
  2.面对复杂的网络流量和攻击模式，xNIDS如何适应不同的网络环境和防御需求？
