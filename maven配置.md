## 下载
## 解压
## 配置环境变量

## 修改配置文件 bin/config/settings.xml
#### 配置阿里镜像
    <mirror>      
        <id>nexus-aliyun</id>    
        <name>nexus-aliyun</name>  
        <url>http://maven.aliyun.com/nexus/content/groups/public</url>    
        <mirrorOf>central</mirrorOf>      
    </mirror>
#### 配置本地仓库
    <localRepository>
        D:\Program Files\mavenRepository
    </localRepository>
* 把 user/li/.m2/repository 删掉，再把 setting.xml 复制一份到 user/li/.m2 和 mavenRepository 
