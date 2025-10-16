# Video-Streaming-Survey

# Awesome Next-Gen Video Streaming :rocket:


![banner](docs/images/video_streaming_banner.png)
This is a repository for collecting resources about **Video Streaming** and its **next-generation evolution**.  
Unlike traditional surveys that only focus on codecs, ABR, and QoE, this repo aims to **bridge the gap** between  
classic streaming techniques and **modern AI/ML-based methods**, especially the integration with  
**Multimodal Large Models (VLMs/VLAs)** and **intelligent production devices**.


## :fire: Table of Contents
- [Introduction](#introduction)
- [Traditional Methods](#traditional-methods)
- [Machine Learning-based Methods](#machine-learning-based-methods)
- [Multimodal LLMs for Streaming](#Multimodal-LLMs-for-Streaming)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Challenges and Future Directions](#challenges-and-future-directions)

## :scroll: Paper List
### Survey of Streaming Video
 1. `['ACM'24]` An End-to-End Pipeline Perspective on Video Streaming in Best-Effort Networks: A Survey and Tutorial [[PDF](https://arxiv.org/pdf/2403.05192)]
 2. `['COMSNETS'24]` Quality of Experience in Video Streaming: Status Quo, Pitfalls, and Guidelines [[PDF](https://ieeexplore-ieee-org.sheffield.idm.oclc.org/stamp/stamp.jsp?tp=&arnumber=10427330)]
 3. `['arXiv'23]` UAV Immersive Video Streaming: A Comprehensive Survey, Benchmarking, and Open Challenges [[PDF](https://arxiv.org/pdf/2311.00082)]
 

### Traditional Methods
 1. `['arXiv'13]` Probe and Adapt: Rate Adaptation for HTTP Video Streaming At Scale [[PDF](https://arxiv.org/pdf/1305.0510)]
 2. `['ACM'16]` ABuffer-Based Approach to Rate Adaptation:Evidence from a Large Video Streaming Service [[PDF](https://dl.acm.org/doi/pdf/10.1145/2619239.2626296)] 

### Machine Learning-based Methods
 1. `['ACM'23]` Empowerment of Atypical Viewers via Low-Effort Personalized Modeling of Video Streaming Quality [[PDF](https://dl-acm-org.sheffield.idm.oclc.org/doi/pdf/10.1145%2F3629139)]
 2. `['IEEE Trans. Multimedia'23]` RAV: Learning-Based Adaptive Streaming to Coordinate the Audio and Video Bitrate Selections [[PDF](https://ieeexplore-ieee-org.sheffield.idm.oclc.org/stamp/stamp.jsp?tp=&arnumber=9854189&tag=1)]
 3. `['IEEE Trans. Netw. Serv. Manage.'24]` MEC-Based Super-Resolution Enhanced Adaptive Video Streaming Optimization for Mobile Networks With Satellite Backhaul [[PDF](https://ieeexplore-ieee-org.sheffield.idm.oclc.org/stamp/stamp.jsp?tp=&arnumber=10473143)]
 4. `['ACM MMSys.'24]` OASIS: Collaborative Neural-Enhanced Mobile Video Streaming [[PDF](https://dl-acm-org.sheffield.idm.oclc.org/doi/pdf/10.1145/3625468.3647610)]
 5. `['IEEE IWCMC.'24]` EASR: Enabling Neural-Enhanced Video Streaming on Mobile Devices with Edge Assistance [[PDF](https://ieeexplore-ieee-org.sheffield.idm.oclc.org/stamp/stamp.jsp?tp=&arnumber=10592463&tag=1)]
 6. `['IEEE Transactions on Mobile Computing.'25]` REM: Enabling Real-Time Neural-Enhanced Video Streaming on Mobile Devices Using Macroblock-Aware Lookup Table [[PDF](https://ieeexplore-ieee-org.sheffield.idm.oclc.org/stamp/stamp.jsp?tp=&arnumber=10750425)]
 7. `['IEEE Conference on Computer Communications.'24]` Dancing with Shackles, Meet the Challenge of Industrial Adaptive Streaming via Offline Reinforcement Learning [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10621126)]
 8. `['arXiv.'22]` ECAS-ML: Edge Computing Assisted Adaptation Scheme with Machine Learning for HTTP Adaptive Streaming [[PDF](https://arxiv.org/pdf/2201.04488)]
 9. `['arXiv.'20]` Real-world Video Adaptation with Reinforcement Learning [[PDF](https://export.arxiv.org/pdf/2008.12858v1)]
 10. `['arXiv.'23]` Improving ABR Performance for Short Video Streaming Using Multi-Agent Reinforcement Learning with Expert Guidance [[PDF](https://arxiv.org/pdf/2304.04637)]
 11. `['ACM Multimedia'22]` Real-time Streaming Video Denoising with Bidirectional Buffers [[PDF](https://arxiv.org/pdf/2207.06937)], [[Code](https://github.com/ChenyangQiQi/BSVD)]
 12. `['IEEE Conference on Computer Vision.'22]` Label-Efficient Online Continual Object Detection in Streaming Video [[PDF](https://arxiv.org/pdf/2206.00309)], [[Code](https://github.com/showlab/Efficient-CLS)]


### Multimodal LLMs for Streaming
1. `['CVPR'24]` VideoLLM-online: Online Large Language Model for Streaming Video [[PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_VideoLLM-online_Online_Video_Large_Language_Model_for_Streaming_Video_CVPR_2024_paper)], [[Code](https://showlab.github.io/videollm-online/)]
2. `['CVPR'25]` Dispider: Enabling Video LLMs with Active Real-Time Interaction via Disentangled Perception, Decision, and Reaction [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Qian_Dispider_Enabling_Video_LLMs_with_Active_Real-Time_Interaction_via_Disentangled_CVPR_2025_paper.pdf)], [[Code](https://github.com/Mark12Ding/Dispider)]
3. `['CVPR'25]` LiveCC: Learning Video LLM with Streaming Speech Transcription at Scale [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Qian_Dispider_Enabling_Video_LLMs_with_Active_Real-Time_Interaction_via_Disentangled_CVPR_2025_paper.pdf)], [[Code](https://showlab.github.io/livecc/)]
4. `['arXiv'25]` TimeChat-Online: 80% Visual Tokens are Naturally Redundant in Streaming Videos [[PDF](https://arxiv.org/pdf/2504.17343)], [[Code](https://github.com/yaolinli/TimeChat-Online)]
5. `['CVPR'25]` OmniMMI:AComprehensive Multi-modal Interaction Benchmark in Streaming Video Contexts [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_OmniMMI_A_Comprehensive_Multi-modal_Interaction_Benchmark_in_Streaming_Video_Contexts_CVPR_2025_paper.pdf)], [[Code](https://omnimmi.github.io/)]
6. `['arXiv'25]` VideoLLaMB: Long Streaming Video Understanding with Recurrent Memory Bridges [[PDF](https://arxiv.org/pdf/2409.01071)], [[Code](https://github.com/bigai-nlco/VideoLLaMB)]
7. `['EMNLP'24]` Efficient Temporal Extrapolation of Multimodal Large Language Models with Temporal Grounding Bridge [[PDF](https://aclanthology.org/2024.emnlp-main.556.pdf)], [[Code](https://github.com/bigai-nlco/VideoTGB)]
8. `['ICLR'25]`  STREAMING VIDEO QUESTION-ANSWERING WITH IN-CONTEXT VIDEO KV-CACHE RETRIEVAL [[PDF](https://arxiv.org/pdf/2503.00540)]
9. `['CVPR'25]`   BIMBA:Selective-Scan Compression for Long-Range Video Question Answering [[PDF](https://openaccess.thecvf.com/content/CVPR2025/papers/Islam_BIMBA_Selective-Scan_Compression_for_Long-Range_Video_Question_Answering_CVPR_2025_paper.pdf)], [[Code](https://sites.google.com/view/bimba-mllm)]
10. `['arXiv.'25]` InternLM-XComposer2.5-OmniLive: A Comprehensive Multimodal System for Long-term Streaming Video and Audio Interactions [[PDF](https://arxiv.org/abs/2412.09596)], [[Code](https://github.com/InternLM/InternLM-XComposer/tree/main/InternLM-XComposer-2.5-OmniLive)]
11. `['arXiv'25]` VideoMind: AChain-of-LoRAAgent for Long Video Reasoning [[PDF](https://arxiv.org/pdf/2503.13444)], [[Code](https://huggingface.co/spaces/yeliudev/VideoMind-2B)]
12. `['arXiv'24]` Video Token Sparsification for Efficient Multimodal LLMs in Autonomous Driving [[PDF](https://arxiv.org/pdf/2409.11182)]
13. `['arXiv'24]` Streaming Long Video Understanding with Large Language Models [[PDF](https://arxiv.org/pdf/2405.16009)]
14. `['arXiv'24]` VideoLLM-MoD: Efficient Video-Language Streaming with Mixture-of-Depths Vision Computation [[PDF](https://arxiv.org/pdf/2408.16730)]
15. `['NeurIPS'25]` StreamBridge: Turning Your Offline Video Large Language Model into a Proactive Streaming Assistant [[PDF](https://arxiv.org/pdf/2505.05467)]
16. `['arXiv'25]` Chat with AI: The Surprising Turn of Real-time Video Communication from Human to AI [[PDF](https://arxiv.org/pdf/2507.10510)]
17. `['arXiv'25]` Memory Helps, but Confabulation Misleads: Understanding Streaming Events in Videos with MLLMs [[PDF](https://arxiv.org/pdf/2502.15457)]
18. `['arXiv'24]` Inf-MLLM: Efficient Streaming Inference of Multimodal Large Language Models on a Single GPU [[PDF](https://arxiv.org/pdf/2409.09086)]
19. `['arXiv'25]` StreamForest: Efficient Online Video Understanding with Persistent Event Memory [[PDF](arxiv.org/pdf/2509.24871)], [[Code](https://github.com/MCG-NJU/StreamForest)]
20. `['CVPR'24]` MA-LMM: Memory-Augmented Large Multimodal Model for Long-Term Video Understanding [[PDF](https://arxiv.org/pdf/2404.05726)], [[Code](https://github.com/boheumd/MA-LMM)]
21. `['ICLR'25]` Understanding Long Videos with Multimodal Language Models [[PDF](https://arxiv.org/abs/2403.16998)], [[Code](https://github.com/kahnchana/mvu)]
22. `['CVPR'25]` Video-XL: Extra-Long Vision Language Model for Hour-Scale Video Understanding [[PDF](https://arxiv.org/pdf/2409.14485)], [[Code](https://github.com/VectorSpaceLab/Video-XL)]
23. `['ECCV'24]` LongVLM: Efficient Long Video Understanding via Large Language Models [[PDF](https://arxiv.org/pdf/2404.03384)], [[Code](https://github.com/ziplab/LongVLM)]
24. `['ICLR'25]` Streaming Video Understanding and Multi-round Interaction with Memory-enhanced Knowledge[[PDF](https://arxiv.org/pdf/2501.13468)], [[Code](https://github.com/hmxiong/StreamChat)]
25. `['ICLR'25]` LongVILA: Scaling Long-Context Visual Language Models for Long Videos[[PDF](https://arxiv.org/pdf/2408.10188)], [[Code](https://github.com/NVlabs/VILA/tree/main/longvila)]
26. `['ICLR'25]` TimeSuite: Improving MLLMs for Long Video Understanding via Grounded Tuning[[PDF](https://arxiv.org/pdf/2410.19702)], [[Code](https://github.com/OpenGVLab/TimeSuite)]
27. `['arXiv'25]` LiveVLM: Efficient Online Video Understanding via Streaming-Oriented KV Cache and Retrieval[[PDF](https://arxiv.org/abs/2505.15269)]
28. `['ICLR'25]` Streaming Video Question-Answering with In-context Video KV-Cache Retrieval[[PDF](https://arxiv.org/pdf/2503.00540)]
29. `['arXiv'23]`Audio-Visual LLM for Video Understanding[[PDF](https://arxiv.org/pdf/2312.06720)]
30. `['CVPR'24]`Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-modal LLMs in Video Analysis[[PDF](https://arxiv.org/pdf/2405.21075)]
31. `['arXiv'24]`SlowFast-LLaVA: A Strong Training-Free Baseline for Video Large Language Models[[PDF](https://arxiv.org/pdf/2407.15841)]
32. `['IEEE Transactions on Pattern Analysis and Machine Intelligence'24]`MovieChat+: Question-aware Sparse Memory for Long Video Question Answering[[PDF](https://arxiv.org/pdf/2404.17176)]
33. `['Neural Information Processing Systems'24]`E.T. Bench: Towards Open-Ended Event-Level Video-Language Understanding[[PDF](https://arxiv.org/pdf/2409.18111)]
34. `['CVPR'23]`TimeChat: A Time-sensitive Multimodal Large Language Model for Long Video Understanding[[PDF](https://arxiv.org/pdf/2312.02051)]
35. `['CVPR'24]Streaming Dense Video Captioning[[PDF](https://arxiv.org/pdf/2404.01297)]





### Datasets and Benchmark
1. `['arXiv.'25]`LongViTU: Instruction Tuning for Long-Form Video Understanding [[PDF](https://arxiv.org/pdf/2501.05037)], [[Code](https://rujiewu.github.io/LongViTU.github.io/)]
2. `['CVPR'25]`OVO-Bench: How Far is Your Video-LLMs from Real-World Online Video Understanding? [[PDF](https://arxiv.org/pdf/2501.05510)], [[Code](https://github.com/JoeLeelyf/OVO-Bench)]
3. `['arXiv'25]`StreamingBench: Assessing the Gap for MLLMs to Achieve Streaming Video Understanding [[PDF](https://arxiv.org/pdf/2411.03628)], [[Code](https://github.com/THUNLP-MT/StreamingBench)]
4. `['arXiv'25]`Online Video Understanding: A Comprehensive Benchmark and Memory-Augmented Method [[PDF](https://arxiv.org/pdf/2501.00584v1)], [[Code](https://videochat-online.github.io/)]
5. `['arXiv'24]`Flash-VStream: Memory-Based Real-Time Understanding for Long Video Streams [[PDF](https://arxiv.org/pdf/2406.08085)], [[Code](https://invinciblewyq.github.io/vstream-page/)]
6. `['ICLR'25]` SVBENCH: A BENCHMARK WITH TEMPORAL MULTI TURN DIALOGUES FOR STREAMING VIDEO UNDER STANDING [[PDF](https://arxiv.org/pdf/2502.10810)], [[Code](https://yzy-bupt.github.io/SVBench/)]
7. `['arXiv'23]` BVI-Artefact: An Artefact Detection Benchmark Dataset for Streamed Videos [[PDF](https://arxiv.org/pdf/2312.08859)], [[Code](https://chenfeng-bristol.github.io/BVI-Artefact/)]
8. `['arXiv'23]` Bitstream-corrupted Video Recovery:A Novel Benchmark Dataset and Method [[PDF](https://arxiv.org/pdf/2309.13890)], [[Code](https://github.com/LIUTIGHE/BSCV-Dataset)]


### Challenges and Future Directions
 1. `['IEEE Open Journal of the Communications Society'24]` Real-Time Immersive Aerial Video Streaming: A Comprehensive Survey, Benchmarking, and Open Challenges [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10668820)]
 2. `['MDPI'24]` A Survey on Video Streaming for Next-Generation Vehicular Networks[[PDF](https://www.mdpi.com/2079-9292/13/3/649)]

## :toolbox: Timeline
- 2025-09-01: Repo initialized
- 2025-09-05: First batch of papers added

## :bulb: TODO
- [ ] Add 2024�?2025 survey papers
- [ ] Build timeline figure
- [ ] Add datasets section
