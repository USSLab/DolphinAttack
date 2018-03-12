# What is DolphinAttack?
Speech recognition (SR) systems such as Siri or Google Now have become an increasingly popular human-computer interaction method, and have turned various systems into voice controllable systems (VCS). Prior work on attacking VCS shows that the hidden voice commands that are incomprehensible to people can control the systems. Hidden voice commands, though ‘hidden’, are nonetheless audible. In this work, we design a completely inaudible attack, DolphinAttack, that modulates voice commands on ultrasonic carriers (e.g., f > 20 kHz) to achieve inaudibility. By leveraging the nonlinearity of the microphone circuits, the modulated low frequency audio commands can be successfully demodulated, recovered, and more importantly interpreted by the speech recognition systems. We validate DolphinAttack on popular speech recognition systems, including Siri, Google Now, Samsung S Voice, Huawei, HiVoice, Cortana and Alexa. By injecting a sequence of inaudible voice commands, we show a few proof-of-concept attacks, which include activating Siri to initiate a FaceTime call on iPhone, activating Google Now to switch the phone to the airplane mode, and even manipulating the navigation system in an Audi automobile. We propose hardware and software defense solutions. We validate that it is feasible to detect DolphinAttack by classifying the audios using supported vector machine (SVM), and suggest to re-design voice controllable systems to be resilient to inaudible voice command attacks.

# How does DolphinAttack work?

# Tested Devices
The following devices and voice assistants have been tested in our experiments. Experimental parameters are provided in our paper.

Manufacturer | Model | OS/Version | Voice Assistant | Activation<sup>1</sup> | Recognition<sup>2</sup>
------------ | ------| -----------| --------------  | ---------------------- | ----------
Apple        | iPhone 4s          | iOS 9.3.5       | Siri            | Y           | Y
Apple        | iPhone 5s          | iOS 10.0.2      | Siri            | Y           | Y
Apple        | iPhone SE          | iOS 10.3.1, 10.3.2 | Siri         | Y           | Y
Apple        | iPhone 6s          | iOS 10.2.1      | Siri            | Y           | Y
Apple        | iPhone 6 Plus      | iOS 10.3.1      | Siri            | Y           | N
Apple        | iPhone 7 Plus      | iOS 10.3.1      | Siri            | Y           | Y
Apple        | watch              | watchOS 3.1     | Siri            | Y           | Y
Apple        | iPad mini 4        | iOS 10.2.1      | Siri            | Y           | Y
Apple        | MacBook            | macOS Sierra    | Siri            | N/A           | Y
Google       | Nexus 5X           | Android 7.1.1   | Google Now      | Y           | Y
Google       | Nexus 7            | Android 6.0.1   | Google Now      | Y           | Y
Samsung      | Galaxy S6 edge     | Android 6.0.1   | S Voice         | Y           | Y
Huawei       | Honor 7            | Android 6.0     | HiVoice         | Y           | Y
Lenovo       | ThinkPad T440p     | Windows 10      | Cortana         | Y           | Y
Amazon       | Echo               | 5589            | Alexa           | Y           | Y
Audi         | Q3                 | N/A             | N/A             | N/A           | Y

<sup>1</sup> The voice assistant/device can be activated by DolphinAttack voice commands.

<sup>2</sup> The voice assistant/device can recognize the DolphinAttack voice commands after being activated.

# Read our paper
* Guoming Zhang, Chen Yan, Xiaoyu Ji, Tianchen Zhang, Taimin Zhang, Wenyuan Xu. [**DolphinAttack: Inaudible Voice Commands**](https://dl.acm.org/citation.cfm?id=3134052). *Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security (CCS 2017)*, October 2017. [[pdf]](http://usslab.org/papers/CCS2017_DolphinAttack_CameraReady.pdf) [(**Best Paper Award**)](https://www.sigsac.org/ccs/CCS2017/awards.html)

## Related papers
* Vaidya, Tavish, et al. ["Cocaine noodles: exploiting the gap between human and machine speech recognition."](https://www.usenix.org/node/191969) WOOT 15 (2015): 10-11.

* Carlini, Nicholas, et al. ["Hidden Voice Commands."](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/carlini) USENIX Security Symposium. 2016.

* Song, Liwei, and Prateek Mittal. ["Inaudible voice commands."](https://arxiv.org/abs/1708.07238) arXiv preprint arXiv:1708.07238 (2017).

* Roy, Nirupam, et al. ["Inaudible Voice Commands: The Long-Range Attack and Defense."](https://www.usenix.org/conference/nsdi18/presentation/roy) Symposium on Networked Systems Design and Implementation (NSDI 18). 2018.

# In the news
* **MIT Technology Review** [Secret Ultrasonic Commands Can Control Your Smartphone, Say Researchers](https://www.technologyreview.com/s/608825/secret-ultrasonic-commands-can-control-your-smartphone-say-researchers/)
* **WIRED** [Ultrasonic Voice Commands Can Hijack Siri and Amazon Echos](https://www.wired.com/story/security-roundup-germany-election-software-is-hackable)
* **BBC** ['Dolphin' attacks fool Amazon, Google voice assistants](http://www.bbc.com/news/technology-41188557) 
* **新华社** [苹果、三星都中招——“海豚音攻击”究竟是何方神器？](http://www.xinhuanet.com/fortune/2017-10/31/c_1121881819.htm)
* **浙江大学** [对不起，你的手机被“无声”操控了](http://www.zju.edu.cn/2017/0911/c578a637706/page.htm)

# Contact
* Prof. Wenyuan Xu (<wyxu@zju.edu.cn>)
* Prof. Xiaoyu Ji (<xji@zju.edu.cn>)

# Powered by
## Ubiquitous System Security Laboratory (USSLab)
<a href="http:/usslab.org">![USSLab logo](https://github.com/USSLab/DolphinAttack/blob/master/images/usslab_logo.png)</a>
## Zhejiang University 
<a href="http://www.zju.edu.cn/english/">![ZJU logo](https://github.com/USSLab/DolphinAttack/blob/master/images/zju_logo.png)</a>
