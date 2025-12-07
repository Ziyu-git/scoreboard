# 🎓 智能成绩分析看板系统

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)

一个功能强大的学生成绩分析与可视化系统，支持多角色权限管理、数据导出、历史对比、成绩预测等功能。


## ✨ 功能特性

### 🔐 多角色权限系统
- **管理员** - 完整权限（数据编辑、导出、设置）
- **教师** - 查看和分析权限
- **学生** - 仅查看个人成绩等级
- **预览模式** - 数据模糊化展示
- **体验模式** - 沙盒环境测试

### 📊 数据可视化
- 📈 成绩分布图表（柱状图、雷达图、饼图、折线图）
- 🏆 排名榜单与学生详情
- 📉 历史成绩趋势对比
- 🎯 班级对比分析
- 🔮 成绩预测曲线

### 🛠 核心功能
- ✏️ **数据编辑** - 实时修改学生成绩
- 📥 **Excel导出** - 一键导出完整报表
- 🔍 **智能搜索** - 支持姓名/学号/分数段筛选
- ⚠️ **预警系统** - 自动识别学业困难学生
- 📚 **学科分析** - 单科深度统计
- 🎨 **主题切换** - 4种精美主题（默认/科技蓝/活力橙/暗黑）

### 🎯 分析维度
- 班级总览统计
- 个人成绩详情
- 科目横向对比
- 历史纵向追踪
- 成绩预测建议
- 分数段分布
- 及格率统计

## 🚀 快速开始

### 方式一：直接使用（推荐）

1. 下载 `index.html` 文件
2. 使用浏览器打开即可（支持 Chrome、Safari、Edge、Firefox）
3. 使用测试账号登录体验


### 方式二：在线托管

上传到 GitHub Pages、Vercel、Netlify 等平台即可使用。

## 🔑 测试账号

| 角色 | 账号 | 密码 | 权限说明 |
|------|------|------|----------|
| 管理员 | admin@gmail.com | admin123456 | 完整权限 |
| 教师 | teacher@cold.edu | teacher123 | 查看分析权限 |
| 学生 | 拼音（如zhangwei） | 123456 | 仅查看个人等级 |
| 预览 | 1 | 1 | 数据模糊展示 |
| 体验 | test | test123 | 沙盒测试环境 |

> 💡 学生账号：使用姓名全拼登录（如"张伟"→"zhangwei"），密码统一为 123456

## 📖 使用文档

### 主要页面介绍

#### 1️⃣ 总览页面
- 查看班级平均分、最高分、最低分、及格率
- 总分分布柱状图
- TOP 5 优秀学生榜单

#### 2️⃣ 排名榜
- 完整学生排名列表
- 支持姓名/学号搜索
- 分数段筛选
- 多维度排序

#### 3️⃣ 数据分析
- 各科平均分雷达图
- 成绩分布对比
- 分数段统计表

#### 4️⃣ 学生详情
- 个人成绩雷达图
- 班级排名与百分位
- 历史成绩趋势

#### 5️⃣ 学科分析
- 单科成绩分布
- TOP 10 榜单
- 及格率统计

#### 6️⃣ 预警系统
- 学业困难学生列表
- 单科不及格统计
- 个性化建议

#### 7️⃣ 历史对比
- 多次考试趋势图
- 成绩波动分析

#### 8️⃣ 班级对比
- 6个班级横向比较
- 平均分与及格率对比

#### 9️⃣ 成绩预测
- 基于历史数据预测
- 趋势判断
- 学习建议

#### 🔟 系统设置
- 数据导出（Excel）
- 主题切换
- 数据刷新（沙盒模式）

### 数据编辑

管理员和体验账号可以编辑学生成绩：

1. 进入"排名榜"页面
2. 点击学生行的"编辑"按钮
3. 修改各科成绩
4. 保存后自动更新排名和统计

### Excel 导出

点击"设置"→"导出Excel"，将生成包含所有班级的完整报表。

### 主题切换

在"设置"页面选择喜欢的主题：
- 🎨 默认主题 - 紫色渐变
- 💙 科技蓝 - 蓝色科技风
- 🧡 活力橙 - 橙色活力风
- 🌙 暗黑模式 - 深色护眼

## 🏗 技术架构

### 技术栈

```
前端框架：Vanilla JavaScript（无依赖）
图表库：Chart.js 3.x
表格导出：SheetJS (xlsx)
样式：原生 CSS3（CSS Variables）
```


### 核心特性

- ✅ **单文件应用** - 无需构建，开箱即用
- ✅ **响应式设计** - 完美支持 PC/iPad/手机
- ✅ **数据持久化** - 使用 sessionStorage 保持登录状态
- ✅ **主题记忆** - localStorage 存储用户偏好
- ✅ **模块化代码** - 清晰的函数划分
- ✅ **沙盒模式** - 隔离测试环境


## 📊 数据说明

### 成绩构成

| 科目 | 满分 |
|------|------|
| 语文 | 150 |
| 数学 | 150 |
| 英语 | 150 |
| 物理 | 100 |
| 化学 | 100 |
| 生物 | 100 |
| **总分** | **750** |

### 等级划分（学生视角）

- **A优** - 总分 ≥ 562.5（75%）
- **B优** - 总分 ≥ 450（60%）
- **C** - 总分 ≥ 375（50%）
- **D** - 总分 < 375

### 数据生成

- 自动生成 6 个班级，每班 50 名学生
- 使用真实姓名库（50个常见姓名）
- 成绩符合正态分布
- 历史数据自动模拟（4次考试）

## 🔧 自定义配置

### 修改班级数量

```javascript
// 在 initializeClassesData() 函数中修改
for (let i = 1; i <= 6; i++) {  // 改为需要的班级数
    const className = `${i}班`;
    classesData[className] = generateStudentData(className);
}
```

### 修改学生数量

```javascript
// 在 generateStudentData() 函数中修改
for (let i = 0; i < 50; i++) {  // 改为需要的人数
    // ...
}
```

### 添加新科目

```javascript
// 1. 修改 SUBJECTS 对象
const SUBJECTS = {
    chinese: { name: '语文', maxScore: 150 },
    // ... 添加新科目
    politics: { name: '政治', maxScore: 100 }
};

// 2. 修改 generateStudentData() 函数
// 3. 修改相关表格和图表
```

### 修改及格线

```javascript
// 默认为总分的 60%
const passLine = TOTAL_SCORE * 0.6; // 450分
```

## 🌟 亮点功能

### 1. 智能预警系统
自动识别以下情况：
- 总分低于 375 分（严重预警）
- 总分低于 450 分（及格预警）
- 单科不及格
- 提供个性化建议

### 2. 成绩预测算法
基于历史趋势的线性预测：
```javascript
trend = (最新成绩 - 首次成绩) / 考试次数
预测成绩 = 最新成绩 + trend
```

### 3. 权限隔离
- 不同角色看到不同界面
- 预览模式数据模糊化
- 沙盒模式数据隔离

### 4. 数据验证
- 分数范围检查（0-满分）
- 必填项验证
- 实时总分计算

## 📱 兼容性

| 浏览器 | 版本要求 | 支持度 |
|--------|---------|--------|
| Chrome | ≥ 90 | ✅ 完美 |
| Safari | ≥ 14 | ✅ 完美 |
| Edge | ≥ 90 | ✅ 完美 |
| Firefox | ≥ 88 | ✅ 完美 |
| 移动端 | iOS 14+ / Android 10+ | ✅ 完美 |

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 开发建议

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 建议改进方向

- [ ] 添加更多图表类型
- [ ] 支持自定义科目
- [ ] 添加数据导入功能
- [ ] 增加打印功能
- [ ] 支持多学期管理
- [ ] 添加家长端
- [ ] 移动端 App 封装

## 📄 开源协议

本项目采用 [MIT](LICENSE) 协议开源。

## 👨‍💻 作者

**Your Name**
- GitHub: [@Ziyu-git](https://github.com/Ziyu-git)
- Email: ziyu-github@outlook.sg

## 🙏 致谢

- [Chart.js](https://www.chartjs.org/) - 强大的图表库
- [SheetJS](https://sheetjs.com/) - Excel 处理库
- 所有贡献者和使用者

## 📞 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 💬 [提交 Issue](https://github.com/yourusername/grade-dashboard/issues)
- 📧 Email: ziyu-github@outlook.sg

---

<div align="center">

**如果这个项目对你有帮助，请给一个 ⭐️ Star 支持一下！**

Made with ❤️ by [Ziyu-git]

</div>
