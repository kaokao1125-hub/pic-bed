# 🖼️ pic-bed — 超哥的图床仓库

用 GitHub 仓库当图床，存放图片供 Agent 在 Hermes 聊天中展示。

## 如何使用

### 上传图片

直接把图片拖到 GitHub 仓库页面，或者用 git push：

```bash
# 克隆到本地
git clone https://github.com/kaokao1125-hub/pic-bed.git

# 把图片放进去
# 提交推送
git add .
git commit -m "添加图片"
git push
```

### 获取图片链接

上传后，图片的 HTTPS 链接格式：

```
https://raw.githubusercontent.com/kaokao1125-hub/pic-bed/main/图片名.png
```

在 Hermes 聊天里用这个链接就能显示图片了。

## 命名规范

建议用英文/拼音命名，避免中文URL编码问题。
