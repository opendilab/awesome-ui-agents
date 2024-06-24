# Awesome UI Agent

This is a collection of research papers for **UI Agent**.
And the repository will be continuously updated to track the frontier of UI Agent or related fields.

Welcome to follow and star!

## Table of Contents

- [Awesome UI Agent](#awesome-ui-agent)
  - [Table of Contents](#table-of-contents)
  - [Overview of UI Agent](#overview-of-ui-agent)
  - [Papers](#papers)
    - [Models](#models)
    - [Tools](#tools)
    - [Datasets](#datasets)
  - [Related Repositories](#related-repositories)
  - [Contributing](#contributing)
  - [License](#license)

## Overview of UI Agent

UI Agent aims to build a generalist agent that can interact with various user interfaces (UIs) in different environments, such as mobile apps, web pages, and PC applications. The agent can understand the UIs through vision-language models and interact with them to complete tasks. The agent can be applied to various scenarios, such as mobile device operation, web browsing, and game playing. The agent can be trained in a simulated environment or with real-world data. The agent can be evaluated in terms of task completion rate, efficiency, and generalization ability.

The research on UI Agent is still in its early stage, and there are many challenges to be addressed, such as the scalability of the agent, the robustness of the agent, and the interpretability of the agent. The research on UI Agent is interdisciplinary, involving computer vision, natural language processing, reinforcement learning, human-computer interaction, and software engineering. The research on UI Agent has the potential to revolutionize the way we interact with computers and improve the efficiency and usability of computer systems.

## Papers

```
format:
- [title](paper link) [links]
    - author1, author2, and author3...
    - year
    - publisher
    - key 
    - code 
    - experiment environment
```

### Models

- [ScreenAI: A Vision-Language Model for UI and Infographics Understanding](https://arxiv.org/abs/2402.04615)
    - Gilles Baechler and Srinivas Sunkara and Maria Wang and Fedir Zubach and Hassan Mansoor and Vincent Etter and Victor Cărbune and Jason Lin and Jindong Chen and Abhanshu Sharma
    - Key: Vision-Language Model, Mobile, Infographics
    - 2024

- [ScreenAgent: A Vision Language Model-driven Computer Control Agent](https://arxiv.org/abs/2402.07945)
    - Runliang Niu and Jindong Li and Shiqi Wang and Yali Fu and Xiyu Hu and Xueyuan Leng and He Kong and Yi Chang and Qi Wang
    - Key: Vision Language Model, PC
    - 2024
    - [code](https://github.com/niuzaisheng/ScreenAgent)

- [Android in the Zoo: Chain-of-Action-Thought for GUI Agents](https://arxiv.org/abs/2403.02713)
    - Jiwen Zhang and Jihao Wu and Yihua Teng and Minghui Liao and Nuo Xu and Xiao Xiao and Zhongyu Wei and Duyu Tang
    - Key: Vision-Language Model, Android, Chain-of-Action-Thought
    - 2024
    - [code](https://github.com/IMNearth/CoAT)

- [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/html/2312.08914v1)
    - Wenyi Hong and Weihan Wang and Qingsong Lv and Jiazheng Xu and Wenmeng Yu and Junhui Ji and Yan Wang and Zihan Wang and Yuxuan Zhang and Juanzi Li and Bin Xu and Yuxiao Dong and Ming Ding and Jie Tang
    - Key: Vision-Language Model, PC, Android, screenshots
    - 2023
    - [code](https://github.com/THUDM/CogVLM)

- [AppAgent: Multimodal Agents as Smartphone Users](https://arxiv.org/abs/2312.13771)
    - Chi Zhang and Zhao Yang and Jiaxuan Liu and Yucheng Han and Xin Chen and Zebiao Huang and Bin Fu and Gang Yu
    - Key: Vision-Language Model, Android
    - 2023
    - [code](https://github.com/mnotgod96/AppAgent)

- [Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration](https://arxiv.org/abs/2406.01014)
    - Junyang Wang and Haiyang Xu and Haitao Jia and Xi Zhang and Ming Yan and Weizhou Shen and Ji Zhang and Fei Huang and Jitao Sang
    - Key: Vision-Language Model, Android
    - 2024
    - [code](https://github.com/X-PLUG/MobileAgent)

- [Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception](https://arxiv.org/abs/2401.16158)
    - Junyang Wang and Haiyang Xu and Jiabo Ye and Ming Yan and Weizhou Shen and Ji Zhang and Fei Huang and Jitao Sang
    - Key: Vision-Language Model, Android
    - 2024
    - [code](https://github.com/X-PLUG/MobileAgent)

- [WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models](https://arxiv.org/abs/2401.13919)
    - Hongliang He and Wenlin Yao and Kaixin Ma and Wenhao Yu and Yong Dai and Hongming Zhang and Zhenzhong Lan and Dong Yu
    - Key: Vision-Language Model, Web
    - 2024
    - [code](https://github.com/MinorJerry/WebVoyager)

- [OS-Copilot: Towards Generalist Computer Agents with Self-Improvement](https://arxiv.org/abs/2402.07456)
    - Zhiyong Wu and Chengcheng Han and Zichen Ding and Zhenmin Weng and Zhoumianze Liu and Shunyu Yao and Tao Yu and Lingpeng Kong
    - Key: Vision-Language Model, PC
    - 2024
    - [code](https://github.com/OS-Copilot/OS-Copilot)

- [UFO: A UI-Focused Agent for Windows OS Interaction](https://arxiv.org/abs/2402.07939)
    - Chaoyun Zhang and Liqun Li and Shilin He and Xu Zhang and Bo Qiao and Si Qin and Minghua Ma and Yu Kang and Qingwei Lin and Saravan Rajmohan and Dongmei Zhang and Qi Zhang
    - Key: Vision-Language Model, PC, Windows OS
    - 2024
    - [code](https://github.com/microsoft/UFO)

- [Octopus v2: On-device language model for super agent](https://arxiv.org/abs/2404.01744)
    - Wei Chen and Zhiyuan Li
    - Key: Vision-Language Model, Android, IOS
    - 2024

- [Octopus: Embodied Vision-Language Programmer from Environmental Feedback](https://arxiv.org/abs/2310.08588)
    - Jingkang Yang and Yuhao Dong and Shuai Liu and Bo Li and Ziyue Wang and Chencheng Jiang and Haoran Tan and Jiamu Kang and Yuanhan Zhang and Kaiyang Zhou and Ziwei Liu
    - Key: Vision-Language Model, Android, IOS
    - 2023
    - [code](https://github.com/dongyh20/Octopus)

- [Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study](https://arxiv.org/html/2403.03186v1)
    - Weihao Tan and Ziluo Ding and Wentao Zhang and Boyu Li and Bohan Zhou and Junpeng Yue and Haochong Xia and Jiechuan Jiang and Longtao Zheng and Xinrun Xu and Yifei Bi and Pengjie Gu and Xinrun Wang and Börje F. Karlsson and Bo An and Zongqing Lu
    - Key: Vision-Language Model, PC, Game
    - 2024
    - [code](https://github.com/BAAI-Agents/Cradle)

### Tools

- [AndroidEnv: A Reinforcement Learning Platform for Android](https://arxiv.org/abs/2105.13231)
    - Daniel Toyama and Philippe Hamel and Anita Gergely and Gheorghe Comanici and Amelia Glaese and Zafarali Ahmed and Tyler Jackson and Shibl Mourad and Doina Precup
    - Key: Android, Reinforcement Learning, Simulator
    - 2021
    - [code](https://github.com/google-deepmind/android_env)

- [LlamaTouch: A Faithful and Scalable Testbed for Mobile UI Automation Task Evaluation](https://arxiv.org/abs/2404.16054)
    - Li Zhang and Shihe Wang and Xianqing Jia and Zhihan Zheng and Yunhe Yan and Longxi Gao and Yuanchun Li and Mengwei Xu
    - Key: Mobile UI, Simulator
    - 2024
    - [code](https://github.com/llamatouch/llamatouch)

### Datasets

- [Rico: A Mobile App Dataset for Building Data-Driven Design Applications](https://dl.acm.org/doi/10.1145/3126594.3126651)
    - Deka, Biplab and Huang, Zifeng and Franzen, Chad and Hibschman, Joshua and Afergan, Daniel and Li, Yang and Nichols, Jeffrey and Kumar, Ranjitha
    - Key: mobile app, datasets
    - 2017

- [Android in the Wild: A Large-Scale Dataset for Android Device Control](https://arxiv.org/abs/2307.10088)
    - Christopher Rawles and Alice Li and Daniel Rodriguez and Oriana Riva and Timothy Lillicrap
    - Key: Android, datasets
    - 2023

- [Mind2Web: Towards a Generalist Agent for the Web](https://arxiv.org/abs/2306.06070)
    - Xiang Deng and Yu Gu and Boyuan Zheng and Shijie Chen and Samuel Stevens and Boshi Wang and Huan Sun and Yu Su
    - Key: Web, datasets
    - 2023
    - [code](https://github.com/OSU-NLP-Group/Mind2Web)

- [Android in the Zoo: Chain-of-Action-Thought for GUI Agents](https://arxiv.org/abs/2403.02713)
    - Jiwen Zhang and Jihao Wu and Yihua Teng and Minghui Liao and Nuo Xu and Xiao Xiao and Zhongyu Wei and Duyu Tang
    - Key: Vision-Language Model, Android, Chain-of-Action-Thought
    - 2024
    - [code](https://github.com/IMNearth/CoAT)

## Related Repositories

- [awesome-llm-powered-agent](https://github.com/hyp1231/awesome-llm-powered-agent)
- [Awesome-LLM-based-Web-Agent-and-Tools](https://github.com/albzni/Awesome-LLM-based-Web-Agent-and-Tools)


## Contributing

Our purpose is to make this repo even better. If you are interested in contributing, please refer to [HERE](CONTRIBUTING.md) for instructions in contribution.

## License

This repository is released under the Apache 2.0 license.


