欢迎您为 **SCUT-BDA Wiki** 贡献内容！  
无论是补充笔记、修正错误，还是分享学习经验，我们都非常欢迎 🎉  
本 Wiki 采用 **GitHub + Pull Request** 的协作方式，所有贡献者都会被**自动署名并展示在页面底部**。

---

## 贡献方式总览

你可以通过以下方式参与贡献：

- ✏️ 修正错别字、公式错误、代码错误
- 📚 补充或完善已有页面内容
- 🆕 新增课程笔记、学习资料或经验总结
- 🧩 优化页面结构、目录层级或表述方式

所有贡献均通过 **Pull Request（PR）** 合并。

---

## 开始贡献（标准流程）

### 1️⃣ Fork 仓库

访问 Wiki 仓库：

👉 https://github.com/SCUT-BDA/BDA-wiki

点击右上角 **Fork**，将仓库复制到你的 GitHub 账户下。

---

### 2️⃣ 克隆到本地

```bash
git clone https://github.com/<your-username>/BDA-wiki.git
cd BDA-wiki
```

### 3️⃣ 创建新分支（推荐）

```
git checkout -b add-my-notes
```

> 请使用有意义的分支名，例如：
>
> - `fix-typo-linear-algebra`
> - `add-ml-notes`
> - `update-cloud-computing-lab`

------

### 4️⃣ 编写或修改内容

- 所有文档均位于 `docs/` 目录下
- 使用 **Markdown** 编写（`.md` 文件）
- 建议一个页面聚焦一个主题，结构清晰、层次分明

📌 示例路径：

```
docs/
├── intro/
│   └── contribution.md
├── ml/
│   └── logistic-regression.md
```

------

### 5️⃣ 本地预览（可选但推荐）

如果你希望在提交前本地查看效果：

```
pip install mkdocs-material
mkdocs serve
```

浏览器访问：

```
http://127.0.0.1:8000
```

------

### 6️⃣ 提交修改

```
git add .
git commit -m "Add notes for Logistic Regression"
```

⚠️ **请确保提交信息简洁、明确**

------

### 7️⃣ 推送并创建 Pull Request

```
git push origin add-my-notes
```

然后在 GitHub 页面点击 **New Pull Request**，填写说明即可。

------

## 关于作者署名

### ✅ 自动署名机制

- 本 Wiki 会**自动识别每个页面的 GitHub 贡献者**
- 页面底部会显示：
  - 本页贡献者
  - 并链接到对应的 GitHub 个人主页

📌 **你无需手动填写作者信息**

只要你：

- 提交过该页面的修改
- 你的 PR 被合并

👉 **你就会自动成为该页面的贡献者**

------

## 内容规范建议

为了保证 Wiki 的整体质量，建议遵循以下规范：

### 写作风格

- 语言清晰、准确，避免口语化
- 数学公式建议使用 LaTeX
- 代码块注明语言类型

------

## 图片与资源

- 图片请放在 `docs/assets/` 或对应子目录
- 使用相对路径引用
- 外部资源请注明来源

------

## 行为准则

我们致力于营造一个 **友好、开放、尊重他人** 的学习社区：

- 尊重不同学习阶段和背景
- 欢迎建设性讨论
- 不接受抄袭、恶意内容或不当言论

------

## 帮助

如果你在贡献过程中遇到问题：

- 可以在仓库中提 **Issue**
- 或联系 SCUT-BDA 管理团队成员

------

🎉 **感谢你的贡献！**
 你的每一次提交，都会让 SCUT-BDA Wiki 变得更好。