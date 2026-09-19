# 沃土风格 · AI工艺老师傅(演示版)

仿沃土工业大模型(蓝沃AI LevelField)界面风格的在线体验网页,由市面**免费大模型 API**(硅基流动 SiliconFlow)驱动,调用成本 ¥0。

> ⚠️ 本页仅为界面风格学习演示,与蓝沃AI官方无任何关联。

## 功能

- **01 加工图纸解析**:上传 2D 工艺图纸图片(PNG/JPG)→ 自动调用免费视觉模型(GLM-4.1V / DeepSeek-OCR)提取零件名称、图号、材料、尺寸公差、粗糙度、技术要求
- **02 工艺路线推荐**:内置「AI工艺老师傅」提示词,输出工序顺序、设备选型、装夹方式、切削参数(Markdown 表格)
- 6 款免费模型切换、流式输出、多会话管理、Markdown 渲染

## 使用方法

1. 打开页面 → 右上角「⚙ 设置」
2. 粘贴 API Key(免费注册 [cloud.siliconflow.cn](https://cloud.siliconflow.cn) 获取,新用户赠约 2000 万 Token)
3. 密钥仅保存在本机浏览器 localStorage,不会上传到任何服务器

## 部署

纯静态网页,克隆后直接托管即可(GitHub Pages / Vercel / Cloudflare Pages),或本地:

```bash
python -m http.server 8000 --bind 127.0.0.1
```
