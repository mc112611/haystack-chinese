# haystack-chinese
:mag: 基于deepsetAI的开源项目haystack进行修改，使其支持中文场景下的任务

**注意：haystack官方最新版本对整体项目进行修改，因此本替换文件适用于1.21.1以及之前的版本，目前在haystack官方项目中使用的安装命令是'pip install haystack-ai',而本项目使用的是'pip install farm-haystack'，但是，这种方法完全兼容haystack官方教程里的内容。**

使用方法：

  1.使用`pip install farm-haystack`命令安装haystack
  
  2.将项目中的preprocessor.py和txt.py两个文件，替换原项目中的同名文件


此方法兼容haystack官方教程的全部功能，但是中文部分被我写死了，如果切换语言，会导致对于英语等其他语种不兼容，因此建议只使用中文场景。

[haystack官方教程](https://haystack.deepset.ai/tutorials/01_basic_qa_pipeline)

[haystack官方文档](https://docs.haystack.deepset.ai/docs/intro)

[haystack接口文档](https://docs.haystack.deepset.ai/reference/agent-api)


**遵守开源协议，如有侵权，请联系本人删除**

**因为修改代码，以及制作教程都是本人一个人在弄，因此issues回复可能不是那么快**


### 知乎开更：

[DeepsetAI-haystack中文场景下使用（一）haystack简介](https://zhuanlan.zhihu.com/p/669982164)

[DeepsetAI-haystack中文场景下使用（二）haystack安装](https://zhuanlan.zhihu.com/p/670002223)

[DeepsetAI-haystack中文场景下使用（三）让haystack能用在中文任务上！](https://zhuanlan.zhihu.com/p/670097450)

[DeepsetAI-haystack中文场景下使用（四）在中文文档上用embedding进行RAG！](https://zhuanlan.zhihu.com/p/670768194)
