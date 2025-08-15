# QuantaKit Angular Docs

🧭 **QuantaDocs** is the official documentation and showcase platform for QuantaKit, designed to help developers explore, test, and integrate modular UI components with ease. Featuring interactive demos, real-time style editing, and theme customization, it brings clarity, performance, and precision into focus.

## 🌟 Features

- **📖 Interactive Documentation** - Comprehensive component guides with live examples
- **🎮 Live Demos** - Real-time component interaction and testing
- **🎨 Theme Customization** - Dynamic theme switching and style editing
- **📱 Responsive Examples** - Mobile-first responsive demonstrations
- **🔍 Component Explorer** - Browse and search all QuantaKit components
- **⚡ Performance Focused** - Fast loading and smooth interactions
- **♿ Accessibility Showcase** - WCAG compliance demonstrations
- **📚 Usage Examples** - Copy-paste ready code snippets

## 🛠️ Prerequisites

- Node.js (version 22 or higher)
- npm (comes with Node.js)
- Git

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/marvin-aroza/quanta-kit-angular-docs.git
cd quanta-kit-angular-docs
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The documentation site will be available at `http://localhost:4200`.

## 🚀 Quick Navigation

- **Components** - Browse all QuantaKit components
- **Themes** - Explore available design themes
- **Examples** - Real-world implementation examples
- **API Reference** - Detailed component API documentation
- **Getting Started** - Installation and setup guides

## 🏗️ Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run unit tests
- `npm run test:ci` - Run tests in CI mode with coverage

## 📁 Project Structure

```
src/
├── app/
│   ├── components/     # Documentation components
│   ├── pages/          # Documentation pages
│   ├── shared/         # Shared utilities
│   └── examples/       # Component examples
├── assets/
│   ├── images/         # Documentation images
│   └── themes/         # Theme configurations
└── styles/             # Global documentation styles
```

## 🎯 Content Areas

### Component Documentation
- **API Reference** - Props, events, and methods
- **Usage Examples** - Common implementation patterns
- **Accessibility** - WCAG compliance information
- **Theming** - Customization options

### Interactive Features
- **Live Code Editor** - Edit and preview component code
- **Theme Switcher** - Test components with different themes
- **Responsive Viewer** - See components across device sizes
- **Copy to Clipboard** - Easy code snippet copying

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details on:
- Documentation standards
- Example creation
- Content organization
- Review process

## 📚 Related Documentation

- **QuantaKit Library**: [Component source code and Storybook](https://github.com/marvin-aroza/quanta-kit-angular)
- **Admin Panel**: [Example implementation](https://github.com/marvin-aroza/angular-admin-panel)

## 📄 License

This project is private and proprietary.

## 🔗 Related Projects

- [QuantaKit Angular](https://github.com/marvin-aroza/quanta-kit-angular) - UI Component Library
- [Angular Admin Panel](https://github.com/marvin-aroza/angular-admin-panel) - Example Implementation

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
