## 简介

序列是许多机器学习和数据挖掘任务面对的一种输入数据类型，以自然语言处理任务为例：句子由词语构成，而多个句子进一步构成了段落。因此，段落可以看作是一个嵌套的序列（或者叫作：双层序列），这个序列的每个元素又是一个序列。

双层序列是 PaddlePaddle 支持的一种非常灵活的数据组织方式， 能够帮助我们更好地描述段落、多轮对话等更为复杂的数据。以双层序列作为输入，我们可以设计一个层次化的网络，从而更好地完成一些复杂的任务。

本单元将介绍如何在 PaddlePaddle 中使用双层序列。

- [基于双层序列的文本分类](https://github.com/PaddlePaddle/models/tree/develop/nested_sequence/text_classification)