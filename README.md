# larksdk-dep-mesa3d

编译 [LarkSDK](https://gitee.com/cytech_05/larksdk) 需要的 mesa3d 依赖库。

# 使用方法

下载 Release 到本地，注意不要下载 Source Code。

在下载好的根目录中执行，建议使用 Conan 2：

```bash
conan export-pkg .
```

即可成功将该 Conan 包存储到本地 Cache。

