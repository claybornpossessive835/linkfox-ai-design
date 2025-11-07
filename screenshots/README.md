# 📸 项目截图说明

## 截图文件放置指南

请将以下截图保存到此目录（`screenshots/`），并按照指定的文件名命名：

### 必需的截图

1. **home.png** - 首页截图
   - 内容：包含上传区域、6个功能卡片、优秀案例展示
   - 建议尺寸：1920x1080 或更高
   - 示例：登录后的主页全屏截图

2. **profile.png** - 用户中心截图
   - 内容：用户头像、积分显示、VIP等级、个人信息
   - 建议尺寸：1920x1080 或更高
   - 示例：点击右上角用户头像进入个人中心的截图

3. **feature-1.png** - 智能修图功能
   - 内容：智能修图功能卡片或使用界面
   - 建议尺寸：800x600

4. **feature-2.png** - 场景制变功能
   - 内容：场景制变功能卡片或使用界面
   - 建议尺寸：800x600

5. **feature-3.png** - 商品图功能
   - 内容：商品图功能卡片或使用界面
   - 建议尺寸：800x600

6. **feature-4.png** - AI穿衣功能
   - 内容：AI穿衣功能卡片或使用界面
   - 建议尺寸：800x600

## 如何截图

### macOS
- 全屏截图：`Command + Shift + 3`
- 区域截图：`Command + Shift + 4`
- 窗口截图：`Command + Shift + 4` 然后按空格键

### Windows
- 全屏截图：`PrtScn` 或 `Win + PrtScn`
- 区域截图：`Win + Shift + S`
- 窗口截图：`Alt + PrtScn`

### Chrome浏览器
- 使用开发者工具截图（推荐）
  1. 按 `F12` 打开开发者工具
  2. 按 `Ctrl + Shift + P` (Mac: `Cmd + Shift + P`)
  3. 输入 "screenshot"
  4. 选择 "Capture full size screenshot" 截取整个页面

## 截图要求

✅ **推荐做法**：
- 使用高分辨率截图（至少 1920x1080）
- 确保界面完整，没有被截断
- 截图时保持浏览器窗口最大化
- 使用管理员账号（admin/123456）登录后截图
- 截图前清除浏览器控制台和开发者工具

❌ **避免**：
- 模糊或低分辨率的截图
- 包含敏感信息的截图
- 窗口被遮挡的截图
- 包含浏览器书签栏的截图（可以隐藏）

## 快速截图步骤

1. 启动项目
   ```bash
   ./start.sh
   ```

2. 访问 http://localhost:3001

3. 使用 admin/123456 登录

4. 截取以下页面：
   - 首页 → 保存为 `home.png`
   - 点击右上角头像 → 保存为 `profile.png`
   - 各个功能卡片 → 保存为 `feature-1.png` 到 `feature-4.png`

5. 将截图放到 `screenshots/` 目录

6. 提交到 Git
   ```bash
   git add screenshots/
   git commit -m "docs: 添加项目截图"
   git push origin main
   ```

## 示例结构

```
screenshots/
├── README.md          # 本文件
├── home.png          # 首页截图
├── profile.png       # 用户中心截图
├── feature-1.png     # 智能修图
├── feature-2.png     # 场景制变
├── feature-3.png     # 商品图
└── feature-4.png     # AI穿衣
```

## 更新 GitHub

截图放置完成后，执行以下命令推送到 GitHub：

```bash
cd /tmp/linkfox-ai-design
git add screenshots/
git commit -m "docs: 添加项目界面截图"
git push origin main
```

---

**提示**：README.md 已经配置好了截图引用，只需要将对应的截图文件放到本目录即可自动显示！

