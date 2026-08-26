最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang redis 分布式计数器开发
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.b2hisu.asia/arts/726925.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.b2hisu.asia/arts/142224.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.b2hisu.asia/arts/118446.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/908653.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.b2hisu.asia/arts/604033.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.b2hisu.asia/arts/982488.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.b2hisu.asia/arts/263699.Doc

原标题：nodejs 跨域中间件配置细节
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/073251.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/971780.Doc

原标题：缓存穿透防护保护数据库
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/353100.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.b2hisu.asia/arts/427715.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/667479.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.b2hisu.asia/arts/138308.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.b2hisu.asia/arts/859527.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.b2hisu.asia/arts/565285.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.b2hisu.asia/arts/293633.Doc

原标题：静态站点自动部署发布方案
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.b2hisu.asia/arts/971271.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.b2hisu.asia/arts/219834.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/594701.Doc

原标题：golang redis 发布订阅简单示例
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.b2hisu.asia/arts/497841.Doc

原标题：Git 标签版本标记发布管理
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.b2hisu.asia/arts/209750.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.b2hisu.asia/arts/457007.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/323294.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.b2hisu.asia/arts/701031.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/901476.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/230068.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.b2hisu.asia/arts/563942.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/019146.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.b2hisu.asia/arts/472850.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.b2hisu.asia/arts/458762.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/565814.Doc

原标题：golang es 映射 mapping 设计避坑
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.b2hisu.asia/arts/815991.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.b2hisu.asia/arts/048643.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.b2hisu.asia/arts/311987.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.b2hisu.asia/arts/618080.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.b2hisu.asia/arts/016886.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.b2hisu.asia/arts/508033.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.b2hisu.asia/arts/059114.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/423876.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.b2hisu.asia/arts/248016.Doc


二、踩坑排错｜Troubleshooting
原标题：OpenSource：开源项目许可证License选型指南
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/985479.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.b2hisu.asia/arts/453250.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/238793.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.b2hisu.asia/arts/526875.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.b2hisu.asia/arts/711749.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/313286.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.b2hisu.asia/arts/100625.Doc

原标题：golang github actions 缓存依赖提速
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.b2hisu.asia/arts/319933.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/879872.Doc

原标题：golang redis 连接池参数最佳值
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.b2hisu.asia/arts/234607.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/755818.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.b2hisu.asia/arts/312263.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/822157.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/589035.Doc

原标题：重复提交幂等防护再次讲解
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.b2hisu.asia/arts/311638.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.b2hisu.asia/arts/897634.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.b2hisu.asia/arts/187777.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.b2hisu.asia/arts/161730.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.b2hisu.asia/arts/711311.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/999187.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.b2hisu.asia/arts/965817.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.b2hisu.asia/arts/389345.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.b2hisu.asia/arts/163153.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.b2hisu.asia/arts/213516.Doc

原标题：golang redis 发布订阅简单示例
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/751668.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.b2hisu.asia/arts/490924.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/290323.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.b2hisu.asia/arts/823098.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.b2hisu.asia/arts/063009.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.b2hisu.asia/arts/931743.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.b2hisu.asia/arts/158559.Doc

原标题：golang mysql json 字段查询使用
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.b2hisu.asia/arts/344394.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.b2hisu.asia/arts/595840.Doc

原标题：Shell 运维脚本服务器效率提升
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.b2hisu.asia/arts/822176.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.b2hisu.asia/arts/197028.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.b2hisu.asia/arts/344910.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.b2hisu.asia/arts/275508.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/790318.Doc

原标题：CI 持续集成自动构建流程
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.b2hisu.asia/arts/652295.Doc

原标题：golang 系统设计分布式任务调度
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.b2hisu.asia/arts/671743.Doc

三、实战开发｜Practice
原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.b2hisu.asia/arts/289897.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/343840.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.b2hisu.asia/arts/190356.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.b2hisu.asia/arts/505447.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.b2hisu.asia/arts/828068.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.b2hisu.asia/arts/806570.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/082108.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/903950.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.b2hisu.asia/arts/188920.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/998056.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/480261.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.b2hisu.asia/arts/891732.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/965887.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/569580.Doc

原标题：对象存储上传下载权限实操
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.b2hisu.asia/arts/086610.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/073937.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.b2hisu.asia/arts/693402.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.b2hisu.asia/arts/535710.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.b2hisu.asia/arts/867491.Doc

原标题：golang 系统设计内存高占用排查思路
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.b2hisu.asia/arts/084125.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.b2hisu.asia/arts/004993.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.b2hisu.asia/arts/342845.Doc

原标题：golang gorm ORM 数据库操作
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.b2hisu.asia/arts/083628.Doc

原标题：前端防抖节流高频事件处理
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/264047.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.b2hisu.asia/arts/212476.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/859137.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.b2hisu.asia/arts/648310.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/947971.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.b2hisu.asia/arts/781100.Doc

原标题：golang k8s 滚动更新回滚策略
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.b2hisu.asia/arts/561105.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/861408.Doc

原标题：nodejs 事件循环机制完整讲解
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.b2hisu.asia/arts/691984.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.b2hisu.asia/arts/754109.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/374872.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/690095.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/198057.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/298785.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/123222.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.b2hisu.asia/arts/271186.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.b2hisu.asia/arts/311536.Doc

四、架构设计｜Architecture
原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.b2hisu.asia/arts/973461.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.b2hisu.asia/arts/077958.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.b2hisu.asia/arts/280398.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.b2hisu.asia/arts/753037.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.b2hisu.asia/arts/660729.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/688095.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/120745.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.b2hisu.asia/arts/425283.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/294000.Doc

原标题：数据库分表存储大表优化方案
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.b2hisu.asia/arts/452965.Doc

原标题：快速入门消息通知简单实现方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/745530.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.b2hisu.asia/arts/482707.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.b2hisu.asia/arts/253416.Doc

原标题：golang websocket 服务端开发
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.b2hisu.asia/arts/271170.Doc

原标题：golang mysql 批量导入数据实操
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.b2hisu.asia/arts/353055.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/261632.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/054048.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/129525.Doc

?
