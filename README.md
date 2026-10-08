# 课表（2026—2027学年秋季学期）

在线查看：https://yuxiangrousi-xie.github.io/kebiao/

学期通用课表，不含具体日期；周六、周日无课安排。

## 文件说明

| 文件 | 说明 |
| --- | --- |
| `index.html` | 单文件网页课表，样式与脚本全部内嵌，无外部依赖，离线也能打开 |
| `大一上学期课表_美化版.xlsx` | Excel 版课表，含“课表”“课程一览”两个工作表 |

## 更新方式

1. 改好课表后重新生成 `index.html`
2. 提交并推送：

   `ash
   git add .
   git commit -m "说明这次改了什么"
   git push
   `

3. GitHub Pages 约 1 分钟后自动重新发布，网址不变

## 备注

- 本机直连 github.com 不通，git 已配置走系统代理（`http.https://github.com.proxy`）；代理软件关闭时推送会失败。
