# 📋 任务协作管理系统（Task Manager）

一个基于 Flask 构建的轻量级团队任务协作系统，支持用户注册登录、任务创建、成员分配与任务状态管理，适用于小团队或个人项目管理场景。

---

## 🚀 项目简介

本项目是一个简洁实用的 Web 应用，旨在帮助团队成员高效协作与任务跟踪。系统通过清晰的角色划分与任务流转机制，实现基本的项目管理能力。

适合用于：

* 学习 Flask Web 开发
* 课程设计 / 毕设项目
* 个人作品集展示
* 小型团队协作工具

---

## 🧩 功能特性

### 👤 用户系统

* 用户注册 / 登录 / 登出
* 密码加密存储（安全性保障）
* 支持角色区分（运营 / 组长 / 主管）

### 📌 任务管理

* 创建任务（标题 + 描述）
* 指派多个协作成员
* 自动记录创建人

### 🔄 状态流转

* 待处理
* 进行中
* 已完成

### 👥 权限控制

* 仅任务成员或创建者可查看任务详情
* 防止未授权访问

### 📊 工作台（Dashboard）

* 查看“我参与的任务”
* 查看“我创建的任务”

---

## 🛠 技术栈

* 后端：Python + Flask
* 数据库：SQLite + SQLAlchemy
* 登录管理：Flask-Login
* 前端：HTML + CSS（Bootstrap 风格）

---

## 📂 项目结构

```bash
task-manager/
├── app.py                # 主程序入口
├── templates/            # 页面模板
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── create_task.html
│   └── task_detail.html
├── static/               # 静态资源
│   └── style.css
```

---

## ⚙️ 安装与运行

### 1️⃣ 克隆项目

```bash
git clone https://github.com/LSXH571/task-manager.git
cd task-manager
```

---

### 2️⃣ 安装依赖

```bash
pip install flask flask-sqlalchemy flask-login werkzeug
```

---

### 3️⃣ 运行项目

```bash
python app.py
```

---

### 4️⃣ 打开浏览器

访问：

```
http://127.0.0.1:5000
```

---

## 🧪 使用说明

1. 注册一个新账号
2. 登录系统
3. 创建任务并填写信息
4. 指派团队成员
5. 在 Dashboard 查看任务
6. 进入任务详情页更新状态

---

## 📌 项目亮点

* 结构清晰，适合学习 Flask
* 功能完整，具备基础项目管理能力
* 支持多用户协作
* 易于扩展（可添加评论、附件、通知等功能）

---

## 🔮 后续可扩展方向

* ✅ 任务优先级 / 截止时间
* ✅ 评论系统（任务讨论）
* ✅ 文件上传（附件）
* ✅ 邮件 / 消息提醒
* ✅ 数据统计与图表分析
* ✅ 前后端分离（Vue + Flask API）

---

## 📄 License

本项目仅用于学习与交流，欢迎二次开发与改进。

---

## 🙌 作者

* GitHub: https://github.com/LSXH571

如果这个项目对你有帮助，欢迎点个 ⭐ 支持一下！
