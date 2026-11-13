# VibePier Desktop Releases

本仓库仅用于分发 VibePier Desktop 安装包、更新包、公开签名及更新清单，不存放应用源码或任何私钥、令牌。

## 发布平台

- macOS：Apple Silicon（aarch64）
- Windows：x64
- Linux：x64

## 更新方式

安装包与更新包发布在 GitHub Releases。应用内更新仍由 VibePier 正式更新接口控制；公开一个 Release 不会自动将该版本推广给客户端。

更新包应具有对应的 `.sig` 签名，并由客户端内置公钥校验。请勿关闭应用内的签名校验，也不要把仓库中的文件视为业务后端部署程序。

安装包及版本可用状态以本仓库的 Releases 页面为准。只有通过构建、验签和实际升级验收的版本才会被推广给正式客户端。
