# 智能感知与信号处理实验室主页

这是一个可直接部署到 GitHub Pages 的高校实验室主页模板，已经根据漆进博士中文简历整理了以下内容：

- 实验室简介
- 研究方向
- 团队成员
- 代表性论文
- 主持项目
- 竞赛与获奖
- 招生招聘
- 联系方式

## 文件结构

```text
university-lab-homepage-updated/
├── index.html
├── assets/
│   ├── style.css
│   └── main.js
├── .nojekyll
└── README.md
```

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库，例如 `lab-homepage`。
2. 将本文件夹中的所有文件上传到仓库根目录。
3. 进入仓库 `Settings` → `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub 生成网址。

访问地址通常为：

```text
https://你的GitHub用户名.github.io/lab-homepage/
```

## 建议继续补充

- 添加团队成员真实姓名、头像与个人主页。
- 为论文补充 DOI、PDF、代码和 Google Scholar 链接。
- 为项目补充项目编号、合作单位和平台截图。
- 若要公开手机号，请在 `index.html` 的联系方式部分自行添加。当前版本默认不展示手机号。

## 修改方法

主要修改 `index.html` 即可。常见位置：

- `<title>`：网页标题
- `.hero`：首页大标题和简介
- `#research`：研究方向
- `#people`：团队成员
- `#publications`：论文列表
- `#projects`：项目列表
- `#contact`：联系方式
