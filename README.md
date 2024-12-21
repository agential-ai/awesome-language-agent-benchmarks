# Awesome Language Agent Benchmarks

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

As Large Language Models (LLMs) demonstrate strong performance in their ability to reason, plan, and make decisions, many researchers are studying how to leverage these models to perform various tasks in diverse environments, hence the term Language Agents.

📚 This repository is an awesome and ongoing list of benchmarks for LLM/language agents. This repository's purpose is to provide a comprehensive, organized list of these benchmarks. _Pull requests and issues are welcome!_ 😎

---

## Table of Contents

1. [🧠 General](#-general)
   - [Embodied](#embodied)
   - [Game-Playing](#game-playing)
   - [Multi-Task](#multi-task)
   - [Planning & Interaction](#planning--interaction)
   - [Role-Playing](#role-playing)
   - [Adversarial](#adversarial)
2. [💻 Computer Use](#-computer-use)
   - [Computer](#computer)
   - [Web](#web)
   - [Mobile](#mobile)
   - [Documents](#documents)
3. [🔨 Software Engineering](#-software-engineering)
   - [SWE](#swe)
   - [Data Science & ML](#data-science--ml)
4. [🧰 Tool-Use](#-tool-use)
5. [🔍 RAG](#-rag)
6. [🤖🤖 Multi-Agent](#-multi-agent)
7. [🗄️ Other Awesome Lists](#%EF%B8%8F-other-awesome-lists)

---

## 🧠 General
---

### Embodied

- Shridhar, Mohit, et al. "Alfworld: Aligning text and embodied environments for interactive learning." arXiv preprint arXiv:2010.03768 (2020). [[paper](https://arxiv.org/abs/2010.03768)] [[project](https://alfworld.github.io)]
- Kannan, Shyam Sundar, Vishnunandan LN Venkatesh, and Byung-Cheol Min. "Smart-llm: Smart multi-agent robot task planning using large language models." arXiv preprint arXiv:2309.10062 (2023). [[paper](https://arxiv.org/abs/2309.10062)] [[project](https://github.com/SMARTlab-Purdue/SMART-LLM)]

### Game-Playing

- Wu, Yue, et al. "Smartplay: A benchmark for llms as intelligent agents." arXiv preprint arXiv:2310.01557 (2023). [[paper](https://arxiv.org/abs/2310.01557)]
- Gioacchini, Luca, et al. "AgentQuest: A Modular Benchmark Framework to Measure Progress and Improve LLM Agents." arXiv preprint arXiv:2404.06411 (2024). [[paper](https://arxiv.org/abs/2404.06411)] [[project](https://github.com/nec-research/agentquest)]
- Liu, Xiao, et al. "Agentbench: Evaluating llms as agents." arXiv preprint arXiv:2308.03688 (2023). [[paper](https://arxiv.org/abs/2308.03688)] [[project](https://github.com/THUDM/AgentBench)]
- Liu, Xiao, et al. "Visualagentbench: Towards large multimodal models as visual foundation agents." arXiv preprint arXiv:2408.06327 (2024). [[paper](https://arxiv.org/abs/2408.06327)] [[project](https://github.com/THUDM/VisualAgentBench)]

### Multi-Task

- Yin, Guoli, et al. "MMAU: A Holistic Benchmark of Agent Capabilities Across Diverse Domains." arXiv preprint arXiv:2407.18961 (2024). [[paper](https://arxiv.org/abs/2407.18961)] [[project](https://github.com/apple/axlearn/tree/main/docs/research/mmau)]

### Planning & Interaction

- Valmeekam, Karthik, et al. "Planbench: An extensible benchmark for evaluating large language models on planning and reasoning about change." Advances in Neural Information Processing Systems 36 (2024). [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7a92bcdede88c7afd108072faf5485c8-Abstract-Datasets_and_Benchmarks.html)] [[project](https://github.com/karthikv792/LLMs-Planning)]
- Xiao, Ruixuan, et al. "Flowbench: Revisiting and benchmarking workflow-guided planning for llm-based agents." arXiv preprint arXiv:2406.14884 (2024). [[paper](https://arxiv.org/abs/2406.14884)]
- Xie, Jian, et al. "Travelplanner: A benchmark for real-world planning with language agents." arXiv preprint arXiv:2402.01622 (2024). [[paper](https://arxiv.org/abs/2402.01622)] [[project](https://osu-nlp-group.github.io/TravelPlanner/)]
- Cheng, Ching-An, et al. "Llf-bench: Benchmark for interactive learning from language feedback." arXiv preprint arXiv:2312.06853 (2023). [[paper](https://arxiv.org/abs/2312.06853)] [[project](https://github.com/microsoft/LLF-Bench)]
- Wu, Cheng-Kuang, et al. "StreamBench: Towards Benchmarking Continuous Improvement of Language Agents." arXiv preprint arXiv:2406.08747 (2024). [[paper](https://arxiv.org/abs/2406.08747)] [[project](https://github.com/stream-bench/stream-bench)]

### Role-Playing

- Tu, Quan, et al. "Charactereval: A chinese benchmark for role-playing conversational agent evaluation." arXiv preprint arXiv:2401.01275 (2024). [[paper](https://arxiv.org/abs/2401.01275)] [[project](https://github.com/morecry/CharacterEval)]


### Adversarial

- Debenedetti, Edoardo, et al. "AgentDojo: A Dynamic Environment to Evaluate Attacks and Defenses for LLM Agents." arXiv preprint arXiv:2406.13352 (2024). [[paper](https://arxiv.org/abs/2406.13352)] [[project](https://github.com/ethz-spylab/agentdojo)]


## 💻 Computer Use
---

### Computer

- Xu, Tianqi, et al. "Crab: Cross-environment agent benchmark for multimodal language model agents." arXiv preprint arXiv:2407.01511 (2024). [[paper](https://arxiv.org/abs/2407.01511)] [[project](https://github.com/camel-ai/crab)]
- Xie, Tianbao, et al. "Osworld: Benchmarking multimodal agents for open-ended tasks in real computer environments." arXiv preprint arXiv:2404.07972 (2024). [[paper](https://arxiv.org/abs/2404.07972)] [[project](https://os-world.github.io)]
- Bonatti, Rogerio, et al. "Windows agent arena: Evaluating multi-modal os agents at scale." arXiv preprint arXiv:2409.08264 (2024). [[paper](https://arxiv.org/abs/2409.08264)] [[project](https://microsoft.github.io/WindowsAgentArena/)]
- Wang, Zilong, et al. "Officebench: Benchmarking language agents across multiple applications for office automation." arXiv preprint arXiv:2407.19056 (2024). [[paper](https://arxiv.org/abs/2407.19056)]
- Styles, Olly, et al. "WorkBench: a Benchmark Dataset for Agents in a Realistic Workplace Setting." arXiv preprint arXiv:2405.00823 (2024). [[paper](https://arxiv.org/abs/2405.00823)]
- Drouin, Alexandre, et al. "WorkArena: How Capable are Web Agents at Solving Common Knowledge Work Tasks?." arXiv preprint arXiv:2403.07718 (2024). [[paper](https://arxiv.org/abs/2403.07718)] [[project](https://github.com/ServiceNow/WorkArena)]
- Humphreys, Peter C., et al. "A data-driven approach for learning to control computers." International Conference on Machine Learning. PMLR, 2022. [[paper](https://arxiv.org/pdf/2202.08137)]



### Web

- Zhou, Shuyan, et al. "Webarena: A realistic web environment for building autonomous agents." arXiv preprint arXiv:2307.13854 (2023). [[paper](https://arxiv.org/abs/2307.13854)] [[project](https://webarena.dev)]
- Koh, Jing Yu, et al. "Visualwebarena: Evaluating multimodal agents on realistic visual web tasks." arXiv preprint arXiv:2401.13649 (2024). [[paper](https://arxiv.org/abs/2401.13649)] [[project](https://jykoh.com/vwa)]
- Yoran, Ori, et al. "AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?." arXiv preprint arXiv:2407.15711 (2024). [[paper](https://arxiv.org/abs/2407.15711)] [[project](https://assistantbench.github.io)]
- Jang, Lawrence, et al. "Videowebarena: Evaluating long context multimodal agents with video understanding web tasks." arXiv preprint arXiv:2410.19100 (2024). [[paper](https://arxiv.org/abs/2410.19100)]
- Xu, Frank F., et al. “Theagentcompany: Benchmarking LLM Agents on Consequential Real World Tasks.” arXiv.Org, 18 Dec. 2024, arxiv.org/abs/2412.14161. [[paper](https://arxiv.org/abs/2412.14161)] [[project](https://github.com/TheAgentCompany/TheAgentCompany)]
- Xu, Kevin, et al. "Tur [k] ingbench: A challenge benchmark for web agents." arXiv preprint arXiv:2403.11905 (2024). [[paper](https://arxiv.org/abs/2403.11905)] [[project](https://github.com/JHU-CLSP/turking-bench)]
- Yao, Shunyu, et al. "Webshop: Towards scalable real-world web interaction with grounded language agents." Advances in Neural Information Processing Systems 35 (2022): 20744-20757. [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/82ad13ec01f9fe44c01cb91814fd7b8c-Abstract-Conference.html)] [[project](https://webshop-pnlp.github.io)]
- Lin, Kevin Qinghong, et al. "VideoGUI: A Benchmark for GUI Automation from Instructional Videos." arXiv preprint arXiv:2406.10227 (2024). [[paper](https://showlab.github.io/videogui/assets/preprint.pdf)] [[project](https://showlab.github.io/videogui/)]
- Deng, Xiang, et al. "Mind2web: Towards a generalist agent for the web." Advances in Neural Information Processing Systems 36 (2024). [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5950bf290a1570ea401bf98882128160-Abstract-Datasets_and_Benchmarks.html)] [[project](https://osu-nlp-group.github.io/Mind2Web/)]
- Liu, Zhiwei, et al. "Bolaa: Benchmarking and orchestrating llm-augmented autonomous agents." arXiv preprint arXiv:2308.05960 (2023). [[paper](https://arxiv.org/abs/2308.05960)] [[project](https://github.com/salesforce/BOLAA)]


### Mobile

- Rawles, Christopher, et al. "AndroidWorld: A dynamic benchmarking environment for autonomous agents." arXiv preprint arXiv:2405.14573 (2024). [[paper](https://arxiv.org/abs/2405.14573)] [[project](https://google-research.github.io/android_world/)]
- Zhang, Danyang, et al. "Mobile-Env: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction." arXiv preprint arXiv:2305.08144 (2023). [[paper](https://rhythmcao.github.io/publication/2024-mobile-env/2024-mobile-env.pdf)] [[project](https://github.com/X-LANCE/Mobile-Env)]
- Lee, Juyong, et al. "Benchmarking Mobile Device Control Agents across Diverse Configurations." arXiv preprint arXiv:2404.16660 (2024). [[paper](https://arxiv.org/abs/2404.16660)] [[project](https://b-moca.github.io)]

- Wang, Luyuan, et al. "MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents." arXiv preprint arXiv:2406.08184 (2024). [[paper](https://arxiv.org/abs/2406.08184)] [[project](https://mobileagentbench.github.io)]
- Trivedi, Harsh, et al. "Appworld: A controllable world of apps and people for benchmarking interactive coding agents." arXiv preprint arXiv:2407.18901 (2024). [[paper](https://arxiv.org/abs/2407.18901)] [[project](https://github.com/StonyBrookNLP/appworld)]

### Documents

- Rodriguez, Juan, et al. "BigDocs: An Open and Permissively-Licensed Dataset for Training Multimodal Models on Document and Code Tasks." arXiv preprint arXiv:2412.04626 (2024). [[paper](https://arxiv.org/abs/2412.04626)] [[project](https://openreview.net/forum?id=b1ivBPLb1n)]
- Zou, Anni, et al. "DOCBENCH: A Benchmark for Evaluating LLM-based Document Reading Systems." arXiv preprint arXiv:2407.10701 (2024). [[paper](https://arxiv.org/abs/2407.10701)] [[project](https://github.com/Anni-Zou/DocBench)]


## 🔨 Software Engineering
---

### SWE

- Carlos E. Jimenez, John Yang, et al. "SWE-bench: Can Language Models Resolve Real-World GitHub Issues?" arXiv preprint arXiv:2310.06770 (2023). [[paper](https://arxiv.org/abs/2310.06770)] [[project](https://github.com/swe-bench/SWE-bench)]
- Aleithan, Reem, et al. "SWE-Bench+: Enhanced Coding Benchmark for LLMs." arXiv preprint arXiv:2410.06992 (2024). [[paper](https://arxiv.org/abs/2410.06992)] [[project](https://www.swebench.com/index.html)]
- Zan, Daoguang, et al. "Swe-bench-java: A github issue resolving benchmark for java." arXiv preprint arXiv:2408.14354 (2024). [[paper](https://arxiv.org/abs/2408.14354)] [[project](https://github.com/multi-swe-bench/multi-swe-bench-env)]
- Yang, John, et al. "SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?." arXiv preprint arXiv:2410.03859 (2024). [[paper](https://arxiv.org/abs/2410.03859)] [[project](https://www.swebench.com/multimodal)]
- Gu, Alex, et al. "Cruxeval: A benchmark for code reasoning, understanding and execution." arXiv preprint arXiv:2401.03065 (2024). [[paper](https://arxiv.org/abs/2401.03065)] [[project](https://github.com/facebookresearch/cruxeval)]
- Siegel, Zachary S., et al. "CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark." arXiv preprint arXiv:2409.11363 (2024). [[paper](https://arxiv.org/abs/2409.11363)] [[project](https://github.com/siegelz/core-bench?tab=readme-ov-file)]
- Guo, Chengquan, et al. "RedCode: Risky Code Execution and Generation Benchmark for Code Agents." arXiv preprint arXiv:2411.07781 (2024). [[paper](https://arxiv.org/abs/2411.07781)] [[project](https://github.com/AI-secure/RedCode)]
- Zhuo, Terry Yue, et al. "Bigcodebench: Benchmarking code generation with diverse function calls and complex instructions." arXiv preprint arXiv:2406.15877 (2024). [[paper](https://arxiv.org/abs/2406.15877)] [[project](https://github.com/bigcode-project/bigcodebench)]


### Data Science & ML

- Zhang, Yuge, et al. "Benchmarking Data Science Agents." arXiv preprint arXiv:2402.17168 (2024). [[paper](https://arxiv.org/abs/2402.17168)] [[project](https://github.com/MetaCopilot/dseval)]
- Gu, Ken, et al. "Blade: Benchmarking language model agents for data-driven science." arXiv preprint arXiv:2408.09667 (2024). [[paper](https://arxiv.org/abs/2408.09667)] [[project](https://github.com/behavioral-data/BLADE)]
- Zhang, Dan, et al. "DataSciBench: An LLM Agent Benchmark for Data Science." [[paper](https://openreview.net/forum?id=BltaWJZMeR)]
- Huang, Yiming, et al. "DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models." arXiv preprint arXiv:2410.07331 (2024). [[paper](https://arxiv.org/abs/2410.07331)] [[project](https://da-code-bench.github.io/)]
- Hu, Xueyu, et al. "Infiagent-dabench: Evaluating agents on data analysis tasks." arXiv preprint arXiv:2401.05507 (2024).Hu, Xueyu, et al. "Infiagent-dabench: Evaluating agents on data analysis tasks." arXiv preprint arXiv:2401.05507 (2024). [[paper](https://arxiv.org/abs/2401.05507)] [[project](https://github.com/InfiAgent/InfiAgent)]
- Chan, Jun Shern, et al. "Mle-bench: Evaluating machine learning agents on machine learning engineering." arXiv preprint arXiv:2410.07095 (2024). [[paper](https://arxiv.org/abs/2410.07095)] [[project](https://github.com/openai/mle-bench)]
- Chen, Ziru, et al. "Scienceagentbench: Toward rigorous assessment of language agents for data-driven scientific discovery." arXiv preprint arXiv:2410.05080 (2024). [[paper](https://arxiv.org/abs/2410.05080)] [[project](https://osu-nlp-group.github.io/ScienceAgentBench/)]
- Jansen, Peter, et al. "DISCOVERYWORLD: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents." arXiv preprint arXiv:2406.06769 (2024). [[paper](https://arxiv.org/abs/2406.06769)] [[project](https://github.com/allenai/discoveryworld)]
- Huang, Qian, et al. "Benchmarking large language models as ai research agents." NeurIPS 2023 Foundation Models for Decision Making Workshop. 2023. [[paper](https://openreview.net/forum?id=kXlTY0BmK3)] [[project](https://github.com/snap-stanford/MLAgentBench)]

## 🧰 Tool-Use
---

- Wang, Jize, et al. "GTA: A Benchmark for General Tool Agents." arXiv preprint arXiv:2407.08713 (2024). [[paper](https://arxiv.org/abs/2407.08713)] [[project](https://github.com/open-compass/GTA)]
- Yao, Shunyu, et al. "$\tau $-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains." arXiv preprint arXiv:2406.12045 (2024). [[paper](https://arxiv.org/abs/2406.12045)] [[project](https://github.com/sierra-research/tau-bench)]
- Lu, Jiarui, et al. "Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities." arXiv preprint arXiv:2408.04682 (2024). [[paper](https://arxiv.org/abs/2408.04682)] [[project](https://github.com/apple/ToolSandbox)]
- Chen, Zehui, et al. "T-Eval: Evaluating the Tool Utilization Capability of Large Language Models Step by Step." arXiv preprint arXiv:2312.14033 (2023). [[paper](https://arxiv.org/abs/2312.14033)] [[project](https://github.com/open-compass/T-Eval)]
- Wu, Mengsong, et al. "Seal-tools: Self-instruct tool learning dataset for agent tuning and detailed benchmark." CCF International Conference on Natural Language Processing and Chinese Computing. Singapore: Springer Nature Singapore, 2024. [[paper](https://link.springer.com/chapter/10.1007/978-981-97-9434-8_29)] [[project](https://github.com/fairyshine/Seal-Tools)]
- Guo, Zishan, Yufei Huang, and Deyi Xiong. "Ctooleval: A chinese benchmark for llm-powered agent evaluation in real-world API interactions." Findings of the Association for Computational Linguistics ACL 2024. 2024. [[paper](https://aclanthology.org/2024.findings-acl.928/)] [[project](https://github.com/tjunlp-lab/CToolEval)]
- Li, Minghao, et al. "Api-bank: A comprehensive benchmark for tool-augmented llms." arXiv preprint arXiv:2304.08244 (2023). [[paper](https://arxiv.org/abs/2304.08244)] [[project](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank)]

## 🔍 RAG
---

- Yang, Xiao, et al. "CRAG--Comprehensive RAG Benchmark." arXiv preprint arXiv:2406.04744 (2024). [[paper](https://arxiv.org/abs/2406.04744)] [[project](https://github.com/facebookresearch/CRAG/)]
- Wang, Shuting, et al. "OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in Financial Domain." arXiv preprint arXiv:2412.13018 (2024). [[paper](https://arxiv.org/abs/2412.13018)] [[project](https://github.com/RUC-NLPIR/OmniEval)]
- Lyu, Yuanjie, et al. "Crud-rag: A comprehensive chinese benchmark for retrieval-augmented generation of large language models." ACM Transactions on Information Systems (2024). [[paper](https://dl.acm.org/doi/abs/10.1145/3701228)] [[project](https://github.com/IAAR-Shanghai/CRUD_RAG)]
- Pipitone, Nicholas, and Ghita Houir Alami. "LegalBench-RAG: A Benchmark for Retrieval-Augmented Generation in the Legal Domain." arXiv preprint arXiv:2408.10343 (2024). [[paper](https://arxiv.org/abs/2408.10343)] [[project](https://github.com/ZeroEntropy-AI/legalbenchrag)]
- *RAG*-ConfusionQA [[paper](https://arxiv.org/abs/2410.14567)] [[project](https://github.com/zhiyuanpeng/RAG-ConfusionQA)] [Request access]
- Kuzman, Taja, et al. "PandaChat-RAG: Towards the Benchmark for Slovenian RAG Applications." (2024).[[paper](https://is.ijs.si/wp-content/uploads/2024/10/SCAI_2024_paper_0538.pdf)] [[project](https://github.com/TajaKuzman/pandachat-rag-benchmark)]

## 🤖🤖 Multi-Agent
---

- Ossowski, Timothy, et al. "COMMA: A Communicative Multimodal Multi-Agent Benchmark." arXiv preprint arXiv:2410.07553 (2024). [[paper](https://arxiv.org/abs/2410.07553)]
- Xu, Lin, et al. "MAgIC: Benchmarking Large Language Model Powered Multi-Agent in Cognition, Adaptability, Rationality and Collaboration." arXiv preprint arXiv:2311.08562 (2023). [[paper](https://arxiv.org/abs/2311.08562)] [[project](https://zhiyuanhubj.github.io/MAgIC/)]

## 🗄️ Other Awesome Lists

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
