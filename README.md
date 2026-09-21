# 效率集 Hub (xiaolvjihub)

批量导出 **[效率集 xiaolvji.com](https://www.xiaolvji.com/)** 公开用户的导航收藏数据。

## 📊 数据统计

| 指标 | 数值 |
|------|------|
| 用户数 | **33** |
| 站点总数 | **14,364** |
| 分类文件夹 | **699** |
| 文件数 | 169 |
| 生成时间 | 2026-09-21 10:56:01 |

## 📁 仓库结构

`
xiaolvjihub/
├── README.md
├── index.html                     # 入口页
├── xiaolvji_batch_index.html      # 批量索引 (V1)
├── xiaolvji_batch_index-V2.html   # 批量索引 (V2, 推荐)
├── xiaolvji_batch_manifest.json   # 元数据 + 排行榜
└── xiaolvji/                      # 每个用户一组 5 件套
    ├── {username}_nested.json     # 嵌套 JSON (分类 → 站点)
    ├── {username}_nested.csv      # CSV (Excel 直开)
    ├── {username}_nested.xlsx     # 原生 xlsx
    ├── {username}_bookmarks.html  # Netscape 书签格式
    └── {username}_nav_v2.html     # 单页导航站 (Tab + 搜索)
`

## 📈 用户排行榜

按站点数量排序：

| # | 用户 | 站点数 | 分类数 |
|---|------|--------|--------|
| 1 | anywhere | 2537 | 52 |
| 2 | yongyuanshipengyou | 1596 | 38 |
| 3 | taoxiangjiang | 1044 | 49 |
| 4 | ljyandlwl | 1007 | 34 |
| 5 | yanmulan | 991 | 47 |
| 6 | cywang | 891 | 29 |
| 7 | 2301908761 | 817 | 24 |
| 8 | researchtools | 653 | 27 |
| 9 | lhw12345678 | 643 | 45 |
| 10 | tiantian | 586 | 26 |
| 11 | leviathan | 432 | 25 |
| 12 | zhaohui | 360 | 29 |
| 13 | daihuo | 344 | 17 |
| 14 | wufeng | 289 | 21 |
| 15 | yzhrjd | 205 | 13 |
| 16 | pcsoftware | 181 | 20 |
| 17 | changyong | 176 | 20 |
| 18 | spatialtranscriptome | 157 | 19 |
| 19 | mlmism | 147 | 22 |
| 20 | qingyuntian | 147 | 17 |
| 21 | titan | 141 | 10 |
| 22 | meitiren | 140 | 16 |
| 23 | edcsion | 121 | 10 |
| 24 | communism | 111 | 9 |
| 25 | fangzichang | 111 | 4 |
| 26 | wesafe | 108 | 15 |
| 27 | junwei | 87 | 13 |
| 28 | cancerinfo | 78 | 10 |
| 29 | peixunshi | 77 | 14 |
| 30 | yingshiziyuan | 73 | 10 |
| 31 | xianshi | 47 | 4 |
| 32 | bangong | 37 | 6 |
| 33 | waimao | 30 | 4 |

## 🔧 每个文件的用途

| 文件 | 用途 | 推荐场景 |
|------|------|----------|
| _nested.json | 嵌套 JSON，保留完整分类结构 | 二次开发、编程处理 |
| _nested.csv | UTF-8 BOM，Excel 双击打开 | 数据分析、表格编辑 |
| _nested.xlsx | 原生 xlsx 格式 | Excel 偏好用户 |
| _bookmarks.html | Netscape Bookmark File Format | 浏览器「导入书签」 |
| _nav_v2.html | 自包含 HTML，分类 Tab + 搜索 + 响应式 | 本地浏览、离线导航 |

## 🌐 批量索引页

- **[index.html](index.html)** — 最简洁入口
- **[xiaolvji_batch_index-V2.html](xiaolvji_batch_index-V2.html)** — 推荐，33 个用户一键跳转
- **[xiaolvji_batch_manifest.json](xiaolvji_batch_manifest.json)** — 全部元数据

## 📦 原始效率集

所有数据来源：https://www.xiaolvji.com/u/{username}

效率集是一个「自定义导航主页」服务，每个用户有独立 URL，支持分类文件夹、嵌套二级分类、收藏真实外部 URL（非 go 跳转）。

## ⚠️ 使用注意

- 数据公开导出，仅用于个人学习/数据分析/离线备份
- 如需更精确的最新数据，请自行访问原站
- 站点所有权归效率集及各用户本人所有

## 📄 License

本仓库数据仅供参考使用。原始站点版权归效率集运营方所有。
