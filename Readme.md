# cachedRequirejs
一个脚本模块化方案，如下内容：

自动版本管理（自动生成MD5版本号）

减少304（支持LS的情况下）
智能加载（首次下载打包文件，其后如果支持LS则增量下载小模块文件）
增量下载（仅下载修改的小模块文件）

