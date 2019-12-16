# Nestjs 开发模版

## 声明

本项目仅针对个人习惯定制，取消对service概念的使用，逻辑集中在了controller中

## v1.0

1. 支持登陆，jwt校验（jwt方案暂未接入官方那一套）
2. 单文件上传
3. 响应内容格式化
4. 跨域
5. api前缀
6. controller内部错误捕获（注意函数需返回一个与操作项相关联的值，否则可能会捕获不到错误，建议返回一个promise链式调用）

## v2.0

1. prettier 保存文件自动格式化
2. 身份验证分级