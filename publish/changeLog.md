### 优化

- 优化对系统Media Session的支持，现在切歌不会再会导致信息丢失的问题了
- 启用桌面歌词时，取消对歌词窗口的聚焦
- 增加kg歌单歌曲flac24bit显示（@helloplhm-qwq）
- 增加tx源热门评论图片显示（@Folltoshe）
- 优化更新弹窗弹出时机
- 优化搜索框背景配色，使其适应高透明主题
- 支持wy热门评论翻页

### 修复

- 修复启用全局快捷键时与Media Session注册冲突的问题，启用全局快捷键时，不再注册媒体控制快捷键
- 修复mg搜索不显示时长的问题（@Folltoshe）
- 修复mg评论加载失败的问题（@Folltoshe）
- 修复对存在错误时间标签的歌词的解析

### 其他

- 自定义源API utils对象新增`zlib.inflate`与`zlib.deflate`方法，API版本更新到 v1.3.0
- 更新kg、tx、wy等平台排行榜列表
- 更新 electron 到 v22.3.7
