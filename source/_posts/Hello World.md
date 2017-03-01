---
title: Hello Hexo
date: 2017-03-01 11:24:59
categories: [tool]
tag: [hexo,tool]
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## 快速开始

### 创建项目

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### 运行

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)


### 代码高亮示例

{% codeblock Javascript Array Syntax lang:js %}
var arr1 = new Array(arrayLength);
var arr2 = new Array(element0, element1, ..., elementN);
{% endcodeblock %}

{% codeblock Java Syntax lang:java %}

    public
    @Service
    static class DataBaseService extends PerformanceMonitoring {

        @Override
        IPerformanceMonitoringSearch<QueryBuilder, SortBuilder> getCustomIProject132Search() {
            return SearchFactory.getCustomIProjectSearch(
                    ElasticIndexTimeType.MONTH,
                    IPerformanceMonitoringSearch.INDEX_PREFIX,
                    IPerformanceMonitoringSearch.CD132_ORACLE_DATABASE_TYPE
            );
        }
    }
    
{% endcodeblock %}