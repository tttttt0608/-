# 薯评洞察｜小红书评论区需求挖掘助

## Live Demo
Gradio Demo 链接: (https://ef2efb1c76797a84d0.gradio.live/)
如果 Gradio 链接过期,请打开Colab notebook并运行所有 并重新运行demo.
Colab Notebook: [https://colab.research.google.com/xxxx](https://colab.research.google.com/drive/1fTSPeMHxOTpUvWCj6tVzRsVhr1GxFHz1?usp=sharing)

## 问题
很多小红书创作者发完笔记后，会收到大量评论。  
但他们通常只是零散回复评论，没有系统地把评论转化成下一篇内容选题。
评论区其实包含大量真实用户需求，例如：
- 价格敏感
- 安全顾虑
- 交易风险
- 地点选择
- 适配疑问

## 解决方法
薯评洞察可以帮助创作者把评论区内容转化为结构化洞察，包括：
1. 用户需求分类
2. 高频问题总结
3. 下一篇笔记选题
4. 推荐标题
5. 封面文案
6. 评论回复模板

## Demo
当前版本使用 Google Colab + Gradio 搭建。  
用户可以手动粘贴小红书评论，点击按钮后生成分析结果。
当前版本不爬取真实小红书数据，避免数据权限和隐私问题。

## 使用工具
- Python
- Google Colab
- Gradio
- Rule-based keyword analysis

## 可改进
- 接入创作者授权数据
- 加入更强的 AI 语义分析
- 支持多篇笔记评论对比
- 输出内容复盘报告
- 加入评论回复优先级判断
