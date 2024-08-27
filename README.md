# 假装绝对核心
导出群聊天记录，微调ChatGLM，假装“绝对核心”——补胎诗人

微调方法参考——https://github.com/liucongg/ChatGLM-Finetuning

制作多轮对话数据集 single.json 和 multi.json, 对应Loss计算时计算单个Loss与多个Loss。

使用single.json数据集多轮对话仅将最后的回答计算Loss效果不是很好；

multi.json数据集效果优于single.json。
