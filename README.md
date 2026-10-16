# DramaProductionWorkbench Pages

AI漫剧工作台的 GitHub Pages 静态页面仓库，用于托管隐私协议和用户协议。

## 应用信息

- 应用名称：AI漫剧工作台（DramaProductionWorkbench）
- 包名：com.xmgod.dramaworkbench
- 版本：1.0.0
- 应用源码仓库（Gitee）：git@gitee.com:kuku-harmonyos/drama-production-workbench.git

## 推荐入口

- `docs/index.html`: 当前 GitHub Pages 首页，支持中文 / English 切换，支持隐私协议 / 用户协议切换。
- `privacy-policy.md`: 中文隐私政策推荐文件名。
- `privacy-policy-en.md`: English privacy policy recommended filename.
- `terms-of-service.md`: 中文用户协议推荐文件名。
- `terms-of-service-en.md`: English terms of service recommended filename.

## 兼容入口

以下历史文件名继续保留，避免旧链接失效：

- `PRIVACY_POLICY.md` -> 对应 `privacy-policy.md`
- `PRIVACY_POLICY_EN.md` -> 对应 `privacy-policy-en.md`
- `TERMS_OF_SERVICE.md` -> 对应 `terms-of-service.md`
- `TERMS_OF_SERVICE_EN.md` -> 对应 `terms-of-service-en.md`

推荐文件与兼容文件内容保持一致；修改协议正文时需要同步更新两边。

## 部署说明

仓库已配置 `.github/workflows/pages.yml`，推送到 `main` 分支后自动部署 `docs/` 目录。

GitHub Pages 需在仓库 Settings -> Pages 中将 Source 设置为 `GitHub Actions`。

公开入口：

- 协议中心首页：https://tomkuku588-bot.github.io/DramaProductionWorkben/
- 隐私协议直达：https://tomkuku588-bot.github.io/DramaProductionWorkben/?doc=privacy
- 用户协议直达：https://tomkuku588-bot.github.io/DramaProductionWorkben/?doc=terms

## 关联远程

```
git remote add origin git@github.com:tomkuku588-bot/DramaProductionWorkben.git
git push -u origin main
```
