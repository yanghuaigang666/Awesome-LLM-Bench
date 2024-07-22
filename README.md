# Awesome-LLM-Bench
An Awesome Collection for large language models evaluations and benchmarks.

## 1 LLM评估

### 1.1 国内

- C-MMLU
	- 地址：[https://github.com/haonan-li/CMMLU](https://github.com/haonan-li/CMMLU)
	- 简介：包括来自医学、法律、心理学和教育等四大领域的测试，这些数据也是从中国高考、资格考试以及大学考试中收集的，测试大模型基础知识能力。是一个用于评估中文大型语言模型多任务理解能力的数据集。它类似于 MMLU（Massive Multitask Language Understanding）数据集，但专门针对中文语言的特点和需求进行设计和构建。
	
- C-Eval
	- 地址：[https://github.com/hkust-nlp/ceval](https://github.com/hkust-nlp/ceval)
	- 简介：覆盖更广泛的领域。具有四种不同的难度--特别是C-EVAL HARD基准是中国第一个提供复杂推理问题的基准。
	
- OpenCompass
	- 地址：[https://github.com/open-compass/opencompass](https://github.com/open-compass/opencompass)
	- 简介：该工具采用自上而下的三级能力维度设计，根据定义的20个能力维度构造了一个评测数据集，并引入ChatGPT，以及提出了 CircularEval的评测方式，使评测的结果更加稳定。开源评测集，支持自行下载评测。
	
- CLUE
	- 地址：[https://github.com/CLUEbenchmark/CLUE](https://github.com/CLUEbenchmark/CLUE)
	- 简介：CLUE是中国国内第一个大规模中文语言理解评估基准，涵盖多项任务，包括分类、阅读理解、自然语言推理等。
	
- KoLA
	- 地址：[https://github.com/THU-KEG/KoLA](https://github.com/THU-KEG/KoLA)
	- 简介：KOLA数据集是一个知识导向的大语言模型评估基准，设计了四级认知能力分类，涵盖19个任务，使用已知和不断更新的数据源评估大语言模型的世界知识水平，并通过对比评估系统来提供模型能力的详细诊断结果。
	
### 1.2 国外

- AlpacaEval
	- 地址：[https://github.com/tatsu-lab/alpaca_eval](https://github.com/tatsu-lab/alpaca_eval)
	- 简介：AlpacaEval是一个用于评估聊天LLM的基准测试，利用LLMs估计响应质量。通过引入长度控制，AlpacaEval减少了对长输出的偏好，显著提高了评估的鲁棒性和与人类偏好的相关性。
	
- MT-bench
	- 地址：[https://github.com/tatsu-lab/alpaca_eval](https://github.com/tatsu-lab/alpaca_eval)
	- 简介：该工具评测大模型具备的对话能力，包括具有挑战性的多轮问题集，使用GPT-4对模型响应进行评分。开源评测集，支持自行下载评测。
	
- HELM
	- 地址：[https://github.com/stanford-crfm/helm](https://github.com/stanford-crfm/helm)
	- 简介：HELM提供了大语言模型的全面评估，涵盖语言理解、生成、一致性、上下文敏感性、常识推理和领域知识，旨在跨不同任务和领域全面评估语言模型性能。
	
- SuperGLUE
	- 地址：[https://huggingface.co/datasets/aps/super_glue](https://super.gluebenchmark.com/)
	- 简介：BIG-bench包含204项挑战性任务，涵盖数学、儿童发展、语言学、生物学、常识推理、社会偏见、物理学和软件开发等多个领域，评估语言模型的能力。
	
- BIG-bench
	- 地址：[https://github.com/google/BIG-bench](https://github.com/google/BIG-bench)
	- 简介：BIG-bench包含204项挑战性任务，涵盖数学、儿童发展、语言学、生物学、常识推理、社会偏见、物理学和软件开发等多个领域，评估语言模型的能力。
	
- MMLU
	- 地址：[https://huggingface.co/datasets/cais/mmlu](https://huggingface.co/datasets/cais/mmlu)
	- 简介：MMLU 是一个包含了 57 个子任务的英文评测数据集，涵盖了初等数学、美国历史、计算机科学、法律等，难度覆盖高中水平到专家水平，有效地衡量了人文、社科和理工等多个大类的综合知识能力。它的难度从初级到高级专业水平不等，它既考验世界知识，也考验解决问题的能力。科目范围从数学和历史等传统领域到法律和伦理学等更专业的领域。主题的粒度和广度使基准测试成为识别模型盲点的理想选择。
	
## 2 Agents评估
### 2.1 国内

- AgentBench
	- 地址：[https://github.com/THUDM/AgentBench](https://github.com/THUDM/AgentBench)
	- 简介：该工具用于评估大语言模型使能智能体的能力，其中预设了操作系统、数据库、知识图谱等8种环境任务，用于评测大语言模型在对应的复杂环境中的实际表现
	
- ToolBench
	- 地址：[https://github.com/OpenBMB/ToolBench?tab=readme-ov-file](https://github.com/OpenBMB/ToolBench?tab=readme-ov-file)
	- 简介：ToolBench 是一个由 OpenBMB 和 THUNLP-MT 团队开发的基准测试套件，用于评估大语言模型（LLMs）在工具操作中的能力。它涵盖了广泛的API和实际使用场景，包括Google Sheets和虚拟家庭环境等，通过真实的API调用和模拟数据生成，提升模型的实际应用效果和稳定性
	
- T-Eval
	- 地址：[https://github.com/open-compass/T-Eval](https://github.com/open-compass/T-Eval)
	- 简介：T-Eval是一个评估大语言模型工具使用能力的基准测试，细分为计划、推理、检索、理解、执行和评审六个子任务，提供细致性能评估，减少外部因素影响，确保评估的稳定性和公平性。
	
- API-Bank
	- 地址：[https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank)
	- 简介：API-Bank是一种创新的基准，用于增强大型语言模型（LLMs）工具使用能力，包含73个API工具和314个对话示例，旨在评估、训练和改进LLMs的工具利用能力。
	
### 2.2 国外

- AgentSims
	- 地址：[https://github.com/py499372727/AgentSims?tab=readme-ov-file](https://github.com/py499372727/AgentSims?tab=readme-ov-file)
	- 简介：AgentSims是一款易于使用的基础设施，旨在为研究人员提供测试大型语言模型（LLM）能力的平台。用户可通过交互式界面创建评估任务，或通过少量代码部署和测试新的支持机制，如记忆系统和规划系统。
	
- toolbench
	- 地址：[https://github.com/sambanova/toolbench](https://github.com/sambanova/toolbench)
	- 简介：ToolBench评估开源LLMs工具操作能力，涵盖八种任务，提供定量评估。通过模型对齐、示例检索和系统提示技术，开源LLMs在8个任务中有4个达到与GPT-4相竞争的成功率，体现少量人类监督的重要性。

### 参考链接
-  https://abyssinian-molybdenum-f76.notion.site/237e9f7515d543c0922c74f4c3012a77?v=0a309e53d6454afcbe7a5a7e169be0f9

