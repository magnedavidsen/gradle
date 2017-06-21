## MagneDavidsen - Gradle [![Build Status](https://travis-ci.org/MagneDavidsen/gradle.png)](https://travis-ci.org/MagneDavidsen/gradle)

Ansible role which installs [Gradle](http://www.gradle.org/).

#### Requirements & Dependencies
- Working with ansible >= 1.7
- Requires JDK > 7 to be installed

#### Variables

```yaml
gradle_version: "2.1"             # The version of gradle to install
```

#### Testing matrix

- Tested with Ansible 2.3.1.0


| OS        | Java               |
|-----------|--------------------|
| CentOS 6  | java-1.7.0-openjdk |
| CentOS 7  | java-1.7.0-openjdk |
| Ubuntu 12 | openjdk-7-jdk      |
| Ubuntu 14 | openjdk-7-jdk      |
| Ubuntu 16 | openjdk-8-jdk      |

#### Bugs and requests

Can be reported [here](https://github.com/MagneDavidsen/gradle/issues)!
