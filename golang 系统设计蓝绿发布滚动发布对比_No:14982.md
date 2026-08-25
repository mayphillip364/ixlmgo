最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9051024.sHtMl

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4108373.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8667373.sHtMl

原标题：文件句柄上限调整上传随机失败
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3194025.sHtMl

原标题：golang 系统设计定时任务分布式锁
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4212933.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3275973.sHtMl

原标题：golang proto 默认值坑点梳理
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3798821.sHtMl

原标题：golang mongodb 分页性能优化技巧
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3449384.sHtMl

原标题：实战项目：容器资源限制配置压力测试实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4160497.sHtMl

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7505902.sHtMl

原标题：nodejs http 服务性能调优实战
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2968087.sHtMl

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6357301.sHtMl

原标题：express 中间件开发业务实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1944954.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3296767.sHtMl

原标题：Redis 内存淘汰策略数据防丢失
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5731618.sHtMl

原标题：批量操作分批处理防止 OOM
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3418739.sHtMl

原标题：从零学习基础的接口请求与参数处理
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2679422.sHtMl

原标题：入门实践：简单批量处理脚本编写
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4407669.sHtMl

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6909160.sHtMl

原标题：golang 系统设计数据库连接池调优实践
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2641967.sHtMl

原标题：入门实践：使用模板快速生成项目脚手架
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8624452.sHtMl

原标题：golang 系统设计分布式会话方案对比
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2048871.sHtMl

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3433455.sHtMl

原标题：前端水印防信息泄露实现
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4211621.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7149003.sHtMl

原标题：磁盘 inode 耗尽文件创建失败
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5463724.sHtMl

原标题：前端国际化多语言方案落地
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6800105.sHtMl

原标题：golang jaeger 链路追踪 go 接入
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0163238.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0806906.sHtMl

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9380130.sHtMl

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8245403.sHtMl

原标题：golang docker 私有仓库搭建使用
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8672083.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5916313.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4546462.sHtMl

原标题：实战：Redis管道批量操作性能优化实践
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3139096.sHtMl

原标题：golang kafka 同步异步消费对比
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2021323.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5745349.sHtMl

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0500388.sHtMl

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2721295.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4439939.sHtMl


二、踩坑排错｜Troubleshooting
原标题：方案对比：几种任务队列架构选型优缺点
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0560433.sHtMl

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7502748.sHtMl

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6736310.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5943016.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3965448.sHtMl

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9398549.sHtMl

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1618347.sHtMl

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4735562.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8985377.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9492421.sHtMl

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3362132.sHtMl

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7276807.sHtMl

原标题：golang 分布式锁防死锁处理
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6065536.sHtMl

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7540241.sHtMl

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6887768.sHtMl

原标题：golang prometheus 告警规则编写
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2335994.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1943796.sHtMl

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0495127.sHtMl

原标题：golang grpc protobuf 开发实操
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5647269.sHtMl

原标题：OpenSource：开源项目许可证License选型指南
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1843734.sHtMl

原标题：后端分页查询逻辑代码实现
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0424367.sHtMl

原标题：站内邮件消息通知功能开发
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9594825.sHtMl

原标题：golang 系统设计大事务拆分实战思路
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1188433.sHtMl

原标题：实战：搭建日志收集分析简易完整演示环境
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9344725.sHtMl

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5306442.sHtMl

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1136440.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6640444.sHtMl

原标题：新手指南：本地防火墙端口访问失败排查
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2067264.sHtMl

原标题：golang prometheus counter gauge 使用
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5435022.sHtMl

原标题：时间精度统一业务判断修复
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6056802.sHtMl

原标题：前端静态缓存更新生效处理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1674557.sHtMl

原标题：golang 工具函数库封装思路
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0840058.sHtMl

原标题：golang k8s liveness readiness 探针
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3698711.sHtMl

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7810756.sHtMl

原标题：Architecture：服务注册发现架构原理与选型
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7179781.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7725020.sHtMl

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7187695.sHtMl

原标题：Architecture：链路追踪架构核心组件与埋点
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8894314.sHtMl

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2077721.sHtMl

原标题：部署实践：DockerCompose管理多服务环境
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6719176.sHtMl

三、实战开发｜Practice
原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3878802.sHtMl

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1390379.sHtMl

原标题：快速上手简单性能监控指标查看
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3645013.sHtMl

原标题：设计思考：系统限流熔断降级完整防护体系
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6325498.sHtMl

原标题：golang 简易埋点日志上报实现
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8093414.sHtMl

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5313897.sHtMl

原标题：百万数据 Excel 导出内存优化
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0512181.sHtMl

原标题：golang aes 对称加密解密示例
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8638047.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5753845.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4436824.sHtMl

原标题：开发测试生产多环境配置区分
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1209835.sHtMl

原标题：灰度发布策略服务平滑升级
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7039160.sHtMl

原标题：DevOps：日志标准输出容器日志收集方案
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6311684.sHtMl

原标题：死信队列处理消息阻塞业务
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1482254.sHtMl

原标题：分布式锁失效问题排查修复
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9953681.sHtMl

原标题：golang mysql 悲观锁乐观锁实现
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8465328.sHtMl

原标题：数据库死锁成因规避方案
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2371697.sHtMl

原标题：golang redis zset 延时队列实现
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2596497.sHtMl

原标题：不必要字符转义关闭业务异常
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5488619.sHtMl

原标题：跨库查询性能优化处理
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5743967.sHtMl

原标题：golang es 更新文档注意版本冲突
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8144521.sHtMl

原标题：golang es 映射 mapping 设计避坑
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8502244.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7803271.sHtMl

原标题：日志输出规范防止磁盘爆满
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5234732.sHtMl

原标题：线上故障：消息队列重复消费业务处理异常
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5352684.sHtMl

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4873423.sHtMl

原标题：快速上手简单的限流逻辑模拟实现
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3785431.sHtMl

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1894031.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7251750.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8169074.sHtMl

原标题：简易日志收集集中管理方案
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7503170.sHtMl

原标题：Debug日志：生产环境偶发空指针异常排查
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4589310.sHtMl

原标题：golang 消息队列 kafka 消费开发
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0730720.sHtMl

原标题：golang 系统设计无锁编程思路简单示例
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7810951.sHtMl

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1254242.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8823352.sHtMl

原标题：golang k8s cronjob 定时任务配置
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2669534.sHtMl

原标题：golang 系统设计容量评估简单方法论
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7624057.sHtMl

原标题：golang 日志 zap 结构化日志实践
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7280753.sHtMl

原标题：golang 系统设计数据库死锁分析规避
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4844981.sHtMl

四、架构设计｜Architecture
原标题：服务启动依赖顺序配置正确
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7835298.sHtMl

原标题：浮点计算精度错误处理方案
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9409614.sHtMl

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1219689.sHtMl

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2680184.sHtMl

原标题：实战：Nginx负载均衡多种策略配置实践
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/4508462.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2513316.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/3666424.sHtMl

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/9225699.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5703686.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/5467157.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/1859679.sHtMl

原标题：开源项目本地运行排错完整清单
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/2096947.sHtMl

原标题：golang mongodb 事务多文档使用
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8501973.sHtMl

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/8831314.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/6101306.sHtMl

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/7558779.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0758404.sHtMl

原标题：SourceMap 生成线上报错定位
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://zhishi.i7rc7a.asia/blog/0766051.sHtMl

?
