# Arab AI

<div align="center">

![Arab AI Logo](public/arab-ai-logo.png)

**✨ Light and Fast AI Assistant with Arabic Cultural Design**

[Web App Demo](https://arab-ai.vercel.app) / [GitHub](https://github.com/Al-Garadi/Arab-AI)

</div>

## Features

🎨 **Arabic Cultural Design**: Beautiful mandala-inspired logo and culturally appropriate design elements

🚀 **Multi-Provider AI Support**: 
- OpenAI (GPT-4, GPT-3.5)
- Anthropic (Claude)
- Google (Gemini Pro)
- Azure OpenAI
- Chinese providers (Baidu, ByteDance, Alibaba, iFlytek, ChatGLM, DeepSeek)

🔒 **Privacy First**: All data stored locally in your browser

📱 **Cross-Platform**: Web, iOS, macOS, Android, Linux, Windows

🌍 **Multi-Language**: Support for 14+ languages including Arabic

⚡ **Fast & Lightweight**: ~5MB client, fast loading

🎭 **Advanced Features**:
- Prompt templates and masks
- Plugin system
- Real-time chat
- Artifacts for content sharing
- MCP (Model Context Protocol) support
- Markdown, LaTeX, Mermaid support
- Dark mode and responsive design

## Quick Start

### Deploy with One Click

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAl-Garadi%2FArab-AI&env=OPENAI_API_KEY&env=CODE&project-name=arab-ai&repository-name=arab-ai)

### Environment Variables

Before deployment, set these environment variables:

#### Required
- `OPENAI_API_KEY`: Your OpenAI API key
- `CODE`: Access password (comma-separated for multiple passwords)

#### Optional AI Providers
- `GOOGLE_API_KEY`: Google Gemini Pro API key
- `ANTHROPIC_API_KEY`: Anthropic Claude API key
- `AZURE_URL`: Azure OpenAI endpoint
- `AZURE_API_KEY`: Azure API key
- `AZURE_API_VERSION`: Azure API version

#### Chinese Providers
- `BAIDU_API_KEY`: Baidu API key
- `BAIDU_SECRET_KEY`: Baidu secret key
- `BYTEDANCE_API_KEY`: ByteDance API key
- `ALIBABA_API_KEY`: Alibaba Cloud API key
- `CHATGLM_API_KEY`: ChatGLM API key
- `DEEPSEEK_API_KEY`: DeepSeek API key

### Local Development

```bash
# Clone the repository
git clone https://github.com/Al-Garadi/Arab-AI.git
cd Arab-AI

# Install dependencies
yarn install

# Start development server
yarn dev
```

### Build for Production

```bash
# Build the application
yarn build

# Start production server
yarn start
```

## Configuration

### Access Control

Set the `CODE` environment variable to control access:

```bash
CODE=your-password-here
```

For multiple passwords:
```bash
CODE=password1,password2,password3
```

### Custom Models

Use the `CUSTOM_MODELS` environment variable to add or modify available models:

```bash
CUSTOM_MODELS=+llama,+claude-2,-gpt-3.5-turbo,gpt-4-1106-preview=gpt-4-turbo
```

- `+model`: Add a custom model
- `-model`: Remove a model from the list
- `model=display-name`: Rename a model for display

### Hide Features

- `HIDE_USER_API_KEY=1`: Prevent users from entering their own API keys
- `DISABLE_GPT4=1`: Disable GPT-4 models
- `HIDE_BALANCE_QUERY=1`: Hide balance query feature

## Deployment Options

### Vercel (Recommended)
1. Fork this repository
2. Import to Vercel
3. Set environment variables
4. Deploy

### Docker
```bash
docker run -d -p 3000:3000 \
  -e OPENAI_API_KEY=your_key \
  -e CODE=your_password \
  arab-ai:latest
```

### Self-Hosted
1. Build the application
2. Deploy to your server
3. Configure reverse proxy (nginx/apache)
4. Set up SSL certificate

## Features in Detail

### Plugin System
- Network search capabilities
- Calculator functionality
- Custom API integrations
- Extensible architecture

### Artifacts
- Preview generated content
- Share webpages and documents
- Copy and export functionality

### Real-time Chat
- WebSocket-based communication
- Streaming responses
- Live message updates

### MCP Support
- Model Context Protocol integration
- Enhanced AI capabilities
- Tool integration

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on the excellent [ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) project
- Arabic cultural design elements inspired by traditional Islamic art
- Community contributions and feedback

## Support

- 📧 Email: support@arab-ai.com
- 💬 GitHub Issues: [Report a bug](https://github.com/Al-Garadi/Arab-AI/issues)
- 📖 Documentation: [Wiki](https://github.com/Al-Garadi/Arab-AI/wiki)

---

<div align="center">

**Made with ❤️ for the Arabic-speaking AI community**

[⭐ Star this project](https://github.com/Al-Garadi/Arab-AI) if you find it useful!

</div>

# arab-ai-final
#   A r a b - A I - 7  
 # Arab-AI-7
# Arab-AI-7
