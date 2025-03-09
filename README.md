# 假装绝对核心
导出群聊天记录，微调ChatGLM，假装“绝对核心”——补胎诗人

微调方法参考——https://github.com/liucongg/ChatGLM-Finetuning

制作多轮对话数据集 data.json 和 multi.json, 对应Loss计算时计算当前生成回答的loss。

评估方式——
1. 同一上下文多轮回归，计算与测试label的余弦相似度，取平均值
2. A/B测试，还未实现
