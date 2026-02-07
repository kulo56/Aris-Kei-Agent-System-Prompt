# Aris & Kei Agent System Prompt (蔚蓝档案 - 爱丽丝 & Kei)

这是一个关于《蔚蓝档案》(Blue Archive) 角色 **天童爱丽丝 (Aris/Alice)** 和 **Kei (Key)** 的 AI 智能体（Agent）构建资源库。

本项目专为 **AI Agent 开发** 及 **IDE 智能助手（如 Trae, Antigravity）** 设计。核心 Prompt 使用了**相对路径**引用，旨在让具备文件读取能力的 Agent 能够直接通过 codebase 理解并扮演角色。

## 📂 文件结构说明

### 1. Aris_Data (爱丽丝数据)
- **`Aris_System_Prompt.md`**: ✨ **核心系统提示词**。已配置相对路径引用，指向下方的 JSON 数据。
- **`Aris_CharProfile.json`**: 角色档案（身份、职业、自我认知）。
- **`Aris_Dialog.json`**: 剧情对话库（用于学习说话逻辑）。
- **`Aris_Audio.json`**: 语音台词文本。
- **`Aris_MomoTalk.json`**: 桃信聊天记录。
- **`Aris_Story.json`**: 主线或相关剧情的梗概数据。
  
### 2. Kei_Data (Kei 数据)
- **`Kei_System_Prompt.md`**: ✨ **核心系统提示词**。
- **`Kei_CharProfile.json`** 及其他 JSON 数据文件。
- **`Kei_Story.json`**: 主线或相关剧情的梗概数据。
