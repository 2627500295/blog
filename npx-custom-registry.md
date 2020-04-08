
# NPX 自定义源

## 参考

[allow custom registry](https://github.com/zkat/npx/issues/133#issuecomment-348684449)

## 食用

```bash
npm_config_registry=<npmRegistry> npx <command>
```

例:

```bash
npm_config_registry=https://registry.npm.taobao.org npx @vue/cli
```
