# mwitkow@'s Maven Repos

This repository contains binary artifacts for Java and Scala. They are served using the `raw` endpoints of Github.

To use this repository in your projects, add the following to your `pom.xml` (or equivalent config):

```xml
<repositories>
  ...
  <repository>
    <id>mwitkow-github-repo</id>
    <url>https://raw.github.com/mwitkow/maven-repos/master</url>
  </repository>
  ...
</repositories>
<dependencies>
```

## Projects

 * `org.flagz` - [java-flagz](https://github.com/mwitkow/java-flagz) - FlagZ - modern flag library for Java/Scala


## License

These are just binary artifacts, each of them contains metadata mentioning the respective license.
