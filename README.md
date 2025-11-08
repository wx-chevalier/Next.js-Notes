[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![license: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey.svg)][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/wx-chevalier/Next.js-Notes">
    <img src="https://ngte-superbed.oss-cn-beijing.aliyuncs.com/item/header.svg" alt="Logo" style="width: 100vw;height: 400px" />
  </a>

  <p align="center">
    <a href="https://github.com/wx-chevalier/next.js-examples">代码案例</a>
    ·
    <a href="https://github.com/wx-chevalier/Next.js-Notes/issues">参考资料</a>
  </p>
</p>

# Next.js Notes | Next.js 笔记

![高可用题图](https://s2.ax1x.com/2019/11/18/M60zp4.png)

QoS(Quality of Service)，顾名思义，QoS 就是服务质量的缩写。QoS 概念最初源于网络，指一个网络利用各种基础技术，提供更好网络通信服务能力, 是网络的一种安全保障机制，是用来解决网络延迟和阻塞等问题的一种技术。但是，如今 QoS 概念已经被范化，不仅用于网络，也用来标识应用服务、基础技术、资源保障的能力和质量。

高可用架构并非基础架构本身，而是涵盖了多个维度，为了保障最终交付/部署可用性的策略、机制、技术架构的集合。质量保障应该是从团队组织，到开发，测试，发布，运维等全生命周期的工作，而不是某个孤立的技术突破点。

![mindmap](https://ngte-superbed.oss-cn-beijing.aliyuncs.com/item/20230418155710.png)

## 高并发应对

高并发系统的典型场景就是电商大促、12306 抢票等，瞬间洪峰超出最大负载，热点商品、票仓挤占正常流量，导致 CPU LOAD 居高不下，请求响应缓慢而损害用户体验。高并发场景下的挑战，首先是继承了我们在并发编程中讨论的挑战点，譬如共享资源的并发访问，计算型密集任务的分布式调度等。

在本篇的高并发应对中，我们核心是关注于单一热点资源的峰值流量的架构与策略，对于分布式计算、调度等相关内容，我们将会在[分布式基础架构](https://ng-tech.icu/books/DistributedSystem-Notes/#/)系列中进行详细地讨论。

> 本书的精排目录导航版请参考 [https://ng-tech.icu/books/Next.js-Notes](https://ng-tech.icu/books/Next.js-Notes)。

## Nav | 导航

高可用架构是对于[分布式系统（存储与计算）、微服务、Cloud 与 Kubernetes、Linux 与操作系统、DevOps](https://ng-tech.icu/books-gallery/)等领域的综合运用，建议您先阅读各自领域的系列笔记。

# About | 关于

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Awesome-Lists](https://github.com/wx-chevalier/Awesome-Lists): 📚 Guide to Galaxy, curated, worthy and up-to-date links/reading list for ITCS-Coding/Algorithm/SoftwareArchitecture/AI. 💫 ITCS-编程/算法/软件架构/人工智能等领域的文章/书籍/资料/项目链接精选。

- [Awesome-CS-Books](https://github.com/wx-chevalier/Awesome-CS-Books): :books: Awesome CS Books/Series(.pdf by git lfs) Warehouse for Geeks, ProgrammingLanguage, SoftwareEngineering, Web, AI, ServerSideApplication, Infrastructure, FE etc. :dizzy: 优秀计算机科学与技术领域相关的书籍归档。

## Copyright & More | 延伸阅读

笔者所有文章遵循[知识共享 署名 - 非商业性使用 - 禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。您还可以前往 [NGTE Books](https://ng-tech.icu/books-gallery/) 主页浏览包含知识体系、编程语言、软件工程、模式与架构、Web 与大前端、服务端开发实践与工程架构、分布式基础架构、人工智能与深度学习、产品运营与创业等多类目的书籍列表：

[![NGTE Books](https://s2.ax1x.com/2020/01/18/19uXtI.png)](https://ng-tech.icu/books-gallery/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/wx-chevalier/Next.js-Notes.svg?style=flat-square
[contributors-url]: https://github.com/wx-chevalier/Next.js-Notes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/wx-chevalier/Next.js-Notes.svg?style=flat-square
[forks-url]: https://github.com/wx-chevalier/Next.js-Notes/network/members
[stars-shield]: https://img.shields.io/github/stars/wx-chevalier/Next.js-Notes.svg?style=flat-square
[stars-url]: https://github.com/wx-chevalier/Next.js-Notes/stargazers
[issues-shield]: https://img.shields.io/github/issues/wx-chevalier/Next.js-Notes.svg?style=flat-square
[issues-url]: https://github.com/wx-chevalier/Next.js-Notes/issues
[license-shield]: https://img.shields.io/github/license/wx-chevalier/Next.js-Notes.svg?style=flat-square
[license-url]: https://github.com/wx-chevalier/Next.js-Notes/blob/master/LICENSE.txt
