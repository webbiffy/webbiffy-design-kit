# Webbiffy Design Kit

A comprehensive design system for Webbiffy applications, built with modern tools and best practices.

## 🚀 Overview

Webbiffy Design Kit is a repository workspace containing reusable UI components for building consistent user interfaces across Webbiffy applications.

## 📦 Packages

### [@webbiffy.design/ui-react](./packages/webbiffy-ui-react/README.md)

React UI component library with TypeScript support, built on shadcn/ui and Radix UI primitives.

- [📖 Full Documentation](./packages/webbiffy-ui-react/README.md)
- [🚀 Quick Start](./packages/webbiffy-ui-react/README.md#-quick-start)
- [🎨 Customization](./packages/webbiffy-ui-react/README.md#-customization)
- [🧪 Testing](./packages/webbiffy-ui-react/README.md#-testing)

## 🛠 Development Setup

### Prerequisites

- Node.js 20+
- pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/webbiffy/webbiffy-design-kit.git
cd webbiffy-design-kit

# Install dependencies for entire workspace
pnpm install

# OR install dependencies for specific package only
pnpm ui-react:install
```

#### Installation Options

- **`pnpm install`** - Installs dependencies for **all packages** in the workspace (recommended for development)
- **`pnpm ui-react:install`** - Installs dependencies for **@webbiffy.design/ui-react package only** (useful for CI/CD or specific deployments)

### Available Scripts

```bash
# Installation
pnpm ui-react:install      # Install dependencies for @kmc.solutions/ui-react package only

# Development
pnpm ui-react:dev          # Start UI React development server
pnpm ui-react:story        # Start Storybook for component documentation
pnpm ui-react:build-watch  # Build UI React package and watch for changes

# Testing & Quality
pnpm ui-react:test         # Run unit tests
pnpm ui-react:lint         # Run linting
pnpm ui-react:type-check   # Run TypeScript type checking

# Building
pnpm ui-react:build        # Build UI React package
pnpm ui-react:story-build  # Build Storybook for production
pnpm ui-react:story-build-with-tests  # Run all tests + build Storybook (recommended for deployment)
```

## 🎯 Project Structure

```
webbiffy-design-kit/
├── packages/
│   └── webbiffy-ui-react/      # React UI components
├── apps/                  # Testing/demo apps (gitignored)
├── package.json           # Workspace configuration
├── pnpm-workspace.yaml    # pnpm workspace setup
└── README.md              # This file
```

## 🤝 Contributing

1. Clone the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

Webster Pacheco <webster.pacheco@gmail.com>

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for component inspiration
- [Radix UI](https://www.radix-ui.com/) for accessible primitives
- [Tailwind CSS](https://tailwindcss.com/) for utility-first styling
