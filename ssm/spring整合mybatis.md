关键在于写在xml的配置信息，用配置类进行封装
@configuration可以标记此类为配置类
把配置类生成的bean用@bean交给spring容器管理

mybatis的配置类是子类
用@import把子类的子节码文件（.class）导入到主配置类



