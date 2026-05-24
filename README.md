# AzusaMochi

一个给 Codex Desktop 用的阿梓团子桌宠分享包。

这个桌宠从形象迭代、动作调整、打包到演示说明，主要由 Codex 完成。

## 下载

直接下载分享包：

```text
dist/azusamochi-pet.zip
```

或者使用仓库里的目录：

```text
azusamochi/
  pet.json
  spritesheet.webp
```

## 安装

把 `azusamochi` 文件夹放到 Codex 的 pets 目录：

```bash
mkdir -p ~/.codex/pets
cp -R azusamochi ~/.codex/pets/
```

最终目录结构应为：

```text
~/.codex/pets/azusamochi/pet.json
~/.codex/pets/azusamochi/spritesheet.webp
```

然后重启或刷新 Codex Desktop，在宠物列表里选择 `AzusaMochi`。

## 分享给别人

如果你只想发一个文件，发这个 zip 即可：

```text
dist/azusamochi-pet.zip
```

对方解压后，把解压出来的 `azusamochi` 文件夹放到 `~/.codex/pets/`。

## 说明

- 这是粉丝向 Codex 桌宠包。
- 仓库只包含桌宠安装文件和分享 zip。
- 不包含 token、缓存、日志、会话记录或本机临时状态。
