# Typescript 函数静态方法

```
function setup() {
  if (setup.installed) return;
  setup.installed = true;
}

declare namespace setup {
  let installed: undefined | boolean;
}
```
