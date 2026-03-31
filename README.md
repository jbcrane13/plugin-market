<div align="center">

# 🚀 Agentic Development Marketplace

**Personal collection of Claude Code plugins for iOS/SwiftUI development and workflow automation**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude-Code-5A67D8)](https://claude.ai/code)
[![Version](https://img.shields.io/badge/version-1.3.0-blue.svg)](https://github.com/jbcrane13/plugin-market)

[Installation](#-installation) • [Plugins](#-available-plugins) • [Requirements](#-requirements) • [License](#-license)

</div>

---

## 📦 Installation

Add this marketplace to Claude Code in one command:

```bash
claude plugins:add-marketplace jbcrane13/plugin-market
```

Or using the slash command:

```bash
/plugin marketplace add jbcrane13/plugin-market
```

## 🔌 Available Plugins

### [swiftui-dev](https://github.com/jbcrane13/swiftui-dev) `v1.0.0`

> Comprehensive SwiftUI development toolkit for iOS 18+/macOS 15+ with Swift 6 patterns, SwiftData, Liquid Glass support, and test automation

**Features:**
- ✅ **8 Commands** - `/new-app`, `/design`, `/plan`, `/audit`, `/build`, `/test`, `/screenshot`, `/simulator`
- 🤖 **7 Agents** - Specialized agents for architecture, UI/UX design, SwiftData, CloudKit, and more
- 📚 **5 Skills** - modern-apple-dev, xcode-build, ios-simulator, appium-xcuitest, cloudkit
- 🎯 **Enforced Standards** - Swift 6 strict concurrency, @Observable patterns, accessibility identifiers

**Keywords:** `swiftui` `ios` `swift6` `swiftdata` `liquid-glass` `appium` `xcuitest` `cloudkit`

**Install:**
```bash
/plugin install swiftui-dev@agentic-development-marketplace
```

---

### [dev-workflow](https://github.com/jbcrane13/dev-workflow) `v0.1.0`

> Workflow orchestration for mobile and macOS development - manages TDD cycles, quality gates, visual verification, and context preservation

**Features:**
- 🔄 **TDD Cycle Management** - Automated test-driven development workflows
- 🛡️ **Quality Gates** - Hard gates including mandatory visual verification with screenshots
- 📸 **Visual Verification** - Screenshot-based UI validation for mobile apps
- 🧠 **Context Management** - Session and state preservation across development cycles
- 🔗 **Integration** - Works seamlessly with swiftui-dev for complete lifecycle management

**Keywords:** `workflow` `orchestration` `tdd` `quality-gates` `mobile-development` `ios` `macos` `context-management` `visual-verification`

**Install:**
```bash
/plugin install dev-workflow@agentic-development-marketplace
```

---

### [ui-design](https://github.com/jbcrane13/ui-design-plugin) `v0.1.0`

> Craft distinctive, visually striking UIs that avoid generic AI slop aesthetics. Covers web (React, HTML, Tailwind) and SwiftUI.

**Keywords:** `ui` `design` `aesthetics` `frontend` `swiftui` `react` `tailwind` `typography` `color`

**Install:**
```bash
/plugin install ui-design@agentic-development-marketplace
```

---

### [ui-test](https://github.com/jbcrane13/ui-test) `v1.0.0`

> XCUITest UI testing toolkit — accessibility ID auditing, UI test coverage generation, naming conventions, and automation scripts for Swift/SwiftUI apps

**Features:**
- 🔍 **ID Auditing** — Scan all views for missing or malformed accessibility identifiers
- 🏗️ **Stub Generation** — Auto-generate `.accessibilityIdentifier()` stubs following `{screen}_{type}_{descriptor}` convention
- 📊 **Coverage Cross-Reference** — Find untested IDs and orphaned test references
- 🪝 **PostToolUse Hook** — Warns when view files are created/modified without accessibility IDs
- 📋 **2 Commands** — `/check-ids` (audit), `/coverage` (full UI test lifecycle)
- 📚 **1 Skill** — XCUITest patterns, anti-patterns, and architecture guidance

**Keywords:** `xcuitest` `ui-testing` `accessibility-identifiers` `swift` `swiftui` `xcode` `ios` `macos` `automation` `test-coverage`

**Install:**
```bash
/plugin install ui-test@agentic-development-marketplace
```

---

## 💡 Quick Start

After installing the marketplace, explore available plugins:

```bash
# List all marketplace plugins
/plugin marketplace list

# Install a specific plugin
/plugin install swiftui-dev@agentic-development-marketplace

# View installed plugins
/plugin list
```

## 🎯 Use Cases

### iOS/macOS Development
The `swiftui-dev` plugin provides a complete toolkit for modern Apple platform development:
- Generate new SwiftUI apps with best practices
- Design UI/UX flows with specialized agents
- Build and test with Xcode integration
- Capture screenshots and manage simulators
- Implement CloudKit and SwiftData persistence

### Quality-Driven Workflows
The `dev-workflow` plugin enforces rigorous development standards:
- Test-driven development cycles
- Automated quality gates before commits
- Visual regression testing for mobile UIs
- Context preservation across sessions
- Integration with CI/CD pipelines

## 🛠️ Requirements

- **Claude Code CLI** - [Install here](https://claude.ai/code)
- **macOS 15+** (for iOS development plugins)
- **Xcode 16+** with iOS 18+ SDK
- **Git** for version control

## 📖 Documentation

Each plugin includes comprehensive documentation:

- [swiftui-dev Documentation](https://github.com/jbcrane13/swiftui-dev#readme)
- [dev-workflow Documentation](https://github.com/jbcrane13/dev-workflow#readme)
- [ui-test Documentation](https://github.com/jbcrane13/ui-test#readme)

## 🤝 Contributing

This is a personal plugin collection, but suggestions and feedback are welcome:

1. Open an issue for bugs or feature requests
2. Submit pull requests for improvements
3. Share your experience using these plugins

## 👨‍💻 Author

**Blake Crane**
- GitHub: [@jbcrane13](https://github.com/jbcrane13)
- Email: jbcrane13@github.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with ❤️ for the Claude Code community**

[⬆ Back to top](#-agentic-development-marketplace)

</div>
