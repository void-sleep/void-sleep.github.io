# void-sleep.github.io

[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/void-sleep/void-sleep.github.io/.github%2Fworkflows%2Fgh-pages.yml)](https://github.com/void-sleep/void-sleep.github.io/actions)
[![GitHub Repo stars](https://img.shields.io/github/stars/void-sleep/void-sleep.github.io)](https://github.com/void-sleep/void-sleep.github.io/stargazers)
[![GitHub contributors](https://img.shields.io/github/contributors/void-sleep/void-sleep.github.io)](https://github.com/void-sleep/void-sleep.github.io/graphs/contributors)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/void-sleep/void-sleep.github.io)](https://github.com/void-sleep/void-sleep.github.io)

Void Sleep，一个专注于技术创新的开源组织。

此项目为 Void Sleep 主页 [voidsleep.com][] 的源码。

欢迎提交 PR 进行开源共建。

## 贡献指南

本项目使用 [Hugo][] 开发，使用 [Doks][] 作为 Hugo 主题，一切内容都是 Markdown，专心写文字即可。

本地开发时需要先安装 Nodejs 和 Hugo。

```bash
# 安装 npm 依赖包，注意此过程需要连接 github 下载 hugo
npm install
# 启动 Web，然后浏览器访问 http://localhost:1313/即可浏览效果
npm run dev
# 创建新页面
npm run create docs/platform/backstage.md
npm run create blog/k8s.md
# 编译结果
npm run build
```

## License

本文档采用 [CC BY-NC 4.0][] 许可协议。

[voidsleep.com]: https://www.voidsleep.com
[Hugo]: https://gohugo.io/
[Doks]: https://github.com/thuliteio/doks
[CC BY-NC 4.0]: https://creativecommons.org/licenses/by-nc/4.0/
