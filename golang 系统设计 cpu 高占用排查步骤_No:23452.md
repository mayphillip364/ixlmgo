最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.hmnrxg.asia/arts/757938.Doc

原标题：开发代理服务网络限制解决
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.hmnrxg.asia/arts/912814.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.hmnrxg.asia/arts/853663.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.hmnrxg.asia/arts/630874.Doc

原标题：GET POST 接口请求参数处理
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.hmnrxg.asia/arts/900317.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/615218.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.hmnrxg.asia/arts/337137.Doc

原标题：线程池拒绝策略任务丢失防护
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/601826.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.hmnrxg.asia/arts/189643.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.hmnrxg.asia/arts/192557.Doc

原标题：golang http 服务性能优化调参
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/642172.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.hmnrxg.asia/arts/429699.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/601037.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.hmnrxg.asia/arts/081876.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.hmnrxg.asia/arts/304036.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.hmnrxg.asia/arts/865273.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.hmnrxg.asia/arts/937037.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.hmnrxg.asia/arts/193329.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.hmnrxg.asia/arts/886500.Doc

原标题：golang url 参数编码处理方案
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.hmnrxg.asia/arts/763481.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.hmnrxg.asia/arts/049630.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.hmnrxg.asia/arts/904007.Doc

原标题：golang redis 分布式计数器开发
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/861663.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/911650.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.hmnrxg.asia/arts/375771.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/235287.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.hmnrxg.asia/arts/411210.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.hmnrxg.asia/arts/752840.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.hmnrxg.asia/arts/712650.Doc

原标题：golang 单例模式实现几种方式
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.hmnrxg.asia/arts/638925.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/568494.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.hmnrxg.asia/arts/781819.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.hmnrxg.asia/arts/302629.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.hmnrxg.asia/arts/410317.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.hmnrxg.asia/arts/159240.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.hmnrxg.asia/arts/040254.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.hmnrxg.asia/arts/637477.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.hmnrxg.asia/arts/553691.Doc

原标题：golang 熔断降级简易组件开发
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/860311.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.hmnrxg.asia/arts/619514.Doc


二、踩坑排错｜Troubleshooting
原标题：接口请求重试容错机制实现
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.hmnrxg.asia/arts/792022.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.hmnrxg.asia/arts/305885.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.hmnrxg.asia/arts/634800.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.hmnrxg.asia/arts/129436.Doc

原标题：golang gin 框架接口开发实战
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/823761.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.hmnrxg.asia/arts/217444.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.hmnrxg.asia/arts/970234.Doc

原标题：提交第一个开源 PR 完整流程
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.hmnrxg.asia/arts/517700.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/936258.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.hmnrxg.asia/arts/115553.Doc

原标题：golang go test 覆盖率统计实操
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/903807.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.hmnrxg.asia/arts/423700.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/401373.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/934747.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/304900.Doc

原标题：跨域偶现失败配置修复
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/734290.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.hmnrxg.asia/arts/866688.Doc

原标题：golang 简易埋点日志上报实现
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/597360.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/533918.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/726477.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.hmnrxg.asia/arts/414863.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/346675.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/693381.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.hmnrxg.asia/arts/004844.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/471431.Doc

原标题：golang minio 分片上传断点续传
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.hmnrxg.asia/arts/922114.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.hmnrxg.asia/arts/541720.Doc

原标题：前端国际化多语言方案落地
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.hmnrxg.asia/arts/713932.Doc

原标题：本地简易配置中心动态管理
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.hmnrxg.asia/arts/059980.Doc

原标题：请求重试组件退避策略实现
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/932144.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.hmnrxg.asia/arts/592248.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.hmnrxg.asia/arts/904788.Doc

原标题：nodejs 多进程任务分发处理
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.hmnrxg.asia/arts/971874.Doc

原标题：golang defer panic 异常处理
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.hmnrxg.asia/arts/877025.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.hmnrxg.asia/arts/730743.Doc

原标题：golang redis 位图用户签到统计
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.hmnrxg.asia/arts/883919.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.hmnrxg.asia/arts/433090.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.hmnrxg.asia/arts/832138.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/701729.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.hmnrxg.asia/arts/455249.Doc

三、实战开发｜Practice
原标题：任务执行锁防止并发重复调度
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/539686.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.hmnrxg.asia/arts/713310.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/719633.Doc

原标题：golang 日志与链路 ID 关联打印
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.hmnrxg.asia/arts/156609.Doc

原标题：内存溢出问题现象识别排查
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/803226.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/374467.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.hmnrxg.asia/arts/414708.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.hmnrxg.asia/arts/487789.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/488653.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/986129.Doc

原标题：Performance：数据库join优化，大表join规避
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.hmnrxg.asia/arts/903148.Doc

原标题：golang http client 连接池调优
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.hmnrxg.asia/arts/666166.Doc

原标题：HTTP 状态码请求头完整梳理
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.hmnrxg.asia/arts/296693.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.hmnrxg.asia/arts/015028.Doc

原标题：前端权限路由动态生成实现
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.hmnrxg.asia/arts/612463.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/074987.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.hmnrxg.asia/arts/236261.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/191991.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.hmnrxg.asia/arts/415626.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.hmnrxg.asia/arts/727776.Doc

原标题：golang consul 服务发现简单示例
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/567152.Doc

原标题：服务健康检查监控接口开发
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.hmnrxg.asia/arts/596854.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.hmnrxg.asia/arts/890960.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/007833.Doc

原标题：golang docker 容器资源限制设置
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/531647.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/163634.Doc

原标题：golang docker 网络模式桥接 host
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.hmnrxg.asia/arts/001049.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.hmnrxg.asia/arts/063547.Doc

原标题：短信服务封装失败自动重试
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.hmnrxg.asia/arts/171149.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.hmnrxg.asia/arts/238268.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/677256.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.hmnrxg.asia/arts/260221.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.hmnrxg.asia/arts/361763.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.hmnrxg.asia/arts/780283.Doc

原标题：图片上传预览格式大小处理
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/267639.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.hmnrxg.asia/arts/708258.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.hmnrxg.asia/arts/078911.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.hmnrxg.asia/arts/497402.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.hmnrxg.asia/arts/859970.Doc

原标题：新手教程：本地环境变量配置全流程
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.hmnrxg.asia/arts/084130.Doc

四、架构设计｜Architecture
原标题：快速入门容器基础概念，理解镜像与容器
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/567441.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.hmnrxg.asia/arts/531390.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.hmnrxg.asia/arts/299225.Doc

原标题：golang gorm 预加载关联查询优化
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.hmnrxg.asia/arts/529294.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.hmnrxg.asia/arts/936790.Doc

原标题：eslint prettier 代码规范落地
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.hmnrxg.asia/arts/193066.Doc

原标题：golang kafka 核心概念分区副本
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.hmnrxg.asia/arts/639858.Doc

原标题：网关超时时间调优后端等待
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.hmnrxg.asia/arts/153707.Doc

原标题：golang gitlab runner 部署与注册实操
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.hmnrxg.asia/arts/745332.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.hmnrxg.asia/arts/371941.Doc

原标题：前端权限路由动态生成实现
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.hmnrxg.asia/arts/763159.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/096545.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.hmnrxg.asia/arts/458321.Doc

原标题：golang redis 锁超时业务处理
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.hmnrxg.asia/arts/336110.Doc

原标题：HTTPS 证书过期更新操作
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.hmnrxg.asia/arts/719221.Doc

原标题：golang mysql 批量导入数据实操
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.hmnrxg.asia/arts/020353.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.hmnrxg.asia/arts/642206.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.hmnrxg.asia/arts/419407.Doc

?
