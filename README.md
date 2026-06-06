# AzusaMochi

阿梓系 Codex Desktop 桌宠分享仓库。

当前主推桌宠是 **坨梓**：圆圆一坨的阿梓 A 版小人，蓝发、熊猫趴趴头饰、蝴蝶装饰和眯眼小表情都保留下来了。

## 坨梓有什么可爱

- 会眯眼笑，桌面待机时像一坨软乎乎的小团子。
- `waiting` 状态会捧碗乞讨，适合等你输入或审批的时候出现。
- `running` 状态会拿话筒唱歌，小音符跟着动。
- 移动、挥手、跳跳、委屈、审阅都有单独动作，不是静态贴纸。

## 下载

推荐下载坨梓压缩包：

[dist/tuozi-pet.zip](https://github.com/yim7/AzusaMochi/raw/main/dist/tuozi-pet.zip)

也可以在 GitHub 页面里打开 `dist/tuozi-pet.zip`，点击右上角下载按钮保存文件。

仓库里同时保留早期版本：

[dist/azusamochi-pet.zip](https://github.com/yim7/AzusaMochi/raw/main/dist/azusamochi-pet.zip)

## 安装

下载 `tuozi-pet.zip` 后解压，里面会得到 `tuozi` 文件夹。

把 `tuozi` 文件夹放到 Codex 的 pets 目录：

```bash
mkdir -p ~/.codex/pets
cp -R tuozi ~/.codex/pets/
```

最终目录结构应为：

```text
~/.codex/pets/tuozi/pet.json
~/.codex/pets/tuozi/spritesheet.webp
```

然后重启或刷新 Codex Desktop，在宠物列表里选择 `坨梓`。

## 目录

```text
tuozi/
  pet.json
  spritesheet.webp

azusamochi/
  pet.json
  spritesheet.webp

dist/
  tuozi-pet.zip
  azusamochi-pet.zip
```

## 说明

- 这是粉丝向 Codex 桌宠包。
- 仓库只包含桌宠安装文件和分享 zip。
- 不包含 token、缓存、日志、会话记录或本机临时状态。
