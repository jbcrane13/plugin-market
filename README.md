# Agentic Development Marketplace

Personal collection of Claude Code plugins for iOS/SwiftUI development and workflow automation.

## Installation

Add this marketplace to Claude Code:

```bash
claude plugins:add-marketplace jbcrane13/plugin-market
```

Or add directly from GitHub:

```bash
/plugin marketplace add jbcrane13/plugin-market
```

## Available Plugins

| Plugin | Description | Version |
|--------|-------------|---------|
| [swiftui-dev](https://github.com/jbcrane13/swiftui-dev) | Comprehensive SwiftUI development toolkit for iOS 18+/macOS 15+ with Swift 6 patterns | 1.0.0 |
| dev-workflow | Development workflow management with quality gates and verification | *Coming soon* |

## Installing Individual Plugins

Once the marketplace is added, install plugins with:

```bash
/plugin install swiftui-dev@agentic-development-marketplace
```

## Plugin Details

### swiftui-dev

Modern iOS 18+/macOS 15+ development toolkit featuring:

- **8 Commands**: `/new-app`, `/design`, `/plan`, `/audit`, `/build`, `/test`, `/screenshot`, `/simulator`
- **7 Agents**: liquid-glass-expert, project-architect, architect-review, swiftdata-expert, cloudkit-expert, swiftui-ux-designer, mobile-code-implementer
- **5 Skills**: modern-apple-dev, xcode-build, ios-simulator, appium-xcuitest, cloudkit
- **Enforced Standards**: Swift 6 strict concurrency, @Observable patterns, accessibility identifiers

### dev-workflow

*Coming soon* - Development workflow management including:

- Session memory
- Verification gates
- Quality enforcement
- TDD workflows

## Requirements

- Claude Code CLI
- macOS 15+ (for iOS development plugins)
- Xcode 16+ with iOS 18+ SDK

## Author

Blake Crane ([@jbcrane13](https://github.com/jbcrane13))

## License

MIT
