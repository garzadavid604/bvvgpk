最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.1d3jeg.asia/arts/718818.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/534011.Doc

原标题：golang 结构体深拷贝几种实现
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.1d3jeg.asia/arts/743424.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.1d3jeg.asia/arts/821287.Doc

原标题：环境变量不生效问题修复
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.1d3jeg.asia/arts/754825.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/052826.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/788201.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.1d3jeg.asia/arts/218663.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.1d3jeg.asia/arts/862118.Doc

原标题：golang redis 客户端业务使用
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/794736.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.1d3jeg.asia/arts/385511.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/860613.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.1d3jeg.asia/arts/677032.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.1d3jeg.asia/arts/353623.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.1d3jeg.asia/arts/139584.Doc

原标题：golang alertmanager 钉钉告警推送
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.1d3jeg.asia/arts/935230.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/281769.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/132436.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.1d3jeg.asia/arts/711755.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/393614.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/976380.Doc

原标题：golang es 高亮搜索结果实现方案
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/312878.Doc

原标题：golang docker 镜像体积优化技巧
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.1d3jeg.asia/arts/856980.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/704736.Doc

原标题：golang makefile 自动化构建脚本
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.1d3jeg.asia/arts/479053.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.1d3jeg.asia/arts/319236.Doc

原标题：移动端适配 rem vw 方案对比
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.1d3jeg.asia/arts/484109.Doc

原标题：消息队列重复消费业务处理
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.1d3jeg.asia/arts/773492.Doc

原标题：golang 互斥锁读写锁并发安全
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/266656.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/676941.Doc

原标题：缓存穿透防护保护数据库
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.1d3jeg.asia/arts/536614.Doc

原标题：golang jwt 过期刷新 token 实现
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/208571.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/953950.Doc

原标题：golang mongodb 聚合管道实操案例
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/901102.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/923036.Doc

原标题：包管理器依赖缓存清理
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.1d3jeg.asia/arts/315611.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/828223.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.1d3jeg.asia/arts/674703.Doc

原标题：从零搭建本地开发环境完整教程
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.1d3jeg.asia/arts/567470.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/466356.Doc


二、踩坑排错｜Troubleshooting
原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.1d3jeg.asia/arts/129871.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/466958.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/886658.Doc

原标题：golang 内存缓存简单实现方案
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.1d3jeg.asia/arts/117559.Doc

原标题：golang goroutine 协程基础实操
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.1d3jeg.asia/arts/742474.Doc

原标题：包管理器依赖缓存清理
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/700923.Doc

原标题：前后端会话登录状态持久化
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.1d3jeg.asia/arts/548305.Doc

原标题：golang redis 分布式计数器开发
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/152770.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/004074.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.1d3jeg.asia/arts/271921.Doc

原标题：golang 单元测试 table‑driven
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.1d3jeg.asia/arts/842778.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.1d3jeg.asia/arts/725514.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.1d3jeg.asia/arts/088770.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.1d3jeg.asia/arts/267911.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.1d3jeg.asia/arts/977704.Doc

原标题：golang kafka 死信队列业务落地
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.1d3jeg.asia/arts/011876.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/180441.Doc

原标题：golang 消息死信处理业务逻辑
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.1d3jeg.asia/arts/077045.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/074982.Doc

原标题：API 接口调试与异常处理实战
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/675334.Doc

原标题：golang gitlab runner 部署与注册实操
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/784765.Doc

原标题：批量异步处理系统业务落地
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/455252.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/960981.Doc

原标题：从零学习简单分页逻辑实现思路
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.1d3jeg.asia/arts/492770.Doc

原标题：零基础理解进程、线程基础概念区别
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.1d3jeg.asia/arts/647957.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/471990.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.1d3jeg.asia/arts/933950.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.1d3jeg.asia/arts/599119.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.1d3jeg.asia/arts/199170.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/386528.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/154854.Doc

原标题：golang 系统设计大表加索引线上执行方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/263683.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/647580.Doc

原标题：golang elasticsearch 索引设计思路
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.1d3jeg.asia/arts/482399.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.1d3jeg.asia/arts/892298.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/364209.Doc

原标题：golang http 代理客户端配置
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.1d3jeg.asia/arts/990779.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/177961.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/248180.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.1d3jeg.asia/arts/785582.Doc

三、实战开发｜Practice
原标题：WSL 搭建 Windows Linux 开发环境
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.1d3jeg.asia/arts/015846.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.1d3jeg.asia/arts/607638.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.1d3jeg.asia/arts/292957.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/883283.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.1d3jeg.asia/arts/917405.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.1d3jeg.asia/arts/915413.Doc

原标题：golang 系统设计多级缓存架构落地
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.1d3jeg.asia/arts/673143.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.1d3jeg.asia/arts/982917.Doc

原标题：golang k8s job 一次性任务执行
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.1d3jeg.asia/arts/549290.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/524461.Doc

原标题：全局异常处理器接口返回统一
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.1d3jeg.asia/arts/535522.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.1d3jeg.asia/arts/805157.Doc

原标题：请求重试组件退避策略实现
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/830192.Doc

原标题：golang etcd 分布式锁实现原理
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.1d3jeg.asia/arts/367780.Doc

原标题：数据库分表存储大表优化方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.1d3jeg.asia/arts/144103.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.1d3jeg.asia/arts/982529.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.1d3jeg.asia/arts/393788.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/111072.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/275351.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.1d3jeg.asia/arts/900663.Doc

原标题：echarts 大数据渲染性能调优
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.1d3jeg.asia/arts/422245.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.1d3jeg.asia/arts/341094.Doc

原标题：golang k8s service 服务暴露几种类型
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/417114.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.1d3jeg.asia/arts/039002.Doc

原标题：YAML 配置文件语法快速上手
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.1d3jeg.asia/arts/264775.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.1d3jeg.asia/arts/366111.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.1d3jeg.asia/arts/792730.Doc

原标题：浏览器内存泄漏排查前端页面
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.1d3jeg.asia/arts/881545.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.1d3jeg.asia/arts/206493.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.1d3jeg.asia/arts/483669.Doc

原标题：Dockerfile 编写容器打包实战
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.1d3jeg.asia/arts/241687.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/110503.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/898713.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.1d3jeg.asia/arts/668742.Doc

原标题：Nginx 丢失请求头配置修正
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/453424.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.1d3jeg.asia/arts/892165.Doc

原标题：限流组件计数器令牌桶模式实现
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.1d3jeg.asia/arts/612027.Doc

原标题：零基础理解读写分离基础思想
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.1d3jeg.asia/arts/752216.Doc

原标题：react 状态管理方案选型对比
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/122179.Doc

原标题：对象存储上传下载权限实操
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.1d3jeg.asia/arts/886125.Doc

四、架构设计｜Architecture
原标题：golang 系统设计压力测试性能测试执行流程
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.1d3jeg.asia/arts/930524.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.1d3jeg.asia/arts/744009.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.1d3jeg.asia/arts/894691.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.1d3jeg.asia/arts/561608.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.1d3jeg.asia/arts/048975.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.1d3jeg.asia/arts/618866.Doc

原标题：golang md5 sha 加密工具实现
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.1d3jeg.asia/arts/192876.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.1d3jeg.asia/arts/529747.Doc

原标题：浮点计算精度错误处理方案
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.1d3jeg.asia/arts/492946.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.1d3jeg.asia/arts/597109.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.1d3jeg.asia/arts/792847.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.1d3jeg.asia/arts/374954.Doc

原标题：golang mysql exists in 性能对比
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.1d3jeg.asia/arts/501513.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.1d3jeg.asia/arts/326872.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.1d3jeg.asia/arts/937213.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.1d3jeg.asia/arts/300495.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.1d3jeg.asia/arts/618173.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.1d3jeg.asia/arts/315980.Doc

?
