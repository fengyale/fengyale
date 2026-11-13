<div align="center">

# Hi, I'm King Feng

**Java 后端工程师 · 把 LLM / Agent / RAG / MCP 落到工程里**

[![GitHub](https://img.shields.io/badge/GitHub-fengyale-181717?style=flat-square&logo=github)](https://github.com/fengyale)
[![Java](https://img.shields.io/badge/Java-21-007396?style=flat-square&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![MCP](https://img.shields.io/badge/Protocol-MCP-6E56CF?style=flat-square)](https://modelcontextprotocol.io/)

</div>

## 我是谁

Java 后端工程师，日常写 Spring Boot 服务。最近把主要精力放在大模型工程落地上：不做只停在对话界面的 demo，而是把 Agent、RAG、MCP 做成能在**内网环境真实运行**、并且有明确安全边界的工具。

判断标准一直很朴素：能不能不依赖外网跑起来、能不能把只读边界守住、能不能在断网机器上拷过去就工作。

## 当前在做什么

**Agent 工程化**
把决策分析、深度调研这类开放流程拆成可执行的状态机，用调用预算和断言约束模型行为，而不是让它自由发挥。

**RAG 全链路**
从文档切分、向量化、召回到重排完整搭一遍，记录每一步的取舍，而不是只调一个向量库。

**MCP 工具层**
让 AI 客户端能读写数据库、缓存和代码平台，同时用只读模式、SQL 白名单、token scope 三层把风险压住。

## 主要项目

| Project | 说明 | 技术栈 |
| --- | --- | --- |
| [kf-agent](https://github.com/fengyale/kf-agent) | 三个可独立运行又能互相引用的本地 Agent：决策分析、深度调研、知识库问答 | Java 21 · Spring Boot · LangChain4j |
| [kf-mcp](https://github.com/fengyale/kf-mcp) | 三个自研 MCP Server：多库只读数据库、Redis 管理、GitLab 操作，适配内网离线环境 | Java · Python · Node.js |
| [harness-bootstrap](https://github.com/fengyale/harness-bootstrap) | 把 AI 编码规范固化成可复用的 harness：规则、门禁、依据与闭环 | Skill · 工程规范 |
| [kf-tool](https://github.com/fengyale/kf-tool) | 浏览器自动化与文档处理工具集 | Node.js · PowerShell |
| [kf-skill](https://github.com/fengyale/kf-skill) | 可独立安装的技能集合 | Skill |
| [kf-business](https://github.com/fengyale/kf-business) | 响应式企业官网静态站点示例 | HTML · Tailwind · GSAP |

## 常用技术

`Java` `Spring Boot` `LangChain4j` `JDBC / MyBatis` `SQLite` `Redis` `MySQL` `Oracle` `SQL Server`
`Python` `Node.js` `PowerShell` `Maven` `Git` `MCP`

## 关注的方向

- 后端工程化：Spring Boot、数据访问、服务可观测性
- 大模型落地：Agent 编排、RAG 调优、MCP 工具设计
- 内网与离线环境下的 AI 工具链

## 联系方式

- GitHub：[@fengyale](https://github.com/fengyale)
