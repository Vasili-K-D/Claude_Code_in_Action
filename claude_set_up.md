# Time to get Claude Code set up locally!

You can find full setup instructions here: https://code.claude.com/docs/en/quickstart

In short, you'll need to do the following:

### Install Claude Code
- MacOS, Linux, WSL: curl -fsSL https://claude.ai/install.sh | bash
- Windows PowerShell: irm https://claude.ai/install.ps1 | iex
- Windows Command Prompt (cmd.exe): curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd
- MacOS (Homebrew): brew install --cask claude-code

### After installation, run claude at your terminal. 
The first time you run this command you will be prompted to pick a color theme for the terminal and authenticate with your claude.ai credentials
If you get an error that claude isn't found after installing, or you hit a network or permissions error, see `Troubleshoot installation issues` in the docs.

Using Claude Code through Amazon Bedrock, Google Cloud Vertex AI, or Microsoft Foundry? See `third-party provider setup` for additional setup instructions.