# Open WebUI Functions

This repository contains functions for Open WebUI. Functions extend Open WebUI capabilities by adding support for new AI providers, modifying message processing, or adding interface elements.

Functions run within the Open WebUI environment - they're fast, modular, and have no external dependencies. Written in Python, they're customizable building blocks for enhancing your Open WebUI experience.

## Available Functions

- **Dify**: Pipeline for Dify API integration
- **AzureOpenAI**: Pipeline for Azure AI services

## How to Use Functions

1. **Install**: Via Open WebUI interface or manual import
   
2. **Enable**:
   - Pipe Functions appear as models in the interface
   - Filter/Action Functions need assignment to specific models

3. **Assign**:
   - Go to Workspace => Models to assign to specific models
   - Or enable globally via Workspace => Functions

## Types of Functions

- **Pipes**: Standalone models you interact with directly
- **Filters**: Modify inputs/outputs for AI interactions
- **Actions**: Add interactive buttons to chat messages

⚠️ Only install Functions from trusted sources.

## Contributing

Contributions welcome! Please provide documentation with your code.