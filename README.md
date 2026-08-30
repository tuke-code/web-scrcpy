# PANDASCRCPY · 浏览器里的 Android 投屏与控制

基于 **WebUSB + scrcpy** 的开源方案：用 Chrome / Edge 即可 USB 连接手机，低延迟镜像、键鼠/触控、录制与远程观看。**本仓库为开源核心；加强版（PANDAPERF）在之上提供 AI、群控与企业级性能能力，免费使用。**

---

## 在线体验（开源版）

1. 手机开启 **USB 调试**，用数据线连上电脑。  
2. 使用 **Chrome 或 Edge** 打开：  
   **[https://pandatestgrid.github.io/PandaScrcpy/](https://pandatestgrid.github.io/PandaScrcpy/)**  
3. 按页面提示授权 WebUSB，连接后即可投屏与操作。

### 开源版能力一览

| 能力 | 说明 |
|------|------|
| 屏幕镜像 | WebCodecs 解码，流畅低延迟 |
| 触控 / 键鼠 | 焦点与指针轨迹优化，减少「卡住」 |
| 录制 / 截图 | 本地录制与快照 |
| 远程观看 | PeerJS 分享画面给另一浏览器 |
| 设备侧工具 | 应用管理、Logcat、ADB Shell 终端等 |

建议直接打开 **[在线体验](https://pandatestgrid.github.io/PandaScrcpy/)** 查看实时界面
---

## 加强版 PANDAPERF（免费）

**[→ 立即体验加强版](https://www.pandatest.net/device)**  

在开源投屏之上，加强版面向 **研发调试、多机测试与性能分析**，典型能力包括：

- **AI 助手**：多模态理解 + 推理 + **ADB 执行闭环**——用自然语言描述任务（如打开某应用、检索、改设置），由助手规划并驱动设备完成。  
- **设备群控**：多路同屏、批量管理，适合兼容性测试与脚本验证。  
- **性能工作台**：CPU / 内存 / 网络 / GPU / 帧率与卡顿、电量等采集与图表（含时间轴与多指标联动）。  
- **脚本录制与回放**：操作轨迹录制，便于回归与自动化。  
- **虚拟屏幕、截图时间线、视觉对比** 等增强能力，持续迭代。

### 加强版界面预览

<p align="center">
  <img src="docs/images/pandaperf-full-workbench.png" alt="PANDAPERF 加强版：多设备投屏、AI 助手、性能曲线与 CPU 核心视图" width="920" />
</p>

*上图：三台设备同屏投控、右侧 AI 助手对话、底部性能时间轴（CPU / 帧率 / 内存等多指标联动）与 CPU 核心视图。*

---

## 本地开发（开源版）

```bash
npm install
npm run dev
```

构建与预览：

```bash
npm run build
npm run preview
```

更多依赖与 scrcpy-server 版本见 `package.json` 与 `postinstall` 脚本。

---

## 贡献与协议

欢迎 PR：Fork → 分支 → 提交 → Pull Request。  
许可证：**[MIT](LICENSE)**  

## 致谢

- [Tango / ya-webadb 生态](https://github.com/yume-chan) 与 **scrcpy** 相关项目  
- 社区贡献者与使用者反馈

---

<p align="center">
  <b>开源投屏 · 加强版 AI + 群控 + 性能 · <a href="https://www.pandatest.net/device">免费体验 PANDAPERF</a></b>
</p>
