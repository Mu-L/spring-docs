*   [1\. Spring的远程处理和Web服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting)
    *   [1.1. 使用RMI公开服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-rmi)
        *   [1.1.1. 使用RmiServiceExporter暴露服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-rmi-server)
        *   [1.1.2. 连接客户端和服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-rmi-client)
    *   [1.2. 使用Hessian通过HTTP远程调用服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-caucho-protocols)
        *   [1.2.1. 使用DispatcherServlet 连接Hessian](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-caucho-protocols-hessian)
        *   [1.2.2. 使用HessianServiceExporter暴露您的Bean](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-caucho-protocols-hessian-server)
        *   [1.2.3. 在客户端的服务中链接](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-caucho-protocols-hessian-client)
        *   [1.2.4. 通过Hessian公开的服务来应用HTTP基本的验证](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-caucho-protocols-security)
    *   [1.3. 使用HTTP调用公开服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-httpinvoker)
        *   [1.3.1. 公开服务对象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-httpinvoker-server)
        *   [1.3.2. 在客户端链接服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-httpinvoker-client)
    *   [1.4. Web Services](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-web-services)
        *   [1.4.1. 使用JAX-WS公开基于Servlet的Web服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-web-services-jaxws-export-servlet)
        *   [1.4.2. 使用JAX-WS公开独立Web服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-web-services-jaxws-export-standalone)
        *   [1.4.3. 使用JAX-WS RI的Spring支持公开Web服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-web-services-jaxws-export-ri)
        *   [1.4.4. 使用JAX-WS访问Web服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-web-services-jaxws-access)
    *   [1.5. 通过JMS公开服务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-jms)
        *   [1.5.1. 服务端的配置](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-jms-server)
        *   [1.5.2. 客户端方面的配置](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-jms-client)
    *   [1.6. AMQP](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-amqp)
    *   [1.7. 选择技术时的注意事项](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#remoting-considerations)
    *   [1.8. REST 端点](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-client-access)
        *   [1.8.1. 使用 RestTemplate](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-resttemplate)
            *   [初始化](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-resttemplate-create)
            *   [URIs](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-resttemplate-uri)
            *   [Headers](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-template-headers)
            *   [Body](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-template-body)
            *   [消息转换器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-message-conversion)
            *   [Jackson JSON 视图](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-template-jsonview)
            *   [Multipart](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-template-multipart)
        *   [1.8.2. 使用 AsyncRestTemplate (已废弃)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/remoting.md#rest-async-resttemplate)
*   [2\. 企业级JavaBean(EJB) 集成](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb)
    *   [2.1. 访问 EJB](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb-access)
        *   [2.1.1. 概念](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb-access-concepts)
        *   [2.1.2. 访问本地的SLSBs](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb-access-local)
        *   [2.1.3. 访问远程的SLSBs](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb-access-remote)
        *   [2.1.4. 访问EJB 2.x SLSBs 和 EJB 3 SLSBs](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/ejb.md#ejb-access-ejb2-ejb3)
*   [3\. JMS (Java 消息服务 )](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms)
    *   [3.1. 使用 Spring JMS](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-using)
        *   [3.1.1. 使用 JmsTemplate](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-jmstemplate)
        *   [3.1.2. Connections](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-connections)
            *   [缓存消息资源](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-caching-resources)
            *   [使用 SingleConnectionFactory](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-connection-factory)
            *   [使用 CachingConnectionFactory](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jdbc-connection-factory-caching)
        *   [3.1.3. 目的地管理](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-destinations)
        *   [3.1.4. 消息监听容器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-mdp)
            *   [使用 SimpleMessageListenerContainer](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-mdp-simple)
            *   [使用 DefaultMessageListenerContainer](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-mdp-default)
        *   [3.1.5. 事务管理](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-tx)
    *   [3.2. 发送消息](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-sending)
        *   [3.2.1. 使用消息转换器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-msg-conversion)
        *   [3.2.2.  使用 SessionCallback 和 ProducerCallback](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-callbacks)
    *   [3.3. 接收消息](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-receiving)
        *   [3.3.1. 同步接收](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-receiving-sync)
        *   [3.3.2. 异步接收：消息驱动的POJO](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-asynchronousMessageReception)
        *   [3.3.3. 使用SessionAwareMessageListener接口](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-receiving-async-session-aware-message-listener)
        *   [3.3.4. Using MessageListenerAdapter](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-receiving-async-message-listener-adapter)
        *   [3.3.5. 处理事务内的消息](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-tx-participation)
    *   [3.4. 用于支持JCA消息端点](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-jca-message-endpoint-manager)
    *   [3.5. 注解驱动监听器端点](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-annotated)
        *   [3.5.1. 允许监听器端点注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-annotated-support)
        *   [3.5.2. 编程端点注册](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-annotated-programmatic-registration)
        *   [3.5.3. 注解端点方法签名](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-annotated-method-signature)
        *   [3.5.4. 响应管理](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-annotated-response)
    *   [3.6. JMS命名空间支持](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jms.md#jms-namespace)
*   [4\. JMX](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx)
    *   [4.1. 公开你的bean给JMX](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-exporting)
        *   [4.1.1. 创建一个MBeanServer](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-exporting-mbeanserver)
        *   [4.1.2. 重用已有的MBeanServer](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-mbean-server)
        *   [4.1.3. 延迟初始化的MBean](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-exporting-lazy)
        *   [4.1.4. 自动注册MBeans](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-exporting-auto)
        *   [4.1.5. 控制注册的行为](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-exporting-registration-behavior)
    *   [4.2. 控制您的Bean的管理界面](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface)
        *   [4.2.1. 使用MBeanInfoAssembler 接口](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-assembler)
        *   [4.2.2. 使用源码级别的元数据：Java注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-metadata)
        *   [4.2.3. 源码级别的元数据类型](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-metadata-types)
        *   [4.2.4. 使用AutodetectCapableMBeanInfoAssembler 接口](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-autodetect)
        *   [4.2.5. 使用Java接口定义管理接口](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-java)
        *   [4.2.6. 使用 MethodNameBasedMBeanInfoAssembler](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-interface-methodnames)
    *   [4.3. 为你的bean控制ObjectName实例](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-naming)
        *   [4.3.1. 从属性中读取ObjectName](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-naming-properties)
        *   [4.3.2. 使用 MetadataNamingStrategy](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-naming-metadata)
        *   [4.3.3. 配置基于注解的MBean导出](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-context-mbeanexport)
    *   [4.4. 使用 JSR-160 连接器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-jsr160)
        *   [4.4.1. 服务端的连接器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-jsr160-server)
        *   [4.4.2. 客户端连接器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-jsr160-client)
        *   [4.4.3. 基于 Hessian/SOAP的JMX](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-jsr160-protocols)
    *   [4.5. 通过代理访问MBeans](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-proxy)
    *   [4.6. 通知](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-notifications)
        *   [4.6.1. 注册通知的监听器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-notifications-listeners)
        *   [4.6.2.发布通知](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-notifications-publishing)
    *   [4.7. 更多资源](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/jmx.md#jmx-resources)
*   [5\. JCA CCI](#https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci)
    *   [5.1. 配置 CCI](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-config)
        *   [5.1.1. 连接器配置](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-config-connector)
        *   [5.1.2. 在Spring中配置ConnectionFactory](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-config-connectionfactory)
        *   [5.1.3. 配置CCI连接](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-config-cci-connections)
        *   [5.1.4. 使用单独的CCI连接](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-config-single-connection)
    *   [5.2. 使用Spring的CCI访问支持](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-using)
        *   [5.2.1. 记录转换](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-record-creator)
        *   [5.2.2. 使用 CciTemplate](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-using-template)
        *   [5.2.3. DAO支持](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-using-dao)
        *   [5.2.4. 自动输出记录生成](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#automatic-output-generation)
        *   [5.2.5. CciTemplate Interaction 总结](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#template-summary)
        *   [5.2.6. 直接使用CCI连接和交互](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-straight)
        *   [5.2.7. CciTemplate 用法示例](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-template-example)
    *   [5.3. 将CCI访问建模为操作对象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-object)
        *   [5.3.1. 使用 MappingRecordOperation](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-object-mapping-record)
        *   [5.3.2. 使用 MappingCommAreaOperation](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-object-mapping-comm-area)
        *   [5.3.3. 自动的输出记录生成](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-automatic-record-gen)
        *   [5.3.4. 总结](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-object-summary)
        *   [5.3.5. MappingRecordOperation 使用例子](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-objects-mappring-record-example)
        *   [5.3.6. MappingCommAreaOperation 的使用例子](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-objects-mapping-comm-area-example)
    *   [5.4. 事务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cci.md#cci-tx)
*   [6\. 电子邮件](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail)
    *   [6.1. Usage](#mail-usage)
        *   [6.1.1. MailSender与 SimpleMailMessage的基本用法](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-usage-simple)
        *   [6.1.2. 使用 JavaMailSender 和 MimeMessagePreparator](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-usage-mime)
    *   [6.2.使用JavaMail MimeMessageHelper](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-javamail-mime)
        *   [6.2.1. 发送附件和内嵌资源](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-javamail-mime-attachments)
            *   [附件](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-javamail-mime-attachments-attachment)
            *   [内嵌资源](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-javamail-mime-attachments-inline)
        *   [6.2.2. 使用模板库创建电子邮件内容](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/mail.md#mail-templates)
*   [7\. 执行任务和任务计划](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling)
    *   [7.1. Spring TaskExecutor 抽象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-executor)
        *   [7.1.1. TaskExecutor 类型](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-executor-types)
        *   [7.1.2. 使用 TaskExecutor](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-executor-usage)
    *   [7.2. Spring TaskScheduler 抽象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-scheduler)
        *   [7.2.1. Trigger 接口](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-trigger-interface)
        *   [7.2.2. Trigger 实现](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-trigger-implementations)
        *   [7.2.3. TaskScheduler 实现](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-scheduler-implementations)
    *   [7.3. 对调度和异步执行的注解支持](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-annotation-support)
        *   [7.3.1. 启用调度注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-enable-annotation-support)
        *   [7.3.2. @Scheduled 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-annotation-support-scheduled)
        *   [7.3.3. @Async 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-annotation-support-async)
        *   [7.3.4. 使用 @Async的Executor的条件](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-annotation-support-qualification)
        *   [7.3.5. 使用@Async的异常管理](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-annotation-support-exception)
    *   [7.4. task 命名空间](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-namespace)
        *   [7.4.1. 'scheduler' 元素](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-namespace-scheduler)
        *   [7.4.2. executor 元素](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-namespace-executor)
        *   [7.4.3. 'scheduled-tasks' 元素](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-task-namespace-scheduled-tasks)
    *   [7.5. 使用Quartz的Scheduler](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-quartz)
        *   [7.5.1. 使用JobDetailFactoryBean](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-quartz-jobdetail)
        *   [7.5.2. 使用 MethodInvokingJobDetailFactoryBean](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-quartz-method-invoking-job)
        *   [7.5.3. 使用triggers和SchedulerFactoryBean来织入任务](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/scheduling.md#scheduling-quartz-cron)
*   [8\. 缓存抽象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache)
    *   [8.1. 了解缓存抽象](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-strategies)
    *   [8.2. 基于注解声明缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations)
        *   [8.2.1. @Cacheable 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable)
            *   [默认的键生成](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-default-key)
            *   [自定义键生成器](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-key)
            *   [默认的缓存解析](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-default-cache-resolver)
            *   [自定义缓存解析](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-cache-resolver)
            *   [同步缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-synchronized)
            *   [条件缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-cacheable-condition)
            *   [可用的缓存SpEL表达式内容](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-spel-context)
        *   [8.2.2. @CachePut 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-put)
        *   [8.2.3. @CacheEvict 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-evict)
        *   [8.2.4. @Caching 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-caching)
        *   [8.2.5. @CacheConfig 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotations-config)
        *   [8.2.6. 启用缓存注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotation-enable)
        *   [8.2.7. 使用自定义的注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-annotation-stereotype)
    *   [8.3. JCache (JSR-107) 注解](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-jsr-107)
        *   [8.3.1. 特性总结](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-jsr-107-summary)
        *   [8.3.2. 启用 JSR-107 支持](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#enabling-jsr-107-support)
    *   [8.4. 声明式基于XML的缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-declarative-xml)
    *   [8.5. 配置缓存的存储](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration)
        *   [8.5.1. 基于JDKConcurrentMap 缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-jdk)
        *   [8.5.2. 基于Ehcache的缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-ehcache)
        *   [8.5.3. Caffeine Cache](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-caffeine)
        *   [8.5.4. 基于GemFire的缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-gemfire)
        *   [8.5.5. JSR-107 缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-jsr107)
        *   [8.5.6. 处理没有后端的缓存](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-store-configuration-noop)
    *   [8.6. 各种各样的后端缓存插件](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-plug)
    *   [8.7. 我可以如何设置TTL/TTI/Eviction policy/XXX特性?](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/cache.md#cache-specific-config)
*   [9\. 附录](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#appendix)
    *   [9.1. XML Schemas](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas)
        *   [9.1.1. jee Schema](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee)
            *   [<jee:jndi-lookup/> (simple)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-jndi-lookup)
            *   [<jee:jndi-lookup/> (使用单个JNDI环境设置)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-jndi-lookup-environment-single)
            *   [<jee:jndi-lookup/> (多个JNDI环境设置)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-jndi-lookup-evironment-multiple)
            *   [<jee:jndi-lookup/> (复杂)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-jndi-lookup-complex)
            *   [<jee:local-slsb/> (简单)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-local-slsb)
            *   [<jee:local-slsb/> (复杂)](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-local-slsb-complex)
            *   [<jee:remote-slsb/>](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jee-remote-slsb)
        *   [9.1.2. jms Schema](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-jms)
        *   [9.1.3. 使用 <context:mbean-export/>](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-context-mbe)
        *   [9.1.4. cache Schema](https://github.com/DocsHome/spring-docs/blob/master/pages/integration/appendix.md#xsd-schemas-cache)