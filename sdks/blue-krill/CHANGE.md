## Change logs

### 1.0.5

- `StructuredEnum` 中新增 `get_choices`、`get_labels` 和 `get_values` 方法
- 重构 `StructuredEnum` 的 `get_choice_label` 方法，支持 unhashable 的枚举

### 1.0.4

- 对象存储模块支持签发上传链接

### 1.0.3

- 增加健康探针功能

### 1.0.2

- 允许 SecureEnv 设置自定义解密方法

### 1.0.1

- 增加 better-loaddata 命令

### 1.0.0

- 重新格式化，去除敏感信息
- 调整 encrypt.legacy 模块

### 0.0.17

- 增加 `blue_krill.web` 模块，包含标准错误码 `std_error` 与 DRF 工具模块 `drf_utils`
- 增加 `blue_krill.async_utils` 模块，包含异步轮询工具包 `poll_task`

### 0.0.14

- 增加 blobstore 模块
  - 支持 上传/下载/签发分享链接 三个基础功能
  - 对接 `s3对象存储` 和 `蓝鲸二进制仓库` 两个后端服务 

### 0.0.13

- 增加 data_types.enum 模块
  - 增加 FeatureFlag、FeatureFlagField 用于定义功能标记(FeatureFlag)
  - 增加 StructuredEnum 用于定义带有额外属性的枚举类

### 0.0.12

- 增加 toml 模块依赖

### 0.0.11

- 增加多版本管理工具 editionctl

### 0.0.10

- 增加 `blue_krill.secure.dj_environ` 模块，支持 Django 框架读取加密环境变量
- 增加 `bk-secure` 命令，辅助环境变量加密时使用

### 0.0.9

- 添加 `blue_krill.auth.jwt` 模块，供访问基于 JWT 鉴权的服务时使用

### 0.0.8

- `PrometheusExposeHandler` 增加 `extra_registries` 参数