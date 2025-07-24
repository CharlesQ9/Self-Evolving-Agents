# <img src="figures/evolution.png" alt="Example Figure" width="50" height="50" /> A Survey of Self-Evolving Agents: On Path to Artificial Super Intelligence


<!-- omit in toc -->
## 📢 Updates

- **2025.07**: We released a github repo to record papers related with reasoning economy. Feel free to cite or open pull requests.


---

- [A Survey of Self-Evolving Agents: On Path to Artificial Super Intelligence](#a-survey-of-self-evolving-agents-on-path-to-artificial-super-intelligence)
    - [1. Introduction](#1-introduction)
    - [2. Definitions and Foundations](#2-definitions-and-foundations)
    - [3. What to Evolve?](#3-what-to-evolve)
        - [3.1 Models](#31-models)
        - [3.2 Context](#32-context)
            - [3.2.1 Memory Evolution](#321-memory-evolution)
            - [3.2.2 Prompt Optimization](#322-prompt-optimization)
        - [3.3 Tools](#33-tools)
        - [3.4 Architecture](#34-architecture)
            - [3.4.1 Single-Agent System Optimization](#341-single-agent-system-optimization)
            - [3.4.2 Multi-Agent System Optimization](#342-multi-agent-system-optimization)
    - [4. When to Evolve?](#4-when-to-evolve)
        - [4.1 Intra-test-Time Self-Evolution](#41-intra-test-time-self-evolution)
        - [4.2 Inter-test-Time Self-evolution](#42-inter-test-time-self-evolution)
    - [5. How to Evolve](#5-how-to-evolve)
        - [5.1 Reward-based Self-Evolution](#51-reward-based-self-evolution)
        - [5.2 Imitation and Demonstration Learning](#52-imitation-and-demonstration-learning)
            - [5.2.1 Self-generated Demonstration Learning](#521-self-generated-demonstration-learning)
            - [5.2.2 Cross-Agent Demonstration Learning](#522-cross-agent-demonstration-learning)
            - [5.2.3 Hybrid Demonstration Learning](#523-hybrid-demonstration-learning)
        - [5.3 Population-based and Evolutionary Methods](#53-population-based-and-evolutionary-methods)
        - [5.4 Cross-cutting Evolutionary Dimensions](#54-cross-cutting-evolutionary-dimensions)
        - [5.5 Other Dimensions of Self-Evolution Methods](#55-other-dimensions-of-self-evolution-methods)
    - [6. Where to Evolve?](#6-where-to-evolve)
        - [6.1 General Domain Evolution](#61-general-domain-evolution)
        - [6.2 Specialized Domain Evolution](#62-specialized-domain-evolution)
    - [7. Evaluation of Self-evolving Agents](#7-evaluation-of-self-evolving-agents)
        - [7.1 Evaluation Goal and Metrics](#71-evaluation-goal-and-metrics)
        - [7.2 Evaluation Paradigm](#72-evaluation-paradigm)
            - [7.2.1 Static Assessment](#721-static-assessment)
            - [7.2.2 Short-Horizon Adaptive Assessment](#722-short-horizon-adaptive-assessment)
            - [7.2.3 Long-Horizon Lifelong Learning Ability Assessment](#723-long-horizon-lifelong-learning-ability-assessment)
    - [8. Future Directions](#8-future-directions)


---

### 1. Introduction

- [Large language model agent: A survey on methodology, applications and challenges](https://arxiv.org/abs/2503.21460.pdf)

- [Advances and challenges in foundation agents: From brain-inspired intelligence to evolutionary, collaborative, and safe systems](https://arxiv.org/abs/2504.01990.pdf)

- [Toward a Theory of Agents as Tool-Use Decision-Makers](https://arxiv.org/abs/2506.00886.pdf)

- [A survey on self-evolution of large language models](https://arxiv.org/abs/2404.14387.pdf)

### 2. Definitions and Foundations

- [Curriculum Learning for Cooperation in Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2312.11768.pdf)

- [A Survey on Curriculum Learning]

- [Self-Evolving Curriculum for LLM Reasoning]

- [Continual lifelong learning with neural networks: A review] 

- [Lifelong Learning of Large Language Model-based Agents: A Roadmap]

### 3. What to Evolve?

#### 3.1 Models

- [Gödel Agent: A Self-Referential Framework for Agents Recursively Self-Improvement]

- [Symbolic Learning Enables Self-Evolving Agents]

- [Self-Challenging Language Model Agents]

- [Self-reasoning Language Models]

- [Self-Rewarding Language Models](https://arxiv.org/abs/2401.10020.pdf)

- [Self-Adapting Language Models]

- [AgentGen: Enhancing Planning Abilities for Large Language Model based Agent via Environment and Task Generation]

- [UI-Genie: A Self-Improving Approach for Iteratively Boosting MLLM-based Mobile GUI Agents] `large vision models`

#### 3.2 Context

#### 3.2.1 Memory Evolution

- SAGE: Self-evolving Agents with Reflective and Memoryaugmented Abilities

- Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy

- Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks

- A-MEM: Agentic Memory for LLM Agents

- Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory 

- Learn-by-interact: A Data-Centric Framework for Self-Adaptive Agents in Realistic Environments

- Long Term Memory : The Foundation of AI Self-Evolution

- LARGE LANGUAGE MODELS AS OPTIMIZERS

#### 3.2.2 Prompt Optimization

- AutoManual: Constructing Instruction Manuals by LLM Agents via Interactive Environmental Learning

- AutoGuide: Automated Generation and Selection of Context-Aware Guidelines for Large Language Model Agents

- PreAct: Prediction Enhances Agent's Planning Ability

- EXACT: TEACHING AI AGENTS TO EXPLORE WITH REFLECTIVE-MCTS AND EXPLORATORY LEARNING

- Agents of Change: Self-Evolving LLM Agents for Strategic Planning


#### 3.3 Tools

- Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents

- Self-Evolving Multi-Agent Collaboration Networks for Software Development

- ATLASS: An Advanced Tool Learning and Selection System

- Agentic Skill Discovery

- From Exploration to Mastery: Enabling LLMs to Master Tools via Self-Driven Interactions

- ToolGen: Unified Tool Retrieval and Calling via Generation

#### 3.4 Architecture

- [AgentSquare: Automatic LLM Agent Search in Modular Design Space](https://arxiv.org/abs/2410.06153.pdf)

- [Gödel Agent: A Self-Referential Framework for Agents Recursively Self-Improvement](https://arxiv.org/abs/2410.04444.pdf)

- [AlphaEvolve: A coding agent for scientific and algorithmic discovery](https://arxiv.org/abs/2506.13131.pdf)

- [TextGrad: Automatic "Differentiation" via Text](https://arxiv.org/abs/2406.07496.pdf)

- [EvoFlow: Evolving Diverse Agentic Workflows On The Fly](https://arxiv.org/abs/2502.07373.pdf)

- [Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies](https://arxiv.org/abs/2502.02533.pdf)

- [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762.pdf)

- [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435.pdf)

- [AutoFlow: Automated Workflow Generation for Large Language Model Agents](https://arxiv.org/abs/2407.12821.pdf)

- [Language Agents as Optimizable Graphs](https://arxiv.org/abs/2402.16823.pdf)

- [ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization](https://arxiv.org/abs/2502.04306.pdf)

- [FlowReasoner: Reinforcing Query-Level Meta-Agents](https://arxiv.org/abs/2504.15257.pdf)

- [ReMA: Learning to Meta-think for LLMs with Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2503.09501.pdf)

### 4. When to Evolve?

#### 4.1 Intra-test-Time Self-Evolution

- [AdaPlanner: Adaptive Planning from Feedback with Language Models](https://arxiv.org/abs/2305.16653.pdf)

- [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366.pdf)

- [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651.pdf)

- [TrustAgent: Towards Safe and Trustworthy LLM-based Agents](https://arxiv.org/abs/2402.01586.pdf)

- [Self-Adapting Language Models](https://arxiv.org/abs/2506.10943.pdf)

- [Test-Time Training on Nearest Neighbors for Large Language Models](https://arxiv.org/abs/2305.18466.pdf)

- [Efficiently Learning at Test-Time: Active Fine-Tuning of LLMs](https://arxiv.org/abs/2410.08020.pdf)

- [LADDER: Self-Improving LLMs Through Recursive Problem Decomposition](https://arxiv.org/abs/2503.00735.pdf)

- [TTRL: Test-Time Reinforcement Learning](https://arxiv.org/abs/2504.16084.pdf)

#### 4.2 Inter-test-Time Self-evolution

- [SELF: Self-Evolution with Language Feedback](https://arxiv.org/abs/2310.00533.pdf)

- [STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465.pdf)

- [Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking](https://arxiv.org/abs/2403.09629.pdf)

- [SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning](https://arxiv.org/abs/2502.04780.pdf)

- [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073.pdf)

- [DYSTIL: Dynamic Strategy Induction with Large Language Models for Reinforcement Learning](https://arxiv.org/abs/2505.03209.pdf)

- [Learning Like Humans: Advancing LLM Reasoning Capabilities via Adaptive Difficulty Curriculum Learning and Expert-Guided Self-Reformulation](https://arxiv.org/abs/2505.08364.pdf)

- [WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning](https://arxiv.org/abs/2411.02337.pdf)

- [DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement Learning](https://arxiv.org/abs/2406.11896.pdf)

### 5. How to Evolve?

#### 5.1 Reward-based Self-Evolution

- [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651.pdf)

- [Training Language Models to Self-Correct via Reinforcement Learning](https://arxiv.org/abs/2409.12917.pdf)

- [PAG: Multi-Turn Reinforced LLM Self-Correction with Policy as Generative Verifier](https://arxiv.org/abs/2506.10406.pdf)

- [Confidence Improves Self-Consistency in LLMs](https://arxiv.org/abs/2502.06233.pdf)

- [Self-ensemble: Mitigating Confidence Distortion for Large Language Models](https://arxiv.org/abs/2506.01951.pdf)

- [Self Rewarding Self Improving](https://arxiv.org/abs/2505.08827.pdf)

- [Scalable Best-of-N Selection for Large Language Models via Self-Certainty](https://arxiv.org/abs/2502.18581.pdf)

- [Can Large Reasoning Models Self-Train?](https://arxiv.org/abs/2505.21444.pdf)

- [Unsupervised Post-Training for Multi-Modal LLM Reasoning via GRPO](https://arxiv.org/abs/2505.22453.pdf)

- [Consistent Paths Lead to Truth: Self-Rewarding Reinforcement Learning for LLM Reasoning](https://arxiv.org/abs/2506.08745.pdf)

- [SWE-Dev: Evaluating and Training Autonomous Feature-Driven Software Development](https://arxiv.org/abs/2505.16975.pdf)

- [A Self-Improving Coding Agent](https://arxiv.org/abs/2504.15228.pdf)

- [Feedback Friction: LLMs Struggle to Fully Incorporate External Feedback](https://arxiv.org/abs/2506.11930.pdf)

- [Unified Software Engineering agent as AI Software Engineer](https://arxiv.org/abs/2506.14683.pdf)

- [OTC: Optimal Tool Calls via Reinforcement Learning](https://arxiv.org/abs/2504.14870v1.pdf)

- [AutoRule: Reasoning Chain-of-thought Extracted Rule-based Rewards Improve Preference Learning](https://arxiv.org/abs/2506.15651.pdf)

- [SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2506.24119.pdf)

- [Reward Is Enough: LLMs Are In-Context Reinforcement Learners](https://arxiv.org/abs/2506.06303.pdf)

- [Generalist Reward Models: Found Inside Large Language Models](https://arxiv.org/abs/2506.23235)

#### 5.2 Imitation and Demonstration Learning

- [STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465.pdf)

- [V-STaR: Training Verifiers for Self-Taught Reasoners](https://arxiv.org/abs/2402.06457.pdf)

- [AdaSTaR: Adaptive Data Sampling for Training Self-Taught Reasoners](https://arxiv.org/abs/2505.16322.pdf)

- [Enhancing Large Vision Language Models with Self-Training on Image Comprehension](https://arxiv.org/abs/2405.19716.pdf)

- [Genixer: Empowering Multimodal Large Language Models as a Powerful Data Generator](https://arxiv.org/abs/2312.06731.pdf)

- [SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning](https://arxiv.org/abs/2502.04780.pdf)

- [Bridging the Gap: Self-Optimized Fine-Tuning for LLM-based Recommender Systems](https://arxiv.org/abs/2505.20771.pdf)

- [Recursive Introspection: Teaching Language Model Agents How to Self-Improve](https://arxiv.org/abs/2407.18219.pdf)

- [Confidence Matters: Revisiting Intrinsic Self-Correction Capabilities of Large Language Models](https://arxiv.org/abs/2402.12563.pdf)

#### 5.3 Population-based and Evolutionary Methods

- [Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954.pdf)

- [Nature-Inspired Population-Based Evolution of Large Language Models](https://arxiv.org/abs/2503.01155.pdf)

- [Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models](https://arxiv.org/abs/2401.01335)

- [SPC: Evolving Self-Play Critic via Adversarial Games for LLM Reasoning](https://arxiv.org/abs/2504.19162)

- [Language Models can Self-Improve at State-Value Estimation for Better Search](https://arxiv.org/abs/2503.02878)

- [elf-Evolving Multi-Agent Collaboration Networks for Software Development](https://arxiv.org/abs/2410.16946)

- [Multi-Agent Collaboration via Evolving Orchestration](https://arxiv.org/abs/2505.19591)

- [MDTeamGPT: A Self-Evolving LLM-based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation](https://arxiv.org/abs/2503.13856)

- [Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions](https://arxiv.org/abs/2503.22678)


### 6. Where to Evolve?

### 6.1 General Domain Evolution

- Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks

- WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning

- WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model

- MobileSteward: Integrating Multiple App‑Oriented Agents with Self‑Evolution

- Generative Agents: Interactive Simulacra of Human Behavior

- Intelligent Virtual Assistants with LLM-based Process Automation

- UI-Genie: A Self-Improving Approach for Iteratively Boosting MLLM-based Mobile GUI Agents

### 6.2 Specialized Domain Evolution

- Arxiv Copilot: A Self-Evolving and Efficient LLM System for Personalized Academic Assistance

- Richelieu: Self-Evolving LLM-Based Agents for AI Diplomacy

- AlphaEvolve: A Learning Framework to Discover Novel Alphas in Quantitative Investment

- A Self-Evolving Framework for Multi-Agent Medical Consultation Based on Large Language Models

- Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions

- LLMs Can Simulate Standardized Patients via Agent Coevolution

- SEW: Self-Evolving Agentic Workflows for Automated Code Generation

- AgentCoder: Multi-Agent-based Code Generation with Iterative Testing and Optimisation

- A Self-Improving Coding Agent

- QuantAgent: Seeking Holy Grail in Trading by Self-Improving Large Language Model

- Voyager: An Open-Ended Embodied Agent with Large Language Models

- Learning to Be A Doctor: Searching for Effective Medical Agent Architectures

- Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents 

- Simulating Classroom Education with LLM-Empowered Agents

- One Size Doesn’t Fit All: A Personalized Conversational Tutoring Agent for Mathematics Instruction 
  
### 8. Future Directions

#### 8.1 Personalize AI Agents

- How can AI agent accurately capture users' unique behavioral patterns or preferences？

- Personalize Your LLM: Fake it then Align it

- Personalization of Large Language Models: A Survey

#### 8.2 Generalization

- Scalable agent architecture & scaling vs. performance trade-off

- Position: Scaling LLM Agents Requires Asymptotic Analysis with LLM Primitives

- Safety, Alignment and Control

- Automating Safety Enhancement for LLM-based Agents with Synthetic Risk Scenarios

- TrustAgent: Towards Safe and Trustworthy LLM-based Agents

- Foundational Challenges in Assuring Alignment and Safety of Large Language Models

#### 8.3 Safe and Controllable Agents

#### 8.4 Ecosystems of Multi-Agents


### Others

- https://github.com/EvoAgentX/EvoAgentX

- https://deepmind.google/discover/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/
    - https://github.com/codelion/openevolve