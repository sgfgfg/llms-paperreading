# Prompting Is All You Need: Automated Android Bug Replay with Large Language Models

提出了adbgpt，采用提示工程，从bug报告中重新bug（有些报告很模糊），
i）S2R 实体提取和ii）引导重放
i）S2R 实体提取 提供思考链和少量示例提取实体
ii）引导重放  新方法编码gui屏幕，提供中间推理示例，推断目标组件
与两种最先进的基准方法以及两种消融研究相比
在步骤提取和实体提取方面分别达到了90.4%和90.8%。其次，我们评估了AdbGPT在引导软件缺陷重放方面的性能，并展示了我们的方法能够成功地重现81.3%的缺陷，超过了基准方法和消融研究。此外，与基准方法相比，我们的方法更加高效，每个软件缺陷报告平均节省了1105.17秒的时间。

# LLM Platform Security: Applying a Systematic Evaluation Framework to OpenAI’s ChatGPT Plugins 

分析大语言模型插件安全性和隐私性，制定了一个系统评估的框架。
框架：利用我们制定的攻击分类体系，系统地分析了OpenAI插件商店托管的插件，通过审查其代码（清单和API规范）并与它们进行交互。当我们发现了新的攻击可能性或发现某种猜测的攻击不可行时，我们进行了迭代修订我们的攻击分类。

# Examining Zero-Shot Vulnerability Repair with Large Language Models

探讨了如何设计提示以引导LLMs修复不安全代码
比较了用于鼓励LLMs生成功能性和安全代码的提示、上下文线索和模型设置（温度、采样策略等）
简单情景下生成安全修复，而无需进行额外的训练，一些现实世界的情景中对LLMs进行评估时，我们发现它们可能难以生成可信的修复
开源了我们的数据集和评估框架

# Exploring the Potential of ChatGPT in Automated Code Refinement: An Empirical Study

使用给定的审查意见进行代码优化
在我们新生成的数据集中，ChatGPT在新数据集上的EM和BLEU分数分别为22.78和76.44，而CodeReviewer的EM和BLEU分数分别仅达到15.50和62.88。ChatGPT在涉及文档和功能优化的任务上存在困难，主要是由于缺乏领域知识、模糊的位置以及审查意见中的不清楚更改。通过提高审查质量和使用更先进的大型语言模型，这些限制可能会得到解决

# Deduplicating Training Data Mitigates Privacy Risks in Language Models Abstract

大型语言模型容易受到隐私攻击，这一片是针对语言模型实验，不是llms
序列在训练数据中重复的次数与该序列生成的速率之间存在超线性关系
成员推断方法对于那些多次重复的序列具有高达0.90的ROC曲线下面积，但对于只出现一次的序列，其准确率仅为偶然准确率。
我们发现，去重的模型的模型逆推攻击确实要弱得多