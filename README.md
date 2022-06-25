### 토큰발급
```
https://github.com/settings/tokens 
```
### 세팅추가
```
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0" 
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
   <servers>
    <server>
      <id>github</id>
      <password>XXXXXXXXXXXXXXXXX</password>
    </server>
  </servers>
</settings>
```


### 레포지토리 추가

```
<repositories>
	<repository>
		<id>ghkdwls-repo</id>
		<url>https://github.com/ghkdwls30/maven-repository/tree/main</url>
	</repository>
</repositories>
```
### 디펜던시 설정

```
<dependencies>
	<dependency>
		<groupId>kr.jframework</groupId>
		<artifactId>core</artifactId>
		<version>1.0.0-REALEASE</version>
	</dependency>
</dependencies>
```
