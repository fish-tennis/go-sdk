**v1.5.0** (2021/11/02)
- 增加支持复杂结构类型

**v1.4.2** (2021/09/23)
- BatchConsumer 修复：修复多线程Add数据时可能会错误的问题

**v1.4.1** (2021/08/24)
- 优化：properties里支持array类型和slice类型
- 优化：Flush()和Close()增加失败时返回error

**v1.4.0** (2021/05/10)
- BatchConsumer 优化：增加缓存，在网络连接中断时缓存数据

**v1.3.0** (2020/11/25)
- LogConsumer 优化：支持自动创建目录
- 优化：增加自动上传功能

**v1.2.0** (2020/08/24)
- 支持track_update和track_overwrite接口

**v1.1.1** (2020/07/08)
- 字段#time支持上传符合TA格式的字符串
- 去除字段2k大小的限制

**v1.1.0** (2020/02/12)
- 支持上报数组类型
- 支持 UserAppend 接口
- DebugConsumer 优化: 在服务端对数据进行更完备准确地校验
- BatchConsumer 性能优化：支持配置压缩模式；移除 Base64 编码

**v1.0.2** (2019/12/25)
- 支持 UserUnset 接口

**v1.0.1** (2019/12/12)
- BugFix: 允许为空的属性值不写入日志中

**v1.0.0** (2019/09/25)
- 初始版本, 实现了数据上报核心功能
    - Track: 追踪用户行为事件
    - 公共事件属性设置
    - 用户属性设置: UserSet、UserSetOnce、UserAdd、UserDelete
- 支持: LogConsumer, DebugConsumer, BatchConsumer
