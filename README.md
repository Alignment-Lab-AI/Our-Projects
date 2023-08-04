# Welcome to Our Projects

Here we outline the growing collection of projects being developed by and with Alignment Lab AI. Our mission is to shape the future of AI with groundbreaking work, and we invite you to join us in this venture. If you are interested in our projects and want to be part of this exciting journey, [join our Discord server](https://discord.gg/n9hXaBPWxx) and visit our [website](https://alignmentlab.ai)!

We invite you to dive into these initiatives and engage with the authors and repository owners, as we hope for our work to inspire you to contribute in this new AI renaissance. Together, we can reach new heights!


# Current Headline Projects

## [Axolotl Trainer](https://github.com/OpenAccess-AI-Collective/axolotl)

Helmed by [OpenAccess-AI-Collective](https://github.com/OpenAccess-AI-Collective), our close partners and team members. This training environment aims to democratize AI by creating accessible tools, high-quality models, and an accessible framework with a more open and convenient system to use datasets of different formats.  We include as much as possible in terms of compatibility and interoperability with modern techniques.
Additionally, includes our custom packing and masking system which allows us to reduce compute requirement of training by 2/3's over traditional methods and end with higher quality models as well!

## [OpenOrca](https://huggingface.co/Open-Orca)

Our first foray into major alignment advancements. We have reproduced the dataset and text generation model outlined in the Microsoft Research Orca paper. Our open source resource has produced and enabled the most advanced and capable open source models in the world today, and dramatically improved the ability of small generative language models which run on consumer CPU and GPU to perform accurate and complex detailed step-by-steap reasoning on broad sets of previously intractable tasks. Beyond reproduction, we have improved the dataset and training methods to surpass the initial research via extensive ablations, evaluations, and refinement of our methods.

### Latest Model: [OpenOrca x OpenChat - Preview 2 - 13B](https://huggingface.co/Open-Orca/OpenOrcaxOpenChat-Preview2-13B/)

Beyond Orca parity. Trained in under 3 days with <10% of the original Orca's compute budget. On top of all leaderboards for 13B text generation models at release by good margin. Better than most 30B models. Comparable to original LLaMA 65B.

### First Model: [OpenOrca Preview 1 - 13B](https://huggingface.co/Open-Orca/OpenOrca-Preview1-13B) 

The original preview model we released as part of our project by the same name. We used 6% of the dataset cleaned and slightly optimized with our own techniques and achieved 60% of the improvement over Vicuna reported in the Orca evals from the paper [Orca: Progressive Learning from Complex Explanation Traces of GPT-4](https://paperswithcode.com/paper/orca-progressive-learning-from-complex)

## [OpenChat](https://github.com/imoneoi/openchat/tree/master)

An open sourced framework and set of models helmed by [imeoneoi](https://github.com/imoneoi), a core Alignment Lab team member. The framework handles training, inference, and serving. The models are notable for including the first non-proprietary one to beat ChatGPT on [Alpaca Eval](https://tatsu-lab.github.io/alpaca_eval/), and being able to do so running locally on consumer computers. Imoneoi developed and incorporated the novel Multipack packing and masking technique described above. As well, OpenChat framework leverages vLLM and Ray to accelerate model evaluations, and provides high speed parallelizable inference via included API server with async requests. Continuously updated in symbiosis with Axolotl and OpenOrca!

## [MoE Llama2 Project](https://discord.gg/e5PcEab4ub)

Our Mixture-of-Experts project which has rapidly advanced due to the passionate core team working on it. Building towards a modular framwork for scaling out MoE options to the broader open source community.

## [CodeInterpereter-API](https://github.com/shroominic/codeinterpreter-api)

An open implementation of OpenAI's Code interpreter which already outpaces it in functionality, helmed by [Shroominic](https://github.com/shroominic). Being tooled for open sourced LLMs, link will update here soon!


# Our Datasets

Core to our work is insight into what will produce advancements in future neural nets. Our open datasets offer a glimpse into our understanding of this process and a resource to other ML practitioners on this path of discovery with us.

## [OpenOrca](https://huggingface.co/datasets/Open-Orca/OpenOrca) 

The replicated dataset from [Orca: Progressive Learning from Complex Explanation Traces of GPT-4](https://paperswithcode.com/paper/orca-progressive-learning-from-complex)
We started by aiming for a faithful replication of the methods, but the results so far have been staggering. Many organizations have used our open dataset, and the most capable open text generation models in the world now incorporate it in their training corpus; some metrics are comparable to or surpassing GPT-3.5. Our own models have surpassed the initial Orca paper results using only an early subset of the full data, and we are still expanding and refining the dataset.

## [FLAN](https://huggingface.co/datasets/Open-Orca/FLAN)

The first fully collected and easily accessible repository of the FLAN Collection, a >400 GB instruction pre-training [dataset developed by Google](https://ai.googleblog.com/2023/02/the-flan-collection-advancing-open.html). This dataset was notorious for being difficult and time consuming to wrangle, so we offer it in an easily consumed, fully processed and templated parquet format as a courtesy to other ML practitioners.

## [Unified code instruct sets](https://huggingface.co/datasets/AtlasUnified/Code-Instruct-Sets)

Pile of python oriented code instruction data ready for fine tuning, helmed by [AtlasUnified](https://huggingface.co/datasets/AtlasUnified)

## [EverythingIsAllYouNeed](https://huggingface.co/datasets/Alignment-Lab-AI/EverythingIsAllYouNeed)

To be announced soon.


# Early Stage and Roadmap Projects

## [Synthetic Data Generators](https://github.com/Alignment-Lab-AI/synthetic-data-generators)

System to agnostically create training data of a user defined format and shape using raw data, or by reshaping preconstructed datasets.
A toolbox which is designed to work with and include: [Instruction-Set Generator](https://github.com/atlasunified/instruction-set-generator)

## [TALIS-Follow](https://github.com/Alignment-Lab-AI/TALIS-Follow)

A project to allow users to host and instantiate large models on local gpus, initially optimized for llama 65b future efforts will focus on falcon 40b, long context models, and llama2 70b as well

## [AutoMeticAssistant](https://github.com/Alignment-Lab-AI/AutoMeticAssistant) 

A repository currently operating as a placeholder until the projects needed to catch up to it, aims to generate a multimodal model trained to interact with a users pc and the internet functionally and serve as a system to fully automate any digital task.

## [Transformers-UI](https://github.com/Alignment-Lab-AI/transformers-ui)

The early framework for a project to create a functional ui for the transformers and datasets libraries to allow users to more Accessibly fine tune models, shape datasets, collect and understand the metadata from training and engage in the lesser understood elements of the transformers library such as model editing.

## [Landmark Attention QLORA](https://github.com/eugenepentland/landmark-attention-qlora)
An efficient composition of landmark attention with QLORA and other optimizations to reduce the impact of the scaling of vram over the length of the context of the model

## [AutoCode](https://github.com/Alignment-Lab-AI/autocode)

A series of scripts and experiments related to using the Openai api to create a script that writes script, some are more performative than others, development on [Codeinterpereter-api](https://github.com/shroominic/codeinterpreter-api) has depreciated the repository, but it still provides useful scripts worth sharing

## [RHODAN](https://github.com/Alignment-Lab-AI/RHODAN)

A custom api-agnostic extensible ai chat ui which seeks to create a simple framework for productivity similar to obsidian to provide the maximum amount of utility and flexibility with minimal complexity

## [VectorChat](https://github.com/Alignment-Lab-AI/vectorchat) 

A straightforward chat bot with a simple vector storage network able to provide the benefits of memory without a lot of the bloat and complexity of similar models

## [Model-Merge-Mega](https://github.com/Alignment-Lab-AI/Model-Merge-Mega)
A project which aims to consolidate all of the current model merging systems into a singular accessible interface which can intelligently measure models and provide relevant information about the merging to inform user decisions.
    Next steps include developing [ties-merging](https://github.com/prateeky2806/ties-merging) into the system to remove or mitigate the downsides to model merging, and eventually build a framework for developers to patch their released models rather than having to continuously release new ones, bury their users, and waste a lot of money retraining on the same data.


# Open Brainstorming for Future Projects


## Babelm (link soon!)

A project to make use of substantial and ongoing research to generate an efficient method for converting a model's language from english to non english, with particular focus on languages which use non latin characters primarily. will include generally useful tools for optimizing vocabulary and reducing the weight cost converting languages typically holds, as well as a pipeline to automatically generate a full cleaned corpus of data in the target language.

## General Intelligence Agency (link soon!)

An ecosystem designed as an interoperable framework for agents to enhance and augment their utility and centralize functionality to a local system. Avoids dealing with APIs, costs, and privacy concerns. Uses a custom model trained for the purpose.  link will update here soon!

## Enhanced Evaluator (link soon!)

A custom implementation of Eleuthers eval harness and HuggingFace's benchmarks along with vllm it’s currently accessible in [OpenChat](https://github.com/imoneoi/openchat/tree/master). Aims to benchmark modern LLMs by removing prompt bias and adding categories to rank suitability in MoE frameworks and agent harnesses as well.

## Synthetic Sentience Systems (link soon!)

Ongoing research and development towards a system to imbue a model with the necessary qualia to emulate sentience and establish an objective framework for measuring and charting this quality. The goal aims to help us understand our own sentience, and provide a meaningful guideline for estimating and measuring our progress towards a true AGI.

## Retention Oriented Attention (link soon!)

A planned project aimed at researching and generating an drop in system to allow the use of language models without a strict cap for sequence length.

For now, there isn't a single centralized location that covers all of this project, so we provide a list of a few of the resources we've been referring to.

Some citations for works included with Retention Oriented Attention include:

1. [Landmark Attention](https://github.com/epfml/landmark-attention) by Amirkeivan Mohtashami, Martin Jaggi, EPFML

2. [xPos RoPE](https://github.com/kaiokendev/cutoff-len-is-context-len) by lucidrains, Microsoft, Zhuiyi Technology, and KaiokenDev

3. [QLORA](https://github.com/artidoro/qlora) by dettmers,artidoro,ahai,lsz @ university of Washington  

4. [ALiBi](https://github.com/ofirpress/attention_with_linear_biases) by Ofir Press, Noah A. Smith, Mike Lewis, university of Washington, Facebook, Allen institute for AI

5. [longmem](https://github.com/Victorwz/LongMem)  by victorwz

6. [longmem](https://arxiv.org/abs/2306.07174) by Weizhi Wang, Li Dong, Hao Cheng, Xiaodong Liu, Xifeng Yan, Jianfeng Gao, Furu Wei


## Live Training System

An online learning framework making use of ROME, MEMIT, and various other research weve conducted allowing users to give a personality to a model and train it gradually over time through various one shot training steps punctuated by sentiment analysis enhanced self supervised training over user/model chat data

## The Ecosystem

An all in one modular framework to allow users to have a composable api system interoperable with our host of projects entirely locally.

## Sparsity Stack

A singular location where we compose the variety of research and tools we've gained or developed for operating models with a minimal amount of hardware and a minimal amount of performance loss.


# More soon!

We are accelerating at a wild pace! Documenting everything is taking a little while, and getting everything cohesively organized and thoroughly documented is going to happen incrementally. Please be patient and follow along for updates. Major releases will be announced on Twitter/X at [@Alignment_Lab](https://twitter.com/alignment_lab)

We have many exciting projects on the horizon. If you are as passionate about AI as we are, we would love to have you on board!
