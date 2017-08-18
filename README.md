# ω bbs

次世代富交互论坛系统。

## Installation

Use docker.

WIP

## Features (WIP)

* 移动端友好
* SEO 友好（完整的 SSR 支持）
* 实时讨论、通知

## Design Concept

现在，并没有一款刚好“够用”的论坛系统。Discuz! 功能丰富但臃肿复杂，难以完成轻量级的交流，且架构老旧；Flarum 精致典雅但填坑无望，功能缺失严重而生态贫乏；Discourse 设计现代，但体量巨大且运行缓慢，不接底气。鉴于此，ω bbs 致力于构建一个适用于中文（甚至全球）社区的论坛社区。

总体说来，ω bbs 的设计遵循以下几个原则：

### 面向所有用户

无论是对站长还是最终用户，无论是 Geek 还是小白，无论使用桌面浏览器亦或是移动浏览器，我们希望 ω bbs 都能为你带来良好的体验。这或许意味着 ω bbs 没有这样或那样的自定义功能，或是需要运用某些折衷，但我们相信你的用户依然会喜欢它。

### 聚焦于有深度的讨论沉淀

沉淀讨论和知识，是 ω bbs 设计的核心。我们希望社区的讨论是尽量有价值的，水楼与版聊只是点缀。内容的沉淀将成为社区的价值，而过度水化会导致内容与用户的流失。因此，ω bbs 采用较为激进的策略，将部分非重要内容弱化甚至折叠，帮助社区提升内容质量。

### 尽量少的使用复杂度

无论是对最终用户，还是对使用 ω bbs 建设站点的技术人员，ω bbs 希望暴露尽量少的复杂度。我们希望我们的精心设计，能适用于大多数社区的场景，而不需要社区自行针对性调整。对于最终用户，我们使用传统的论坛概念，无论是传统论坛的用户还是只会用贴吧的小白都能轻松上手。

ω bbs 的绝大部分的特性只需要你进行安装即可使用，而无需经过复杂的配置。默认的部署方式加上一台[低至 2.5 美元/月](https://www.vultr.com/?ref=6959761)的 VPS 即可让你安心的撑过种子用户期。得益于 Docker 的广泛引用，你也可以通过 Kubernetes、Swarm 或 docker-compose 对其进行轻松进行横向扩展。

----

总而言之，ω bbs 希望为大多数用户提供超越大多数论坛的体验。在此基础上，拥有一定的可定制性、可扩展性。若你需要丰富的扩展或是玲琅满目的自定义选项，请考虑使用 Discourse 或 Discuz!。

## Issues

请向各子项目提交 issue。

[前端](https://github.com/omega-bbs/mua) | [API 服务](https://github.com/omega-bbs/len) | [接口及特性](https://github.com/omega-bbs/spec)

## Roadmap

See [spec/projects](https://github.com/omega-bbs/spec/projects).

## Contribution

- [Development](./docs/development.md)
- [Code Style](./docs/code-style.md)
- [Rich Editor](./docs/rich-editor.md)
- Front-end
  - [Technology Stack](./docs/web/tech-stack.md)
- API Service
  - [Technology Stack](./docs/api/tech-stack.md)
- [Meeting Notes](./docs/meeting-notes.md)

## License

如非特殊说明，本论坛系统的部分或全部组件，均遵循 AGPL-3.0 协议开源。
