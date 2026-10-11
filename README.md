# 来时路 · Evidence of Becoming

**个人成长档案与作品集** · [tingfengling.space](https://tingfengling.space)（自定义域名待配置）

> 做成一些事。成为想成为的人。  
> 认真做事，认真生活。

## 目前完成

- 独立、响应式公开网站：作品 / 思考 / 来时路 / 关于。
- 默认无任何私人记录、真实个人敏感资料或虚构作品。
- 原生 HTML / CSS / JS；无需安装依赖，可直接由 GitHub Pages 发布。

## 首次发布 GitHub Pages（先验证默认地址）

1. 打开仓库 **Settings → Pages**。
2. 在 **Build and deployment** 中设置 **Source: Deploy from a branch**。
3. 选择 **Branch: main** / **Folder: /(root)**，点击 **Save**。
4. 等待 Pages 发布，访问：<https://Aileen4869.github.io/laishilu/>。
5. 请在默认地址可以访问、HTML/CSS 正常后，再绑定自定义域名。

## 绑定腾讯云域名（第二阶段，先不要修改 DNS）

使用 GitHub Pages **Settings → Pages → Custom domain** 添加 `tingfengling.space`。
DNSPod 根域名记录 `@` 对应四条 A 记录：

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

`www` 的 CNAME 可以指向 `Aileen4869.github.io`（不是 `/laishilu` URL）。须先检查已有 DNS 记录，避免影响已有网站/邮箱。DNS 生效和证书准备好后再开启 **Enforce HTTPS**。不要在默认 GitHub Pages 地址验证通过前添加 CNAME 文件，以免过早重定向。

## ⚠ 隐私与后续开发

**当前仅是公开网站地基，并没有实现私人登录或数据库。**

- 不要把私人证据卡、私人照片、密钥或未脱敏工作资料提交到此公开仓库。
- 未来私密记录使用 Supabase Auth、Postgres RLS、私密 Storage 和受控图片 URL。严禁把 service_role 密钥放在浏览器代码中。
- 第一批真实记录应在权限验证、管理员账号创建、批量导入功能做好并经本人审核后再上传。
- 公共记录需要本人明确选择公开；历史已公开内容即使改为私有，也无法撤回第三方缓存或截图。

## 内容方向

真实行动 → 证据卡（默认私人）→ 成长案例 → 公开作品 / 文章。

先积累真实记录，再选择适合展示的内容；不为了填充页面而编造项目或经历。
