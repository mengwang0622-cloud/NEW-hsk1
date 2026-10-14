# NEW-hsk1
生词


## HSK1 熊猫词汇游戏

波兰语界面，适用于电脑、平板和手机；学生无需注册。

- 题库：上传 PDF 中全部 163 个词条，保留汉字、拼音、波兰语翻译和源文件编号、页码。
- 四种游戏：汉字与波兰语配对、拼音选汉字、30 秒挑战、汉字认读闯关。
- 每轮 10 道随机题，首次答对得 10 分，答错显示提示。
- 可搜索词汇表，页面可打开或下载原 PDF。

### 运行

所有必要文件位于仓库根目录。下载或克隆仓库后，用浏览器打开 `index.html`，也可在仓库目录运行：

```sh
python3 -m http.server 8000
```

无需 npm 安装、数据库、API 密钥或账户。

### 在 GitHub 查看

打开仓库的 **Code** 页面，选择 **main** 分支，点击文件即可查看源码。GitHub 的源码页面不会直接运行 HTML 游戏。

### 分享可玩的网页

进入 **Settings → Pages**，Source 选择 **Deploy from a branch**，Branch 选择 **main**，目录选择 **/ (root)**，点击 **Save**。部署完成后，Pages 页面会显示网站网址；将网址发给学生即可。是否可启用 Pages 取决于仓库可见性、账户方案及组织策略。

详见 [使用说明](使用说明.md)。词汇来源：POCHIŃSKU.PL，用户提供的 `Pochinsku_HSK1_Nowe_Slownictwo_2026.pdf`；源文件保存在 `HSK1-slownictwo.pdf`。
