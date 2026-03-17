# Awesome Agentic ToM LLM

## 1. 目录

本论文列表聚焦以下方向，欢迎老师同学修改讨论：

1. Benchmark 与 Evaluation
2. Survey 与 Position Paper
3. 分类别具体工作

---

## 2. Benchmarks / Evaluation

### 2.1 核心 benchmark

1. **ToMBench: Benchmarking Theory of Mind in Large Language Models**  
   **关键词**：benchmark, 8 tasks, 31 abilities, bilingual, MCQ, leakage control  
   **链接**：https://aclanthology.org/2024.acl-long.847/  
   **代码**：https://github.com/zhchen18/ToMBench

2. **FANToM: A Benchmark for Stress-testing Machine Theory of Mind in Interactions**  
   **关键词**：interactive dialogue, information asymmetry, conversational ToM, stress test  
   **链接**：https://aclanthology.org/2023.emnlp-main.890/  
   **代码**：https://github.com/skywalker023/fantom

3. **NegotiationToM: A Benchmark for Stress-testing Machine Theory of Mind on Negotiation Surrounding**  
   **关键词**：negotiation, BDI, belief-desire-intention, real-world interaction  
   **链接**：https://aclanthology.org/2024.findings-emnlp.244/  
   **arXiv**：https://arxiv.org/abs/2404.13627

4. **Understanding Social Reasoning in Language Models with Language Models（BigToM）**  
   **关键词**：procedural generation, social reasoning, causal template, controls, benchmark generation  
   **链接**：https://proceedings.neurips.cc/paper_files/paper/2023/hash/2b9efb085d3829a2aadffab63ba206de-Abstract-Datasets_and_Benchmarks.html

5. **Hi-ToM: Benchmarking Higher-Order Theory of Mind in Large Language Models**  
   **关键词**：higher-order ToM, recursive beliefs, deception, advanced mental-state reasoning  
   **链接**：https://arxiv.org/abs/2310.16755

6. **T4D / Thinking for Doing: Towards AI with Theory of Mind in the Wild**  
   **关键词**：ToM-to-action, situated decision-making, social action, pragmatic reasoning  
   **链接**：https://arxiv.org/abs/2310.03051

7. **MoToMQA: Benchmarking LLMs on Higher-Order Theory of Mind with Question Answering**  
   **关键词**：multi-order ToM, second-to-sixth order beliefs, adult-level benchmark  
   **链接**：https://arxiv.org/abs/2405.18870

8. **ToMATO: Benchmarking Theory-of-Mind in Role-Playing Conversations**  
   **关键词**：role-playing, dialogue, first-order belief, second-order belief, emotion, intention  
   **链接**：https://arxiv.org/abs/2501.08838

9. **MotiveBench**  
   **关键词**：motivation reasoning, desire modeling, Maslow, social intelligence  
   **链接**：https://arxiv.org/abs/2506.13065

10. **CogToM**  
    **关键词**：cognitive mechanisms, beyond false belief, broader ToM coverage  
    **链接**：https://arxiv.org/abs/2601.15628

11. **ToMBench-Hard**  
    **关键词**：hard cases, adversarial ToM, deception, belief revision, RL-ready evaluation  
    **链接**：https://openreview.net/forum?id=3qAzQyOOnA

### 2.2 多模态 / embodied benchmark

1. **MuMA-ToM**  
   **关键词**：multimodal, multi-agent, embodied interaction, mental reasoning  
   **链接**：https://arxiv.org/abs/2408.12574

2. **MOMENTS: A Multimodal Benchmark for Theory of Mind in Short Films**  
   **关键词**：short films, multimodal mental states, narrative understanding  
   **链接**：https://aclanthology.org/2025.findings-emnlp.1230/

3. **EgoToM**  
   **关键词**：egocentric video, goals, beliefs, next actions, causal ToM  
   **链接**：https://arxiv.org/abs/2503.22152

4. **CHARTOM**  
   **关键词**：visual ToM, chart understanding, misleading visualization, belief manipulation  
   **链接**：https://arxiv.org/abs/2408.14419

5. **CoMMET**  
   **关键词**：multimodal, multi-turn conversation, mental states, moral evaluation  
   **链接**：https://arxiv.org/abs/2603.11915

---

## 3. Survey / Review / Position Papers

### 3.1 ToM in LLMs survey

1. **Theory of Mind in Large Language Models: Assessment and Enhancement**  
   **关键词**：survey, benchmarks, enhancement methods, future directions  
   **链接**：https://aclanthology.org/2025.acl-long.1522/  
   **arXiv**：https://arxiv.org/abs/2505.00026

2. **A Survey of Theory of Mind in Large Language Models**  
   **关键词**：behavioural ToM, representational ToM, safety risks, evaluation landscape  
   **链接**：https://arxiv.org/abs/2502.06470

3. **A Systematic Review on the Evaluation of Large Language Models in Theory of Mind Tasks**  
   **关键词**：systematic review, taxonomy, benchmark landscape, evaluation methods  
   **链接**：https://arxiv.org/abs/2502.08796

### 3.2 Agentic / strategic / RL survey

1. **Agentic Large Language Models, a Survey**  
   **关键词**：agentic LLM, reason-act-interact, reflection, retrieval, tool use, multi-agent  
   **链接**：https://arxiv.org/abs/2503.23037

2. **LLM as a Mastermind: A Survey of Strategic Reasoning with Large Language Models**  
   **关键词**：strategic reasoning, game-theory, opponent modeling, multi-agent  
   **链接**：https://arxiv.org/abs/2404.01230

3. **The Landscape of Agentic Reinforcement Learning for LLMs**  
   **关键词**：agentic RL, autonomous decision-making, dynamic environment, RL taxonomy  
   **链接**：https://arxiv.org/abs/2509.02547

### 3.3 Position / critique

1. **Position: Theory of Mind Benchmarks are Broken for Large Language Models**  
   **关键词**：functional ToM, partner adaptation, benchmark critique, anthropomorphism  
   **链接**：https://arxiv.org/abs/2412.19726  
   **OpenReview**：https://openreview.net/forum?id=BCP8UU2BcU

2. **Rethinking Theory of Mind Benchmarks for LLMs**  
   **关键词**：dynamic interaction, HCI, user preference, benchmark rethink  
   **链接**：https://arxiv.org/abs/2504.10839

---

## 4. 分类别具体工作

### 4.1 Agentic 方法：prompting / scaffolding / perspective-taking

1. **Boosting Theory-of-Mind Performance in Large Language Models via Prompting**  
   **关键词**：prompting, ICL, CoT, step-by-step, RLHF model gains  
   **链接**：https://arxiv.org/abs/2304.11490

2. **Think Twice: Perspective-Taking Improves Large Language Models’ Theory-of-Mind Capabilities（SimToM）**  
   **关键词**：perspective-taking, simulation theory, two-stage prompting, context filtering  
   **链接**：https://aclanthology.org/2024.acl-long.451/  
   **arXiv**：https://arxiv.org/abs/2311.10227

3. **TimeToM**  
   **关键词**：temporal belief state chain, self-world belief, social-world belief, temporal reasoning  
   **链接**：https://arxiv.org/abs/2407.01455

4. **PercepToM / Percept-ToMi / Percept-FANToM**  
   **关键词**：perception inference, perception-to-belief, ToM precursor, inhibitory control  
   **链接**：https://arxiv.org/abs/2407.06004

5. **Agentic-ToM**  
   **关键词**：cognition-inspired processing, agent framing, guided reasoning, explicit mental-state tracking  
   **链接**：https://aclanthology.org/2025.findings-emnlp.1398/

### 4.2 Agentic 方法：symbolic / belief-tracking / structured state

1. **Minding Language Models’ (Lack of) Theory of Mind: A Plug-and-Play Multi-Character Belief Tracker（SymbolicToM）**  
   **关键词**：symbolic belief tracking, multi-character state, plug-and-play, OOD robustness  
   **链接**：https://aclanthology.org/2023.acl-long.780/  
   **arXiv**：https://arxiv.org/abs/2306.00924

2. **Theory of Mind for Multi-Agent Collaboration via Large Language Models**  
   **关键词**：multi-agent collaboration, explicit belief state, cooperative text game, higher-order reasoning  
   **链接**：https://arxiv.org/abs/2310.10701

3. **ToM-agent: Large Language Models as Theory of Mind Aware Generative Agents with Counterfactual Reflection**  
   **关键词**：generative agent, BDI inference, counterfactual reflection, dialogue  
   **链接**：https://arxiv.org/abs/2501.15355

### 4.3 Agentic 方法：strategic / interactive / multi-agent social reasoning

1. **Strategic Reasoning with Language Models**  
   **关键词**：strategic reasoning, hidden information, beliefs, negotiation, values  
   **链接**：https://arxiv.org/abs/2305.19165

2. **Evaluating Theory of Mind and Internal Beliefs in LLM-Based Multi-Agent Systems**  
   **关键词**：internal beliefs, multi-agent systems, belief consistency, evaluation  
   **链接**：https://arxiv.org/abs/2603.00142

### 4.4 Agentic RL：用 RL 提升 ToM / social reasoning

1. **ToM-RL: Reinforcement Learning Unlocks Theory of Mind in Small Language Models**  
   **关键词**：RL, small LLM, social reasoning, higher-order belief, generalization  
   **链接**：https://arxiv.org/abs/2504.01698

2. **Social-R1: Towards Human-like Social Reasoning in LLMs**  
   **关键词**：social reasoning RL, reward design, hard ToM data, human-like alignment  
   **链接**：https://arxiv.org/abs/2603.09249

3. **MARO: Learning Stronger Reasoning from Social Interaction**  
   **关键词**：multi-agent reward optimization, reasoning from interaction, social environment  
   **链接**：https://arxiv.org/abs/2601.12323
