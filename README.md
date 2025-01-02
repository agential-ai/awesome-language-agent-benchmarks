![](https://github.com/agential-ai/awesome-language-agent-benchmarks/blob/main/banner.png)

---

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  <img src="https://awesome.re/badge.svg" alt="Awesome">
</p>


As Large Language Models (LLMs) demonstrate strong performance in their ability to reason, plan, and make decisions, many researchers are studying how to leverage these models to perform various tasks involving these complex abilities in diverse environments, hence the term Language Agents. In a burgeoning field, language agent evaluation is being rapidly developed and challenges arise when it comes to measuring an agent's performance on diverse tasks ranging from QA, math, code, to planning, decision-making, and web navigation. Thus, it's imperative to understand the existing evaluation approaches and benchmarks!

📚 This awesome (and ongoing) repository aims to provide a comprehensive, organized list of LLM/language agent benchmarks! As a bonus, we also provide a comprehensive list of other awesome language-agent-adjacent lists. _Pull requests and issues are welcome!_ 😎

---

## Table of Contents

1. [🧠 General](#-general)
   - [LLM Benchmarks](#llm-benchmarks)
   - [Embodied](#embodied)
   - [Game-Playing](#game-playing)
   - [Multi-Task](#multi-task)
   - [Planning & Interaction](#planning--interaction)
   - [Role-Playing](#role-playing)
   - [Adversarial](#adversarial)
3. [💻 Computer Use](#-computer-use)
   - [Computer](#computer)
   - [Web](#web)
   - [Mobile](#mobile)
   - [Documents](#documents)
4. [🔨 Software Engineering](#-software-engineering)
   - [SWE](#swe)
   - [Data Science & ML](#data-science--ml)
5. [🧰 Tool-Use](#-tool-use)
6. [🔍 RAG](#-rag)
7. [🤖🤖 Multi-Agent](#-multi-agent)
8. [🗄️ Other Awesome Lists](#%EF%B8%8F-other-awesome-lists)
   - [Language Agent](#language-agent)
   - [RAG](#rag)
   - [LLM](#llm)
  

---

## 🧠 General
---

### LLM Benchmarks

Depending on the domain, some agents are tested on LLM benchmarks. So we briefly include a couple popular ones. You can find comprehensive lists of LLM benchmarks in the [🗄️ Other Awesome Lists](#%EF%B8%8F-other-awesome-lists) section!

#### QA

- Yang, Zhilin, et al. "**HotpotQA: A dataset for diverse, explainable multi-hop question answering.**" arXiv preprint arXiv:1809.09600 (2018). [[paper](https://arxiv.org/abs/1809.09600)] [[project](https://hotpotqa.github.io/)]
- Thorne, James, et al. "**FEVER: a large-scale dataset for fact extraction and VERification.**" arXiv preprint arXiv:1803.05355 (2018). [[paper](https://arxiv.org/abs/1803.05355)] [[project](https://fever.ai/)]
- Joshi, Mandar, et al. "**Triviaqa: A large scale distantly supervised challenge dataset for reading comprehension.**" arXiv preprint arXiv:1705.03551 (2017). [[paper](https://arxiv.org/abs/1705.03551)] [[project](https://nlp.cs.washington.edu/triviaqa/)]
- Min, Sewon, et al. "**AmbigQA: Answering ambiguous open-domain questions.**" arXiv preprint arXiv:2004.10645 (2020). [[paper](https://arxiv.org/abs/2004.10645)] [[project](https://nlp.cs.washington.edu/ambigqa/)]
- Hendrycks, Dan, et al. "**Measuring massive multitask language understanding.**" arXiv preprint arXiv:2009.03300 (2020). [[paper](https://arxiv.org/abs/2009.03300)] [[project](https://github.com/hendrycks/test)]


#### Math

- Cobbe, Karl, et al. "**Training verifiers to solve math word problems.**" arXiv preprint arXiv:2110.14168 (2021). [[paper](https://arxiv.org/abs/2110.14168)] [[project](https://github.com/openai/grade-school-math)]
- Patel, Arkil, Satwik Bhattamishra, and Navin Goyal. "**Are NLP models really able to solve simple math word problems?.**" arXiv preprint arXiv:2103.07191 (2021). [[paper](https://arxiv.org/abs/2103.07191)] [[project](https://github.com/arkilpatel/SVAMP)]
- Lu, Pan, et al. "**Dynamic prompt learning via policy gradient for semi-structured mathematical reasoning.**" arXiv preprint arXiv:2209.14610 (2022). [[paper](https://arxiv.org/abs/2209.14610)] [[project](https://promptpg.github.io/)]
- Hendrycks, Dan, et al. "**Measuring mathematical problem solving with the math dataset.**" arXiv preprint arXiv:2103.03874 (2021). [[paper](https://arxiv.org/abs/2103.03874)] [[project](https://github.com/hendrycks/math/)]


#### Code

- Chen, Mark, et al. "**Evaluating large language models trained on code.**" arXiv preprint arXiv:2107.03374 (2021). [[paper](https://arxiv.org/abs/2107.03374)] [[project](https://github.com/openai/human-eval)]
- Austin, Jacob, et al. "**Program synthesis with large language models.**" arXiv preprint arXiv:2108.07732 (2021). [[paper](https://arxiv.org/pdf/2108.07732)] [[project](https://github.com/google-research/google-research/tree/master/mbpp)]


### Embodied

- Shridhar, Mohit, et al. "**Alfworld: Aligning text and embodied environments for interactive learning.**" arXiv preprint arXiv:2010.03768 (2020). [[paper](https://arxiv.org/abs/2010.03768)] [[project](https://alfworld.github.io)]
- Kannan, Shyam Sundar, Vishnunandan LN Venkatesh, and Byung-Cheol Min. "**Smart-llm: Smart multi-agent robot task planning using large language models.**" arXiv preprint arXiv:2309.10062 (2023). [[paper](https://arxiv.org/abs/2309.10062)] [[project](https://github.com/SMARTlab-Purdue/SMART-LLM)]
- Chang, Matthew, et al. "**PARTNR: A Benchmark for Planning and Reasoning in Embodied Multi-agent Tasks.**" arXiv preprint arXiv:2411.00081 (2024). [[paper](https://arxiv.org/abs/2411.00081)] [[project](https://ai.meta.com/research/publications/partnr-a-benchmark-for-planning-and-reasoning-in-embodied-multi-agent-tasks/)]
- Gao, Chen, et al. "**EmbodiedCity: A Benchmark Platform for Embodied Agent in Real-world City Environment.**" arXiv preprint arXiv:2410.09604 (2024). [[paper](https://arxiv.org/abs/2410.09604)] [[project](https://embodied-city.fiblab.net)]
- Choi, Jae-Woo, et al. "**Lota-bench: Benchmarking language-oriented task planners for embodied agents.**" arXiv preprint arXiv:2402.08178 (2024). [[paper](https://arxiv.org/abs/2402.08178)] [[project](https://choi-jaewoo.github.io/LoTa-Bench/)]
- Xu, Tianqi, et al. "**CRAB: Cross-platfrom agent benchmark for multi-modal embodied language model agents.**" NeurIPS 2024 Workshop on Open-World Agents. 2024. [[paper](https://openreview.net/forum?id=kyExS4V0H7)] [[project](https://pypi.org/project/crab-framework/)]
- Zhang, Lingfeng, et al. "**ET-Plan-Bench: Embodied Task-level Planning Benchmark Towards Spatial-Temporal Cognition with Foundation Models.**" arXiv preprint arXiv:2410.14682 (2024). [[paper](https://arxiv.org/abs/2410.14682)]
- Framework, LLM Multi-Agent. "**VillagerBench: Benchmarking Multi-Agent Collaboration in Minecraft.**" [[paper](https://openreview.net/forum?id=SI94CGKCus)]


### Game-Playing

- Qian, Cheng, et al. "**EscapeBench: Pushing Language Models to Think Outside the Box.**" arXiv preprint arXiv:2412.13549 (2024). [[paper](https://arxiv.org/abs/2412.13549)] [[project](https://github.com/qiancheng0/EscapeBench)]
- Wu, Yue, et al. "**Smartplay: A benchmark for llms as intelligent agents.**" arXiv preprint arXiv:2310.01557 (2023). [[paper](https://arxiv.org/abs/2310.01557)]
- Gioacchini, Luca, et al. "**AgentQuest: A Modular Benchmark Framework to Measure Progress and Improve LLM Agents.**" arXiv preprint arXiv:2404.06411 (2024). [[paper](https://arxiv.org/abs/2404.06411)] [[project](https://github.com/nec-research/agentquest)]
- Liu, Xiao, et al. "**Agentbench: Evaluating llms as agents.**" arXiv preprint arXiv:2308.03688 (2023). [[paper](https://arxiv.org/abs/2308.03688)] [[project](https://github.com/THUDM/AgentBench)]
- Liu, Xiao, et al. "**Visualagentbench: Towards large multimodal models as visual foundation agents.**" arXiv preprint arXiv:2408.06327 (2024). [[paper](https://arxiv.org/abs/2408.06327)] [[project](https://github.com/THUDM/VisualAgentBench)]
- Ma, Chang, et al. "**AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents.**" arXiv preprint arXiv:2401.13178 (2024). [[paper](https://arxiv.org/abs/2401.13178)] [[project](https://hkust-nlp.github.io/agentboard/)]


### Multi-Task

- Yin, Guoli, et al. "**MMAU: A Holistic Benchmark of Agent Capabilities Across Diverse Domains.**" arXiv preprint arXiv:2407.18961 (2024). [[paper](https://arxiv.org/abs/2407.18961)] [[project](https://github.com/apple/axlearn/tree/main/docs/research/mmau)]
- Liu, Zhiwei, et al. "**Bolaa: Benchmarking and orchestrating llm-augmented autonomous agents.**" arXiv preprint arXiv:2308.05960 (2023). [[paper](https://arxiv.org/abs/2308.05960)] [[project](https://github.com/salesforce/BOLAA)]
- Mialon, Grégoire, et al. "**Gaia: a benchmark for general ai assistants.**" arXiv preprint arXiv:2311.12983 (2023). [[paper](https://arxiv.org/abs/2311.12983)] [[project](https://huggingface.co/gaia-benchmark)]
- Wang, Wei, et al. "**BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities of Language Models in Multi-Agent Systems.**" arXiv preprint arXiv:2408.15971 (2024). [[paper](https://arxiv.org/abs/2408.15971)] [[project](https://github.com/THUDM/BattleAgentBench)]
- Li, Youquan, et al. "**FB-Bench: A Fine-Grained Multi-Task Benchmark for Evaluating LLMs' Responsiveness to Human Feedback.**" arXiv preprint arXiv:2410.09412 (2024). [[paper](https://arxiv.org/abs/2410.09412)]
- Shen, Yongliang, et al. "**Taskbench: Benchmarking large language models for task automation.**" arXiv preprint arXiv:2311.18760 (2023). [[paper](https://arxiv.org/abs/2311.18760)] [[project](https://huggingface.co/datasets/microsoft/Taskbench)]


### Planning & Interaction

- Valmeekam, Karthik, et al. "**Planbench: An extensible benchmark for evaluating large language models on planning and reasoning about change.**" Advances in Neural Information Processing Systems 36 (2024). [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7a92bcdede88c7afd108072faf5485c8-Abstract-Datasets_and_Benchmarks.html)] [[project](https://github.com/karthikv792/LLMs-Planning)]
- Xiao, Ruixuan, et al. "**Flowbench: Revisiting and benchmarking workflow-guided planning for llm-based agents.**" arXiv preprint arXiv:2406.14884 (2024). [[paper](https://arxiv.org/abs/2406.14884)]
- Xie, Jian, et al. "**Travelplanner: A benchmark for real-world planning with language agents.**" arXiv preprint arXiv:2402.01622 (2024). [[paper](https://arxiv.org/abs/2402.01622)] [[project](https://osu-nlp-group.github.io/TravelPlanner/)]
- Cheng, Ching-An, et al. "**Llf-bench: Benchmark for interactive learning from language feedback.**" arXiv preprint arXiv:2312.06853 (2023). [[paper](https://arxiv.org/abs/2312.06853)] [[project](https://github.com/microsoft/LLF-Bench)]
- Wu, Cheng-Kuang, et al. "**StreamBench: Towards Benchmarking Continuous Improvement of Language Agents.**" arXiv preprint arXiv:2406.08747 (2024). [[paper](https://arxiv.org/abs/2406.08747)] [[project](https://github.com/stream-bench/stream-bench)]


### Role-Playing

- Tu, Quan, et al. "**Charactereval: A chinese benchmark for role-playing conversational agent evaluation.**" arXiv preprint arXiv:2401.01275 (2024). [[paper](https://arxiv.org/abs/2401.01275)] [[project](https://github.com/morecry/CharacterEval)]
- Wang, Zekun Moore, et al. "**Rolellm: Benchmarking, eliciting, and enhancing role-playing abilities of large language models.**" arXiv preprint arXiv:2310.00746 (2023). [[paper](https://arxiv.org/abs/2310.00746)] [[project](https://github.com/InteractiveNLP-Team/RoleLLM-public)]
- Chen, Hongzhan, et al. "**RoleInteract: Evaluating the Social Interaction of Role-Playing Agents.**" arXiv preprint arXiv:2403.13679 (2024). [[paper](https://arxiv.org/abs/2403.13679)] [[project](https://github.com/InteractiveNLP-Team/RoleLLM-public)]
- Liu, Jiaheng, et al. "**RoleAgent: Building, Interacting, and Benchmarking High-quality Role-Playing Agents from Scripts.**" The Thirty-eight Conference on Neural Information Processing Systems Datasets and Benchmarks Track. [[paper](https://openreview.net/forum?id=hORTHzt2cE#discussion)]
- Yan, Ming, et al. "**Larp: Language-agent role play for open-world games.**" arXiv preprint arXiv:2312.17653 (2023). [[paper](https://arxiv.org/abs/2312.17653)] 


### Adversarial

- Debenedetti, Edoardo, et al. "**AgentDojo: A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents.**" arXiv preprint arXiv:2406.13352 (2024). [[paper](https://arxiv.org/abs/2406.13352)] [[project](https://github.com/ethz-spylab/agentdojo)]
- Zhang, Hanrong, et al. "**Agent security bench (asb): Formalizing and benchmarking attacks and defenses in llm-based agents.**" arXiv preprint arXiv:2410.02644 (2024). [[paper](https://arxiv.org/abs/2410.02644)] [[project](https://github.com/agiresearch/ASB)]
- Andriushchenko, Maksym, et al. "**Agentharm: A benchmark for measuring harmfulness of llm agents.**" arXiv preprint arXiv:2410.09024 (2024). [[paper](https://arxiv.org/abs/2410.09024)] [[project](https://huggingface.co/datasets/ai-safety-institute/AgentHarm)]
- Yin, Sheng, et al. "**SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents.**" arXiv preprint arXiv:2412.13178 (2024). [[paper](https://arxiv.org/abs/2412.13178)] [[project](https://huggingface.co/datasets/ai-safety-institute/AgentHarm)]
- Yuan, Tongxin, et al. "**R-judge: Benchmarking safety risk awareness for llm agents.**" arXiv preprint arXiv:2401.10019 (2024). [[paper](https://arxiv.org/abs/2401.10019)] [[project](https://rjudgebench.github.io)]
- BENCHMARK, JUDGE. "**JAILJUDGE: AComprehensive JAILBREAK JUDGE BENCHMARK WITH MULTI-AGENT ENHANCED EXPLANATION EVALUATION FRAMEWORK.**" [[paper](https://openreview.net/forum?id=cLYvhd0pDY)] [[project](https://github.com/usail-hkust/Jailjudge/)]


## 💻 Computer Use
---

### Computer

- Kapoor, Raghav, et al. "**OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web.**" European Conference on Computer Vision. Springer, Cham, 2025. [[paper](https://arxiv.org/abs/2402.17553)]
- Xu, Tianqi, et al. "**Crab: Cross-environment agent benchmark for multimodal language model agents.**" arXiv preprint arXiv:2407.01511 (2024). [[paper](https://arxiv.org/abs/2407.01511)] [[project](https://github.com/camel-ai/crab)]
- Xie, Tianbao, et al. "**Osworld: Benchmarking multimodal agents for open-ended tasks in real computer environments.**" arXiv preprint arXiv:2404.07972 (2024). [[paper](https://arxiv.org/abs/2404.07972)] [[project](https://os-world.github.io)]
- Bonatti, Rogerio, et al. "**Windows agent arena: Evaluating multi-modal os agents at scale.**" arXiv preprint arXiv:2409.08264 (2024). [[paper](https://arxiv.org/abs/2409.08264)] [[project](https://microsoft.github.io/WindowsAgentArena/)]
- Wang, Zilong, et al. "**Officebench: Benchmarking language agents across multiple applications for office automation.**" arXiv preprint arXiv:2407.19056 (2024). [[paper](https://arxiv.org/abs/2407.19056)]
- Styles, Olly, et al. "**WorkBench: a Benchmark Dataset for Agents in a Realistic Workplace Setting.**" arXiv preprint arXiv:2405.00823 (2024). [[paper](https://arxiv.org/abs/2405.00823)]
- Drouin, Alexandre, et al. "**WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?.**" arXiv preprint arXiv:2403.07718 (2024). [[paper](https://arxiv.org/abs/2403.07718)] [[project](https://github.com/ServiceNow/WorkArena)]
- Humphreys, Peter C., et al. "**A data-driven approach for learning to control computers.**" International Conference on Machine Learning. PMLR, 2022. [[paper](https://arxiv.org/pdf/2202.08137)]
- Gao, Difei, et al. "**Assistgui: Task-oriented desktop graphical user interface automation.**" arXiv preprint arXiv:2312.13108 (2023). [[paper](https://arxiv.org/abs/2312.13108)] [[project](https://showlab.github.io/assistgui/)]


### Web

- Zhang, Ziniu, et al. "**MMInA: Benchmarking Multihop Multimodal Internet Agents.**" arXiv preprint arXiv:2404.09992 (2024). [[paper](https://arxiv.org/abs/2404.09992)] [[project](https://mmina.cliangyu.com/)]
- Zhou, Shuyan, et al. "**Webarena: A realistic web environment for building autonomous agents.**" arXiv preprint arXiv:2307.13854 (2023). [[paper](https://arxiv.org/abs/2307.13854)] [[project](https://webarena.dev)]
- Koh, Jing Yu, et al. "**Visualwebarena: Evaluating multimodal agents on realistic visual web tasks.**" arXiv preprint arXiv:2401.13649 (2024). [[paper](https://arxiv.org/abs/2401.13649)] [[project](https://jykoh.com/vwa)]
- Yoran, Ori, et al. "**AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?.**" arXiv preprint arXiv:2407.15711 (2024). [[paper](https://arxiv.org/abs/2407.15711)] [[project](https://assistantbench.github.io)]
- Jang, Lawrence, et al. "**Videowebarena: Evaluating long context multimodal agents with video understanding web tasks.**" arXiv preprint arXiv:2410.19100 (2024). [[paper](https://arxiv.org/abs/2410.19100)]
- Xu, Frank F., et al. “**Theagentcompany: Benchmarking LLM Agents on Consequential Real World Tasks.**” arXiv.Org, 18 Dec. 2024, arxiv.org/abs/2412.14161. [[paper](https://arxiv.org/abs/2412.14161)] [[project](https://github.com/TheAgentCompany/TheAgentCompany)]
- Xu, Kevin, et al. "**Tur [k] ingbench: A challenge benchmark for web agents.**" arXiv preprint arXiv:2403.11905 (2024). [[paper](https://arxiv.org/abs/2403.11905)] [[project](https://github.com/JHU-CLSP/turking-bench)]
- Yao, Shunyu, et al. "**Webshop: Towards scalable real-world web interaction with grounded language agents.**" Advances in Neural Information Processing Systems 35 (2022): 20744-20757. [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/82ad13ec01f9fe44c01cb91814fd7b8c-Abstract-Conference.html)] [[project](https://webshop-pnlp.github.io)]
- Lin, Kevin Qinghong, et al. "**VideoGUI: A Benchmark for GUI Automation from Instructional Videos.**" arXiv preprint arXiv:2406.10227 (2024). [[paper](https://showlab.github.io/videogui/assets/preprint.pdf)] [[project](https://showlab.github.io/videogui/)]
- Deng, Xiang, et al. "**Mind2web: Towards a generalist agent for the web.**" Advances in Neural Information Processing Systems 36 (2024). [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5950bf290a1570ea401bf98882128160-Abstract-Datasets_and_Benchmarks.html)] [[project](https://osu-nlp-group.github.io/Mind2Web/)]
- Shi, Tianlin, et al. "**World of bits: An open-domain platform for web-based agents.**" International Conference on Machine Learning. PMLR, 2017. [[paper](https://proceedings.mlr.press/v70/shi17a)]
  

### Mobile

- Deng, Shihan, et al. "**Mobile-bench: An evaluation benchmark for llm-based mobile agents.**" arXiv preprint arXiv:2407.00993 (2024). [[paper](https://arxiv.org/abs/2407.00993)]
- Rawles, Christopher, et al. "**AndroidWorld: A dynamic benchmarking environment for autonomous agents.**" arXiv preprint arXiv:2405.14573 (2024). [[paper](https://arxiv.org/abs/2405.14573)] [[project](https://google-research.github.io/android_world/)]
- Zhang, Danyang, et al. "**Mobile-Env: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction.**" arXiv preprint arXiv:2305.08144 (2023). [[paper](https://rhythmcao.github.io/publication/2024-mobile-env/2024-mobile-env.pdf)] [[project](https://github.com/X-LANCE/Mobile-Env)]
- Lee, Juyong, et al. "**Benchmarking Mobile Device Control Agents across Diverse Configurations.**" arXiv preprint arXiv:2404.16660 (2024). [[paper](https://arxiv.org/abs/2404.16660)] [[project](https://b-moca.github.io)]
- Wang, Luyuan, et al. "**MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents.**" arXiv preprint arXiv:2406.08184 (2024). [[paper](https://arxiv.org/abs/2406.08184)] [[project](https://mobileagentbench.github.io)]
- Trivedi, Harsh, et al. "**Appworld: A controllable world of apps and people for benchmarking interactive coding agents.**" arXiv preprint arXiv:2407.18901 (2024). [[paper](https://arxiv.org/abs/2407.18901)] [[project](https://github.com/StonyBrookNLP/appworld)]
- Sun, Liangtai, et al. "**Meta-gui: Towards multi-modal conversational agents on mobile gui.**" arXiv preprint arXiv:2205.11029 (2022). [[paper](https://arxiv.org/abs/2205.11029)] [[project](https://x-lance.github.io/META-GUI-Leaderboard/)]
- Wang, Junyang, et al. "**Mobile-agent: Autonomous multi-modal mobile device agent with visual perception.**" arXiv preprint arXiv:2401.16158 (2024). [[paper](https://arxiv.org/abs/2401.16158)]
- Zhang, Chi, et al. "**Appagent: Multimodal agents as smartphone users.**" arXiv preprint arXiv:2312.13771 (2023). [[paper](https://arxiv.org/abs/2312.13771)] [[project](https://appagent-official.github.io/)]
- Zhang, Danyang, Lu Chen, and Kai Yu. "**Zhang, Danyang, et al. "Mobile-env: an evaluation platform and benchmark for LLM-GUI interaction." arXiv preprint arXiv:2305.08144 (2023).**" arXiv preprint arXiv:2305.08144 (2023). [[paper](https://arxiv.org/html/2305.08144v3)]


### Documents

- Rodriguez, Juan, et al. "**BigDocs: An Open and Permissively-Licensed Dataset for Training Multimodal Models on Document and Code Tasks.**" arXiv preprint arXiv:2412.04626 (2024). [[paper](https://arxiv.org/abs/2412.04626)] [[project](https://openreview.net/forum?id=b1ivBPLb1n)]
- Zou, Anni, et al. "**DOCBENCH: A Benchmark for Evaluating LLM-based Document Reading Systems.**" arXiv preprint arXiv:2407.10701 (2024). [[paper](https://arxiv.org/abs/2407.10701)] [[project](https://github.com/Anni-Zou/DocBench)]


## 🔨 Software Engineering
---

### SWE

- Carlos E. Jimenez, John Yang, et al. "**SWE-bench: Can Language Models Resolve Real-World GitHub Issues?**" arXiv preprint arXiv:2310.06770 (2023). [[paper](https://arxiv.org/abs/2310.06770)] [[project](https://github.com/swe-bench/SWE-bench)]
- Aleithan, Reem, et al. "**SWE-Bench+: Enhanced Coding Benchmark for LLMs.**" arXiv preprint arXiv:2410.06992 (2024). [[paper](https://arxiv.org/abs/2410.06992)] [[project](https://www.swebench.com/index.html)]
- Zan, Daoguang, et al. "**Swe-bench-java: A github issue resolving benchmark for java.**" arXiv preprint arXiv:2408.14354 (2024). [[paper](https://arxiv.org/abs/2408.14354)] [[project](https://github.com/multi-swe-bench/multi-swe-bench-env)]
- Yang, John, et al. "**SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?.**" arXiv preprint arXiv:2410.03859 (2024). [[paper](https://arxiv.org/abs/2410.03859)] [[project](https://www.swebench.com/multimodal)]
- Gu, Alex, et al. "**Cruxeval: A benchmark for code reasoning, understanding and execution.**" arXiv preprint arXiv:2401.03065 (2024). [[paper](https://arxiv.org/abs/2401.03065)] [[project](https://github.com/facebookresearch/cruxeval)]
- Siegel, Zachary S., et al. "**CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark.**" arXiv preprint arXiv:2409.11363 (2024). [[paper](https://arxiv.org/abs/2409.11363)] [[project](https://github.com/siegelz/core-bench?tab=readme-ov-file)]
- Guo, Chengquan, et al. "**RedCode: Risky Code Execution and Generation Benchmark for Code Agents.**" arXiv preprint arXiv:2411.07781 (2024). [[paper](https://arxiv.org/abs/2411.07781)] [[project](https://github.com/AI-secure/RedCode)]
- Zhuo, Terry Yue, et al. "**Bigcodebench: Benchmarking code generation with diverse function calls and complex instructions.**" arXiv preprint arXiv:2406.15877 (2024). [[paper](https://arxiv.org/abs/2406.15877)] [[project](https://github.com/bigcode-project/bigcodebench)]
- Zhang, Yaolun, et al. "**PyBench: Evaluating LLM Agent on various real-world coding tasks.**" arXiv preprint arXiv:2407.16732 (2024). [[paper](https://arxiv.org/abs/2407.16732)]
- Yang, John, et al. "**Intercode: Standardizing and benchmarking interactive coding with execution feedback.**" Advances in Neural Information Processing Systems 36 (2024). [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4b175d846fb008d540d233c188379ff9-Abstract-Datasets_and_Benchmarks.html)] [[project](https://intercode-benchmark.github.io/)]
- Li, Bowen, et al. "**Devbench: A comprehensive benchmark for software development.**" arXiv preprint arXiv:2403.08604 (2024). [[paper](https://arxiv.org/abs/2403.08604)] [[project](https://github.com/open-compass/DevEval)]
- Si, Chenglei, et al. "**Design2Code: How Far Are We From Automating Front-End Engineering?.**" arXiv preprint arXiv:2403.03163 (2024). [[paper](https://arxiv.org/abs/2403.03163)] [[project](https://salt-nlp.github.io/Design2Code/)]
- Wang, Xingyao, et al. "**Mint: Evaluating llms in multi-turn interaction with tools and language feedback.**" arXiv preprint arXiv:2309.10691 (2023). [[paper](https://arxiv.org/abs/2309.10691)] [[project](https://xwang.dev/mint-bench/)]

### Data Science & ML

- Zhang, Yuge, et al. "**Benchmarking Data Science Agents.**" arXiv preprint arXiv:2402.17168 (2024). [[paper](https://arxiv.org/abs/2402.17168)] [[project](https://github.com/MetaCopilot/dseval)]
- Gu, Ken, et al. "**Blade: Benchmarking language model agents for data-driven science.**" arXiv preprint arXiv:2408.09667 (2024). [[paper](https://arxiv.org/abs/2408.09667)] [[project](https://github.com/behavioral-data/BLADE)]
- Zhang, Dan, et al. "**DataSciBench: An LLM Agent Benchmark for Data Science.**" [[paper](https://openreview.net/forum?id=BltaWJZMeR)]
- Huang, Yiming, et al. "**DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models.**" arXiv preprint arXiv:2410.07331 (2024). [[paper](https://arxiv.org/abs/2410.07331)] [[project](https://da-code-bench.github.io/)]
- Hu, Xueyu, et al. "**Infiagent-dabench: Evaluating agents on data analysis tasks.**" arXiv preprint arXiv:2401.05507 (2024). [[paper](https://arxiv.org/abs/2401.05507)] [[project](https://github.com/InfiAgent/InfiAgent)]
- Chan, Jun Shern, et al. "**Mle-bench: Evaluating machine learning agents on machine learning engineering.**" arXiv preprint arXiv:2410.07095 (2024). [[paper](https://arxiv.org/abs/2410.07095)] [[project](https://github.com/openai/mle-bench)]
- Chen, Ziru, et al. "**Scienceagentbench: Toward rigorous assessment of language agents for data-driven scientific discovery.**" arXiv preprint arXiv:2410.05080 (2024). [[paper](https://arxiv.org/abs/2410.05080)] [[project](https://osu-nlp-group.github.io/ScienceAgentBench/)]
- Jansen, Peter, et al. "**DISCOVERYWORLD: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents.**" arXiv preprint arXiv:2406.06769 (2024). [[paper](https://arxiv.org/abs/2406.06769)] [[project](https://github.com/allenai/discoveryworld)]
- Huang, Qian, et al. "**Benchmarking large language models as ai research agents.**" NeurIPS 2023 Foundation Models for Decision Making Workshop. 2023. [[paper](https://openreview.net/forum?id=kXlTY0BmK3)] [[project](https://github.com/snap-stanford/MLAgentBench)]
- Majumder, Bodhisattwa Prasad, et al. "**Discoverybench: Towards data-driven discovery with large language models.**" arXiv preprint arXiv:2407.01725 (2024). [[paper]([https://arxiv.org/abs/2402.17168](https://arxiv.org/abs/2407.01725))] [[project](https://github.com/allenai/discoverybench)]

## 🧰 Tool-Use
---

- Zhuang, Yuchen, et al. "**Toolqa: A dataset for llm question answering with external tools.**" Advances in Neural Information Processing Systems 36 (2023): 50117-50143. [[paper](https://arxiv.org/abs/2306.13304)] [[project](https://github.com/night-chen/ToolQA)]
- Patil, Shishir G., et al. "**Gorilla: Large language model connected with massive apis.**" arXiv preprint arXiv:2305.15334 (2023). [[paper](https://arxiv.org/pdf/2305.15334)] [[project](https://gorilla.cs.berkeley.edu/)]
- Wang, Jize, et al. "**GTA: A Benchmark for General Tool Agents.**" arXiv preprint arXiv:2407.08713 (2024). [[paper](https://arxiv.org/abs/2407.08713)] [[project](https://github.com/open-compass/GTA)]
- Yao, Shunyu, et al. "**$\tau $-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains.**" arXiv preprint arXiv:2406.12045 (2024). [[paper](https://arxiv.org/abs/2406.12045)] [[project](https://github.com/sierra-research/tau-bench)]
- Lu, Jiarui, et al. "**Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities.**" arXiv preprint arXiv:2408.04682 (2024). [[paper](https://arxiv.org/abs/2408.04682)] [[project](https://github.com/apple/ToolSandbox)]
- Chen, Zehui, et al. "**T-Eval: Evaluating the Tool Utilization Capability of Large Language Models Step by Step.**" arXiv preprint arXiv:2312.14033 (2023). [[paper](https://arxiv.org/abs/2312.14033)] [[project](https://github.com/open-compass/T-Eval)]
- Wu, Mengsong, et al. "**Seal-tools: Self-instruct tool learning dataset for agent tuning and detailed benchmark.**" CCF International Conference on Natural Language Processing and Chinese Computing. Singapore: Springer Nature Singapore, 2024. [[paper](https://link.springer.com/chapter/10.1007/978-981-97-9434-8_29)] [[project](https://github.com/fairyshine/Seal-Tools)]
- Guo, Zishan, Yufei Huang, and Deyi Xiong. "**Ctooleval: A chinese benchmark for llm-powered agent evaluation in real-world API interactions.**" Findings of the Association for Computational Linguistics ACL 2024. 2024. [[paper](https://aclanthology.org/2024.findings-acl.928/)] [[project](https://github.com/tjunlp-lab/CToolEval)]
- Li, Minghao, et al. "**Api-bank: A comprehensive benchmark for tool-augmented llms.**" arXiv preprint arXiv:2304.08244 (2023). [[paper](https://arxiv.org/abs/2304.08244)] [[project](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank)]

## 🔍 RAG
---

- Yang, Xiao, et al. "**CRAG--Comprehensive RAG Benchmark.**" arXiv preprint arXiv:2406.04744 (2024). [[paper](https://arxiv.org/abs/2406.04744)] [[project](https://github.com/facebookresearch/CRAG/)]
- Wang, Shuting, et al. "**OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in Financial Domain.**" arXiv preprint arXiv:2412.13018 (2024). [[paper](https://arxiv.org/abs/2412.13018)] [[project](https://github.com/RUC-NLPIR/OmniEval)]
- Lyu, Yuanjie, et al. "**Crud-rag: A comprehensive chinese benchmark for retrieval-augmented generation of large language models.**" ACM Transactions on Information Systems (2024). [[paper](https://dl.acm.org/doi/abs/10.1145/3701228)] [[project](https://github.com/IAAR-Shanghai/CRUD_RAG)]
- Pipitone, Nicholas, and Ghita Houir Alami. "**LegalBench-RAG: A Benchmark for Retrieval-Augmented Generation in the Legal Domain.**" arXiv preprint arXiv:2408.10343 (2024). [[paper](https://arxiv.org/abs/2408.10343)] [[project](https://github.com/ZeroEntropy-AI/legalbenchrag)]
- Kuzman, Taja, et al. "**PandaChat-RAG: Towards the Benchmark for Slovenian RAG Applications.**" (2024).[[paper](https://is.ijs.si/wp-content/uploads/2024/10/SCAI_2024_paper_0538.pdf)] [[project](https://github.com/TajaKuzman/pandachat-rag-benchmark)]

## 🤖🤖 Multi-Agent
---

- Ossowski, Timothy, et al. "**COMMA: A Communicative Multimodal Multi-Agent Benchmark.**" arXiv preprint arXiv:2410.07553 (2024). [[paper](https://arxiv.org/abs/2410.07553)]
- Xu, Lin, et al. "**MAgIC: Benchmarking Large Language Model Powered Multi-Agent in Cognition, Adaptability, Rationality and Collaboration.**" arXiv preprint arXiv:2311.08562 (2023). [[paper](https://arxiv.org/abs/2311.08562)] [[project](https://zhiyuanhubj.github.io/MAgIC/)]

## 🗄️ Other Awesome Lists

### Language Agent

- https://github.com/Paitesanshi/LLM-Agent-Survey
- https://github.com/git-disl/awesome-LLM-game-agent-papers
- https://github.com/woooodyy/llm-agent-paper-list
- https://github.com/ysymyth/awesome-language-agents
- https://github.com/AGI-Edgerunners/LLM-Agents-Papers
- https://github.com/zjunlp/LLMAgentPapers
- https://github.com/hyp1231/awesome-llm-powered-agent
- https://github.com/AGI-Edgerunners/LLM-Planning-Papers
- https://github.com/taichengguo/LLM_MultiAgents_Survey_Papers
- https://github.com/ysymyth/awesome-language-agents
- https://github.com/kaushikb11/awesome-llm-agents
- https://github.com/e2b-dev/awesome-ai-agents
- https://github.com/kyrolabs/awesome-agents

### RAG

- https://github.com/jxzhangjhu/Awesome-LLM-RAG
- https://github.com/frutik/Awesome-RAG
- https://github.com/hymie122/RAG-Survey

### LLM

- https://github.com/Hannibal046/Awesome-LLM
- https://github.com/Shubhamsaboo/awesome-llm-apps
- https://github.com/shure-dev/Awesome-LLM-Papers-Comprehensive-Topics
- https://github.com/HqWu-HITCS/Awesome-Chinese-LLM
- https://github.com/tensorchord/Awesome-LLMOps
- https://github.com/hijkzzz/Awesome-LLM-Strawberry
- https://github.com/WangRongsheng/awesome-LLM-resourses
- https://github.com/GT-RIPL/Awesome-LLM-Robotics
- https://github.com/DefTruth/Awesome-LLM-Inference
- https://github.com/luban-agi/Awesome-Domain-LLM
- https://github.com/WLiK/LLM4Rec-Awesome-Papers
- https://github.com/RManLuo/Awesome-LLM-KG
- https://github.com/jackaduma/awesome_LLMs_interview_notes
- https://github.com/XiaoxinHe/Awesome-Graph-LLM
- https://github.com/fr0gger/Awesome-GPT-Agents
- https://github.com/atfortes/Awesome-LLM-Reasoning
- https://github.com/codefuse-ai/Awesome-Code-LLM
- https://github.com/JShollaj/awesome-llm-interpretability
- https://github.com/lmmlzn/Awesome-LLMs-Datasets
- https://github.com/horseee/Awesome-Efficient-LLM
- https://github.com/corca-ai/awesome-llm-security
- https://github.com/HuangOwen/Awesome-LLM-Compression
