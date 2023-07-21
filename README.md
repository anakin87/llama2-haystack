# llama2-haystack
**(Experimental) Using Llama2 with Haystack**

The [notebook](llama2-haystack.ipynb) contains my hacky experiments in which I try to load and use [Llama2](https://ai.meta.com/llama/) with [Haystack](https://github.com/deepset-ai/haystack), the NLP/LLM framework.

*It's nothing official or well refined, but perhaps it may be useful to other people experimenting.*

![llama2-haystack](./assets/logo.png)

## Notebook summary
1) Installed Transformers from the main branch (and other libraries) 📚
2) Loaded Llama-2-13b-chat-hf on Colab using 4-bit quantizazion, thanks to the great material shared by Younes Belkada 🙌
3) Disabled Tensor Parallelism, which caused some issues 🛠️
4) Installed a minimal version of Haystack
5) Found a hacky way to load the model in Haystack's PromptNode
6) Had a llama-zing chat session, from 🎧🎶 David Guetta to Don Matteo ⛪📿 (an Italian TV series)!
