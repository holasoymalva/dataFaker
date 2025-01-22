# DataFaker 🚀

[![Deno](https://img.shields.io/badge/deno-1.37.0-green.svg)](https://deno.land)
[![TypeScript](https://img.shields.io/badge/typescript-5.0.0-blue.svg)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/license-MIT-purple.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> The Future of Mock Data Generation - Build Better Software, Faster.

DataFaker is a revolutionary mock data generation platform that empowers developers to create realistic, type-safe test data with zero configuration. Stop wasting time creating mock data manually - focus on what matters: building great software.

## ✨ Features

- 🎯 **Type-Safe Generation**: Built with TypeScript for reliability
- 🔥 **Real-Time Preview**: See your data structure come to life
- 🚄 **Blazing Fast**: Powered by Deno's V8 engine
- 🎮 **Interactive UI**: No-code data structure configuration
- 🔌 **RESTful API**: Easy integration with any tech stack
- 📱 **Modern Stack**: Built with Deno, TypeScript, and React

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/holasoymalva/dataFaker.git

# Install dependencies
cd dataFaker
deno cache deps.ts

# Start the server
deno task start
```

Visit `http://localhost:8000` to access the UI.

## 🔧 API Usage

```typescript
// Request
POST /api/generate
{
  "fields": [
    {
      "name": "userId",
      "type": "Number",
      "connection": "ids"
    },
    {
      "name": "email",
      "type": "String",
      "connection": "emails"
    }
  ],
  "count": 10
}

// Response
[
  {
    "userId": 123,
    "email": "john.doe@example.com"
  },
  // ... more items
]
```

## 🏗️ Architecture

DataFaker is built on a modern, scalable architecture:

- **Frontend**: React + TypeScript + Vite
- **Backend**: Deno + Oak
- **Data Generation**: Custom algorithms + Faker.js

## 🛣️ Roadmap

- [ ] GraphQL API support
- [ ] Custom data templates
- [ ] Data relationships
- [ ] Export to multiple formats
- [ ] Enterprise features

## 🤝 Contributing

We believe in the power of community. Whether it's:

- 🐛 Reporting a bug
- 💡 Proposing new features
- 🔧 Submitting a PR

All contributions are welcome! Check out our [Contributing Guide](CONTRIBUTING.md).

## 📄 License

DataFaker is MIT licensed. See [LICENSE](LICENSE) for details.

## 💪 Backed By

Built with ❤️ by [holasoymalva](https://github.com/holasoymalva)

---

<p align="center">
  <a href="https://github.com/holasoymalva/dataFaker/stargazers">⭐ Star us on GitHub</a> •
  <a href="https://twitter.com/holasoymalva">🐦 Follow us on Twitter</a> •
  <a href="https://discord.gg/holasoymalva">💬 Join our Discord</a>
</p>
