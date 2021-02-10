[![Build Status](https://github.com/heutelbeck/base64uuid/workflows/build/badge.svg)](https://github.com/heutelbeck/base64uuid/actions)

# Convenience class for compactly represented UUIDs encoding the 32bytes as Base64

Usage example: `Base64Id.randomID()`

## Dependencies:

```
<dependency>
  <groupId>com.heutelbeck</groupId>
  <artifactId>base64uuid</artifactId>
  <version>1.0.0-SNAPSHOT</version>
</dependency>

<repositories>
   <repository>
      <id>sapl</id>
      <name>SAPL Maven Repository</name>
      <url>https://maven.pkg.github.com/heutelbeck/packages</url>		
   </repository>
</repositories>
```

## Configure Maven

Generate a personal access token for your GitHub account and add this to your ~/.m2/settings.xml:

```
   </servers>
      <server>
         <id>sapl</id>
         <username>USERNAME</username>
         <!-- see https://github.com/settings/tokens -->
         <password>ACCESS TOKEN</password>
      </server>
   </servers>
```
