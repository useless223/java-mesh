2.0.1
1.解决非守护线程导致应用无法停止的问题
2.解决字节码增强线程死锁的问题
3.解决lambda表达式的异步线程调用链展示异常的问题
4.解决第一次加载类的请求没有采集的问题
5.添加spanId长度限制
6.支持业务状态码的key配置多层
7.解决collector注册过快导致空指针的问题

2.0.2
1.业务code的值支持startwith匹配配置startsWith("test")
2.支持采集JVM中所有线程状态的数量
3.解决和skywalking启动冲突的问题

2.0.3
1.解决jdkhttpclient插件日志报空指针的问题
2.添加调master接口的超时时间设置
3.kafka监控数据采集
4.解决解析多层业务状态码错误的问题
5.解决dubbo2.6.3调用链不完整问题
6.解决dubbo2.7.8高版本不增强问题

2.0.4
1.支持functiongraph调用链数据采集
2.添加方法拦截前后发送异常采集的日志
3.修改异步线程拦截逻辑 没有采样时能把gtraceid传递下去
4.支持grpc数据采集
5.支持在配置文件中配置access地址
6.解决cse数据采集报空指针的异常
7.解决低版本grpcclient没有调用链数据的问题

2.0.5
1.支持reactor-netty
2.解决spring的url没有规整的问题
3.解决与百度openrasp冲突的问题