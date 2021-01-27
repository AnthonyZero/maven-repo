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
