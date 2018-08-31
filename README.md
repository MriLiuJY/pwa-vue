# pwa-vue

progressive web app with vue-cli@3.0

# 开发规则

进行开发时请遵守以下原则：

- 开发时请先fetch下远端代码 确保代码处于最新状态避免冲突
- 在dev分支上进行
- 请开启 `eslint` 进行开发
- 请注意项目中使用 `LF` 换行符保持多端同步
- 请避免使用过于激进ES6新增特性进行开发（历史包袱 / 兼容IE 如需使用请先查阅）
- 如果同时在开发，请同时从dev上拉出一个分支
- 请 **务必** 详细记录[commit](https://ruby-china.org/topics/15737) (如使用 -m 提交务必首先使用 `Type` 介绍当前修改)
- 需要发布某个分支时，将该分支合并到master分支
- 发布分支打 `Tag` 

### Type 说明

```
  feat: 添加新特性
  add: 在项目原有代码中添加代码
  change: 修改代码，涉及业务逻辑请单独说明
  fix: 修复bug
  docs: 仅仅修改了文档
  style: 仅仅修改了空格、格式缩进、都好等等，不改变代码逻辑
  refactor: 代码重构，没有加新功能或者修复bug
  perf: 增加代码进行性能测试
  test: 增加测试用例
  chore: 改变构建流程、或者增加依赖库、工具等
```

# License

Released under the MIT License. Check [LICENSE.md](https://github.com/Pau1fitz/react-spotify/blob/master/LICENSE) for more info.