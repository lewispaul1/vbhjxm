最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计架构图绘制规范简单建议
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.dopjrf.asia/blog/0671707.sHtMl

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.dopjrf.asia/blog/3896691.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.dopjrf.asia/blog/6361712.sHtMl

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.dopjrf.asia/blog/2776915.sHtMl

原标题：golang 系统信号信号量处理
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.dopjrf.asia/blog/0213458.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.dopjrf.asia/blog/0840959.sHtMl

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.dopjrf.asia/blog/5551558.sHtMl

原标题：golang es 查询语句 DSL 实操
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.dopjrf.asia/blog/8275508.sHtMl

原标题：数据库排序规则统一结果一致
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.dopjrf.asia/blog/5654199.sHtMl

原标题：GET POST 接口请求参数处理
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.dopjrf.asia/blog/3206177.sHtMl

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.dopjrf.asia/blog/3360544.sHtMl

原标题：golang etcd 分布式锁实现原理
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.dopjrf.asia/blog/2758774.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.dopjrf.asia/blog/6681197.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.dopjrf.asia/blog/5612222.sHtMl

原标题：优化实践：接口批量合并减少网络请求次数
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.dopjrf.asia/blog/6426012.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.dopjrf.asia/blog/6887609.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.dopjrf.asia/blog/1586500.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.dopjrf.asia/blog/1357777.sHtMl

原标题：golang k8s helm chart 简单编写
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.dopjrf.asia/blog/3397467.sHtMl

原标题：Practice：模拟热点key，验证缓存防护策略
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.dopjrf.asia/blog/3186988.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.dopjrf.asia/blog/7227084.sHtMl

原标题：golang redis 客户端业务使用
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.dopjrf.asia/blog/4310617.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.dopjrf.asia/blog/7165238.sHtMl

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.dopjrf.asia/blog/6132548.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.dopjrf.asia/blog/4363288.sHtMl

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://book.dopjrf.asia/blog/6383055.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.dopjrf.asia/blog/6167751.sHtMl

原标题：零基础理解前后端简单交互流程
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.dopjrf.asia/blog/1903547.sHtMl

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.dopjrf.asia/blog/1276313.sHtMl

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.dopjrf.asia/blog/9880025.sHtMl

原标题：GitHub 项目提交推送完整流程讲解
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.dopjrf.asia/blog/8756985.sHtMl

原标题：实践：数据库回滚点业务调试实践
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.dopjrf.asia/blog/9625096.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.dopjrf.asia/blog/2070583.sHtMl

原标题：golang url 参数编码处理方案
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.dopjrf.asia/blog/9436190.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.dopjrf.asia/blog/8563186.sHtMl

原标题：golang mysql 行锁表锁场景区分
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.dopjrf.asia/blog/6715563.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.dopjrf.asia/blog/5919958.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.dopjrf.asia/blog/4281279.sHtMl

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.dopjrf.asia/blog/0642437.sHtMl

原标题：部署实践：服务器SSH安全加固配置实践
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.dopjrf.asia/blog/7496735.sHtMl


二、踩坑排错｜Troubleshooting
原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.dopjrf.asia/blog/7729649.sHtMl

原标题：部署复盘：服务启动顺序依赖处理方案
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.dopjrf.asia/blog/1815119.sHtMl

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.dopjrf.asia/blog/3897498.sHtMl

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.dopjrf.asia/blog/9996140.sHtMl

原标题：golang 信号捕获程序退出处理
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.dopjrf.asia/blog/4900877.sHtMl

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.dopjrf.asia/blog/4264286.sHtMl

原标题：golang rate‑limiter 限流组件
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.dopjrf.asia/blog/4725896.sHtMl

原标题：golang docker 部署 kafka 本地调试
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.dopjrf.asia/blog/2762509.sHtMl

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.dopjrf.asia/blog/5689534.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.dopjrf.asia/blog/7350359.sHtMl

原标题：golang redis 锁超时业务处理
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.dopjrf.asia/blog/4347210.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.dopjrf.asia/blog/8726970.sHtMl

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.dopjrf.asia/blog/6477836.sHtMl

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.dopjrf.asia/blog/2325981.sHtMl

原标题：零基础理解前后端简单交互流程
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.dopjrf.asia/blog/9227849.sHtMl

原标题：新手参与开源社区贡献指南
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.dopjrf.asia/blog/6454626.sHtMl

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.dopjrf.asia/blog/0599798.sHtMl

原标题：golang 速率限制令牌桶实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.dopjrf.asia/blog/9323872.sHtMl

原标题：golang docker 部署 mongodb 开发环境
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.dopjrf.asia/blog/6100939.sHtMl

原标题：golang redis 缓存穿透解决方案
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.dopjrf.asia/blog/1218354.sHtMl

原标题：磁盘 inode 耗尽文件创建失败
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.dopjrf.asia/blog/5913932.sHtMl

原标题：golang kafka 监控指标简单梳理
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.dopjrf.asia/blog/4785896.sHtMl

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.dopjrf.asia/blog/5781152.sHtMl

原标题：nodejs 脚手架工具开发完整教程
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.dopjrf.asia/blog/1942632.sHtMl

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.dopjrf.asia/blog/8581949.sHtMl

原标题：实践：多配置文件合并加载组件实现
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.dopjrf.asia/blog/3430231.sHtMl

原标题：nodejs 读取大文件 csv 处理方案
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.dopjrf.asia/blog/6491439.sHtMl

原标题：实战：Redis管道批量操作性能优化实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.dopjrf.asia/blog/8652099.sHtMl

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.dopjrf.asia/blog/4281766.sHtMl

原标题：新手参与开源社区贡献指南
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.dopjrf.asia/blog/8993080.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.dopjrf.asia/blog/8954441.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.dopjrf.asia/blog/7288577.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.dopjrf.asia/blog/1665345.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.dopjrf.asia/blog/4165768.sHtMl

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.dopjrf.asia/blog/5280271.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.dopjrf.asia/blog/4086847.sHtMl

原标题：浏览器缓存强制刷新方案
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.dopjrf.asia/blog/4904042.sHtMl

原标题：前端 pdf 预览渲染方案对比
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.dopjrf.asia/blog/6383421.sHtMl

原标题：golang jwt 鉴权中间件完整示例
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.dopjrf.asia/blog/7911752.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.dopjrf.asia/blog/4617641.sHtMl

三、实战开发｜Practice
原标题：golang 大文件 http 下载服务
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.dopjrf.asia/blog/3038167.sHtMl

原标题：批量操作分批处理防止 OOM
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.dopjrf.asia/blog/0008933.sHtMl

原标题：限流规则误拦截正常请求修复
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.dopjrf.asia/blog/1032196.sHtMl

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.dopjrf.asia/blog/7595165.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.dopjrf.asia/blog/5902133.sHtMl

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.dopjrf.asia/blog/3414079.sHtMl

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.dopjrf.asia/blog/8053769.sHtMl

原标题：golang prometheus metrics 埋点开发
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.dopjrf.asia/blog/3715396.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.dopjrf.asia/blog/4216821.sHtMl

原标题：golang 优雅处理系统信号 SIGINT
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.dopjrf.asia/blog/9354046.sHtMl

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.dopjrf.asia/blog/0753506.sHtMl

原标题：golang 系统设计批量处理优化业务性能
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.dopjrf.asia/blog/3050099.sHtMl

原标题：入门实践：简单错误码设计与使用规范
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.dopjrf.asia/blog/8510530.sHtMl

原标题：零基础理解前后端简单交互流程
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.dopjrf.asia/blog/7583403.sHtMl

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.dopjrf.asia/blog/4620018.sHtMl

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.dopjrf.asia/blog/6163247.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.dopjrf.asia/blog/7830329.sHtMl

原标题：golang validator 自定义校验规则
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.dopjrf.asia/blog/7498530.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.dopjrf.asia/blog/6383593.sHtMl

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.dopjrf.asia/blog/6126887.sHtMl

原标题：Fork 开源项目同步上游代码
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.dopjrf.asia/blog/5911785.sHtMl

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.dopjrf.asia/blog/0696962.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.dopjrf.asia/blog/2498065.sHtMl

原标题：nestjs 拦截器过滤器管道实战
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.dopjrf.asia/blog/0332183.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.dopjrf.asia/blog/9727443.sHtMl

原标题：请求工具封装统一异常处理
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.dopjrf.asia/blog/8626970.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.dopjrf.asia/blog/2914254.sHtMl

原标题：Architecture：日志、监控、告警整套可观测架构
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.dopjrf.asia/blog/5528339.sHtMl

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.dopjrf.asia/blog/6037319.sHtMl

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.dopjrf.asia/blog/5994053.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.dopjrf.asia/blog/7108009.sHtMl

原标题：防火墙 IP 白名单回调接口放行
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.dopjrf.asia/blog/2312281.sHtMl

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.dopjrf.asia/blog/1806589.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.dopjrf.asia/blog/3797750.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.dopjrf.asia/blog/7143203.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.dopjrf.asia/blog/5468072.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.dopjrf.asia/blog/4076672.sHtMl

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.dopjrf.asia/blog/1978535.sHtMl

原标题：异步异常捕获避免进程崩溃
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.dopjrf.asia/blog/7612272.sHtMl

原标题：golang docker 镜像安全扫描漏洞
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.dopjrf.asia/blog/7073946.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计接口频率限制业务落地
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.dopjrf.asia/blog/0502263.sHtMl

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.dopjrf.asia/blog/4012738.sHtMl

原标题：golang 开发环境快速搭建指南
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.dopjrf.asia/blog/5839952.sHtMl

原标题：golang toml 配置文件解析教程
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.dopjrf.asia/blog/0058852.sHtMl

原标题：golang docker compose 环境变量
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.dopjrf.asia/blog/7486786.sHtMl

原标题：golang 接口请求日志记录中间件
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.dopjrf.asia/blog/2211448.sHtMl

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.dopjrf.asia/blog/0668607.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.dopjrf.asia/blog/7506074.sHtMl

原标题：数据库分表路由写入分片修正
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.dopjrf.asia/blog/8092542.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.dopjrf.asia/blog/3142115.sHtMl

原标题：golang 简易埋点日志上报实现
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.dopjrf.asia/blog/6490607.sHtMl

原标题：开源实践：开源项目如何写好PullRequest
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.dopjrf.asia/blog/7363814.sHtMl

原标题：golang 系统设计错误码体系完整设计
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.dopjrf.asia/blog/6416473.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.dopjrf.asia/blog/6950738.sHtMl

原标题：Git commit 钩子提交规范校验
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.dopjrf.asia/blog/4650868.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.dopjrf.asia/blog/6455786.sHtMl

原标题：开源项目本地运行排错完整清单
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.dopjrf.asia/blog/8911678.sHtMl

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.dopjrf.asia/blog/0865813.sHtMl

?
