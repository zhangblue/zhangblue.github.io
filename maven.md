#Maven的命令使用

##1.编译主代码
```
mvn clean compile
```
##2.执行测试代码
```
mvn clean test
```
##3.打包程序到target文件夹中
```
mvn clean package
```
##4.打包到target文件夹中，并且将打包好的jar作为第三方jar放入到maven本地仓库中
```
mvn clean install
```
##5.创建maven框架
```
mvn archetype:generate
```
##6.查看所有引入的依赖包，包含传递性依赖
```
mvn dependency:list
```
##7.以树形结构查看所有引入的依赖，包含传递性依赖
```
mvn dependency:tree
```

##8.导出所有POM文件中的jar
```
mvn dependency:copy-dependencies
```