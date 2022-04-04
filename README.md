[教程](https://zhuanlan.zhihu.com/p/91315510)
```
$ cd quark
$ mvn archetype:create-from-project
$ mvn install
$ cd target/generated-sources/archetype/
$ mvn archetype:crawl

$ mvn archetype:generate -DarchetypeCatalog=local

```