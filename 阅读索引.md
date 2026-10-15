# ICLR 2027 大模型与 AIGC 论文包

[下载全部 30 篇论文（ZIP，约 259 MiB）](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/ICLR2027_hot_2026-10-16_30papers.zip) · [全部 PDF 附件](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/tag/papers-2026-10-16)

论文 PDF 存放在本仓库的 Release 附件中，下表各篇标题可直接下载对应 PDF。

整理日期：2026-10-16（北京时间）。已下载 30 篇官方 OpenReview 投稿版 PDF。

## 筛选口径

- 从 Hugging Face 2026 年 10 月月榜发现近期有关注度的论文，再逐篇核对 OpenReview 的 ICLR 2027 主会有效投稿记录。
- 兼顾大模型与 AIGC 方向覆盖，所选论文按同一月榜页面的赞票快照降序编号；这是所选论文之间的顺序，不是全会场前 30 名，也不是官方质量排名。
- 赞票来自月榜快照；月榜和详情页可能因缓存、更新时间不同而显示不同数字，票数也会继续变化。
- 当前均为在审投稿。官方计划 2026-11-05 公布评审、2026-12-16 公布最终决定，不能据此推断录用或论文结论已获验证。
- 下载的是官方投稿版；Hugging Face 上关联的 arXiv 预印本可能使用不同标题或版本。
- 同名论文通过摘要区分。例如本包 HC-DLM 对应 OpenReview sdbvbJqDi7 / 投稿 35340 / arXiv 2610.02193。

来源：[ICLR 2027 官方时间表](https://iclr.cc/Conferences/2027/CallForPapers) · [OpenReview 投稿列表](https://openreview.net/group?id=ICLR.cc/2027/Conference) · [Hugging Face 10 月月榜](https://huggingface.co/papers/month/2026-10)

## 从哪里开始读

- 关注大模型后训练：02 RIDE、07 Cross-Teacher Guarding、11 Distillation Dynamics、16 LoGRA。
- 关注智能体：01 False Frontiers、09 AgentSWE、13 Scaling Agentic Data。
- 关注多模态与空间推理：04 GroundingPI、05 S-Space、08 Latent Visual Reasoning。
- 关注 AIGC 视频：03 ATAS、17 Diffusion-ART、19 FrameMorrow、23 DuoMatching。
- 关注扩散文本生成：24 HC-DLM、26 ALoDLM、28 E-MoE。

以下中文标签用于快速定位主题，不代替精读或实验质量评估。

## 分类目录

- 大模型智能体与评测：6 篇，压缩包内目录 `01_LLM_Agents/`。
- 大模型后训练、强化学习与蒸馏：7 篇，压缩包内目录 `02_LLM_Training/`。
- 多模态大模型与视觉推理：4 篇，压缩包内目录 `03_Multimodal_Models/`。
- 高效推理与缓存：2 篇，压缩包内目录 `04_Efficient_Inference/`。
- AIGC：图像、视频与世界生成：8 篇，压缩包内目录 `05_AIGC_Video_Image_World/`。
- 扩散语言模型：3 篇，压缩包内目录 `06_Diffusion_Language_Models/`。

## 完整清单（所选论文的赞票快照降序）

| 编号 | 论文 / PDF 下载 | 主题 | HF 赞票 | 页数 | 来源 |
|---|---|---|---:|---:|---|
| 01 | [False Frontiers: Diagnosing and Mitigating Co-Cheating in Self-Evolving Search Agents](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/01_False_Frontiers.pdf) | 智能体自演化与奖励失真 | 663 | 20 | [OpenReview](https://openreview.net/forum?id=Id4G8bzzKO) · [热度页](https://huggingface.co/papers/2609.39102) |
| 02 | [The Teacher Is a Direction, Not a Destination: Extrapolating RL-Induced Representation Residuals in On-Policy Distillation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/02_RIDE_On_Policy_Distillation.pdf) | 大模型后训练与表示空间蒸馏 | 524 | 18 | [OpenReview](https://openreview.net/forum?id=qQnxmn109m) · [热度页](https://huggingface.co/papers/2609.36484) |
| 03 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/03_ATAS_Agentic_Video_Generation.pdf) | 跨镜头视频生成与场景记忆 | 318 | 32 | [OpenReview](https://openreview.net/forum?id=vMypxbZHbc) · [热度页](https://huggingface.co/papers/2610.20571) |
| 04 | [GroundingPI: A Grounding Foundation Model towards Physical Intelligence with Visual Primitives](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/04_GroundingPI.pdf) | 视觉定位基础模型与物理智能 | 306 | 59 | [OpenReview](https://openreview.net/forum?id=xvloOO0IWo) · [热度页](https://huggingface.co/papers/2609.39601) |
| 05 | [S-Space: Exploring Spatial Workspace in Multimodal Language Models](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/05_S_Space.pdf) | 多模态大模型的空间表征与推理 | 291 | 24 | [OpenReview](https://openreview.net/forum?id=9V4bHxQRc4) · [热度页](https://huggingface.co/papers/2610.13527) |
| 06 | [RealCompanion: Benchmarking Human Understanding from Reasoning over Longitudinal Real-World Conversations](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/06_RealCompanion.pdf) | 真实长期对话中的记忆与个性化评测 | 286 | 61 | [OpenReview](https://openreview.net/forum?id=VHSTN9e756) · [热度页](https://huggingface.co/papers/2610.01780) |
| 07 | [Beyond Domain-Routed Supervision: Cross-Teacher Guarding for Multi-Teacher On-Policy Distillation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/07_Cross_Teacher_Guarding.pdf) | 多教师蒸馏中的梯度冲突协调 | 232 | 30 | [OpenReview](https://openreview.net/forum?id=q5NpkqNLNY) · [热度页](https://huggingface.co/papers/2610.13521) |
| 08 | [Rethinking Latent Visual Reasoning: Grounding Latent Reasoning in Visual Evidence](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/08_Latent_Visual_Reasoning.pdf) | 视觉证据与潜在空间推理 | 223 | 40 | [OpenReview](https://openreview.net/forum?id=GAaKiNHi5i) · [热度页](https://huggingface.co/papers/2609.34563) |
| 09 | [AgentSWE: Can Coding Agents Build the Agent You Actually Want?](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/09_AgentSWE.pdf) | 编程智能体构建智能体的能力评测 | 222 | 35 | [OpenReview](https://openreview.net/forum?id=5f7tLJjygV) · [热度页](https://huggingface.co/papers/2610.13361) |
| 10 | [Rethinking Cross-Tokenizer On-Policy Distillation: From Alignment Coverage to Supervision Reliability](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/10_Cross_Tokenizer_Distillation.pdf) | 不同分词器之间的在线蒸馏 | 213 | 21 | [OpenReview](https://openreview.net/forum?id=iHdUmEIkbu) · [热度页](https://huggingface.co/papers/2610.08448) |
| 11 | [On-Policy or Off-Policy Learning? A Systematic Study of Distillation Dynamics](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/11_Distillation_Dynamics.pdf) | 在线与离线蒸馏的训练动力学 | 204 | 47 | [OpenReview](https://openreview.net/forum?id=6e3nUwrCxJ) · [热度页](https://huggingface.co/papers/2609.35259) |
| 12 | [Self-Retrospection Distillation: Turning Post-hoc Experiences into Prior Foresight](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/12_Self_Retrospection_Distillation.pdf) | 将事后经验转化为事前能力的蒸馏 | 191 | 46 | [OpenReview](https://openreview.net/forum?id=KG8HVheDgb) · [热度页](https://huggingface.co/papers/2610.08077) |
| 13 | [Scaling Agentic Data for Long-Horizon Terminal Intelligence](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/13_Scaling_Agentic_Data.pdf) | 长时程终端智能体的数据扩展 | 156 | 38 | [OpenReview](https://openreview.net/forum?id=UOwYasdeqY) · [热度页](https://huggingface.co/papers/2610.13166) |
| 14 | [Learn2Play Bench: How Well Do LLM Agents Learn from Experience in Unfamiliar Environments?](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/14_Learn2Play_Bench.pdf) | 陌生环境中的智能体经验学习评测 | 153 | 62 | [OpenReview](https://openreview.net/forum?id=w4WaZoAYsG) · [热度页](https://huggingface.co/papers/2610.08215) |
| 15 | [Player-1: Learning to Play from Synthetic Experience](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/15_Player_1.pdf) | 从合成经验中学习交互策略 | 152 | 22 | [OpenReview](https://openreview.net/forum?id=gpCgvArdO3) · [热度页](https://huggingface.co/papers/2610.20584) |
| 16 | [LoGRA: Scaling LLM Reinforcement Learning with Low-Rank Gradient Sketches](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/16_LoGRA.pdf) | 利用低秩梯度降低大模型强化学习成本 | 151 | 15 | [OpenReview](https://openreview.net/forum?id=SoSbLCz33T) · [热度页](https://huggingface.co/papers/2610.06647) |
| 17 | [Diffusion-ART: Efficient, Stable and Scalable Reinforcement of Diffusion Model](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/17_Diffusion_ART.pdf) | 图像与视频扩散模型的强化学习后训练 | 146 | 22 | [OpenReview](https://openreview.net/forum?id=MiONXSc1yq) · [热度页](https://huggingface.co/papers/2610.12572) |
| 18 | [STEPQuant: When and Where Errors Matter in Delta-Rule Recurrent State Quantization](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/18_STEPQuant.pdf) | 循环状态量化与高效推理 | 130 | 26 | [OpenReview](https://openreview.net/forum?id=OoetS6pSkM) · [热度页](https://huggingface.co/papers/2609.38169) |
| 19 | [FrameMorrow: Future-Guided Frame Selection with Prospective Tokens for Long-Horizon Video Generation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/19_FrameMorrow.pdf) | 面向长视频生成的历史帧选择 | 125 | 20 | [OpenReview](https://openreview.net/forum?id=5oQB8QNU1R) · [热度页](https://huggingface.co/papers/2609.38839) |
| 20 | [OneStreamer: Unifying Perception, Memory, and Proactive Response in Streaming Video Interaction](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/20_OneStreamer.pdf) | 流式视频大模型的感知、记忆与主动响应 | 117 | 29 | [OpenReview](https://openreview.net/forum?id=K9GXRUMM70) · [热度页](https://huggingface.co/papers/2610.01762) |
| 21 | [Sharpening Tax in Post-Training](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/21_Sharpening_Tax.pdf) | 后训练准确率与解空间覆盖的权衡 | 111 | 58 | [OpenReview](https://openreview.net/forum?id=bEYxPWtTNk) · [热度页](https://huggingface.co/papers/2610.01509) |
| 22 | [Prefill-Free Cross-Family KV Cache Transfer for Heterogeneous Multi-Agent LLMs](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/22_Cross_Family_KV_Transfer.pdf) | 异构多智能体之间的 KV 缓存迁移 | 103 | 23 | [OpenReview](https://openreview.net/forum?id=5gFgaB9Rym) · [热度页](https://huggingface.co/papers/2609.32259) |
| 23 | [DuoMatching: Joint–Marginal Distribution Matching for Few-Step Video Generation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/23_DuoMatching.pdf) | 少步视频生成与联合边缘分布匹配 | 101 | 20 | [OpenReview](https://openreview.net/forum?id=UHY5ZSovWh) · [热度页](https://huggingface.co/papers/2610.03543) |
| 24 | [Hierarchical Continuous Diffusion Language Models](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/24_HC_DLM.pdf) | 离散文本与连续潜变量耦合的扩散语言模型 | 92 | 24 | [OpenReview](https://openreview.net/forum?id=sdbvbJqDi7) · [热度页](https://huggingface.co/papers/2610.02193) |
| 25 | [World Observer: Joint Actor-Observer Generation for Persistent World Modeling](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/25_World_Observer.pdf) | 联合主体与观察者视角的持续世界建模 | 89 | 26 | [OpenReview](https://openreview.net/forum?id=D4CEn4EUB8) · [热度页](https://huggingface.co/papers/2610.02162) |
| 26 | [ALoDLM: Adaptively Looped Diffusion Language Models](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/26_ALoDLM.pdf) | 自适应循环计算的扩散语言模型 | 79 | 25 | [OpenReview](https://openreview.net/forum?id=cMNaCZyQdB) · [热度页](https://huggingface.co/papers/2610.04198) |
| 27 | [UltraText Bench: A Comprehensive Bilingual Benchmark for Evaluating Visual Text Rendering in Image Generation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/27_UltraText_Bench.pdf) | 中英文图像生成文字渲染评测 | 73 | 38 | [OpenReview](https://openreview.net/forum?id=e9rnLFpNHc) · [热度页](https://huggingface.co/papers/2610.09823) |
| 28 | [E-MoE: Enhanced Mixture-of-Experts for Non-Factorized Diffusion Language Models](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/28_E_MoE.pdf) | 用专家混合建模并行生成文本的词间依赖 | 67 | 27 | [OpenReview](https://openreview.net/forum?id=6Wg0BsKrDq) · [热度页](https://huggingface.co/papers/2609.37533) |
| 29 | [ExeWorldBench: Benchmarking Code-Based Executable 3D World Modeling](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/29_ExeWorldBench.pdf) | 代码生成可执行三维世界的能力评测 | 66 | 20 | [OpenReview](https://openreview.net/forum?id=LWytqLskTe) · [热度页](https://huggingface.co/papers/2610.15166) |
| 30 | [Hear the World in Stereo: Learning Dynamic Spatial Correspondence for Immersive Joint Video-Audio Generation](https://github.com/insomniapku/ICLR2027-LLM-AIGC-Papers/releases/download/papers-2026-10-16/30_Hear_the_World_in_Stereo.pdf) | 立体声与视频的空间一致联合生成 | 64 | 26 | [OpenReview](https://openreview.net/forum?id=iWSoBuMm8J) · [热度页](https://huggingface.co/papers/2609.38748) |

## 文件说明

- `论文清单.csv`：可在表格软件中筛选，包含完整标题、来源、类别和文件路径。
- `manifest.json`：含来源、投稿编号、页数、文件大小及 SHA-256，便于追溯与重复检查。
- PDF 保持原样，没有翻译、裁剪或修改。

## 来源与署名

论文版权归各自作者所有。PDF 保留下载时的原始内容；每篇论文的原始页面、PDF 地址和许可信息可从 [来源清单](ATTRIBUTION.md) 查询。整理日期为 2026-10-16，论文目前均为在审投稿。
