[教程](https://zhuanlan.zhihu.com/p/91315510)
```
$ cd quark
$ mvn archetype:create-from-project

$ cd target/generated-sources/archetype/
$ mvn install
$ mvn archetype:crawl

$ mvn archetype:generate -DarchetypeCatalog=local

```