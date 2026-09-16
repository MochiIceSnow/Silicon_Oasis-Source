Silicon Oasis / 《硅基绿洲》源代码仓库
本仓库为《硅基绿洲》的源代码仓库，不包含游戏下载与玩法介绍。

🎮 游戏发布页（下载游戏）：dfnjf/Silicon_Oasis

🌐 官方网站：https://silicon-oasis.cc.cd

🛠️ 技术栈 / Tech Stack
类别 / Category	技术 / Technology
语言 / Language	Java 17+
游戏框架 / Framework	LibGDX / jMonkeyEngine（待定）
构建工具 / Build Tool	Maven / Gradle
打包分发 / Packaging	jpackage / Packr
渲染 / Rendering	Low-Poly + Bloom (OpenGL)
📁 项目结构 / Project Structure
bash
Silicon_Oasis-Source/
├── README.md                      # 本文件 / This file
├── LICENSE                        # 开源协议 / License
├── .gitignore                     # Git 忽略配置 / Git ignore rules
├── pom.xml                        # Maven 构建配置 / Maven build config
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/siliconoasis/
│   │   │       ├── core/          # 游戏入口与主循环 / Game entry & main loop
│   │   │       ├── world/         # 世界与场景管理 / World & scene management
│   │   │       ├── entity/        # 实体系统 / Entity system
│   │   │       ├── synthesis/     # 合成系统 / Synthesis system
│   │   │       ├── automation/    # 自动化系统 / Automation system
│   │   │       ├── ecology/       # 生态系统 / Ecosystem
│   │   │       ├── ui/            # 用户界面 / UI
│   │   │       └── save/          # 存档系统 / Save system
│   │   └── resources/
│   │       ├── assets/            # 游戏资源 / Game assets
│   │       └── data/              # 游戏数据 / Game data
│   └── test/                      # 单元测试 / Unit tests
└── docs/                          # 设计文档 / Design docs
🚀 快速开始 / Quick Start
环境要求 / Prerequisites
Java JDK 17 或更高版本 / Java JDK 17 or later

Maven 3.8+ 或 Gradle 7+

IntelliJ IDEA 或 VS Code（推荐 / Recommended）

克隆仓库 / Clone the Repository
bash
git clone https://github.com/MochiIceSnow/Silicon_Oasis-Source.git
cd Silicon_Oasis-Source
构建与运行 / Build & Run
使用 Maven / Using Maven:

bash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.siliconoasis.core.SiliconOasisGame"
mvn clean package
使用 Gradle / Using Gradle:

bash
./gradlew build
./gradlew run
./gradlew shadowJar
IDE 运行 / Run in IDE
用 IntelliJ IDEA 打开项目根目录 / Open the project root in IntelliJ IDEA

等待 Maven/Gradle 依赖自动导入 / Wait for dependencies to auto-import

找到 SiliconOasisGame.java，右键 → Run / Locate SiliconOasisGame.java, right-click → Run

🤝 如何贡献 / Contributing
中文：

欢迎任何形式的贡献！无论是提交 Bug、优化代码还是完善文档。

Fork 本仓库

创建功能分支 (git checkout -b feature/amazing-feature)

提交更改 (git commit -m 'feat: add amazing feature')

推送到分支 (git push origin feature/amazing-feature)

提交 Pull Request

提交规范 / Commit Convention：

遵循 Conventional Commits：

feat: 新功能

fix: 修复 Bug

docs: 文档更新

refactor: 代码重构

test: 测试相关

English:

Contributions of all kinds are welcome! Whether it's reporting bugs, optimizing code, or improving documentation.

Fork this repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'feat: add amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

📄 开源协议 / License
本项目采用 MIT License 开源协议。

This project is licensed under the MIT License.

🔗 相关链接 / Links
链接 / Link	地址 / URL
🌐 官方网站 / Official Website	https://silicon-oasis.cc.cd
🎮 游戏发布页 / Release Page	https://github.com/dfnjf/Silicon_Oasis
📦 最新版本下载 / Latest Release	https://github.com/dfnjf/Silicon_Oasis/releases/latest
💻 源码仓库 / Source Code	https://github.com/MochiIceSnow/Silicon_Oasis-Source
本仓库仅包含源代码，游戏玩法与设计文档请参阅其他资料。

This repository contains source code only. For gameplay and design documents, please refer to other resources.

