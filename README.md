### 运行
./mvnw spring-boot:run

### 版本内容
./mvnw --version

### 发现已经有SDKMAN管理工具了(curl -s "https://get.sdkman.io" | bash)
sdk list java
#### sdk命令会提示是否设为默认JDK。回答Y就会把这个版本设置成默认JDK。
sdk install java 17.0.7-oracle

sdk current java

sdk use java java 17.0.7-oracle
sdk default java 17.0.7-oracle

env命令查看sdkman目录为/usr/local/sdkman/candidates/java
该目录下的每一个子目录都是一个JDK
#### 卸载版本，卸载后/usr/local/sdkman/candidates/java目录对应的版本也会删除
sdk uninstall java 17.0.7-ms

