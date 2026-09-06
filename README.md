# 杨竣博的个人作品集

在线浏览：[blacklemi3.github.io](https://blacklemi3.github.io/)。

项目围绕 AI 应用、开发者工具、数据工作流与桌面软件，介绍具体问题、个人工作、结果和验证范围。公开简历不含电话、具体公司名称和内部资料。

## 页面

- `index.html`：代表项目、7 个公开工具、历史经验与联系入口。
- `resume.html`：公开简历，支持浏览器打印。
- `cases/research-workbench.html`：资料检索、来源登记、缓存复用与结构化审核。
- `cases/local-workbench.html`：本地项目交接工作台，含运行步骤与预期输出。
- `cases/market-research.html`：个人研究用桌面可视化及数据状态处理。
- `cases/system-records.html`：历史设备与应用经验，保留原 URL 和项目锚点。
- `cases/delivery-record.html`：官网、内部工具和交付流程，保留原 URL。

## 本地预览

纯静态 HTML/CSS，无构建依赖。在仓库根目录运行：

```bash
python -m http.server 8080 --bind 127.0.0.1
```

在浏览器打开 `http://127.0.0.1:8080`。主页及公开简历均支持手机宽度。

## 验证与数据范围

2026-09-06，四个公开 Python Demo 的 16 项现有测试与交接工作台的一条样例流程检查通过。桌面研究项目另复跑了 13 项核心离线测试。对应范围在案例页中说明。

研究资料数量为项目本地库的截面，不代表全部结论已审核通过，也不提供资料原文下载。公开示例使用虚构或合成数据；内部项目、账号、客户信息、个人账户数据和受限素材不上传。

## 托管

沿用 GitHub Pages，仓库 `blacklemi3/blacklemi3.github.io` 的 `main` 分支根目录。网站不依赖外部脚本或字体。
