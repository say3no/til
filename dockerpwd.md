 # How to add current directory when write `docker run ...`

` -v $(pwd)/hogefuga/`でいい気がするんだけどどうやんだっけ…？

と思い調べ直したら、公式で  \`pwd\`  でできるようにサポートされていた。

```bash
docker run -ti -v `pwd`/share:`pwd`/share imagename
```

## 参考
[docker run | Docker Documentation](https://docs.docker.com/engine/reference/commandline/run/#mount-volume--v-read-only)
