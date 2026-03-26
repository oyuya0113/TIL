## AIモデル関連
### LLM（Large Language Model）
- [gpt-ossのモデルカード](https://arxiv.org/pdf/2508.10925)

### VLM（Vision-Language Model）
- [LLaVA](https://arxiv.org/pdf/2304.08485)
- ~~[Qwen2-VL](https://arxiv.org/pdf/2409.12191)~~（[Issue投稿済](https://github.com/oyuya0113/TIL/issues/3)）
- [Qwen3-VL](https://arxiv.org/pdf/2511.21631)

### LVM（Large Video Model）
TBD

### LBM（Large Behavior Model）
- [A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation](https://arxiv.org/pdf/2507.05331)（TRIの論文）

### VLA（Vision-Language-Action Model）
- [Agent as Cerebrum, Controller as Cerebellum: Implementing an Embodied LMM-based Agent on Drones](https://arxiv.org/pdf/2311.15033)
- ~~[VLA-AN: An Efficient and Onboard Vision-Language-Action Framework for Aerial Navigation in Complex Environments](https://arxiv.org/pdf/2512.15258)~~（Issue投稿予定）
- ~~[CognitiveDrone: A VLA Model and Evaluation Benchmark for Real-Time Cognitive Task Solving and Reasoning in UAVs](https://arxiv.org/pdf/2503.01378)~~
- [AUTOFLY: VISION-LANGUAGE-ACTION MODEL FOR UAV AUTONOMOUS NAVIGATION IN THE WILD](https://arxiv.org/pdf/2602.09657)
- [Vision-Language-Action Models for Robotics: A Review Towards Real-World Applications](https://arxiv.org/pdf/2510.07077)（VLAモデルのサーベイ論文。[こちら](https://www.youtube.com/watch?v=8wazzrqlKR0)の動画で知った）
- [π0.5: a Vision-Language-Action Model with Open-World Generalization](https://arxiv.org/pdf/2504.16054)
- [GR00T N1: An Open Foundation Model for Generalist Humanoid Robots](https://arxiv.org/pdf/2503.14734)（NVIDIA発のVLAモデル。二重過程理論（System1及びSystem2）をもとにシステム設計されている）
- [Hume: Introducing System-2 Thinking in Visual-Language-Action Model](https://arxiv.org/pdf/2505.21432)（System2をもとにシステム設計されている）
- [The Principles of Diffusion Models](https://arxiv.org/pdf/2510.21890)（拡散モデルのサーベイ論文。470ページある）
- [生成モデルの基礎と応用](https://speakerdeck.com/takahashihiroshi/generative-models)（拡散モデルに関する講義資料）
- [Alpamayo-R1: Bridging Reasoning and Action Prediction for Generalizable Autonomous Driving in the Long Tail](https://arxiv.org/pdf/2511.00088)（自動運転分野におけるVLAモデル。データ構造化及びアノテーションルールが徹底されている）
- [SafeVLA: Towards Safety Alignment of VisionLanguage-Action Model via Constrained Learning](https://arxiv.org/pdf/2503.03480)（VLAモデルの安全性向上に関する論文）
- [Unpacking Failure Modes of Generative Policies: Runtime Monitoring of Consistency and Progress](https://arxiv.org/pdf/2410.04640)（VLAモデルの安全性向上に関する論文②）
- [MEM: Multi-Scale Embodied Memory for Vision Language Action Models](https://arxiv.org/pdf/2603.03596)（VLAモデルにメモリ機能を搭載した論文）

### VAM（Video-Action Model）
- ~~[Unified Video Action Model](https://arxiv.org/pdf/2503.00200)~~（Issue投稿予定）
- [COSMOS POLICY: FINE-TUNING VIDEO MODELS FOR VISUOMOTOR CONTROL AND PLANNING](https://arxiv.org/pdf/2601.16163)（NVIDIA発のVAMモデル）

### WAM（World-Action Model）
- ~~[World Action Models are Zero-shot Policies](https://arxiv.org/pdf/2602.15922)~~（Issue投稿予定）

### VTLA（Vision-Tacticle-Language-Action Model）
- [VTLA: Vision-Tactile-Language-Action Model with Preference Learning for Insertion Manipulation](https://arxiv.org/pdf/2505.09577)（VLAに触覚（Tacticle）の要素を加えた論文）

### モデルアーキテクチャ
- [Nested Learning: The Illusion of Deep Learning Architecture](https://arxiv.org/pdf/2512.24695)（壊滅的忘却を軽減しうる可能性を持ったアーキテクチャの提案）
- [Less is More: Recursive Reasoning with Tiny Networks](https://arxiv.org/pdf/2510.04871)（Samsung発の小型アーキテクチャ（TRM））
- [LANGUAGE MODELS ARE INJECTIVE AND HENCE INVERTIBLE](https://arxiv.org/pdf/2510.15511)（インバージョンによりモデルの学習内容を推定できることを示した論文）
- [A comprehensive taxonomy of hallucinations in Large Language Models](https://arxiv.org/pdf/2508.01781)（ハルシネーションを体系的に纏めた論文）

### 量子化
- [The case for 4-bit precision: k-bit Inference Scaling Laws](https://arxiv.org/pdf/2212.09720)（4bit量子化が最適であることを示した論文）
- [LPCD: Unified Framework from Layer-Wise to Submodule Quantization](https://arxiv.org/pdf/2512.01546)（1bit量子化の提案）
- [AWQ: ACTIVATION-AWARE WEIGHT QUANTIZATION FOR ON-DEVICE LLM COMPRESSION AND ACCELERATION](https://arxiv.org/pdf/2306.00978)（AWQという量子化手法に関する論文。VLA-ANという論文で発見）


## AIエージェント
### エージェント内部構造
- ~~[Building 17 Agentic AI Patterns and Their Role in Large-Scale AI Systems](https://levelup.gitconnected.com/building-17-agentic-ai-patterns-and-their-role-in-large-scale-ai-systems-f4915b5615ce)~~
- ~~[Cognitive Architectures for Language Agents](https://arxiv.org/pdf/2309.02427)~~（[Issue投稿済](https://github.com/oyuya0113/TIL/issues/6)）
- ~~[LLM-Agent-Controller: A Universal Multi-Agent Large Language Model System as a Control Engineer](https://arxiv.org/pdf/2505.19567)~~（[Issue投稿済](https://github.com/oyuya0113/TIL/issues/1)）
- [BUILDING COOPERATIVE EMBODIED AGENTS MODULARLY WITH LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2307.02485)（メモリ機能の有無によりスコアが大幅に変化することを示した論文）
- [Memory in the Age of AI Agents: A Survey](https://arxiv.org/pdf/2512.13564)（メモリ機能を体系的に纏めた論文。107ページある）
- [LangMem](https://langchain-ai.github.io/langmem/)（長期記憶を管理できるライブラリ）
- [Agent Skills](https://agentskills.io/home)
- [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/pdf/2504.19413)（★）
- [CallNavi, A Challenge and Empirical Study on LLM Function Calling and Routing](https://arxiv.org/pdf/2501.05255)（★ API呼び出しにおけるLLMの構造化出力の精度（Exact Match）は100%にはならないことから、MCPツールの引数に設定する構造化データの作成に失敗する可能性があることを示した論文）
- [SubAgents](https://docs.langchain.com/oss/python/langchain/multi-agent/subagents)（★）

### エージェント形態（マルチエージェント）
- 


[A-Mem: Agentic Memory for LLM Agents](https://arxiv.org/pdf/2502.12110)<br>
　-> LLMエージェントのメモリ機能に関する論文

[LLM-LCSA: LLM for Collaborative Control and Decision Optimization in UAV Cluster Security](https://www.mdpi.com/2504-446X/9/11/779)<br>
　-> LLM×ドローンに関する論文

[Improving Multi-Agent Debate with Sparse Communication Topology](https://arxiv.org/pdf/2406.11776)<br>
　-> MASのネットワークに関する論文①

[Understanding the Information Propagation Effects of Communication Topologies in LLM-based Multi-Agent Systems](https://arxiv.org/pdf/2505.23352)<br>
　-> MASのネットワークに関する論文②

[CONFORMITY DYNAMICS IN MULTI-AGENT SYSTEMS: A NETWORK TOPOLOGY PERSPECTIVE](https://openreview.net/pdf?id=WZxgyxL6rw)<br>
　-> MASのネットワークに関する論文③

[RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/pdf/2307.15818)<br>
　-> VLAモデル（RT-2）に関する論文


## その他メモ
- LLMエージェントの品質保証に関する論文（ガイドライン）を要調査
- LLMの暗黙知に関する論文を要調査
