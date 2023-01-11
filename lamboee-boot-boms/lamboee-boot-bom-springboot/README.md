
# lamboee-boot-bom-spring-boot

Provides SpringBoot related dependency management.

# Quick Start

Import by maven `parent`

```xml
<parent>
    <groupId>cn.lamboee</groupId>
    <artifactId>lamboee-boot-bom-spring-boot</artifactId>
    <version>${lamboee-boot.version}</version>
</parent>
```

Import by maven `dependencyManagement`

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>cn.lamboee</groupId>
            <artifactId>lamboee-boot-bom-spring-boot</artifactId>
            <version>${lamboee-boot.version}</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

