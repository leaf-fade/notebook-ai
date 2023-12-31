AI 相关的资料、模型、代码、项目、工具等汇总，尤其是开源并且适合中文世界的。

## Contents

- [LLM](#llm)
- [Community](#communities--organizations)
- [Applications & Tools](#applications--tools)
- [Courses & Books](#courses--books)
- [Articles](#articles)

## 国内云平台
 - [飞桨（AI Studio）](https://aistudio.baidu.com/)  - by 百度
 - [魔搭 modelscope](https://www.modelscope.cn/)  - by 阿里

## LLM

LLM，即 Large Language Model，大语言模型

- [ChatGPT](https://chat.openai.com/) - by OpenAI

- [Claude](https://www.anthropic.com/product) - by [Anthropic](https://www.anthropic.com/) (OpenAI 前员工创建)

- [LLaMA](https://github.com/facebookresearch/llama) ![](https://shields.io/github/stars/facebookresearch/llama?style=social) - by Meta

- [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) ![](https://shields.io/github/stars/tatsu-lab/stanford_alpaca?style=social) - An Instruction-following LLaMA Model。斯坦福基于 LLaMA 微调出的模型。

- [BELLE](https://github.com/LianjiaTech/BELLE) ![](https://shields.io/github/stars/LianjiaTech/BELLE?style=social) - BELLE: Be Everyone's Large Language model Engine（开源中文对话大模型）。基于斯坦福的 Alpaca 完成，但进行了中文优化，并对生成代码进行了一些修改

- [BLOOM](https://huggingface.co/bigscience/bloom) - BigScience Large Open-science Open-access Multilingual Language Model

- [BloomChat](https://github.com/sambanova/bloomchat) ![](https://shields.io/github/stars/sambanova/bloomchat?style=social) - SambaNova 和 Together 推出的开源可商用支持多语言的大语言模型，基于 BLOOM 微调

- [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) ![](https://shields.io/github/stars/Duxiaoman-DI/XuanYuan?style=social) - 轩辕是国内首个开源的千亿级中文对话大模型，同时也是首个针对中文金融领域优化的千亿级开源对话大模型。轩辕在 BLOOM-176B 的基础上针对中文通用领域和金融领域进行了针对性的预训练与微调，它不仅可以应对通用领域的问题，也可以解答与金融相关的各类问题，为用户提供准确、全面的金融信息和建议。

- [GLM](https://github.com/THUDM/GLM) ![](https://shields.io/github/stars/THUDM/GLM?style=social) - by Knowledge Engineering Group (KEG) & Data Mining at Tsinghua University。

- [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) ![](https://shields.io/github/stars/THUDM/ChatGLM-6B?style=social) - by Knowledge Engineering Group (KEG) & Data Mining at Tsinghua University。ChatGLM-6B 是一个开源的、支持中英双语的对话语言模型，基于 General Language Model (GLM) 架构，具有 62 亿参数。结合模型量化技术，用户可以在消费级的显卡上进行本地部署（INT4 量化级别下最低只需 6GB 显存）。 ChatGLM-6B 使用了和 ChatGPT 相似的技术，针对中文问答和对话进行了优化。

- [MLC LLM](https://github.com/mlc-ai/mlc-llm) ![](https://shields.io/github/stars/mlc-ai/mlc-llm?style=social) - 代表了一种新的思路，serverless，允许在手机、电脑等终端上直接运行 LLM
- [Web LLM](https://github.com/mlc-ai/web-llm) ![](https://shields.io/github/stars/mlc-ai/web-llm?style=social) - *MLC LLM* 的兄弟项目，在浏览器里运行 LLM

- [Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca) ![](https://shields.io/github/stars/ymcui/Chinese-LLaMA-Alpaca?style=social) - 在原版 LLaMA 的基础上扩充了中文词表并使用了中文数据进行二次预训练，进一步提升了中文基础语义理解能力。同时，中文Alpaca模型进一步使用了中文指令数据进行精调，显著提升了模型对指令的理解和执行能力。

- [MOSS](https://github.com/OpenLMLab/MOSS) ![](https://shields.io/github/stars/OpenLMLab/MOSS?style=social) - by 复旦大学。An open-source tool-augmented conversational language model from Fudan University

- [LaWGPT](https://github.com/pengxiao-song/LaWGPT) ![](https://shields.io/github/stars/pengxiao-song/LaWGPT?style=social) - Chinese-Llama tuned with Chinese Legal knowledge。基于中文法律知识的大语言模型

- [TigerBot](https://github.com/TigerResearch/TigerBot) ![](https://shields.io/github/stars/TigerResearch/TigerBot?style=social) - 新晋国产创业项目，by 虎博网络技术（上海）。TigerBot 是一个多语言多任务的大规模语言模型(LLM)。根据 OpenAI InstructGPT 论文在公开 NLP 数据集上的自动评测，TigerBot-7B 达到 OpenAI 同样大小模型的综合表现的 96%

## Communities & Organizations

- [Hugging Face](https://huggingface.co/)
  - [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) - 开源 LLM 测评排行榜
  - [HuggingChat](https://huggingface.co/chat) ![](https://shields.io/github/stars/huggingface/chat-ui?style=social) - 类似于 ChatGPT 的 AI Chat
  - [Transformers](https://github.com/huggingface/transformers) ![](https://shields.io/github/stars/huggingface/transformers?style=social) - HuggingFace's NLP (Natural Language Processing) library. Transformers is backed by the three most popular deep learning libraries — [Jax](https://jax.readthedocs.io/en/latest/), [PyTorch](https://pytorch.org/) and [TensorFlow](https://www.tensorflow.org/) — with a seamless integration between them.

- [LMSYS ORG](https://lmsys.org/) - The Large Model Systems Organization develops large models and systems that are open, accessible, and scalable.
  - [Chatbot Arena](https://lmsys.org/blog/2023-05-03-arena/) - A benchmark platform for large language models (LLMs) that features anonymous, randomized battles in a crowdsourced manner.
  - [FatChat](https://github.com/lm-sys/FastChat) ![](https://shields.io/github/stars/lm-sys/FastChat?style=social) - An open platform for training, serving, and evaluating large language models.
  - [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/) - An open-source chatbot trained by fine-tuning LLaMA on user-shared conversations collected from ShareGPT. Online chat: https://chat.lmsys.org/

## Applications & Tools

- [Github Copilot](https://github.com/features/copilot) - GitHub Copilot uses the OpenAI Codex to suggest code and entire functions in real-time, right from your editor.

- [Cursor](https://www.cursor.so) - AI-first code editor powered by OpenAI

- [FastGPT](https://github.com/c121914yu/FastGPT) ![](https://shields.io/github/stars/c121914yu/FastGPT?style=social) - FastGPT 允许你使用自己的 OpenAI API KEY 来快速的调用 OpenAI 接口，目前集成了 Gpt35, Gpt4 和 embedding。 可构建自己的知识库。

- [ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web) ![](https://shields.io/github/stars/Yidadaa/ChatGPT-Next-Web?style=social) - One-Click to deploy well-designed ChatGPT web UI on Vercel

- [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) ![](https://shields.io/github/stars/Significant-Gravitas/Auto-GPT?style=social) - An experimental open-source attempt to make GPT-4 fully autonomous.

- [LangChain](https://github.com/hwchase17/langchain) ![](https://shields.io/github/stars/hwchase17/langchain?style=social) - Building applications with LLMs through composability 

- [ChatBase](https://www.chatbase.co/) - Just upload your documents or add a link to your website and get a ChatGPT-like chatbot for your data. 基于 OpenAI API 构建

- [ChatDoc](https://chatdoc.com/) - ChatDOC is a ChatGPT-based file-reading assistant that can quickly extract, locate, and summarize information from documents.

## Courses & Books

- [Practical Deep Learning](https://course.fast.ai/) - on fast.ai, based on book [Deep Learning for Coders with Fastai and PyTorch: AI Applications Without a PhD ](https://course.fast.ai/Resources/book.html)
- [NLP Course](https://huggingface.co/learn/nlp-course) - by HuggingFace
- [神经网络与深度学习](https://nndl.github.io/nndl-book.pdf) - Neural Network and Deep Learning，邱锡鹏著



## Articles

- [LLM 评测](https://wqw547243068.github.io/llm_eva)
- [文档问答原理及实践 Thoery and Implemetation of the Doucument QA](https://wqw547243068.github.io/doc-chat)
