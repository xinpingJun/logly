# Logly - 育儿手记

一款专为新手爸妈设计的智能育儿记录应用。

---

## App Store 广告文案

### 应用名称
**Logly - 育儿手记**

### 副标题
记录宝宝成长的每一刻，科学育儿更轻松

---

### 应用描述

**Logly** 是一款专为新手爸妈设计的智能育儿记录应用，帮助您轻松追踪宝宝的喂养、睡眠、换尿布、生长发育和疫苗接种，让育儿之路更加从容有序。

**🍼 全面记录，一键搞定**
- 快速记录喂奶（母乳/配方奶）、辅食、睡眠、换尿布
- 支持计时器模式，亲喂时间精准记录
- 照片记录便便状态，方便健康观察
- 生长数据追踪（体重、身高、头围）

**📊 智能统计，一目了然**
- 周/月/年多维数据统计
- 喂养量、睡眠时长、换尿布频率可视化图表
- WHO 生长标准对比，了解宝宝发育状况
- 疫苗接种进度追踪，按时提醒不遗漏

**⏰ 贴心提醒，不再错过**
- 自定义喂奶、换尿布、哄睡提醒
- 基于上次记录智能推算下次时间
- 疫苗接种日程自动提醒

**🎨 个性化主题，记录更有趣**
- 4 款精美主题：简约、手账、海洋、马卡龙
- 明暗模式自动适配
- 多语言支持（中文/英文）

**☁️ 数据安全，云端同步**
- iCloud 自动同步，多设备无缝切换
- 本地存储优先，隐私安全有保障
- 支持数据导出备份

**📚 专业育儿知识**
- 内置喂养手册、生长手册
- 科学育儿指南，新手爸妈的贴心助手
- 疫苗接种计划参考

---

### 关键词
育儿记录,宝宝成长,喂养记录,睡眠追踪,换尿布,生长发育,疫苗接种,新手爸妈,婴儿护理,育儿助手

---

### 宣传语（用于截图文字）

**截图1 - 首页仪表板**
> 清晰记录，轻松育儿
> 宝宝成长的每一刻，都值得被记录

**截图2 - 快速记录**
> 3秒完成记录
> 喂奶、睡眠、换尿布，一键搞定

**截图3 - 数据统计**
> 科学分析，心中有数
> 周月季统计，掌握宝宝成长规律

**截图4 - 生长曲线**
> 对比WHO标准
> 了解宝宝发育是否正常

**截图5 - 疫苗管理**
> 按时接种，健康成长
> 疫苗计划一目了然

---

### 更新日志（示例）

**版本 1.2.0**
- 新增滑块式喂养量选择器，操作更直观
- 优化统计页面，标题栏固定显示
- 改进主题切换体验
- 修复已知问题，提升稳定性

---

## 功能模块分析

### 核心数据模型
- **BabyProfile** - 宝宝档案（姓名、生日、性别、头像、身高体重）
- **FeedingRecord** - 喂养记录（时间、类型、奶量、时长、侧边）
- **SleepRecord** - 睡眠记录（开始/结束时间、质量评分）
- **DiaperRecord** - 换尿布记录（类型、颜色、性状、照片）
- **GrowthRecord** - 生长记录（体重、身高、头围、照片）
- **VaccineRecord** - 疫苗记录（名称、接种状态、备注）

### 主要页面功能

| 页面 | 核心功能 |
|------|----------|
| DashboardView | 首页仪表板、今日动态、快捷记录入口 |
| RecordsListView | 记录列表、分类筛选、时间轴展示 |
| StatisticsView | 周/月/年统计、数据可视化、趋势分析 |
| GrowthView | 生长数据、WHO曲线、百分位计算 |
| VaccineListView | 疫苗计划、接种提醒、进度追踪 |
| SettingsView | 主题切换、语言设置、通知管理 |
| FeedingEntryView | 喂养记录、滑块选择、快捷标签 |
| DiaperEntryView | 换尿布记录、照片拍摄、状态选择 |

### 主题系统
- **Ethereal** - 简约 ethereal 风格（默认暖橙色）
- **Sketchbook** - 手账手绘风格（纸张纹理、荧光标记）
- **OceanBreeze** - 海洋清新风格（蓝绿色调）
- **Macaron** - 马卡龙甜美风格（粉色系）

### 技术特性
- SwiftData 数据持久化 + iCloud 同步
- SwiftUI 响应式界面
- 多语言本地化支持
- 灵动岛实时活动支持（睡眠计时）
- 通知提醒系统

---

## 开发任务清单

### 已完成功能
- [x] 基础记录功能（喂养、睡眠、换尿布、生长、疫苗）
- [x] 周/月/年统计系统
- [x] WHO生长标准对比
- [x] 4款主题系统
- [x] 多语言支持
- [x] iCloud同步
- [x] 通知提醒
- [x] 滑块式喂养量选择器
- [x] 统计/设置页面标题固定

### 待优化任务
- [ ] 睡眠计时灵动岛联动
- [ ] 侧边AI助手（拍照识图、文字保存、照片滤镜）
---

## 开发者备注

Logly 致力于为新手爸妈提供最简洁、最实用的育儿记录工具。我们相信，记录不仅是为了记住，更是为了更好地理解和陪伴宝宝的成长。每一次喂养、每一次睡眠、每一个微笑，都是珍贵的成长印记。

---

## App Store Listing (English Version)

### App Name
**Logly - Baby Tracker & Growth Log**

### Subtitle
Track feedings, sleep & growth effortlessly

---

### App Description

**Logly** is a thoughtfully designed baby tracking app for new parents. Effortlessly log feedings, sleep, diaper changes, growth milestones, and vaccinations—all in one beautiful, intuitive place.

**🍼 Comprehensive Tracking, Made Simple**
- Log breastfeedings, formula, solids, sleep, and diaper changes in seconds
- Built-in timer for accurate breastfeeding sessions
- Photo logging for diaper changes and health monitoring
- Track growth metrics: weight, height, and head circumference

**📊 Smart Insights at a Glance**
- Weekly, monthly, and yearly statistics
- Visual charts for feeding amounts, sleep patterns, and diaper frequency
- WHO growth standards comparison to monitor development
- Vaccination schedule tracking with timely reminders

**⏰ Gentle Reminders, Never Miss a Moment**
- Customizable reminders for feedings, diaper changes, and bedtime
- Smart predictions based on your baby's patterns
- Vaccination alerts to stay on schedule

**🎨 Personalize Your Experience**
- 4 beautiful themes: Minimal, Sketchbook, Ocean Breeze, and Macaron
- Automatic light/dark mode support
- Multi-language support (English, Chinese, and more)

**☁️ Your Data, Safe & Synced**
- iCloud sync across all your devices
- Privacy-first local storage
- Export and backup options available

**📚 Trusted Parenting Guidance**
- Built-in feeding and growth guides
- Evidence-based tips for new parents
- Vaccination schedule reference

---

### Keywords
baby tracker,newborn log,feeding tracker,sleep schedule,diaper log,growth chart,vaccination reminder,new parent app,infant care,baby journal

---

### Screenshot Texts

**Screenshot 1 - Dashboard**
> Track everything in one place
> Every moment of your baby's growth, beautifully recorded

**Screenshot 2 - Quick Log**
> Log in 3 seconds
> Feedings, sleep, diapers—one tap away

**Screenshot 3 - Statistics**
> Insights that matter
> Weekly, monthly, yearly—understand your baby's patterns

**Screenshot 4 - Growth Charts**
> Compare with WHO standards
> Know your baby is growing healthy and strong

**Screenshot 5 - Vaccinations**
> Stay on schedule
> Never miss an important shot

---

### What's New (Example)

**Version 1.2.0**
- New slider-style feeding amount selector for easier input
- Improved statistics page with fixed header
- Enhanced theme switching experience
- Bug fixes and stability improvements

---

*用爱记录每一刻成长*

*Cherishing every moment of growth*
