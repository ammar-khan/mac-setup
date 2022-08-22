### Scala
---

Make sure you have Java installed
> Recommend to use SDKMAN! for Scala

```
brew update
```

```
brew install scala sbt
```

(This step is optional) Update the `/usr/local/etc/sbtopts` by running the command below.

```
echo '-J-XX:+CMSClassUnloadingEnabled' >> /usr/local/etc/sbtopts
echo '-J-Xmx2G' >> /usr/local/etc/sbtopts
```


