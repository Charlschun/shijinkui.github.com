gradle 常用
==========


命令
----------------
1.    gradle dependencies
      查看依赖
2.    gradle properties
      查看所有属性
      
      ```
      task printDeps(dependsOn: build) << {        configurations*.dependencies.each { println it }      }
      ```
3.    gradle -x test xxxxx
      跳过测试
4.    gradle tasks
5.    



插件
--------
1.    maven2gradle
    
      maven2gradle views the effective-pom flat view of aproject’s POM as its bridge to export to a Gradle build file. Based on the utility’sknowledge of the constrained Maven vocabulary, it converts those instructions to Gradleequivalents.
2.    checkstyle    代码风格检查


