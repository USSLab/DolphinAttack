# What is DolphinAttack?
Speech recognition (SR) systems such as Siri or Google Now have become an increasingly popular human-computer interaction method, and have turned various systems into voice controllable systems (VCS). Prior work on attacking VCS shows that the hidden voice commands that are incomprehensible to people can control the systems. Hidden voice commands, though ‘hidden’, are nonetheless audible. In this work, we design a completely inaudible attack, DolphinAttack, that modulates voice commands on ultrasonic carriers (e.g., f > 20 kHz) to achieve inaudibility. By leveraging the nonlinearity of the microphone circuits, the modulated low frequency audio commands can be successfully demodulated, recovered, and more importantly interpreted by the speech recognition systems. We validate DolphinAttack on popular speech recognition systems, including Siri, Google Now, Samsung S Voice, Huawei, HiVoice, Cortana and Alexa. By injecting a sequence of inaudible voice commands, we show a few proof-of-concept attacks, which include activating Siri to initiate a FaceTime call on iPhone, activating Google Now to switch the phone to the airplane mode, and even manipulating the navigation system in an Audi automobile. We propose hardware and software defense solutions. We validate that it is feasible to detect DolphinAttack by classifying the audios using supported vector machine (SVM), and suggest to re-design voice controllable systems to be resilient to inaudible voice command attacks.

# Read our paper
* Guoming Zhang, Chen Yan, Xiaoyu Ji, Tianchen Zhang, Taimin Zhang, Wenyuan Xu. [**DolphinAttack: Inaudible Voice Commands**](https://dl.acm.org/citation.cfm?id=3134052). *Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security (CCS 2017)*, October 2017. [pdf](http://usslab.org/papers/CCS2017_DolphinAttack_CameraReady.pdf)

# In the news

# Contact
* Prof. Wenyuan Xu (<wyxu@zju.edu.cn>)
* Prof. Xiaoyu Ji (<xji@zju.edu.cn>)

# Powered by
## Ubiquitous System Security Laboratory (USSLab)
<a href="http:/usslab.org">![USSLab logo](https://github.com/USSLab/DolphinAttack/blob/master/images/usslab_logo.png)</a>
## Zhejiang University
<a href="http://www.zju.edu.cn/english/">![ZJU logo](https://github.com/USSLab/DolphinAttack/blob/master/images/zju_logo.png)</a>
