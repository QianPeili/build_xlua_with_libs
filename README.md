### 原库地址

[chexiongsheng/build_xlua_with_libs: 为xLua集成几个常用库，方便使用](https://github.com/chexiongsheng/build_xlua_with_libs)

### 我的改动：

根据 `lua-rapidjson` 官方库，修改XLUA内的 `lua-rapidjson` 支持`empty_table_as_array` 参数

[Add empty_table_as_array option for encode(). · xpol/lua-rapidjson@ccd02f2](https://github.com/xpol/lua-rapidjson/commit/ccd02f2b50de11fa837cd8fa8c80d649b84da56c)

### 我的编译：

根据新代码编译了 windows 和 android 平台的库（我不知道叫什么！我只是个服务端！我只知道我编译了！

放在 `my_plugin_lua53` 目录
