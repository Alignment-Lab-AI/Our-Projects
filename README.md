# Welcome to Our Projects

Welcome to an extensive collection of projects being by and with Alignment Lab AI. Our mission is to shape the future of AI with groundbreaking work, and we invite you to join us in this venture. If you are interested in our projects and want to be part of this exciting journey, [join our Discord server](https://discord.gg/n9hXaBPWxx) and visit our [website](alignmentlab.ai)!

Dive into these initiatives and engage with the authors and repository owners. our work is inspiring and together, we can reach new heights.


## Our Projects

### [Axolotl Trainer](https://github.com/OpenAccess-AI-Collective/axolotl)

A product of the Open Access AI Collective. This training wrapper aims to democratize AI by creating accessible tools, high-quality models, and an accessible framework with a more open and convenient system to use datasets of different formats, and include as much as possible in terms of compatiblity and interoperability with modern tecniques
additionally inlcudes our custom packing and masking system which allows us to reduce the wall clock time of training by 2/3's and end with higher quality models as well!

### [OpenChat](https://github.com/imoneoi/openchat/tree/master)

An open sourced framework helmed by [imeoneoi](https://github.com/imoneoi) to handle training, inference, and serving which currently incorporates the packing and masking technique described above, an augmented evaluation system, and is enhanced by vllm to provide high speed parallelizable inference for async requests, Continuously updated with OpenChat models which are extremely performative and now use Llama2 as a base model!


### [OpenOrca Preview 1 - 13B](https://huggingface.co/Open-Orca/OpenOrca-Preview1-13B) 

The original preview model we released as part of our project by the same name, we used 6% of the dataset cleaned and slightly optimized with our own techniques and achieved 60% of the progress to the orca evals posted in the paper [Orca: Progressive Learning from Complex Explanation Traces of GPT-4](https://paperswithcode.com/paper/orca-progressive-learning-from-complex)


### OpenOrca Preview 2(link soon!)

Coming very soon! 

### [MOE Llama Project](https://discord.gg/e5PcEab4ub)

Our MOE project which has rapidly advanced due to the incredibly smart individuals working on it, currently achieves high quality inference using pretrained models and is shaping up to become an interoperable framework to allow users to use any model in an moe framework

### [Babelm](link soon!)

A project to make use of substantial and ongoing research to generate an efficient method for converting a models language from english to non english, with particular focus on languages which use non latin characters primarily. will include generally useful tools for optimizing vocabulary and reducing the weight cost converting languages typically holds, as well as a pipeline to automatically generate a full cleaned corpus of data in the target language.

### [Codeinterpereter-api](https://github.com/shroominic/codeinterpreter-api)

An open implementation of OpenAI's Code interpreter which already outpaces it in functionality, helmed by [shroominic](https://github.com/shroominic). Being tooled for open sourced LLMs, link will update here soon!

### General Intelligence Agency(link soon!)

An ecosystem designed as an interoperable framework for agents to enhance and augment their utility and centralize functionality to a local system. Avoids dealing with APIs, costs, and privacy concerns. Uses a custom model trained for the purpose.  link will update here soon!

### Enhanced Evaluator(link soon!)

A custom implementation of eleuthers eval harness and HuggingFace's benchmarks along with vllm its currently accessible in [OpenChat](https://github.com/imoneoi/openchat/tree/master). Aims to benchmark modern LLMs by removing prompt bias and adding categories to rank suitability in MoE frameworks and agent harnesses as well.

### [Synthetic Data Generators](https://github.com/Alignment-Lab-AI/synthetic-data-generators)

a system to agnostically create training data of a user defined format and shape using raw data, or by reshaping preconstructed datasets.
a toolbox which is designed to work with and include:

  ## [Instruction-Set Generator](https://github.com/atlasunified/instruction-set-generator)

### Synthetic Sentience Systems(link soon!)

ongoing research and development towards a system to imbue a model with the neccesary qualia to emulate sentience and establish an objective framework for measuring and charting this quality. the goal aims to help us understand our own sentience, and provide a meaningful guideline for estimating and measuring our progress towards a true AGI.

### [TALIS-Follow](https://github.com/Alignment-Lab-AI/TALIS-Follow)

a project to allow users to host and instantiate large models on local gpus, initially optimized for llama 65b future efforts will focus on falcon 40b, long context models, and llama2 70b as well

### [AutoMeticAssistant](https://github.com/Alignment-Lab-AI/AutoMeticAssistant) 

a repository currently operating as a placeholder until the projects needed catch up to it, aims to generate a multimodal model trained to interact with a users pc and the internet functionally and serve as a system to fully automate any digital task.

### [Transformers-UI](https://github.com/Alignment-Lab-AI/transformers-ui)

the early framework for a project to create a functional ui for the transformers and datasets libraries to allow users to more accessibly fine tune models, shape datasets, collect and understand the metadata from training and engage in the lesser understood elements of the transformers library such as model editing.

### [Autocode](https://github.com/Alignment-Lab-AI/autocode)

a series of scripts and experiments related to using the openai api to create a script that writes script, some are more performative than others, development on [Open Code Interpreter](placeholderlink) has depreciated the repository, but it still provides useful scripts worth sharing

### [RHODAN](https://github.com/Alignment-Lab-AI/RHODAN)

a custom api-agnostic exensible ai chat ui which seeks to create a simple framework for productivity similar to obsidian to provide the maximum amount of utility and flexibility with minimal complexity

### [VectorChat](https://github.com/Alignment-Lab-AI/vectorchat) 

a straightforward chat bot with a simple vector storage network able to provide the benefits of memory without a lot of the bloat and complexity of similaar models

### [Model-Merge-Mega](https://github.com/Alignment-Lab-AI/Model-Merge-Mega)

a project that aims to consolidate all of the current model merging systems into a singular accessible interface which can inteligently measure models and provide relevant information about the merging to inform user decisions.
    next step include developing [ties-merging](https://github.com/prateeky2806/ties-merging) into the system to remove or mitigate the downsides to model merging, and eventually build a framework for developers to patch their released models rather than having to continuously release new ones, bury their users, and waste a lot of money retraining on the same data.

## Our Datasets

### [OpenOrca](https://huggingface.co/datasets/Open-Orca/OpenOrca) 

The replicated dataset from [Orca: Progressive Learning from Complex Explanation Traces of GPT-4](https://paperswithcode.com/paper/orca-progressive-learning-from-complex)
we aim for a faithful and identical replicationi of the set, but the results so far have been staggering, creating multiple models from other organizations which are nearly on par with gpt 3.5, and within ours which we're releasing slowly after thorough testing. each model weve built has surpassed our initial [preview 1](https://huggingface.co/Open-Orca/OpenOrca-Preview1-13B) release which only included roughly 6% of the dataset and produced state of the art results.

### [Flan](https://huggingface.co/datasets/Open-Orca/FLAN)

The first fully collected and easily accessible version of FLAN, a 500 gb instruction pretraining dataset developed by google [a more thorough explaination can be founud here](https://arxiv.org/pdf/2109.01652.pdf) contains all of the original subsets and includes an additional set for the ones needed to generate [OpenOrca](https://huggingface.co/datasets/Open-Orca/OpenOrca) 

### [EverythingIsAllYouNeed](https://huggingface.co/datasets/Alignment-Lab-AI/EverythingIsAllYouNeed)

to be announced soon

### [a compilation of code instruct sets](https://huggingface.co/datasets/AtlasUnified/Code-Instruct-Sets)

a pile of python oriented code instruction data ready for fine tuning

### [more soon!]

were accelerating at wild pace! documenting everything is taking a little while, and making sure all the repositories are as clean and hassle free as possible is going to happen incrementally, please be patient and follow along for updates! major releases will be announced on twitter/x at [@Alignment_lab](https://twitter.com/alignment_lab)

## Retention Oriented Attention(link soon!)

A planned project aimed at researching and generating an drop in system to allow the use of language models without a strict cap for sequence length

for now, there isnt a single centralized location that covers all of this project, so ill link you to our related repositories, and the repositories which were studying but exist outside of Alignment Lab

### [Landmark Attention Qlora](https://github.com/eugenepentland/landmark-attention-qlora)
an efficient composition of landmark attention with qlora and other optimizations to reduce the impact of the scaling of vram over the length of the context of the model

some citations for works included with Retention Oriented Attation include:

1. [Landmark Attention](https://github.com/epfml/landmark-attention) by Amirkeivan Mohtashami, Martin Jaggi, EPFML

2. [XPos RoPE](https://github.com/kaiokendev/cutoff-len-is-context-len) by lucidrains, Microsoft, Zhuiyi Technology, and KaiokenDev

3. [QLORa](https://github.com/artidoro/qlora) by dettmers,artidoro,ahai,lsz @ university of Washington  

4. [ALiBi](https://github.com/ofirpress/attention_with_linear_biases) by Ofir Press, Noah A. Smith, Mike Lewis, university of Washington, Facebook, Allen institute for AI

5. [longmem](https://github.com/Victorwz/LongMem)  by victorwz

6. [longmem](https://arxiv.org/abs/2306.07174) by Weizhi Wang, Li Dong, Hao Cheng, Xiaodong Liu, Xifeng Yan, Jianfeng Gao, Furu Wei

7. more soon!

We have many exciting projects on the horizon. If you're as passionate about AI as we are, we would love to have you on board!


### planned projects

## live training system

an online learning framework making use of ROME, MEMIT, and various other research weve conducted allowing users to give a personality to a model and train it gradually over time through various one shot training steps punctuated by sentiment analysis enhanced self supervized training over user/model chat data

## The Ecosystem

an all in one modular framework to allow users to have a composablbe api system interoperable with our host of projects entirely locally.

## Sparsity stack

A singular location where we compose the variety of research and tools weve gained or developed for operating models with a minimal amount of hardware and a minimal amount of performance loss

## more soon!
