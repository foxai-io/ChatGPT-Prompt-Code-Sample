# 介绍

这里是 Andrew Ng 的 [ChatGPT API For Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) 免费课程的示例代码。

线上实例以 notebook 的形式，可以直接运行互动。本repo会同时保存 python 源代码 (`.py`)，与 Jupyter notebook (`.ipynb`) 的形式。python 源代码可以在命令行执行，Jupyter notebook 可以直接在vscode里互动运行，比较方便。

# Setup

## OpenAI API Key

你需要一个 API Key 才能执行这些代码。登陆 [openai官网](https://platform.openai.com/)，进入地址：[OpenAI Api Key](https://platform.openai.com/account/api-keys) 地址创建一个新的 API Key，保存后 可以写入环境变量 `OPENAI_API_KEY`

```shell
export OPENAI_API_KEY="sk-...(YOUR API KEY)"
```

或将上一行写入 `~/.zshrc` （mac系统），或`~/.bashrc` (ubuntu)。

## Python

建议使用 `pyenv` 启动一个virtualenv来运行代码。