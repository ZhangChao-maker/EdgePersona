# 🌟**EdgePersona**- 全本地化智能数字人

​**完全离线 | 隐私无忧 | 轻量高效 |笔记本友好**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="demo.gif" alt="实时对话演示" width="600">
</p>

## 🚀 核心特性
- ​**100%本地化运行** - 无需网络连接，所有数据处理在本地完成
- ​**多模态交互** - 支持语音对话、表情控制、肢体动作同步响应
- ​**超低硬件要求** - 实测笔记本NVIDIA 3060显卡即可实时运行
- ​**角色深度定制** - 通过YAML配置文件自定义人物性格/动作/语音风格
- ​**多模型支持** - 兼容Ollama、HuggingFace、GGUF等主流模型格式

## 📦 快速开始

### 环境要求
- NVIDIA显卡（≥6GB VRAM）
- Python >=3.11.11
- Windows/Linux/macOS（M系列芯片需启用Metal加速）

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/yourusername/LocalMind.git
cd LocalMind

# 创建虚拟环境（推荐）
conda #推荐
# 安装依赖
pip install -r requirements.txt


启动数字人
bash
python main.py
🎮 操作指南
角色配置文件示例:
config/main.py

llm本地配置：
self.base_url = 'http://localhost:11434/v1'
self.client = openai.OpenAI(api_key=self.api_key, base_url=self.base_url)
self.model_name = 'qwq-0.5b:latest'
```


🏆 性能基准
硬件配置	推理延迟	显存占用

🙌 本项目基于以下优秀开源项目构建：

bailing:https://github.com/wwbin2017/bailing

Ollama - 本地大模型运行框架
KokoroTTS - 超低延迟语音合成 https://github.com/hexgrad/kokoro

📜 开源协议
本项目采用 MIT 许可证 - 详情请参阅 LICENSE 文件

​​让AI交互回归本质​​ - 无需云端依赖，即刻拥有您的私人数字助手！ 🤖

