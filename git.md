# Conventional Commit 规范

### feat

新功能、新特性

### fix

修复 bug

### docs

只修改文档，比如 README

### style

代码格式调整，不影响代码逻辑（空格、分号、换行等）

### refactor

重构代码，既不是新功能也不是修 bug

### perf

性能优化

### test

添加或修改测试代码

### build

构建系统或外部依赖的变更（webpack、npm、gulp 等）

### ci

CI 配置文件和脚本的变更（GitHub Actions、Travis 等）

### chore

其他不修改 src 或测试文件的变更（更新依赖、配置文件等）

### revert

回退之前的提交

## 示例

```
feat: 添加用户登录功能
fix: 修复首页加载失败的问题
docs: 更新 API 文档
style: 统一代码缩进格式
refactor: 重构用户认证模块
perf: 优化图片加载速度
test: 添加用户模块单元测试
build: 升级 webpack 到 5.0
ci: 配置 GitHub Actions 自动部署
chore: 更新依赖包版本
revert: 回退"添加用户登录功能"提交
```

## 带 scope 的示例

```
feat(auth): 添加微信登录
fix(home): 修复轮播图不显示
docs(api): 更新接口文档
```
