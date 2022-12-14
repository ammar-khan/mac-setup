### Java
---

Using Java requires you to install a JDK ("Java Development Kit") or JRE ("Java Runtime Environment"). We'll use a JDK since it can do everything a JRE can, plus more.

#### Choosing a JDK
As of 2019, there are two major JDKs: OpenJDK (also known as AdoptOpenJDK) and the Oracle JDK. OpenJDK and Oracle JDK provide the same functionality, and are even built from the same code base. They differ only in their packaging and licensing.

OpenJDK is free for use in all situations. Oracle JDK requires a paid-for commercial license when used in a production setting.

Most personal users will probably want to use OpenJDK, since it's easier to acquire and install and that's what we'll be covering here.

#### Verify 
```
java -version
```

If you see a non-empty output like below then Java is already installed on your machine.

>openjdk version "13.0.2" 2020-01-14
OpenJDK Runtime Environment AdoptOpenJDK (build 13.0.2+8)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 13.0.2+8, mixed mode, sharing)

>If you don't see the output like above then you need to install Java on your system


#### Installation
> Recommend to use SDKMAN! for Java


Using Homebrew

```
brew search jdk
```

```
brew install openjdk
```

```
java -version
```
#### Downloading and installing manually
Open a web browser and go to https://adoptopenjdk.net/. Select "OpenJDK 11 (LTS)" and "HotSpot". Click the big "Latest release" button and run the installer file that gets downloaded.

Once you've done that, check if Java is correctly installed by opening a new Terminal session and running the `java -version` command again.

