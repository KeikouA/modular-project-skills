# 按模块管理项目

让不同 AI Agent 都能按模块管理项目，共用同一套项目说明。

## 第一次使用

1. 下载 `modular-project-skills` 文件夹，放在你的 AI Agent 可以读取的位置。
2. 用 Agent 打开要整理的项目，把下面的文件路径换成下载后的实际路径，然后发送这句话。

   > 请读取「modular-project-skills/SKILL.md」，按里面的步骤为当前项目建立模块说明。

3. 完成后，你可以从项目的 `README.md` 查看用法。Agent 则从项目根目录的 `AGENTS.md` 找到每个模块的说明。

以后换用其他 Agent，也可以沿用这些说明。如果它不会自动读取项目指令，在任务开头加一句「请先读取项目根目录的 AGENTS.md」即可。
