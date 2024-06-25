[WIP]
---

# [LangChain + Ollama](https://github.com/ollama/ollama/blob/main/docs/tutorials/langchainpy.md)

[llama3](https://ai.meta.com/blog/meta-llama-3/)
[LangChain](https://www.langchain.com/)
[Ollama](https://ollama.com/)

[LangChain + Ollama demo](demo.ipynb)

# [LangChain for LLM Application Development](https://learn.deeplearning.ai/courses/langchain/)

在学习该课程时，发现没有OpenAI Api-Key(免费额度用光了不想充钱)，
然后在找工作时搜到了[阶跃星辰](https://www.stepfun.com/)一家国内的大模型公司
提供了的一定的API免费额度，并且可以直接复用OpenAI Python的SDK，于是直接拿来搞搞。

- [X] [models,prompts and parsers](L1-Model_prompt_parser.ipynb)

```python
# 只需要初始化一个新的client就可以直接调用阶跃星辰的模型了，
# 从第一个实验体验下来，和课程中调用OpenAI gpt-3.5-turbo返回的内容类似，可以平替
# 具体修改可以参考本仓库下的魔改版notebook(L1-Model_prompt_parser.ipynb)
client = OpenAI(api_key="YOUR_STEP_API_KEY", base_url="https://api.stepfun.com/v1")
``` 

接下来会继续本课程的后续实验，看是否可以用阶跃星辰来全部完成