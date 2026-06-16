[English](README.en.md) | 中文

## 二次开发内容

- **Vercel 部署支持**: 添加 `vercel.json` 配置文件，指定输出目录为 `dist/`
- **相对路径 URL**: 将 `baseUrl` 改为空字符串，所有 URL 使用相对路径，可部署到任意域名
- **浏览器语言自动检测**: 访问根路径时自动检测 `navigator.language` 并跳转对应语言版本

# Logo.surf - 文字生成 Logo 和 Favicon

[![Logo.surf 预览](./assets/logo.surf.preview.png)](https://logo.shiguang666.eu.org)

[访问 Logo.surf](https://logo.shiguang666.eu.org)


Logo.surf 是一个免费、易于使用的工具，可以快速将文字转换为专业的 Logo 和 Favicon。非常适合开发者、设计师以及任何需要创建简洁高效品牌标识的人。

## 功能特点

- **文字转 Logo**：只需输入文字即可创建 Logo 和 Favicon
- **自定义选项**：调整颜色、字体、大小等以完善您的设计
- **多格式支持**：支持下载 PNG、SVG、ICO 等多种格式
- **实时预览**：调整时可实时查看 Logo 变化
- **完全免费**：所有功能均可免费使用
- **无需注册**：无需注册账号即可开始使用
- **多语言支持**：支持 16 种语言，自动检测浏览器语言并跳转对应版本
- **相对 URL**：可部署到任何域名，无需额外配置

## 使用方法

1. 访问 [Logo.surf](https://logo.shiguang666.eu.org)
2. 在输入框中输入您想要的文字
3. 使用可用选项自定义您的 Logo（颜色、字体、大小等）
4. 实时预览您的 Logo
5. 满意后，选择您喜欢的格式下载

## 部署到 Vercel

1. 将 GitHub 仓库连接到 Vercel
2. 项目会自动构建并部署
3. 构建配置已通过 `vercel.json` 设置输出目录为 `dist/`

```json
{
  "outputDirectory": "dist"
}
```

## 国际化

- 支持 16 种语言
- 自动检测浏览器语言并跳转对应版本
- 用户可通过页面右上角语言切换器手动切换

## 相关产品

查看我们的其他工具和服务：

- [QRCode.fun](https://qrcode.fun) - 免费二维码生成器
- [EmojiSpark](https://emojispark.com) - AI 表情符号查找器
- [PDF.dance](https://www.pdfdance.com) - 全能 PDF 工具包
- [Awesome Flux AI](https://www.awesomefluxai.com) - Awesome Flux AI 资源
- [DNS.fish](https://dns.fish) - 域名 DNS 查询
- [IP.network](https://www.ip.network) - IP 地址信息和工具
- [Favicon.im](https://Favicon.im) - 获取任意网站的 Favicon
- [Small.im](https://Small.im) - 图片压缩和转换
- [Base64.sh](https://www.base64.sh) - Base64 编码和解码
- [Query.domains](https://Query.domains) - 域名可用性检查和 WHOIS 查询
- [RedirectCheck](https://www.redirectcheck.org) - URL 重定向检查

## 贡献

欢迎为 Logo.surf 做出贡献！如果您想参与贡献，请按以下步骤操作：

1. Fork 仓库
2. 创建您的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

请确保更新测试并遵守项目的编码标准。

## 许可证

本项目采用知识共享署名-非商业性使用 4.0 国际许可协议，详情请查看 [LICENSE](LICENSE) 文件。

要点：
- 您可以出于非商业目的使用、分享和改编本作品
- 您必须提供出处并包含原始仓库的链接
- 禁止商业使用

更多信息请访问：https://creativecommons.org/licenses/by-nc/4.0/
