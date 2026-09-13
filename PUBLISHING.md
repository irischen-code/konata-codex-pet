# GitHub 发布准备

建议仓库名：`konata-codex-pet`

建议简介：`泉此方同人 Codex 桌面宠物 · Konata Izumi desktop companion with idle, walk and interaction animations.`

## 上传前

1. 确认 `ATTRIBUTION.md` 中的参考来源与公开分发权限；目前仍有未核实项，可先建立私有仓库保存定稿。
2. 如需署名，在 README 中加入自己愿意公开的昵称和联系方式。
3. 只上传此仓库目录内的文件，不上传整个工作目录或整个 `.codex` 目录。
4. 不附带登录凭据、配置、会话记录、客户端源码、参考原图或旧版备份。本包已按此范围整理。
5. 在第二台支持相同图集格式的电脑上安装一次；当前 README 已如实注明 Windows 未验证。
6. 不要选择会给全部角色图像授予开放许可的 LICENSE 模板。若以后为自有脚本选择许可，应明确与图像素材分开。

## 用网页上传

1. 在 GitHub 新建仓库，名称用 `konata-codex-pet`。如上述素材权限尚未确认，先选 Private。
2. 在仓库页面使用 **Add file → Upload files**；空仓库也可使用上传现有文件的入口。
3. 上传本目录中的 `README.md`、`ATTRIBUTION.md`、`PUBLISHING.md`、`VERSION`、`SHA256SUMS`、`pets/`、`docs/` 和 `.gitignore`。README 应在仓库根目录，而不是再套一层文件夹。
4. 提交说明可写 `Add Konata pet 1.0.0`。
5. 确认 README 的图片能显示，且 `pets/konata-preview/` 中两个文件都能下载。
6. 准备好分发后创建 `v1.0.0` Release，附件使用单独的 `konata-pet-1.0.0.zip` 安装包。

GitHub 支持浏览器直接上传文件或文件夹。本包单个文件均小于其网页上传的 25 MiB 上限，无需 Git LFS。

## Release 文案

标题：`泉此方宠物 v1.0.0`

正文：

> 首个定稿版本。包含身体起伏待机、闭眼叉腰、左右行走、举拳、拿面包和看漫画动作。图集采用透明 WebP，适用于支持第二版自定义宠物图集的桌面客户端。下载附件后，将其中的 konata-preview 文件夹放入本机宠物目录；具体路径及动作触发说明见 README。已在 macOS 验证，其他环境尚未实测。本项目为非官方同人，素材来源与授权说明见 ATTRIBUTION.md。

## 参考

- [GitHub：向仓库添加文件](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [GitHub：为仓库选择许可](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
