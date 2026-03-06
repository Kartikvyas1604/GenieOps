# GenieOps 🧞

<div align="center">

**AI-Powered DevOps Automation Platform**

[![VS Code](https://img.shields.io/badge/VS%20Code-1.85+-blue.svg)](https://code.visualstudio.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Gemini AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-8B5CF6.svg)](https://ai.google.dev/)

*Talk to your infrastructure like you talk to a friend. Deploy, monitor, and manage everything with natural language.*

</div>

---

## 🚀 Quick Start

1. **Install GenieOps** from the VS Code Marketplace
2. **Click the 🧞 icon** in the Activity Bar (left sidebar)
3. **Configure your Gemini API Key**:
   - Get your free key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Paste it when prompted (or in Settings → GenieOps → Google API Key)
4. **Start chatting!** Press `Cmd+Shift+O` (Mac) or `Ctrl+Shift+O` (Windows/Linux)

## ✨ What Can GenieOps Do?

### 💬 Natural Language Commands
Just type what you want in plain English:

```
"Deploy my app to AWS"
"Show me all running containers"
"Create a CI/CD pipeline for this Next.js project"
"Scale my Kubernetes deployment to 5 replicas"
"What's using the most CPU in production?"
```

### ☁️ Multi-Cloud Support

| Provider | What You Can Do |
|----------|-----------------|
| **AWS** | Deploy Lambda functions, manage S3, EC2, ECS, CloudWatch monitoring |
| **Google Cloud** | Cloud Run, GKE clusters, Cloud Functions, GCS storage |
| **Azure** | App Service, AKS, Functions, Blob Storage, Container Registry |

### 🐳 Container & Orchestration
- **Docker**: Build, run, stop, logs, inspect containers and images
- **Kubernetes**: Deploy, scale, update pods, services, and deployments
- **Helm**: Install and manage charts

### 🔄 CI/CD & Git
- **GitHub**: Repos, PRs, Issues, Actions workflows
- **GitLab**: Pipelines, Merge Requests
- **Jenkins**: Jobs and builds

### 💬 Team Collaboration
- **Slack**: Send deployment notifications and alerts
- **Jira**: Create issues, update tickets, sprint management

## 🎨 Beautiful Interface

GenieOps features a modern chat interface inspired by GitHub Copilot:

- **Multiple AI Models**: Choose between Gemini Pro, Gemini Flash, Claude, GPT-4, and Perplexity
- **Agent Modes**: Agent, Assistant, Code, or DevOps specialized modes
- **Smart Suggestions**: Context-aware command suggestions
- **Real-time Typing Indicators**: See when GenieOps is thinking
- **Visual Message Groups**: Clean, organized conversation view

## 🔧 Key Features

- **🎯 Project Auto-Detection**: Automatically detects your stack (Next.js, React, Node.js, Python, etc.)
- **🔐 Secure Credential Storage**: All API keys safely stored in VS Code's secure storage
- **📊 Real-time Monitoring**: Live status updates for deployments and infrastructure
- **🔄 Workflow Automation**: Pre-built templates for common DevOps tasks
- **📝 Command History**: Track and replay previous operations
- **🌐 Multi-Cloud**: Switch between AWS, GCP, and Azure seamlessly

## ⚙️ Configuration

### Required: Gemini API Key

1. Open VS Code Settings (`Cmd+,` on Mac, `Ctrl+,` on Windows/Linux)
2. Search for "GenieOps"
3. Enter your Gemini API Key (get one free at [Google AI Studio](https://makersuite.google.com/app/apikey))

### Optional: Other AI Models

Configure additional models for specialized tasks:
- **Claude API Key**: For complex reasoning tasks
- **OpenAI API Key**: For GPT-4 support
- **Anthropic API Key**: For Claude 3.5

### Optional: Cloud Providers

Connect your cloud accounts:
1. Click the 🧞 icon in the Activity Bar
2. Go to "Connections" view
3. Click "+" to add AWS, GCP, or Azure credentials

## 🎮 Usage Examples

### Example 1: Deploy a Web App
```
Open Chat (Cmd+Shift+O) and type:
"Deploy my Next.js app to Vercel"
```

### Example 2: Docker Management
```
"Show me all running containers"
"Stop the nginx container"
"Build a Docker image from the current directory"
```

### Example 3: Kubernetes Operations
```
"Scale my web deployment to 5 replicas"
"Show me pods in the production namespace"
"Update the config map with new environment variables"
```

### Example 4: CI/CD Pipeline
```
"Generate a GitHub Actions workflow for this project"
"Create a Dockerfile optimized for production"
```

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Cmd+Shift+O` (Mac) or `Ctrl+Shift+O` (Win/Linux) | Open Chat Panel |
| `Cmd+Shift+G` (Mac) or `Ctrl+Shift+G` (Win/Linux) | Run Quick Command |

## 🏗️ Architecture

GenieOps is built with:
- **TypeScript** for type safety
- **VS Code Extension API** for native integration
- **Gemini AI** as the primary intelligence layer
- **MCP (Model Context Protocol)** for tool orchestration
- **Secure credential storage** in VS Code's SecretStorage

## 📦 Development

Want to contribute or customize GenieOps?

```bash
# Clone the repository
git clone https://github.com/Kartikvyas1604/GenieOps.git
cd GenieOps

# Install dependencies
npm install

# Compile TypeScript
npm run compile

# Watch mode for development
npm run watch
```

Then press `F5` in VS Code to launch the Extension Development Host.

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a Pull Request

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details

## 🐛 Troubleshooting

### "API key not configured"
Go to Settings → GenieOps → Google API Key and enter your Gemini API key

### "Cannot connect to cloud provider"
Check your credentials in the Connections panel. Click the service to re-authenticate.

### Chat panel is blank
Try reloading VS Code (`Cmd+R` or `Ctrl+R`)

### Extension not appearing
Make sure you've clicked the 🧞 genie icon in the Activity Bar (left sidebar)

## ❓ FAQ

**Q: Is GenieOps free?**  
A: Yes! GenieOps is open source. You only pay for your cloud/API usage (Gemini has a generous free tier).

**Q: What's the difference between Agent and Assistant modes?**  
A: Agent mode can execute actions automatically, while Assistant mode provides guidance without making changes.

**Q: Can I use this in production?**  
A: Yes, but always review commands before execution and test in staging first.

**Q: Which AI model should I use?**  
A: **Gemini Pro** is the best balance of speed and capability. Use **Gemini Flash** for quick queries or **Claude/GPT-4** for complex reasoning.

## 🙏 Acknowledgments

Built with:
- [Gemini AI](https://ai.google.dev/) - Primary AI engine
- [VS Code Extension API](https://code.visualstudio.com/api)
- [Model Context Protocol](https://modelcontextprotocol.io/)

---

<div align="center">

**Made with 💜 by developers, for developers**

[Report Bug](https://github.com/Kartikvyas1604/GenieOps/issues) · [Request Feature](https://github.com/Kartikvyas1604/GenieOps/issues) · [Documentation](https://github.com/Kartikvyas1604/GenieOps/wiki)

⭐ Star us on GitHub if GenieOps helps you!

</div>


---

## 🔌 MCP Server Tools

The extension exposes 35+ tools via Model Context Protocol:

### Docker Tools
- `docker_list_containers` - List all containers
- `docker_run_container` - Run a new container
- `docker_stop_container` - Stop running container
- `docker_build_image` - Build Docker image
- `docker_push_image` - Push image to registry

### Kubernetes Tools
- `k8s_get_pods` - List pods in namespace
- `k8s_apply_manifest` - Apply YAML manifest
- `k8s_scale_deployment` - Scale deployment replicas
- `k8s_rollout_status` - Check rollout status
- `helm_install` - Install Helm chart

### Cloud Tools
- `aws_lambda_invoke` - Invoke Lambda function
- `aws_s3_list_buckets` - List S3 buckets
- `gcp_run_deploy` - Deploy to Cloud Run
- `azure_function_invoke` - Invoke Azure Function

### Git Tools
- `git_clone` - Clone repository
- `git_create_branch` - Create new branch
- `git_create_pr` - Create pull request
- `github_trigger_workflow` - Trigger GitHub Action

---

## 🛡️ Resilience & Reliability

Built-in patterns for production reliability:

```typescript
import { resilience, CircuitBreaker, RetryManager } from './utils';

// Combined resilience policy
const policy = resilience()
  .withCircuitBreaker({ failureThreshold: 5 })
  .withRetry({ maxAttempts: 3, backoffMultiplier: 2 })
  .withBulkhead({ maxConcurrent: 10 })
  .withTimeout(30000);

const result = await policy.execute(() => apiCall());
```

### Features
- **Circuit Breaker**: Prevents cascading failures
- **Retry with Backoff**: Exponential backoff with jitter
- **Bulkhead**: Concurrency isolation
- **Rate Limiting**: Token bucket & sliding window
- **Timeout Control**: Configurable operation timeouts

---

## 📊 Observability

Comprehensive metrics collection:

```typescript
import { metrics, commandMetrics } from './utils';

// Track command execution
commandMetrics.executed.inc();
commandMetrics.duration.time(async () => {
  await executeCommand();
});

// Export Prometheus metrics
const prometheusOutput = metrics.exportPrometheus();
```

### Metrics Types
- **Counter**: Monotonically increasing values
- **Gauge**: Values that can go up/down
- **Histogram**: Distribution of values
- **Timer**: Duration measurements with percentiles

---

## 🧪 Testing

```bash
# Run all tests
npm test

# Run specific test suite
npm test -- --grep "GitHub"

# Run with coverage
npm run test:coverage
```

Test coverage includes:
- Unit tests for all integrations
- AI orchestrator tests
- NLP parsing tests
- Workflow engine tests
- MCP tool tests

---

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Model Context Protocol](https://modelcontextprotocol.io/) for the MCP specification
- [Anthropic](https://anthropic.com/) for Claude AI
- [VS Code](https://code.visualstudio.com/) for the extension API

---

<div align="center">

**Built with ❤️ for the DevOps community**

[Documentation](docs/) · [Report Bug](issues) · [Request Feature](issues)

</div>