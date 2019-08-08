Yarn Force Dependency Version by "resolutions" Demo
===================================================

在package.json中通过指定`resolutions`来强制使用某个版本。

注意：只有yarn支持。如果是npm，需要其它的办法。

```
yarn
yarn run demo
```

检查：

```
yarn list --depth 10
```

可以看到`fsevents`最终使用的是`1.2.9`版本。
