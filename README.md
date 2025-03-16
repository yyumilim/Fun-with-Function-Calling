# 基于 Agent 的有趣 Function Calling 调用
这是一个基于 Agent 和 OpenAI Function Calling 的有趣工具，结合了缘分居的 API，实现了星座配对、生日配对、生肖配对、塔罗牌占卜等功能。通过 OpenAI 的 GPT-3.5 模型，能够智能地调用不同的工具函数，完成用户请求，并返回有趣的结果。

## 项目亮点
- **Function Calling 的强大能力**：通过 OpenAI 的 Function Calling 功能，能够根据用户输入，动态选择并调用合适的工具函数（如星座配对、生肖配对等），实现智能化的任务处理。
- **趣味性功能**：不仅支持星座、生日、生肖配对，还提供了塔罗牌洗牌和占卜功能，增加了趣味性和互动性。
- **灵活的 API 集成**：通过缘分居的 API，快速获取配对和占卜结果，展示了如何将外部 API 与 OpenAI 模型无缝结合。
- **基于 Agent 的架构**：系统通过 Agent 的方式，自动解析用户意图，调用合适的工具函数，并生成最终回复。

## 功能
- 星座配对：输入男女双方的星座，获取配对结果。
- 生日配对：输入男女双方的生日，获取配对结果。
- 生肖配对：输入男女双方的生肖，获取配对结果。
- 塔罗牌洗牌：提供可选的卡牌编号。
- 塔罗牌占卜：根据用户选择的牌阵和卡牌，返回占卜结果。

## 技术栈
- Agent 架构：基于 OpenAI 的 GPT-3.5 模型，构建了一个智能 Agent，能够动态调用工具函数并处理用户请求。

## 快速开始
1. **安装依赖**
   ```bash
   pip install -r requirements.txt
   ```

2. **设置环境变量**

   在 `.env` 文件中添加你的 OpenAI API Key 和缘分居 API Key：
   ```
   OPENAI_API_KEY=your_openai_api_key
   YUANFENJU_API_KEY=your_yuanfenju_api_key
   ```
4. **运行代码**

   打开 `main.ipynb` 文件，运行代码即可体验功能。


## 感谢
感谢 [缘分居](https://yuanfenju.com/) 提供的 API 支持~ 使得这个小项目能够实现星座、生肖、塔罗牌等配对和占卜功能~ 
