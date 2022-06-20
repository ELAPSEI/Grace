#elapse

## springboot整合Mybatis
- 1.找不到或无法加载主类
>maven命令mvn idea model作用：重新构建.iml文件 在rebuild project重建项目
- 2 mybatis.generator1.3.7以下版本不会覆盖mapper.xml版本
>通过配置文件生成mapper.xml时覆盖原文件<plugin type="org.mybatis.generator.plugins.UnmergeableXmlMappersPlugin" />
