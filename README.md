# 声色金鱼 · 作品集与备赛手记

作品集：https://songjinyu302-ship-it.github.io/shengse-jinyu-showcase/
完整本地功能：https://songjinyu302-ship-it.github.io/shengse-jinyu-showcase/use-app/

`use-app/` 复用原 APP，支持新建、编辑、自动保存、背景确认、反馈待办、清单、资产归档和 JSON 备份。无需登录，仅保存在访问者当前浏览器；不同浏览器和设备不自动同步。清理微信/浏览器缓存前应导出备份。不连接 Supabase，不上传私人记录。

本仓库只发布选定公开 HTML 与编译后的浏览器资产，不包含私人工作区、环境文件或备份。源码与构建脚本保留在原私有 APP 工程。不要手动修改编译后 app.js；从原工程 `npm run build:static` 重新构建。

GitHub Pages 来源：main 根目录。静态路由使用 `#/projects/...`，新建作品后刷新不会要求服务器生成任意 ID 页面。

作品集旧入口已由用户在国内微信实测打开；新完整入口的手机网络和持久化需单独验证，不作全网永久可达保证。