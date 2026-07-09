# 三朵金花旅行团 · 珠海国庆亲子悠游导航

## 🚀 云端部署指南

### 方案一：GitHub Pages（推荐，永久免费）

**Step 1** - 在 GitHub 创建新仓库
打开 https://github.com/new
仓库名称：`zhuhai-travel-guide`
设为 Public（公开）
不要勾选任何初始化选项

**Step 2** - 推送代码（在项目目录下执行）：
```bash
cd zhuhai-travel-guide
git add .
git commit -m "三朵金花旅行团 · 珠海导航初版"
git remote add origin https://github.com/你的用户名/zhuhai-travel-guide.git
git branch -M main
git push -u origin main
```

**Step 3** - 启用 GitHub Pages
仓库 → Settings → Pages → Source 选 `main` 分支 → Save
几分钟后访问：`https://你的用户名.github.io/zhuhai-travel-guide/`

---

### 方案二：Netlify Drop（最简单，无需注册）

打开 https://app.netlify.com/drop
把整个 `zhuhai-travel-guide` 文件夹拖进去
立即获得一个可分享的 URL！

---

## 📁 项目文件

```
zhuhai-travel-guide/
└── index.html    # 完整的单页应用（包含所有HTML/CSS/JS）
```

## ✨ 功能特性

- 🎬 开场动画：三朵金花主题，飘落花瓣
- 🧭 四向导航中枢：交通 / 住宿 / 饮食 / 游玩
- ✈️ 交通详情：航班方案、订票窗口、市内交通
- 🏨 住宿卡片：4家酒店/别墅详细信息+价格
- 🍜 互动美食地图：Leaflet 地图 + 7家餐厅标记
- 🎢 互动游玩地图：9个景点标记 + 长隆详细攻略弹窗
- 🎵 背景音乐：点击右上角开启海洋氛围音效
- 📱 移动端响应式适配

---

## 🛠 技术栈

纯静态 HTML + CSS + JavaScript，零依赖编译
- Leaflet.js (CDN) — 互动地图
- Web Audio API — 背景氛围音效
- Google Fonts — 中文字体
- CSS Animations — 全部动效

---

*编制：刘天和 © 2026*
