# Animation Vocabulary CN

**说不出动效的名字？先描述你看到了什么。**

基于 [emilkowalski/skills 的 animation-vocabulary](https://github.com/emilkowalski/skills/tree/main/skills/animation-vocabulary) 的小幅中文适配，独立维护、非官方。

## 保留与补充

保留原始动效词汇表和反查流程：从用户看到或感受到的效果匹配术语，先给最佳匹配，再解释少量近似选项。覆盖进出场、时序、变换、滚动、交互、弹簧、循环、效果与性能等类别。

中文补充帮助解释口语描述，保留英文术语和原英文定义，再附简短中文释义。描述不足就区分候选，不编造名称，也不把词汇表未收录的效果说成精确匹配。

## 安装与调用

```bash
npx skills add batespaige357-tech/animation-vocabulary-cn --skill animation-vocabulary-cn
```

对助手说：“用 animation-vocabulary-cn 帮我给这段动效描述找英文术语，并解释容易混淆的词。”Codex 可使用 `$animation-vocabulary-cn`。手动安装可复制 `skills/animation-vocabulary-cn` 完整目录。

这是命名与解释技能，不生成动画、不修改页面、不自带视频识别或浏览器。没有画面时只根据用户描述匹配；实现与性能诊断属于其他任务。

## 来源与检查

MIT，保留 Emil Kowalski 原版权与完整许可证，详见 [CHANGES.md](CHANGES.md)。原词汇表保留英文，中文释义是适配层。

已检查原正文差异、UTF-8、本地引用与技能格式；未进行真实描述匹配准确率、视频识别或助手行为评估。未运行前端编译，不含示例网页、效果截图或前后对比。
