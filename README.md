# Git 统计与看板系统

一个基于 Vue3 和 Spring Boot 的 Git 提交数据展示大屏，提供给管理者查看项目的 Git 提交情况、人员提交情况、提交频率等信息。

## 功能特性

- 📊 展示项目的 Git 提交情况
- 👥 人员提交情况统计
- 📈 提交频率分析
- 📱 响应式设计
- 🎨 现代化的 UI 界面

## 技术栈

### 前端
- Vue 3
- Vite
- Ant Design Vue
- ECharts

### 后端
- Spring Boot
- JPA
- H2 Database
- GitHub API

## 快速开始

### 前端

```bash
cd frontend
npm install
npm run dev
```

### 后端

```bash
cd backend
mvn spring-boot:run
```

## 配置

在后端的 `application.properties` 文件中配置 GitHub API 访问信息。

## 项目结构

```
├── backend/              # Spring Boot 后端代码
│   └── src/main/java/com/gitstats/  # 后端主要代码
├── frontend/             # Vue 3 前端代码
│   └── src/              # 前端主要代码
└── .gitignore            # Git 忽略文件
```

## License

MIT
