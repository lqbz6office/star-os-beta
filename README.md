# Star OS Beta 内测通道

这是 **内测** 通道的清单仓库。正式版在 [star-os-assets](https://github.com/lqbz6office/star-os-assets)。

## 怎么用

不用手动下载 —— 在 Star OS 主页左上角点紫色 **β**,读完并同意免责声明后,
页面会同时看这个仓库和正式仓库,哪个版本新就推哪个。

## 通道规则

| | 正式通道 | Beta 通道 |
|---|---|---|
| 仓库 | star-os-assets | **star-os-beta** |
| 版本号 | 3.1.1 | 3.1.1-beta.2 |
| versionCode | 37 | **39**(比正式版 +1) |
| 稳定性 | 回归过 | 未完整回归,可能有问题 |
| 回退 | — | 正式版号追上后页面会提示切回 |

## 版本号约定

内测包一律带 `-beta.N` 后缀,`N` 是这一轮的第几个内测包。
内测包取**下一个** versionCode(当前正式版 +1)—— 内测页只在
「远端 vc > 本地 vc」时提示更新,同号不会提示。
正式版发版时用同一个号即可直接覆盖,用户不用卸载重装。

## 免责声明

首次进入 Beta 页必须先同意免责声明(内测风险 / 备份责任 / 责任限制 / 日志说明),
不同意则不做任何改动。声明全文内置在 Star OS 里,不联网、不会被远程篡改。

## 文件

- `update.json` —— 内测清单(version / versionCode / zipUrl / changelog)
- `changelog.md` —— 内测更新日志
- `zz_star_os-<版本>-online.zip` —— 内测包本体(由发布脚本上传)
