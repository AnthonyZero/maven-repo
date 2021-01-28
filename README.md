### maven-repo
My personal maven repository

### Usage

pom.xml:

```
 <repositories>
    <repository>
        <id>anthonyzero-maven-repo</id>
        <url>https://raw.githubusercontent.com/AnthonyZero/maven-repo/main/repository</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
 </repositories>
```

> 如果GitHub的raw.githubusercontent.com无法链接
  通过IPAddress.com首页,输入raw.githubusercontent.com查询到真实IP地址,把得到的IP raw.githubusercontent.com保存到/etc/hosts 里面
