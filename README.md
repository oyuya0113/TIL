## AIモデル関連
### LLM（Large Language Model）
- [gpt-ossのモデルカード](https://arxiv.org/pdf/2508.10925)
- [Llama Nemotron](https://arxiv.org/pdf/2505.00949)
- [Gemma 4](https://ai.google.dev/gemma/docs/core/model_card_4?hl=ja)
- [llm-jp-4](https://llm-jp.nii.ac.jp/release/)

### VLM（Vision-Language Model）
- ~~[LLaVA](https://arxiv.org/pdf/2304.08485)~~
- ~~[Qwen2-VL](https://arxiv.org/pdf/2409.12191)~~（[Issue投稿済](https://github.com/oyuya0113/TIL/issues/3)）
- [Qwen3-VL](https://arxiv.org/pdf/2511.21631)
- [LVLM-Interpret: An Interpretability Tool for Large Vision-Language Models](https://arxiv.org/pdf/2404.03118)（Visual Attentionの可視化手法を提案した論文）

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
- [BUILDING COOPERATIVE EMBODIED AGENTS MODULARLY WITH LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2307.02485)（★ メモリ機能の有無によりスコアが大幅に変化することを示した論文）
- [Memory in the Age of AI Agents: A Survey](https://arxiv.org/pdf/2512.13564)（メモリ機能を体系的に纏めた論文。107ページある）
- [VOYAGER: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/pdf/2305.16291)
- [langgraph-multi-agent-supervisor](https://github.com/pdichone/langgraph-multi-agent-supervisor/tree/main)（★★★ 大変参考になりそうなソースコード有）
- [Ambient Agent](https://github.com/langchain-ai/ambient-agent-101/tree/main)（LangChain公式のAmbient Agentのソースコード有）
- [GAF-GUARD: AN AGENTIC FRAMEWORK FOR RISK MANAGEMENT AND GOVERNANCE IN LARGE LANGUAGE MODELS](https://arxiv.org/pdf/2507.02986)（★★★ ソースコード有）

### エージェント形態（マルチエージェント）
- ~~[AGENTNET: DECENTRALIZED EVOLUTIONARY COORDINATION FOR LLM-BASED MULTI-AGENT SYSTEMS](https://arxiv.org/pdf/2504.00587)~~（[Issue投稿済](https://github.com/oyuya0113/TIL/issues/4)）
- [Project Sid: Many-agent simulations toward AI civilization](https://arxiv.org/pdf/2411.00114)
- [AGENTTAXO: DISSECTING AND BENCHMARKING TOKEN DISTRIBUTION OF LLM MULTI-AGENT SYSTEMS](https://openreview.net/pdf?id=0iLbiYYIpC)（Communication Tax を主張している論文）
- [Distributional AGI Safety](https://arxiv.org/pdf/2512.16856)（AGIは、多数のAgentが組み合わさった集合体として出現することを主張している論文）
- [Improving Multi-Agent Debate with Sparse Communication Topology](https://arxiv.org/pdf/2406.11776)（MASのネットワークに関する論文）
- [Understanding the Information Propagation Effects of Communication Topologies in LLM-based Multi-Agent Systems](https://arxiv.org/pdf/2505.23352)（MASのネットワークに関する論文②）
- [LLM-LCSA: LLM for Collaborative Control and Decision Optimization in UAV Cluster Security](https://www.mdpi.com/2504-446X/9/11/779)（★★）


## RAG（Retrieval-Augmented Generation）
- [Essential GraphRAG](https://neo4j.com/essential-graphrag/)（★）


## 各種プロトコル
### MCP
- ~~[5 Best Practices for Building MCP Servers](https://snyk.io/jp/articles/5-best-practices-for-building-mcp-servers/)~~（LLMが理解できるように、MCPツールのnameやdescriptionは命名規則を整える必要がある）
- [RAG-MCP: Mitigating Prompt Bloat in LLM Tool Selection via Retrieval-Augmented Generation](https://arxiv.org/pdf/2505.03275)（MCPツールのリストが長大になると、不適切なMCPツールをLLMが選択する可能性が高まることを示した論文）
- [CallNavi, A Challenge and Empirical Study on LLM Function Calling and Routing](https://arxiv.org/pdf/2501.05255)（★ API呼び出しにおけるLLMの構造化出力の精度（Exact Match）は100%にはならないことから、MCPツールの引数に設定する構造化データの作成に失敗する可能性があることを示した論文）

### A2A
TBD


## 各種フレームワーク
### LangChain, LangGraph
- [create_agent](https://reference.langchain.com/python/langchain/agents/factory/create_agent)
- [Middleware](https://docs.langchain.com/oss/python/langchain/middleware/overview)（★ interrupt_before及びinterrupt_afterとは何が違う？）
- [MIROSTAT](https://arxiv.org/abs/2007.14966)（create_agentの引数の一つ。何者なのか分かっていない）
- [LangMem](https://langchain-ai.github.io/langmem/)（長期記憶を管理できるライブラリ）
- [SubAgents](https://docs.langchain.com/oss/python/langchain/multi-agent/subagents)（★）
- [Deep Agents](https://github.com/langchain-ai/deepagents)
- [NodeInterrupt](https://blog.generative-agents.co.jp/entry/2024/09/09/164346)（強制的に親ノードへreturnする）

### LangSmith, LangFuse
TBD

### Mem0
- [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/pdf/2504.19413)（★★）

### Agent Skills
- [Agent Skills](https://agentskills.io/home)（★）

### Ollama
- [Ollama](https://ollama.com/)

### vLLM
- [vLLM Docs](https://docs.vllm.ai/en/latest/)（★★ KVキャッシュをブロック単位に分割する手法）
- [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/pdf/2309.06180)

### LMCache
- [LMCache Docs](https://docs.lmcache.ai/)（★★ KVキャッシュの管理機能。LMCache ConnectorはvLLMと互換性あり）
- [LMCache: An Efficient KV Cache Layer for Enterprise-Scale LLM Inference](https://arxiv.org/pdf/2510.09665)

### Llama.cpp
- [Llama.cpp](https://github.com/ggml-org/llama.cpp)（★）

### TensorRT-LLM
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)


## その他
- [Dota 2 with Large Scale Deep Reinforcement Learning](https://arxiv.org/pdf/1912.06680)（OpenAIの強化学習に関する論文。Dota2が題材になっている）
- [研究開発の俯瞰報告書](https://www.jst.go.jp/crds/report/CRDS-FR-S.html)（AIを体系的に紹介している文献）
- [生成AI 品質マネジメントガイドライン](https://www.digiarc.aist.go.jp/publication/aiqm/GenAIQuality-requirements-rev1.0.0.0019.pdf)（産総研が公開しているガイドライン）
- [Position: Levels of AGI for Operationalizing Progress on the Path to AGI](https://arxiv.org/pdf/2311.02462)（AGIのレベルを定義した論文。NLP2026にて紹介あり）
- ~~[形式論理学に基づく演繹コーパスによる言語モデルに対する演繹推論能力の付与](https://speakerdeck.com/morishtr/xing-shi-lun-li-xue-niji-dukuyan-yi-kopasuniyoru-yan-yu-moderunidui-suruyan-yi-tui-lun-neng-li-nofu-yu)~~（NLP2026の招待論文セッションで発表があった論文）
- [Outsmarting Agile Adversaries in the Electromagnetic Spectrum](https://www.rand.org/pubs/research_reports/RRA981-1.html)（コンテナ技術はCognitive EWでは重要だという考えを主張している文献）

