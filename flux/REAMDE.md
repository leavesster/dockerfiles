# flux

根据[官方文档](https://github.com/influxdata/flux)，构建 docker 镜像，进行 REPL 操作。

```shell
docker build --rm -f dockerfile -t flux .
docker run -it --rm flux
```